## To create a Welcome Activity to display messages.
## AIM:
To create a Welcome Activity to display messages using Android Studio.

## EQUIPMENTS REQUIRED:
Android Studio(Min.required Artic Fox)

## ALGORITHM:
Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Change the text colour

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
## activity_main.xml
``` java

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="welcome"
        android:textColor="#E91E63"
        android:textColorHighlight="#00BCD4"
        android:textColorHint="#E91E63"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>



## MainActivity.java

package com.example.recircle1;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
}


```
## OUTPUT
![5](https://user-images.githubusercontent.com/78194419/165477057-21fda754-f9d1-4233-a088-693733e05c0b.png)





## RESULT
Thus a Simple Android Application create a welcome Activity to display messages using Android Studio is developed and executed successfully.
