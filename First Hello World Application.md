# Making Your First App : Hello World
## 1. Welcome to Android Studio Screen
First, open Android Studio. You should see this window. Go ahead and click Start a new Android Studio Project. An Android Studio Project typically means the code and files for one Android Application.
<br>
Select the "Start a new Android Studio project" option

## 2. Configure your new project
For this app, use this configurations:
<br>
Application Name: Happy Birthday<br>
Company domain: android.example.com<b<br>r>
Project location: < Your choice of where to save this project on your computer >
<br>
These are the configurations we are using for this example project
<br>
## 3. Select the form factors your app will run on
We've decided to build this project for Phone and Tablets with Minimum SDK of API 15.
<br>
Remember that you can use the Help me choose link to see Android Platform/API Version distribution to see the number of active devices in the world running on each API.
<br>

We are building for Phone and Tablet and using API 15 as the Minimum SDK
<br>
## 4. Add an Activity to Mobile
In the latest version of Android Studio, you will need to select the "Empty Activity" option to have starter code that matches Lyla's from the previous video.
<br>

Select the "Empty Activity" option
<br>
## 5. Customize the Activity and Finish
For the new activity, give it these names:

Activity Name: MainActivity (Select Generate Layout File)<br>
Layout Name: activity_main (Select Backwards Compatibility (AppCompat))<br>
Once those options have been selected, click Finish to generate your first project!<br>


Name the activity MainActivity and the Layout Name activity_main<br>

Depending on your computer speed it might take a minute to set up your project. Go ahead and get some tea or do a stretch.
<br>
<br>
# Quick Start With Android Studio
[Check out video](https://www.youtube.com/watch?v=lGuh4lTWroY)
<br><br>

# Running Hello World in your phone
[Connect phone to your code](https://www.youtube.com/watch?time_continue=219&v=Q9z6fUSgKIg&feature=emb_logo)
<br><br>

```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:background="#F0F8FF">

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:background="#FAFAD2">


    <ImageView
            android:id="@+id/imagePNG1"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:src="@drawable/PNG1"
            android:layout_centerInParent="true" />

        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content">

            <TextView
                android:id="@+id/text1"
                android:layout_gravity="center"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:textSize="200dp"
                android:text="Happy Valentine's Day Pranjal!"
                android:background="@drawable/PNG1"/>

        </LinearLayout>

    </RelativeLayout>
</androidx.constraintlayout.widget.ConstraintLayout>
```
