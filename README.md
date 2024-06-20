# Moonlight for iOS (No Appstore Restrictions)

Moonlight for iOS is an open-source client for Sunshine and NVIDIA GameStream. This extended version of Moonlight for iOS allows you to stream your full collection of games and apps from your powerful desktop computer to your iOS device, bypassing App Store restrictions for external use.

Moonlight also has clients for PC and Android.

Check out the Moonlight wiki for more detailed project information, setup guide, or troubleshooting steps.

## Features
Stream games and apps from your desktop to your iOS device
Bypass App Store restrictions for external use
Supports Sunshine and NVIDIA GameStream
High performance with low latency
## Building the App
Install Xcode: Download and install Xcode from the App Store.
Clone the Repository:
bash
Copy code
git clone --recursive https://github.com/moonlight-stream/moonlight-ios.git
If you've already cloned the repo without --recursive, run:
bash
Copy code
git submodule update --init --recursive
Open the Project in Xcode:
bash
Copy code
open Moonlight.xcodeproj
Modify Signing Options for Real Devices:
Click on "Moonlight" at the top of the left sidebar.
Click on the "Signing & Capabilities" tab.
Under "Targets", select "Moonlight" (for iOS/iPadOS) or "Moonlight TV" (for tvOS).
In the "Team" dropdown, select your name. If your name doesn't appear, you may need to sign into Xcode with your Apple account.
Change the "Bundle Identifier" to something different. You can add your name or some random letters to make it unique.
Run the App:
Select your Apple device in the top bar as a target.
Click the Play button to run the app on your device.
