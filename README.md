## ⚠️ Notice

This version of `ox_target` has been modified to improve compatibility with the latest version of `qb-core`. It is based on a prior QB-compatible version but updated.

Please be aware that `ox_target` is the property of the Overextended team and remains under its original license. All changes in this version aim to retain core functionality while adapting it for modern `qb-core` environments.

**Note:** The Overextended team does not provide support for `qb-core`, and this project has been archived. Please avoid contacting them regarding this modified version.

# ox_target

![](https://img.shields.io/github/downloads/overextended/ox_target/total?logo=github)
![](https://img.shields.io/github/downloads/overextended/ox_target/latest/total?logo=github)
![](https://img.shields.io/github/contributors/overextended/ox_target?logo=github)
![](https://img.shields.io/github/v/release/overextended/ox_target?logo=github) 


A performant and flexible standalone "third-eye" targeting resource, with additional functionality for supported frameworks.

ox_target is the successor to qtarget, which was a mostly-compatible fork of bt-target.
To improve many design flaws, ox_target has been written from scratch and drops support for bt-target/qtarget standards, though partial compatibility is being implemented where possible.


## 📚 Documentation

https://overextended.dev/ox_target

## 💾 Download

https://github.com/overextended/ox_target/releases/latest/download/ox_target.zip

## ✨ Features

- Improved entity and world collision than its predecessor.
- Improved error handling when running external code.
- Menus for nested target options.
- Partial compatibility for qtarget (the thing qb-target is based on, I made the original idiots).
- Registering options no longer overrides existing options.
- Groups and items checking for supported frameworks.
