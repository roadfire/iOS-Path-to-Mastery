# iOS-Path-to-Mastery
A path to mastery for iOS development.

## About this repository
(Originally published at [http://roadfiresoftware.com/a-path-to-mastery-for-ios-developers/](http://roadfiresoftware.com/a-path-to-mastery-for-ios-developers/). This repository exists solely for feedback.)

## Contributing
Fork this repository. Make changes. Submit a pull request.

---

If you're an iOS developer writing code in Swift, you can use this Path to Mastery to determine where you are now and what skills you need to learn to get to the next level of mastery. Use this as a checklist to track your progress and as a guide to determine what to learn next. Feel free to print it out or create a PDF out of it and cross items off as you learn them.

You can check off each skill in [the accompanying Trello board](https://trello.com/b/dOV9dvBu/a-path-to-mastery-for-ios-development) - it's a great way to track and visualize your progress. Just copy it to your account and start checking off what you already know.

---

## Novice
As a novice iOS developer, you can build very simple apps with table views and buttons. You know the basics of iOS and Swift, and you know how to find and read the official docs to learn more.

### Swift
* Use and understand Swift's basic types like Bool, Int, String, and Double
* Declare and use variables and constants
* Handle flow control with loops and conditionals
* Create and use collections
* Develop and use simple functions
* Cast objects safely from one type to another
* Handle optionals from APIs and unwrap them safely

### UI
* Create a simple user interface with Interface Builder
* Center views vertically and horizontally using Auto Layout
* Create a view that fills the screen using Auto Layout
* Connect views from Interface Builder to code
* Connect actions from Interface Builder to code to handle taps on controls
* Handle and respond to taps from the user
* Customize view properties in Interface Builder
* Change text on a label programmatically when an action is performed

### iOS
* Display a static table of data
* Show an alert when an action is performed
* Understand the view controller lifecycle
* Know how to find and read the official documentation

### Challenges
* Write an app that has a label with white text centered vertically and horizontally on a black background. When the user taps a button, the text in the label should change.
* Write an app that displays a static list of items in a table view

---

## Beginner
As a beginner, you have the skills you need to put an app in the App Store. You're comfortable placing views to create slightly more complex layouts, and you can handle networking, JSON, and displaying dynamic data in table views. You can create segues between view controllers and pass data from one screen to the next.

### Swift
* Work effectively with properties
* Develop and use functions with external parameter names
* Create closures and use them effectively
* Create and use custom model objects

### UI
* Place views relative to their superview using Auto Layout
* Create a more complex user interface with multiple views in Interface Builder
* Create segues in Interface Builder to move between view controllers
* Understand how to include assets for various screen densities (1x, 2x, 3x)

### iOS
* Understand and use the delegate pattern
* Display a dynamic table of data
* Pull data from a REST web service for use in an app
* Parse JSON by serializing and deserializing it into model objects
* Understand the app lifecycle
* Pass data from one view controller to the next during a transition
* Store and fetch user preferences on device using NSUserDefaults

### Challenges
* Write a master-detail app that displays a list of items from a web service and, when an item is tapped, shows detail about the item

---

## Intermediate
As an intermediate developer, you're able to store data on the user's device, customize views, and use more of the built-in frameworks to display maps and photos. You're comfortable with sizing and placing views using Auto Layout, debugging code in Xcode, and taking advantage of Swift's power and flexibility. You write automated tests for the critical parts of your app to ensure your code works as it should.

### Swift
* Understand Swift's initializer pattern
* Know the power and use case of optionals
* Use extensions to extend Swift's standard functionality
* Understand and use pattern matching in switch statements
* Create and conform to protocols to develop a blueprint of functionality
* Increase code flexibility and power using generics
* Understand the similarities and differences between enums, structs, and classes and when to use each
* Create and format date objects

### UI
* Add views and constraints to user interfaces in code
* Lay out custom table view cells
* Create a custom UIView subclass and use it in Interface Builder
* Create custom segues between view controllers
* Use segues programmatically to move between view controllers
* Place views relative to sibling views using Auto Layout
* Resize views based on device size using Auto Layout
* Set a view's aspect ratio with Auto Layout
* Understand and use inequality constraints
* Understand and apply constraint priorities to ensure views are precisely the size they need to be
* Understand compression resistance and content hugging
* Size views properly using compression resistance and content hugging
* Use appearance proxies to customize app appearance
* Use Auto Layout with a scroll view to display content that doesn't fit on a single screen

### iOS
* Understand ARC and manage memory properly to prevent memory leaks and retain cycles
* Create and use a custom delegate protocol
* Define functions that use blocks to communicate between loosely coupled objects
* Display editable tables of data
* Place views a specified number of points from their superview using Auto Layout
* Store and fetch temporary data on device using the file system
* Store and fetch data on device using Core Data
* Set up text input fields and show and hide the keyboard as appropriate
* Write automated tests for the model layer
* Debug apps by setting breakpoints and viewing runtime values
* Access the user's photos and camera
* Use local notifications to alert the user at a specific time
* Display a map interface with a custom zoom level and current location

### Challenges
* Write a todo app that allows the user to add and delete items from a list and stores them on device. The user should be able to set due dates that are formatted and displayed with each item. A local notification should remind the user about the task on the specified due date.
* Write an app that can access the user's photos and use the camera to take new photos for use within the app.

---

## Advanced
As an advanced iOS developer, you think and see things differently. You're starting to develop an intuition about when to use certain patterns and frameworks, and when not to. You're comfortable laying out complex designs with Auto Layout and creating animations for them. Your code is easy to reason about, and you write unit tests regularly for each layer of the app.

### Swift
* Develop and use functions with variadic parameters
* Develop and use functions with closure parameters
* Develop and use functions with generics
* Create and use generators and sequences
* Implement Swift's functional patterns
* Detect and report problems in Swift and post them to Open Radar
* Use Swift effectively with Objective-C and vice versa

### UI
* Space views evenly across the screen using spacer views (iOS 8) or stack views (iOS 9+)
* Understand and use constraint priorities
* Properly configure your user interface to handle multiple device sizes and orientations
* Animate views by modifying layout constraints
* Import and use custom fonts
* Draw with UIKit

### iOS
* Use KVO to communicate between loosely coupled objects
* Use Notification Center to communicate between loosely coupled objects
* Cache data from a web service for increased performance
* Swap out different interfaces (views) with animation
* Know when to use composition over inheritance
* Download files in the background
* Handle and respond to multi-touch events
* Handle warnings from the device so apps don't get shut down
* Import data into Core Data
* Link objects with dependencies in Core Data
* Build animated and user-driven transitions between view controllers
* Improve app performance by performing work concurrently with NSOperationQueue and Grand Central Dispatch
* Authenticate with a web service using OAuth 2
* Make apps accessible to more users using the Accessibility APIs
* Write automated tests for the controller layer using mocks and stubs as needed
* Understand code written in Objective-C
* Use push notifications to alert the user about events in your app
* Detect and report problems in iOS frameworks and post them to Open Radar

### Challenges
* Write an app that has several screens with relatively complex layouts. It should read and send data to a web service using OAuth 2 and store data in Core Data. It should also animate views based on user interaction and have a full suite of automated tests for the model and controller layers. Code should be structured well and be easy to reason about.

---

## Expert
As an expert, you know how to best architect your code for reuse, readability, and maintainability. You know Swift intimately, and you can read and maintain Objective-C code. You can pick up new iOS frameworks with ease; if something's possible to do in iOS, you can get it done. You've done internationalization, localization, and accessibility to make your apps more accessible to all types of users. And you do it all beautifully, simply, and consistently.

### Swift
* Understand and use operator overloading effectively
* Increase performance in Swift with compiler optimization techniques such as memoization
* Understand the internals of the Swift compiler and runtime

### UI
* Create a UI that shows and hides views dynamically based on data from a web service

### iOS
* Apply delegate, blocks, notification, and KVO patterns properly
* Localize apps for international use
* Create custom table view cells that resize dynamically using Auto Layout
* Master Xcode’s performance-tuning Instruments, including CPU Profiler, Leaks and Zombies
* Store credentials securely using the keychain
* Handle concurrency, caching, migrations, undo, and performance tuning with Core Data
* Create app extensions
* Know which pieces of the app will benefit from automated testing - and which ones won't - and write automated tests for the pieces that will benefit
* Understand and address the challenges of collaborating on Storyboards
* Create custom frameworks to share functionality between apps
* Know when to use built-in frameworks, when to use third-party frameworks, and when to build your own
* Architect large apps with multiple sources of data and interfaces
* Use design patterns appropriately to manage a large code base
* Build and maintain multiple apps that share a single code base
* Know how to write and maintain code in Objective-C

### Challenges
* Write an app with a complex UI that adjusts dynamically based on data from a web service as well as device size and orientation. The app should have a large number of screens, send and receive data from multiple web services using OAuth 2, store data in Core Data, use iOS 8 extensions, be localized for multiple regions, and perfom excellently. And it should be usable offline, queing web requests where appropriate to be sent when the connection is restored.
* You're an expert. You can do anything you need to do in iOS, and you can do it beautifully, simply, and consistently. You can and *do* create your own challenges. :-)

---

What are you waiting for? Get started with the 5-Part Guide to Swift, and then power through the Novice and Beginner levels in one day with the [iOS Boot Camp](http://roadfiresoftware.com/ios-boot-camp/).
