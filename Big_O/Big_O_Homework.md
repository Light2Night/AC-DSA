###Big O Homework

##Instructions

Work on these problems in your fork of the AC-DSA repo.  Add the runtimes below, then push your commits up.  If you have not yet made a pull request, make a pull request against AC-DSA.

```swift
func problemOne(arr: [Int]) {
    for i in 0..<1000 {
        print(i)
    }
}
```

problemOne(arr:) runtime: O(n)


```swift
func problemTwo(arr: [Int]) {
    for i in 0..<arr.count {
        for j in 0..<arr.count {
            print("\(i), \(j)")
        }
    }
}
```

problemTwo(arr:) runtime: O(n^2)


```swift
func problemThree(arr: [Int]) {
    for _ in 0..<1000 {
        problemOne(arr: arr)
    }
}
```

problemThree(arr:) runtime: O(1)


```swift
func problemFour(arr: [Int]) {
    for _ in 0..<arr.count {
        problemTwo(arr: arr)
    }
}
```

problemFour(arr:) runtime: O(n)


```swift
func problemFive(arr: [Int]) {
    for _ in 0..<arr.count {
        problemTwo(arr: arr)
    }
    for _ in 0..<arr.count {
        problemTwo(arr: arr)
    }
}
```

problemFive(arr:) runtime: O(n^3)


```swift
func problemSix(arr: [Int]) {
    for _ in 0..<arr.count {
        for _ in 0..<arr.count {
            problemTwo(arr: arr)
        }
    }
}
```

<<<<<<< HEAD
problemSix(arr:) runtime: 0(n^4)
=======
problemSix(arr:) runtime: 
>>>>>>> f11dc0a8d8d0f0e2641654899f92f6dc15831800
