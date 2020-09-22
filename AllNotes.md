# Section 1 - Getting Started w/ iOS 13 and Swift 5.1

-   App Developer program is just for launching apps fully. No need to get one until needed
-   App Store connect can be used to check analytics about the App

# Section 2 - Xcode Storyboards and Interface Builder

-   The 'Interface' Drop down in XCode's new project setup should be set to 'Storyboard'

## 18. A Walkthrough of the Xcode Development Environment

-   The document outline (appears when you click on an object that is in a storyboard) shows the different objects on the screen. This is basically where the layers exist
    ![Document Outline](/Users/nealmatta/Documents/GitHub/iOS13-Swift-5-Notes/Images/section-2/document-outline.png)
-   Look at the [XCode Shortcuts](https://swifteducation.github.io/assets/pdfs/XcodeKeyboardShortcuts.pdf) to improve efficiency
-   Right hand pane primarily used for different properties

## 19. Let's Design the User Interface

-   The 'View' (Located under the view controller) is basically the background of the app
-   Use [Colorhunt](https://colorhunt.co/) to figure out different palletes
    -   Makes it easy to design without having to actually design
-   Changing the X and Y coordinates for different objects aligns them onto a _graph_ onto an iPhone screen

## Let's Incorporate some Image Assets

-   the 1x, 2x, and 3x image assets allow for scaling up for pixel sizes when necessary
-   Start with a 300x300 px size and scale down. Use the [App Icon Generator](https://appicon.co/#image-sets) to generate the different sized images

## How to Design and Add an app icon

-   There is an App Icon generator at the above link to set up all the App Icons. Easy as dragging and dropping. XCode will figure it out itself
    -   AppIcon can be used to generate a whole new folder for the App Icon folder. This means we can just replace the assets folder and everything will be correctly placed
-   Designing a new app can be done using canva.com. Just need to use 1024x1024px
