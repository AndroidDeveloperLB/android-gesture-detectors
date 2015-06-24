Android Gesture Detectors Framework - just the library, with some fixes
===================================
This is a fork of this repo:

https://github.com/Almeros/android-gesture-detectors

The changes are that it includes only the library, it has a tiny fix for touches (shown here: https://github.com/Almeros/android-gesture-detectors/issues/5 ) , and it's available via gradle, this way :

    repositories {
	    maven {
	        url "https://jitpack.io"
	    }
	}
	
    dependencies {
	        compile 'com.github.AndroidDeveloperLB:android-gesture-detectors:3cdeab048d'
	}
