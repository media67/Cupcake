Cupcake app
=================================

This app contains an order flow for cupcakes with options for quantity, flavor, and pickup date.
The order details get displayed on an order summary screen and can be shared to another app to
send the order.

This app demonstrates multiple fragments in an activity, a shared ViewModel across fragments,
data binding, LiveData, and the Jetpack Navigation component.


Pre-requisites
--------------
* Familiar with activities and fragments
* How to use styles and themes in the UI
* Basic understanding of Jetpack architecture components including ViewModel and LiveData
* Data binding and binding expressions
* Kotlin syntax basics


Getting Started
---------------
1. Install Android Studio, if you don't already have it.
2. Download the sample.
3. Import the sample into Android Studio.
4. Build and run the sample.

Links listed throughout the code lab
-----------------------------------
- [Share ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel.html#sharing)
- [Jetpack Navigation](https://developer.android.com/guide/navigation)
- [Navigation - Getting started](https://developer.android.com/guide/navigation/navigation-getting-started)
- [Jetpack Navigation library](https://developer.android.com/jetpack/androidx/releases/navigation)
- [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) 
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture)
- [Data binding library](https://developer.android.com/topic/libraries/data-binding)
- [Android Jetpack](https://developer.android.com/jetpack)
- [scope function](https://kotlinlang.org/docs/reference/scope-functions.html)
- [SimpleDateFormat](https://developer.android.com/reference/java/text/SimpleDateFormat)
- [Locale](https://developer.android.com/reference/java/util/Locale)
- [repeat](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/repeat.html)
- [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)
- [compile time constants](https://kotlinlang.org/docs/reference/properties.html#compile-time-constants)
- [LifeCycleOwner](https://developer.android.com/reference/androidx/lifecycle/LifecycleOwner)
- [Transformations.map()](https://developer.android.com/reference/androidx/lifecycle/Transformations.html#map(androidx.lifecycle.LiveData%3CX%3E,%20androidx.arch.core.util.Function%3CX,%20Y%3E))
- [NumberFormat](https://developer.android.com/reference/kotlin/android/icu/text/NumberFormat)
- [how to create an email intent](https://developer.android.com/guide/components/intents-common#Email)
- [PackageManager](https://developer.android.com/reference/android/content/pm/PackageManager)
- [elvis operator](https://kotlinlang.org/docs/reference/null-safety.html#elvis-operator)
- [Test](https://developer.android.com/studio/test)
- [Training - test apps for Android](https://developer.android.com/training/testing)

Learn More
----------
- [Navigation Component](https://developer.android.com/guide/navigation/navigation-getting-started)
- [ViewModel overview](https://developer.android.com/topic/libraries/architecture/viewmodel)
- [Data binding](https://developer.android.com/topic/libraries/data-binding)
- [Layout and binding expressions](https://developer.android.com/topic/libraries/data-binding/expressions)
- [Transform LiveData](https://developer.android.com/topic/libraries/architecture/livedata#transform_livedata)
- [SimpleDateFormat](https://developer.android.com/reference/java/text/SimpleDateFormat)
- ['apply' score function in Kotlin](https://kotlinlang.org/docs/reference/scope-functions.html#apply) 
- [Compile time constants](https://kotlinlang.org/docs/reference/properties.html#compile-time-constants)
- [Principles of navigation](https://developer.android.com/guide/navigation/navigation-principles)
- [Understand tasks and back stack](https://developer.android.com/guide/components/activities/tasks-and-back-stack)
- [Navigation and the back stack](https://developer.android.com/guide/navigation/navigation-navigate#back-stack)
- [popUpTo and popUpToInclusive](https://developer.android.com/guide/navigation/navigation-navigate#pop)
- [Email intent](https://developer.android.com/guide/components/intents-common#Email)
- [Formatting strings](https://developer.android.com/guide/topics/resources/string-resource#formatting-strings)
- [Quantity strings(plural)](https://developer.android.com/guide/topics/resources/string-resource#Plurals)
- [Elvis operator in Kotlin](https://kotlinlang.org/docs/reference/null-safety.html#elvis-operator)

Extend the cupcake app
----------------------
Extend the Cupcake app with your own variations on the cupcake order flow. Examples:

    Offer a special flavor that has some special conditions around it, such as not being available for same day pickup.
    Ask the user for their name for the cupcake order.
    Allow the user to select multiple cupcake flavors for their order if the quantity is more than 1 cupcake.

What areas of your app would you need to update to accommodate this new functionality?
