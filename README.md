# HQL
High level Query Language. DSL in HLVM

# Syntax

Example 1: Please do for loop 10 times in Swift.
HQL: 
#swift>for loop>*3

```swift
[1,2,3,4,5].forEach {
    print($0)
}

[1,2,3,4,5].forEach {
    print($0)
}
```

Example 2: Please take in Clojure
HQL: 
#clojure>take

```clojure
(loop [i 0]
  (if (< i 5)
    (do 
   		(prn i)
      (recur (inc i)))))
```

Example 3: Please do print 100 in Swift.
HQL: 
#swift>print>*100

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
