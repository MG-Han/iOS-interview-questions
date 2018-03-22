# iOS-interview-questions

### Algorithms
- Explain stack, queue, and linked-list.
- What is Big-O notation?
- What is the time complextiy of insertion and deletion in Linked list?
- What is the time complextiy of search in Linked list?

### Design patterns
- Explain Singleton pattern. How to make a singleton object in iOS? 
  - Objective-c: dispatch_once pattern
  - Swift: static constant property
- What is Observer pattern? What are the typical ways of Observer patterns used in iOS?
  - KVO, NSNotification, property observer in Swift(willSet, didSet), etc.

### Objective-C
- What is ARC(Automatic reference counting)?
- What is the difference between strong and weak?
- Explain strong reference cycle(retain cycle). How to resolve strong reference cycle?
- (Advanced)Have you used an autorelease pool? When?
- (Advanced)What is toll-free-bridging?
- (Advanced)What is objective-c runtime?
- (Advanced)What is method swizzling? Have you ever used it? When?

### Swift
- What is the difference between Class and Struct?
- Explain Copy-on-write.
- Explain Lazy stored properties.
- Explain Higher order functions. Explain some higher order functions in Collection protocol. 
  - map, reduce, filter, etc.
- When do you use Implicitly unwrapped optional?
- What is the requirement to be a Key of Dictionary? Why? 
  - Hashable
- What is closure?
- What is escaping closure? 
- (Advanced)What is auto closure? What are the benefits of using it?
- (Advanced)What is LazySequence protocol?

### Network
- What is the difference between GET and POST?

### concurrent programming
- Explain concurrent programming.
- What is the caution when processing UI in iOS multi-threaded environment?
- How do you implement a multi-threaded function in iOS? 
  - NSThread, NSOperation, GCD
- What is the difference between synchronous and asynchronous?
- (Advanced)Have you used dispatch_barrier_sync and dispatch_barrier_async? What is read-write Lock?

### Xcode
- What is code sigining?
- Have you used Instrument?
- (Advanced)Explain App thining.
- (Advanced)Explain briefly the main features of LLVM.
- (Advanced)What is bitcode?

### Version control system
- Have you used Git or SVN?
- Git: What is the difference between rebase and merge? Could you draw it?

### Continuos integration
- What is Continuous Integration and why do you need it?

### Dependency management
- Have you used Cocoapods, Carthage or Swift package manager?

### Etc
- What development books or documents have you enjoyed recently?
