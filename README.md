# iOS PHPhotoLibrary Python wrapper

This wrapper allows you to use the PHPhotoLibrary on iOS with Python.
This is just a custom wrapper for a couple of functions not a complete wrapper.

## Installation

### iOS

You need to use the latest kivy-ios toolchain:

    ./toolchain.py build pyPhotoLibrary

Then either create or update an Xcode project with the toolchain.

## Usage

    from pyPhotoLibrary import Photos
    photos.capture_image()

Show a standard camera interface and return the captured image.
If the device has no camera or if the camera interface is cancelled, None
is returned.

`save_image` has not yet been exposed.

	Photos.save(image)

