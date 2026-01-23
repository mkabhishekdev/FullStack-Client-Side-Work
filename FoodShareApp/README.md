# FoodShareApp
Independent iOS Mobile Application developed - Food Share using Swift,Firebase,Cocoa pods

Motivation:
I wondered about this idea of connecting people for the cause of food :)
The purpose of my FoodShare App is to reduce Food wastage & share food with people who need it.

Project was developed in XCode environment using Swift. It was a MVC Architecture based project.
Why MVC?
 - Loosely coupled modules
 - Separation of concerns
 
                                                  CODE-FLOW
                       ----------------------------------------------------------------------------
                       
       1. User logins/registers using the Signup/login page.
       2. Storing the information of the application in a real time database, Firebase - A Google offering. It was the real time database used for user authentication and storage.
       3. Cocoa pods used: Firebase, Firebase database, FirebaseAuth, SwiftKey
          Why?
           - cocoapods is a dependency manager for Swift & Objective-C projects. It has over 27,000 libraries.
           - cocoapods help in scaling the project.
           Command: $sudo gem install cocoapods;
       4. Food Display based on the location.
          How was this done?
           - MapFramework was used,(MapKitView) available in the X-Code, just drag and drop to the storyboard.
       5. Map feature indicating direction to pick up food from the donor.
       
       
