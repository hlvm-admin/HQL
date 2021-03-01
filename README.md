# HQL
High level Query Language. DSL in HLVM

# Syntax
<br>
Example 1: Please do for loop 10 times in Swift.
<br>HQL: #swift>for loop>*3
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

Example 2: Please take in Clojure
<br>HQL: #clojure>take
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
```
