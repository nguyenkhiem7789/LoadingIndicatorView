# LoadingIndicatorView

<img src="https://user-images.githubusercontent.com/18132015/79178430-77ff3c80-7e2f-11ea-8ff6-a162da937196.jpg" width="300">

How to

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

    gradle
    maven
    sbt
    leiningen

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.nguyenkhiem7789:LoadingIndicatorView:0.1.0'
	}

Usage

...

    <com.nguyen.loadingindicator.LoadingView
      android:id="@+id/loadingView"
      android:layout_width="wrap_content"
      android:layout_height="wrap_content"
      app:loading_stroke="2dp"/>
     
...
       
