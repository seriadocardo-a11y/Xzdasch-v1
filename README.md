# Xzdasch-v1
Panel de sensibilidad y optimización para Android (sin Root)
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical"
    android:padding="24dp"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#1d151b">

    <TextView
        android:text="Xzdasch 👹"
        android:textSize="32sp"
        android:textStyle="bold"
        android:textColor="#B71C1C"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="sans-serif-condensed"
        android:shadowColor="#8B0000"
        android:shadowDx="2"
        android:shadowDy="2"
        android:shadowRadius="4" />

    <TextView
        android:text="Panel Sangriento Loveling"
        android:textSize="16sp"
        android:textColor="#ff5252"
        android:layout_marginBottom="24dp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />

    <View
        android:layout_width="match_parent"
        android:layout_height="6dp"
        android:background="#B71C1C"
        android:layout_marginBottom="18dp"/>

    <SeekBar
        android:id="@+id/sensitivitySeekBar"
        android:max="100"
        android:progress="50"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:thumbTint="#B71C1C"
        android:progressTint="#E57373"
        android:layout_marginTop="10dp"/>

    <TextView
        android:id="@+id/sensitivityLabel"
        android:text="Sensibilidad: 50"
        android:textColor="#B71C1C"
        android:textStyle="bold"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="24dp"/>

    <Button
        android:id="@+id/btnOptimize"
        android:text="¡Sangrienta Optimización!"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="#B71C1C"
        android:textColor="#fff"
        android:textStyle="bold"
        android:textSize="18sp"
        android:layout_marginTop="20dp"
        android:fontFamily="sans-serif-black"/>

    <TextView
        android:id="@+id/optimizationResult"
        android:text=""
        android:textColor="#ff5252"
        android:textStyle="italic"
        android:textSize="15sp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"/>

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="70dp"
        android:src="@drawable/blood_drip"
        android:layout_gravity="center"
        android:layout_marginTop="24dp"/>

</LinearLayout>