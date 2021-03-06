Resources
=======

This document contains a list of libraries and tools that help with Mac / iOS productivity.

iOS
--------
Below is the list of iOS libraries that are really common to use in almost every iOS project (in addition to **Haystack SDK**). The following libraries are Objective-C based, but can usually be used in Swift projects as well.

- [**AFNetworking**](https://github.com/AFNetworking/AFNetworking)

   Networking library with automatic JSON parsing and NSURLSession support.  
   `pod 'AFNetworking'`
   
- [**Alpha**](https://github.com/legoless/Alpha)

   Next generation debugging framework for iOS with scalable plugin architecture.   
   `pod 'Alpha'`
   
- [**ARAnalytics**](https://github.com/orta/ARAnalytics)

   Abstract analytics library includes most of the common analytics services and combines them into a single component.  
   `pod 'ARAnalytics'`
   
- [**BlocksKit**](https://github.com/pandamonia/BlocksKit)

   Block utility categories for many Foundation classes.  
   `pod 'BlocksKit'`
   
- [**DOSingleton**](https://github.com/stel/DOSingleton)

   Subclassable singleton object, used in almost every project.  
   `pod 'DOSingleton'`
   
- [**FLEX**](https://github.com/flipboard/FLEX)

   Debug tool for view hiearchy and memory.  
   `pod 'FLEX'`
   
- [**IQKeyboardManager**](https://github.com/hackiftekhar/IQKeyboardManager)
   
   Moves text fields and views out of the way of keyboard.  
   `pod 'IQKeyboardManager'`

- [**JLRoutes**](https://github.com/joeldev/JLRoutes)
   
   Setups special application routes with block-based callback API.  
   `pod 'JLRoutes'`

- [**JSONModel**](https://github.com/icanzilb/JSONModel)

   Create objects from JSON dictionaries by only defining the properties.  
   `pod 'JSONModel'`
   
- [**MagicalRecord**](https://github.com/magicalpanda/MagicalRecord)

   Active Record like fetching from Core Data database.  
   `pod 'MagicalRecord'`

- [**MSDynamicsDrawerViewController**](https://github.com/monospacecollective/MSDynamicsDrawerViewController)
   
   A view controller that has ability of drawers on all directions, built with UIKit dynamics.  
   `pod 'MSDynamicsDrawerViewController'`

- [**NUI**](https://github.com/tombenner/nui)

   An UI manager that allows theming of the application using a special variant of the CSS styles.  
   `pod 'NUI'`
   
- [**RBStoryboardLink**](https://github.com/rob-brown/RBStoryboardLink)

  A simple library that helps with separating storyboards.   
  `pod 'RBStoryboardLink'`
   
- [**Realm**](http://realm.io)
   
   Realm is a high performance database designed from ground up for mobile devices.   
   `pod 'Realm'`

- [**Reveal-iOS-SDK**](http://revealapp.com/)
   
   Reveal App is an easy to use application to debug UIView hierarchy. Only for debug builds.  
   `pod 'Reveal-iOS-SDK'`

- [**SDWebImage**](https://github.com/rs/SDWebImage)

   A very handy image caching library.

- [**SVPullToRefresh**](https://github.com/samvermette/SVPullToRefresh)
   
   Pull to refresh and infinite scrolling library for scroll views. Very easy to setup.  
   `pod 'SVPullToRefresh'`
   
- [**UrbanAirship**](https://urbanairship.com)
   
   Cross-platform push notification handling.  
   `pod 'UrbanAirship-iOS-SDK'`


The following libraries are Swift based and can be used only in iOS 8+ targets. Those libraries require the modifier: `use_frameworks!` in your podfile.

- [**Alamofire**](https://github.com/Alamofire/Alamofire)

   Networking library similar to AFNetworking with automatic JSON parsing and NSURLSession support.  
   `pod 'Alamofire'`
   
- [**Locksmith**](https://github.com/matthewpalmer/Locksmith)
  
  A powerful, protocol-oriented library for working with the keychain in Swift.   
  `pod 'Locksmith'`
   
- [**ObjectMapper**](https://github.com/Hearst-DD/ObjectMapper)
 
   Utility library for converting JSON dictionaries into your object models.  
   `pod 'ObjectMapper'`

- [**MagicalRecord**](https://github.com/magicalpanda/MagicalRecord)

   Active Record like fetching from Core Data database. Version 3.0 supports Swift.   
   `pod 'MagicalRecord'`
   
- [**Moya**](https://github.com/Moya/Moya)

   Separate networking layer based on AFNetworking.    
   `pod 'Moya'`
   
- [**SnapKit**](https://github.com/SnapKit/SnapKit)
   
   Similar to Masonry, SnapKit is a Swift based DSL for Auto-Layout.   
   `pod 'SnapKit'`

- [**XCGLogger**](https://github.com/DaveWoodCom/XCGLogger)
   
   Logger for Swift, that supports Xcode Colors.   
   `pod 'XCGLogger'`


Functional Reactive Programming
--------
Libraries under this category fall into FRP.

- [**ReactiveCocoa**](https://github.com/ReactiveCocoa/ReactiveCocoa)

  Started in Objective-C, but now fully supporting Swift.    
  `pod 'ReactiveCocoa'`

- [**RxSwift**](https://github.com/ReactiveX/RxSwift)

  Swift Reactive Extensions that originated with .NET.    
  `pod 'RxSwift'`


Xcode Plugins
--------
Useful Xcode plugins

- [**Alcatraz**](http://alcatraz.io)   
  
  Package manager for Xcode that installs any plugin with a single click.

- [**AtAutoCompletion**](https://github.com/wzqcongcong/AtAutoCompletion/)

  Autocompletion for @ signs in Xcode 6+.

- [**FuzzyAutocomplete**](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin)

  Fuzzy code autocompletion for Xcode.

- [**VVDocumenter**](https://github.com/onevcat/VVDocumenter-Xcode)

  Easy autocompletion for commenting methods and properties.

- [**Xcode Colors**](https://github.com/robbiehanson/XcodeColors)
  
  A plugin that displays colors in the Xcode console, works great together with XCGLogger.
