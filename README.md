# AWS Front-End Developer Tutorial

[AWS Lauch Your First Application–Front-End Developer–Build an iOS Application](https://aws.amazon.com/getting-started/hands-on/build-ios-app-amplify/?e=gs2020&p=frontend&p=gsrc&c=lp_fed)

## Purpose

Encountered a few bugs while trying out the tutorial, and I want to document those bugs and solutions here. 

I only included files that I worked with or modified, since the other files and folders may contain some senstive account info.

For **amplifyconfiguration.json** and **awsconfiguration.json files**, I used *** to replace sensitive account info.

Note that **AppDelegate.swift**, **ContentView.swift**, **info.plist**, and **SceneDelegate.swift** are supposed to be in a "iOS Getting Started" folder. 

I encountered errors from module 1, 3 and 4.

### Module 1: Create iOS APP

It was my first time creating an iOS APP in Xcode, so my set up was incorrect for the first time, and since the screenshot on the tutorial was different, I didn't realize the bug until I ran into the problem of having to add some codes in AppDelegate.swift in module 2.

AppDelegate.swift was missing due to my initial set up, so I couldn't proceed.

Found the solution from [stackoverflow](https://stackoverflow.com/questions/62538110/swiftui-app-life-cycle-ios14-where-to-put-appdelegate-code).

![solution-img](screenshots/appdelegate_solution.png)
