# Section 1 - Getting Started w/ iOS 13 and Swift 5.1

-   App Developer program is just for launching apps fully. No need to get one until needed
-   App Store connect can be used to check analytics about the App

# Section 2 - Xcode Storyboards and Interface Builder

-   The 'Interface' Drop down in XCode's new project setup should be set to 'Storyboard'

## 18. A Walkthrough of the Xcode Development Environment

-   The document outline (appears when you click on an object that is in a storyboard) shows the different objects on the screen. This is basically where the layers exist
    ![Document Outline](./Images/section-2/document-outline.png)
-   Look at the [XCode Shortcuts](https://swifteducation.github.io/assets/pdfs/XcodeKeyboardShortcuts.pdf) to improve efficiency
-   Right hand pane primarily used for different properties

## 19. Let's Design the User Interface

-   The 'View' (Located under the view controller) is basically the background of the app
-   Use [Colorhunt](https://colorhunt.co/) to figure out different palletes
    -   Makes it easy to design without having to actually design
-   Changing the X and Y coordinates for different objects aligns them onto a _graph_ onto an iPhone screen

## 20. Let's Incorporate some Image Assets

-   the 1x, 2x, and 3x image assets allow for scaling up for pixel sizes when necessary
-   Start with a 300x300 px size and scale down. Use the [App Icon Generator](https://appicon.co/#image-sets) to generate the different sized images

## 21. How to Design and Add an app icon

-   There is an App Icon generator at the above link to set up all the App Icons. Easy as dragging and dropping. XCode will figure it out itself
    -   AppIcon can be used to generate a whole new folder for the App Icon folder. This means we can just replace the assets folder and everything will be correctly placed
-   Designing a new app can be done using canva.com. Just need to use 1024x1024px

# Section 4 - Swift Programming Basics - Collections, Constants, Variables

-   'Scale to fill' fills the image view while 'aspect fill' fills the entire image view but keeps the aspect ratio intact
-   While holding the option key and clicking and dragging an object, the object is duplicated
-   To connect an object to the codebase, start by opening up the assistant view by clicking the dashes in the top right corner of the storyboard. The code file that matches the storyboard should pop up. To connect an object via code, hold the 'Control' key and drag and drop it into the code file

### Renaming Variables

-   Renaming variables/outlets is a bit more difficult than anticipated. Can't just change it in the code file because the connection that is created between the object in the design file and the code relies on that name. Rather than just changing the name, you'd have to disable the connection on the object in the design file.
-   A better way to do it though is right click on the variable that you want to change and click Refactor --> Rename
-   ImageLiteral can be used to change the value of an image. It is a small icon that you can see

## 40. Responding to User Interactions with IBActions

-   Buttons exist in the code file as actions. They create functions when an action (even in the properties) occurs
-   IB = Interface Builder

## 42. String Interpolation

    print("Text \(2+3) Text")

-   The backslash allows for code to be inserted mid text
