https://github.com/Droppers/AnimatedBottomBar

implementation 'nl.joery.animatedbottombar:library:1.1.0'

<nl.joery.animatedbottombar.AnimatedBottomBar
    android:id="@+id/bottom_bar"
    android:background="#FFF"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:abb_selectedTabType="text"
    app:abb_indicatorAppearance="round"
    app:abb_indicatorMargin="16dp"
    app:abb_indicatorHeight="4dp"
    app:abb_tabs="@menu/tabs"
    app:abb_selectedIndex="0" />


    <menu xmlns:android="http://schemas.android.com/apk/res/android">
    <item
        android:id="@+id/tab_home"
        android:icon="@drawable/home"
        android:title="@string/home" />
    <item
        android:id="@+id/tab_alarm"
        android:icon="@drawable/alarm"
        android:title="@string/alarm" />
    <item
        android:id="@+id/tab_bread"
        android:icon="@drawable/bread"
        android:title="@string/bread" />
    <item
        android:id="@+id/tab_cart"
        android:icon="@drawable/cart"
        android:title="@string/cart" />
</menu>
