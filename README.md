![image](https://github.com/lampubohlam/intent_mobile-V2/assets/116137169/0c5628e1-8557-42e9-854f-4bb37cc64543)# intent_mobile-V2

<h4>Nama : Abdul Aziz
<br>Nim :312210022
<br>Matakuliah : Pemorograman Mobile
<br>Dosen   : Donny Maulana, S.Kom., M.M.S.I.</h4>

![image](https://github.com/lampubohlam/intent_mobile-V2/assets/116137169/8d904078-b92f-4cb9-b708-95d6da30177b)


# Menu utama
 disini saya hanya menambahkan coding dari button menjadi Imagebutton saja berikut hasil codingannya serta menambah linearliyout

           <?xml version="1.0" encoding="utf-8"?>
      <RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
      xmlns:tools="http://schemas.android.com/tools"
      android:layout_width="match_parent"
      android:layout_height="match_parent"
      tools:context=".MainActivity">


    <ImageView
        android:id="@+id/background"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:adjustViewBounds="true"
        android:scaleType="centerCrop"
        android:src="@drawable/background" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical"
        android:gravity="center_horizontal">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:gravity="center">

            <ImageButton
                android:id="@+id/btnHelloWorld"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_margin="20dp"
                android:background="@drawable/background_icon"
                android:onClick="btnHelloWorld"
                android:src="@drawable/world_icon"
                tools:ignore="UsingOnClickInXml,SpeakableTextPresentCheck" />

            <ImageButton
                android:id="@+id/btnProjectCount"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_margin="20dp"
                android:background="@drawable/background_icon"
                android:onClick="btnCount"
                android:src="@drawable/count_icon"
                tools:ignore="UsingOnClickInXml,SpeakableTextPresentCheck" />

            <ImageButton
                android:id="@+id/btnProjectSianida"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_margin="20dp"
                android:background="@drawable/background_icon"
                android:onClick="btnSianida"
                android:src="@drawable/cold_icon"
                tools:ignore="UsingOnClickInXml,SpeakableTextPresentCheck" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:orientation="horizontal">

            <ImageButton
                android:id="@+id/btnTwoActivity"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_margin="20dp"
                android:background="@drawable/background_icon"
                android:onClick="btnTwoActivity"
                android:src="@drawable/twoactivity_icon"
                tools:ignore="UsingOnClickInXml, SpeakableTextPresentCheck" />

            <ImageButton
                android:id="@+id/btnSetAlarm"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_margin="20dp"
                android:background="@drawable/background_icon"
                android:onClick="btnSetAlarm"
                android:src="@drawable/clock_icon"
                tools:ignore="UsingOnClickInXml,SpeakableTextPresentCheck" />
        </LinearLayout>

    </LinearLayout>
        </RelativeLayout>


serta saya menambahkan file baru di drawable untuk mengatur background si aplikasi agar menjadi bulat atau update V2
berikut codingannnya
              <?xml version="1.0" encoding="utf-8"?>
    <shape xmlns:android="http://schemas.android.com/apk/res/android">
    <solid android:color="@color/red"/>
    <corners android:radius="80dp"/>
    <size android:width="80dp" android:height="80dp"/>
    </shape>

        
        

