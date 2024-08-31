# -CircleImageViewLibrary
Welcome to the Efficient Canvas CircleImageView Library! This library simplifies the process of adding an optimized CircleImageView to your Android apps in android studio, sketchware,sketchware pro,etc.
Step 1:

Add the JitPack repository to your build file


dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' } /// For Kt use this only  maven("https://jitpack.io")
		}
	}

Step 2:

Add the dependency library // Canvas UI

dependencies {
	        implementation 'com.github.androidbulb:CircleImageViewLibrary:1.0'
	}



Step 3:

Efficient CircleImageView Canvas in your View.xml Example

<LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:gravity="center">
        <com.androidbulb.circleimage.CircleImageView
            android:id="@+id/img_icon"
            android:layout_width="150dp"
            android:layout_height="150dp"
            android:src="@drawable/test" />

    </LinearLayout>

    
 
