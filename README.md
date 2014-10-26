DollarAndCentDemoApp
====================

Demo App showing how to integrate the functional library Dollar into your Swift App

### Steps ###
1. Using git add Dollar as a submodule using `git submodule add https://github.com/ankurp/Dollar.swift.git`.
2. Open the Dollar.swift folder. Drag Dollar.xcodeproj, inside the Dollar folder, into the file navigator of your Xcode project.
3. In Xcode, navigate to the target configuration window by clicking on the blue project icon, and selecting the application target under the "Targets" heading in the sidebar.
4. In the tab bar at the top of that window, open the "Build Phases" panel.
5. Expand the "Link Binary with Libraries" group, and add Dollar.framework.
6. In your project file `import Dollar` and you can call all of the helper functions.
