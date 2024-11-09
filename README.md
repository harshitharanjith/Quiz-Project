# Quiz-Project
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#DFFFD6"
    android:padding="16dp">

    <!-- App title or header -->
    <TextView
        android:id="@+id/title"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Choose a Quiz Topic"
        android:textSize="24sp"
        android:textColor="#004D40"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="20dp"
        android:layout_marginTop="20dp" />

    <!-- Container for topic cards -->
    <LinearLayout
        android:id="@+id/cardContainer"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:layout_below="@id/title"
        android:layout_marginTop="20dp"
        android:gravity="center">

        <!-- Nature Topic Card -->
        <ImageButton
            android:id="@+id/cardNature"
            android:layout_width="match_parent"
            android:layout_height="120dp"
            android:src="@drawable/nature" <!-- Replace with your image name -->
        android:contentDescription="Nature"
        android:scaleType="centerCrop"
        android:layout_marginBottom="10dp" />

        <!-- Science Topic Card -->
        <ImageButton
            android:id="@+id/cardScience"
            android:layout_width="match_parent"
            android:layout_height="120dp"
            android:src="@drawable/science" <!-- Replace with your image name -->
        android:contentDescription="Science"
        android:scaleType="centerCrop"
        android:layout_marginBottom="10dp" />

        <!-- Computer Science Topic Card -->
        <ImageButton
            android:id="@+id/cardComputerScience"
            android:layout_width="match_parent"
            android:layout_height="120dp"
            android:src="@drawable/computer_science" <!-- Replace with your image name -->
        android:contentDescription="Computer Science"
        android:scaleType="centerCrop" />
    </LinearLayout>

</RelativeLayout>
