在RecycleViewer的每个线性布局中，我们用RelativeLayout将两个TextViewer分别置于左右两端。出现左边为标题，右边为数字的效果

```xml
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
xmlns:android="http://schemas.android.com/apk/res/android"
xmlns:app="http://schemas.android.com/apk/res-auto"
xmlns:tools="http://schemas.android.com/tools"
android:layout_width="match_parent"
android:layout_height="48dp"
android:background="#161823">
    <TextView
        android:id="@+id/my_tv0"
        android:layout_width="200dp"
        android:layout_height="24dp"
        android:layout_marginTop="12dp"
        android:gravity="left"
        android:textSize="15sp"
        android:textColor="#99ffffff"/>
    <TextView
        android:id="@+id/my_tv1"
        android:layout_width="200dp"
        android:layout_marginTop="12dp"
        android:layout_height="24dp"
        android:textSize="15sp"
        android:gravity="right"
        android:layout_alignParentRight="true"
        android:text="32424324324"
        android:textColor="#99ffffff"/>
</RelativeLayout>
```

