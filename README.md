# Custom-Toast

### Step 1. Create a Custom Layout for the Toast
- Create an XML layout file for your custom toast. For example, you can create a file named custom_toast_layout.xml in the res/layout directory:
```bash

<androidx.cardview.widget.CardView xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:orientation="horizontal"
    app:cardCornerRadius="6dp">

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:background="#FF4081"
        android:paddingHorizontal="6dp"
        android:paddingVertical="5dp"
        >


    <ImageView
        android:id="@+id/custom_toast_image"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginRight="7dp"
        android:contentDescription="Custom Icon"/>

    <TextView
        android:id="@+id/custom_toast_text"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textColor="#FFFFFF"
        />

    </LinearLayout>

</androidx.cardview.widget.CardView>

```







