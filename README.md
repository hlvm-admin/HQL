# HQL
High level Query Language.<br><br>
DSL in HLVM to take a code snippet automatically.

# Syntax
```
#language>statement:indexNumberOfCodeSnippet>*times>+extraStringYouWant

#language(mandatory)>statement(mandatory):indexNumberOfCodeSnippet(can be ignored)>*times(can be ignored)>+extraStringYouWant(can be ignored)
```

HQL => 
```hql
#swift>recursion
#swift>if else:3>*3>+//good
#swift>singly linked list>*2

#javascript>spread operator 
#javascript>spread+operator 
// do not need to put '+', white space can be interpreted in a natural way
```

# Example

Example 1: Please do for loop 2 times in Swift.
```hql
#swift>for loop>*2
```
    
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
```hql
#clojure>recur
```

```clojure
(loop [i 0]
  (if (< i 5)
    (do 
   		(prn i)
      (recur (inc i)))))
```

<br>
Example 3: Please do print 100 in Swift.

```hql
#swift>print>*100
```

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
