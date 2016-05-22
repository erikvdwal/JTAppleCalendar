![JTAppleCalendar](Images/JTAppleCalendar.jpg)

The final iOS calendar control you'll ever try


Inspiration for this control was made possible by Michael @ Karmadust. Want to know how the calendar control works inside out? [Check out his KDCalendar tutorial.](http://blog.karmadust.com/lets-create-a-calendar-using-a-uicollectionview/)


[![CI Status](http://img.shields.io/travis/patchthecode/JTAppleCalendar.svg?style=flat)](https://travis-ci.org/patchthecode/JTAppleCalendar) [![Version](https://img.shields.io/cocoapods/v/JTAppleCalendar.svg?style=flat)](http://cocoapods.org/pods/JTAppleCalendar) [![License](https://img.shields.io/cocoapods/l/JTAppleCalendar.svg?style=flat)](http://cocoapods.org/pods/JTAppleCalendar) [![Platform](https://img.shields.io/cocoapods/p/JTAppleCalendar.svg?style=flat)](http://cocoapods.org/pods/JTAppleCalendar)

### **About Screenshots**
Much like a UITableView, because you can design this calendar to look however you want, screenshots will not be an accurate depiction of what this control looks like, but you can check out what people have developed with this control and also post you own images [at this link.](https://github.com/patchthecode/JTAppleCalendar/issues/2). A sample iOS application is also included in this project's [Github Repository](https://github.com/patchthecode/JTAppleCalendar) to give you an idea of what you can do.

* Downloaded and liked this calendar's ease of use?
* Then don't forget to leave a ★ Star rating on Github. It's needed to make this control #1 :)
* Also, [Support](https://salt.bountysource.com/teams/jtapplecalendar) is not manditory, but will be much appreciated.

### **Features**
---

- [x] Boundary dates - limit the calendar date range
- [x] Week/month mode - show 1 row of weekdays. Or 2, 3 or 6
- [x] Custom cells - make your day-cells look however you want, with any functionality you want
- [x] Custom calendar view - make your calendar look however you want, with what ever functionality you want
- [x] First Day of week - pick anyday to be first day of the week
- [x] Horizontal or vertical mode
- [x] Ability to scroll to any month by simply using the date
- [x] Ability to design your calendar [however you want.](https://github.com/patchthecode/JTAppleCalendar/issues/2) You want it, you build it
- [x] [Complete Documentation](http://cocoadocs.org/docsets/JTAppleCalendar)


### **Requirements**
---

* iOS 8.0+ 
* Xcode 7.2+



### **Communication on Github**
---
* Found a bug? [open an issue](https://github.com/patchthecode/JTAppleCalendar/issues)
* Got a cool feature request? [open an issue](https://github.com/patchthecode/JTAppleCalendar/issues)
* Need a question answered? [open an issue](https://github.com/patchthecode/JTAppleCalendar/issues) 


### **Installation using CocoaPods**

CocoaPods is a dependency manager for Cocoa projects. Cocoapods can be installed with the following command:

$ gem install cocoapods



> CocoaPods 0.39.0+ is required to build JTAppleCalendar

To integrate JTAppleCalendar into your Xcode project using CocoaPods, specify it in your Podfile:

```ruby
platform :ios, '8.0'
use_frameworks!

pod 'JTAppleCalendar'
```

Then, run the following command at your project location:

```bash
$ pod install
```

### **The Problem**
---

1. Apple has no calendar control.
2. Other calendar projects on Github try to cram every feature into their control, hoping it will meet the programmer's requirements.

This is an incorrect way to build controls. It leaves the developer with an extremely wide selection of (in many cases non-conventional) features that he has to sift through in order to configure the calendar. Also, no matter how wide the feature selection, the developer is always restricted to a predefined configuration-set shipped with the calendarControl.  Do you see Apple building their `UITableView` by guessing what they think you want the UITableView to look like? No. So neither should we. 

### **The Solution: JTAppleCalendar**
---

#### Want to get started? 
[Quickly check out this documentation](https://github.com/patchthecode/JTAppleCalendar/wiki)


## Author

JayT, patchthecode@gmail.com

## License

JTAppleCalendar is available under the MIT license. See the LICENSE file for more info.
