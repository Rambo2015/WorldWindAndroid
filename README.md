# World Wind Android #

World Wind Android is a 3D virtual globe API for [Android](http://developer.android.com). You can use it to provide a
geographic context, complete with terrain, for visualizing geographic or geo-located information. World Wind Android
provides high-resolution terrain and imagery, retrieved from remote servers automatically as needed. You can also
provide your own terrain and imagery. World Wind Android additionally provides a rich collection of shapes that you can
use to represent information on the globe or in space.

# Important Sites

- [World Wind Examples](http://worldwindserver.net/android/latest/worldwind-examples.apk) runs on devices with Android
  4.4 (KitKat) and newer
- [World Wind Library](http://worldwindserver.net/android/latest/worldwind.aar) provides the World Wind Library as an Android Archive (AAR)
- [API Docs](http://worldwindserver.net/android/latest/doc) gives class level details for developers
- [JIRA](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA/) provides requirement and issue tracking
- [World Wind Forum](http://forum.worldwindcentral.com) provides help from the World Wind community
- [Android Studio](http://developer.android.com/sdk/) is used for World Wind Android development

# Release 0.2.0, May 13, 2016

World Wind Android v0.2.0 adds support for screen placemarks and navigation events. The World Wind Android Examples
app demonstrates NASA World Wind display of MIL-STD-2525C tactical icons by leveraging point placemarks and the US Army
Mission Command's [MIL-STD-2525 symbol rendering library](https://github.com/missioncommand/mil-sym-android).

This release establishes World Wind support for threaded rendering. Applications are now able to access World Wind
components from the Activity thread without any synchronization, while the actual OpenGL commands are executed in the
Android GLSurfaceView component's rendering thread.

- [World Wind Examples 0.2.0](http://worldwindserver.net/android/0.2.0/worldwind-examples.apk) - Example App for 0.2.0; runs on Android 4.4 and newer
- [World Wind Library 0.2.0](http://worldwindserver.net/android/0.2.0/worldwind.aar) - Android Archive (AAR) for 0.2.0
- [API Docs 0.2.0](http://worldwindserver.net/android/0.2.0/doc) - Developer documentation for 0.2.0
- [JIRA 0.2.0](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA/fixforversion/10912) - Detailed release notes for 0.2.0

#### Release Notes

###### Requirement
- [WWA-4](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-4) - Navigation Events
- [WWA-11](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-11) - Screen placemark
- [WWA-33](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-33) - MIL-STD-2525 support

###### Task
- [WWA-68](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-68) - Bitmap image source
- [WWA-71](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-71) - Threaded rendering
- [WWA-72](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-72) - Performance metrics

###### Bug
- [WWA-70](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-70) - WMS layer makes requests outside layer bounds

# Release 0.1.0, March 30, 2016

World Wind Android's initial prototype release. This release establishes the baseline for World Wind Android
development. It provides a basic navigable 3D globe capable of displaying imagery from OGC Web Map Service (WMS) layers,
has support for displaying local and remote images on the globe, and provides a rich interface for manipulating the
virtual camera.

- [World Wind Examples 0.1.0](http://worldwindserver.net/android/0.1.0/worldwind-examples.apk) - Example App for 0.1.0; runs on Android 4.4 and newer
- [World Wind Library 0.1.0](http://worldwindserver.net/android/0.1.0/worldwind.aar) - Android Archive (AAR) for 0.1.0
- [API Docs 0.1.0](http://worldwindserver.net/android/0.1.0/doc) - Developer documentation for 0.1.0
- [JIRA 0.1.0](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA/fixforversion/10911) - Detailed release notes for 0.1.0

#### Release Notes

###### Requirement
- [WWA-2](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-2) - Surface image
- [WWA-3](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-3) - Navigation
- [WWA-6](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-6) - WMS image layer
- [WWA-20](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-20) - Android example apps

###### Task
- [WWA-57](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-57) - Android project structure
- [WWA-59](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-59) - Rendering infrastructure
- [WWA-60](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-60) - Vector and geographic primitives
- [WWA-61](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-61) - Navigation gesture detectors
- [WWA-62](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-62) - WorldWindow
- [WWA-63](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-63) - Global tessellation
- [WWA-64](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-64) - Units tests for version 0.1.0
- [WWA-65](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-65) - Stub classes for version 0.1.0
- [WWA-66](http://issues.worldwind.arc.nasa.gov/jira/browse/WWA-66) - Logging infrastructure
