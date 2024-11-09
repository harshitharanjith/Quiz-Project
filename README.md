# Quiz-Project
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@android:color/holo_green_light">

    <androidx.recyclerview.widget.RecyclerView
        android:id="@+id/topicsRecyclerView"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:padding="16dp"/>
</RelativeLayout>

<androidx.cardview.widget.CardView xmlns:android="http://schemas.android.com/apk/res/android"
android:layout_width="match_parent"
android:layout_height="wrap_content"
android:layout_marginBottom="16dp"
app:cardElevation="4dp">

<TextView
    android:id="@+id/topicTitle"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:textSize="18sp"
    android:textColor="@android:color/black"
    android:padding="16dp"/>
</androidx.cardview.widget.CardView>
