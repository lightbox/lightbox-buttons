This project demonstrates how to create Android buttons with gradients, strokes and rounded corners using Android's built-in drawable resources.
![Buttons Overview](http://dl.dropbox.com/u/117731/buttons_main.png)

## Usage
In your layout, apply ``lightboxButton.Blue``, ``lightboxButton.Green`` or ``lightboxButton.Grey`` style to your button after adding this Android Library Project as a reference.

**Example:**
```xml
<Button
    style="@style/lightboxButton.Blue"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="Button" />
```

## Installation
1. Download the library
``git clone git://github.com/lightbox/lightbox-buttons.git``
2. Import LightboxButtons project into Eclipse:
``File -> Import Existing Projects into Workspace -> Select root directory
choose lightbox-buttons folder and Finish.``
3. Add LightboxButtons as a reference to your project:
``Right click on your Android Project, choose Properties -> Android -> Library -> Add and select "LightboxButtons" project.``

## Advantages (over using PNG files)
* Smaller APK size
* Easy to create color variations of the same button
* No need to use image editing tools such as Photoshop

## Screenshots
![Blue Buttons](http://dl.dropbox.com/u/117731/buttons_blue.png)
![Grey Buttons](http://dl.dropbox.com/u/117731/buttons_grey.png)
![Green Buttons](http://dl.dropbox.com/u/117731/buttons_green.png)

## Limitations
There is no inheritance mechanism for drawables, so you need to duplicate your XML files for different colors of the same button

## License
Apache License, Version 2.0 (http://www.apache.org/licenses/LICENSE-2.0.html)