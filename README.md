#Adrestia iOS
The iOS client for College Confessions

## Technologies Used
iOS 9.0+
Swift 2.2
Cocoapods
...
More coming

## Installation
#### Repository
As always, first step is to clone the repository.
```
git clone git@github.com:adrestia/adrestia_ios.git
cd adrestia_ios
```
#### CocoaPods
We use CocoaPods for dependence management with iOS.
First thing you're going to need to do is install cocoapods.

`gem install cocoapods`

If you don't know, `gem` is referring to RubyGems.
You can most likely download that from any package manager.
`sudo apt-get install rubygems`

#### Dependencies
Now that CocoaPods is installed, run
`pod install`

This will install all of the necessary dependencies for the project.

## Developing
Once your workspace is installed/configured,
open up the project by double clicking on the `confessions.workspace`.

Don't open up the Xcode project directly,
since we want to be able to use the dependencies that were installed from CocoaPods.

