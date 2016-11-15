##amdiv (Android Material Designs Icon View)
Tried of keeping up with image icons? Simply make icons using TextViews, no visual quality lost, no resolution loss, Change icon colors on the Fly!


##Installation
1. Download this whole repo and unzip somewhere
2. Copy the 'MaterialDesignIcons.ttf' file into '/assets/icons'
3. Copy/import the 'MaterialDesignIconsTextView.java' in your project.
4. Open the `demo.html` in your browser and pick any icon you want and get the code e.g `0xe9fb`.

##Creat a string resource
    //with the icon code you picked from the previous step create a string resource
    <string name="my_icon">&#xe9fb;</string> 


##Create a TextView

                <.MaterialDesignIconsTextView
                    android:id="@+id/my_account"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:textColor="#fff"
                    android:textSize="24dp"
                    android:text="@string/my_icon"
                    tools:ignore="SpUsage" />

## All other methods are similar to android textview class, you can change, size, color e.t.c
