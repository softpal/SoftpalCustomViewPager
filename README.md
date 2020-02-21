# SoftpalCustomViewPager

### Developed by
[Softpal](https://www.github.com/softpal)

### Why This Library?

    If You Want Swipe View Feature in Your Android App Use this Library.
    
   ## Installation

Add repository url and dependency in application module gradle file:
  
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

 ### Gradle
[![](https://jitpack.io/v/softpal/SoftpalCustomViewPager.svg)](https://jitpack.io/#softpal/SoftpalCustomViewPager)
```javascript
dependencies {
    implementation 'com.github.softpal:SoftpalCustomViewPager:1.0'
}
```

## Usage

 ## Adding in Your XML File
 
  <com.softpal.softpalcustomviewpager.CustomViewPager
        android:id="@+id/container"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:layout_behavior="@string/appbar_scrolling_view_behavior" />

 ### 1. Calling CustomViewPager in Your  Fragment
 
 setupViewPager(mViewPager);
		tabLayout.setupWithViewPager(mViewPager);
		mViewPager.setAdapter(mSectionsPagerAdapter);
    
    ```


