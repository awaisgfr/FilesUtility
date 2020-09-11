# FilesUtility
Library for handling Files related functions.

---------------------------------------------

***Implementation:***

You can add this libray by steps followed:

In Project level build.Gradle:

allprojects {
		repositories {

			maven { url 'https://jitpack.io' }
		}
	}

In app level build.Gradle:

dependencies {
	        implementation 'com.github.awaisgfr:FilesUtility:1.0'
	}

--------------------------------------------

***Usage***

initalize like:

FileUtils fileUtils=new FileUtils(context);



