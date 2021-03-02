# HQL
High level Query Language. DSL in HLVM

# Syntax

#language>statement:indexNumberOfCodeSnippet>*times>+extraStringYouWant
#language(mandatory)>statement(mandatory):indexNumberOfCodeSnippet(can be ignored)>*times(can be ignored)>+extraStringYouWant(can be ignored)

HQL => #swift>if else:3>*3>+//good

```swift
var isTrue = true

if isTrue {
    print("if!")
} else if !isTrue {
    print("else if!")
} else {
    print("else!")
}   //good
var isTrue = true

if isTrue {
    print("if!")
} else if !isTrue {
    print("else if!")
} else {
    print("else!")
}   //good
```

for example: 
#javascript>spread operator 
#javascript>spread+operator (do not need to put '+', white space can be interpreted in a natural way)


# Example
<br>
Example 1: Please do for loop 2 times in Swift.
<br>HQL: #swift>for loop>*2
<br>
    
```swift
[1,2,3,4,5].forEach {
    print($0)
}

[1,2,3,4,5].forEach {
    print($0)
}
```
<br>

Example 2: Please do recursion in Clojure
<br>HQL: #clojure>recur
<br>

```clojure
(loop [i 0]
  (if (< i 5)
    (do 
   		(prn i)
      (recur (inc i)))))
```
<br>

Example 3: Please do print 100 in Swift.
<br>HQL: #swift>print>*100
<br>

```swift
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
print("value : \(value)")
```
