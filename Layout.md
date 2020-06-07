# XO-Game
Built using Android studio 4.4
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/activity_main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    tools:context="com.ajayuzumaki.conc.MainActivity"
    android:background="?attr/colorPrimary">

    <GridLayout
        android:layout_width="360dp"
        android:layout_height="360dp"
        android:background="@drawable/board"
        android:columnCount="3"
        android:rowCount="3"
        android:layout_alignParentTop="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:id="@+id/gridlayout">

        <ImageView
            android:layout_width="90dp"
            android:layout_height="90dp"
            android:id="@+id/imageView9"
            android:layout_row="2"
            android:layout_column="0"
            android:layout_marginTop="30dp"
            android:layout_marginLeft="10dp"
            android:onClick="click"

            android:tag="6" />

        <ImageView
            android:layout_width="90dp"
            android:layout_height="90dp"
            android:id="@+id/imageView8"
            android:layout_row="2"
            android:layout_column="1"
            android:layout_marginTop="30dp"
            android:layout_marginLeft="30dp"
            android:onClick="click"

            android:tag="7" />

        <ImageView
            android:layout_width="90dp"
            android:layout_height="90dp"
            android:id="@+id/imageView7"
            android:layout_row="2"
            android:layout_column="2"
            android:layout_marginTop="30dp"
            android:layout_marginLeft="30dp"
            android:onClick="click"

            android:tag="8" />

        <ImageView
            android:layout_width="90dp"
            android:layout_height="90dp"
            android:id="@+id/imageView6"
            android:layout_row="0"
            android:layout_column="1"
            android:layout_marginTop="20dp"
            android:layout_marginLeft="30dp"
            android:onClick="click"

            android:tag="1" />

        <ImageView
            android:layout_width="90dp"
            android:layout_height="90dp"
            android:id="@+id/imageView5"
            android:layout_row="0"
            android:layout_column="2"
            android:layout_marginTop="20dp"
            android:layout_marginLeft="30dp"
            android:onClick="click"

            android:tag="2" />

        <ImageView
            android:layout_width="90dp"
            android:layout_height="90dp"
            android:id="@+id/imageView4"
            android:layout_row="1"
            android:layout_column="0"
            android:onClick="click"

            android:layout_marginTop="25dp"
            android:tag="3" />

        <ImageView
            android:layout_width="90dp"
            android:layout_height="90dp"
            android:id="@+id/imageView2"
            android:layout_row="1"
            android:layout_column="2"
            android:layout_marginTop="25dp"
            android:layout_marginLeft="30dp"
            android:onClick="click"

            android:tag="5" />

        <ImageView
            android:layout_width="90dp"
            android:layout_height="90dp"
            android:id="@+id/imageView3"
            android:layout_row="1"
            android:layout_column="1"
            android:layout_marginTop="25dp"
            android:layout_marginLeft="30dp"
            android:onClick="click"

            android:tag="4" />

        <ImageView
            android:layout_width="90dp"
            android:layout_height="90dp"
            android:id="@+id/imageView"
            android:layout_row="0"
            android:layout_column="0"
            android:layout_marginTop="20dp"
            android:onClick="click"

            android:tag="0" />


    </GridLayout>

    <LinearLayout
        android:orientation="vertical"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="26dp"
        android:id="@+id/tryagain"
        android:visibility="invisible"
        android:layout_alignParentBottom="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_marginLeft="28dp"
        android:layout_marginStart="28dp">

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:id="@+id/textView7" />

        <Button
            android:text="Play AGAIN"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:id="@+id/button3"
            android:onClick="playagain"
            android:background="@android:color/holo_orange_dark" />
    </LinearLayout>

    <TextView
        android:text="AJAY's XOXO"
        android:layout_width="150dp"
        android:layout_alignParentBottom="true"
        android:layout_alignParentRight="true"
        android:layout_alignParentEnd="true"
        android:layout_marginRight="15dp"
        android:layout_marginEnd="15dp"
        android:id="@+id/textView8"
        android:background="@android:color/holo_orange_dark"
        android:textAppearance="@style/TextAppearance.AppCompat.Body2"
        android:textAlignment="center"
        android:layout_height="20dp" />

</RelativeLayout>
