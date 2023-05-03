# Profile-Page

Annesa Maisarah binti Ab Hamid ( 2011728 )

The code starts by importing the necessary libraries, including dart:io and package:flutter/material.dart for creating the UI and package:image_picker/image_picker.dart for picking images from the device's gallery.

Next, defining the MyApp class. This is a stateless widget that builds the app's main structure. It contains a MaterialApp widget with a title, theme, and a ProfilePage as the home page.

The ProfilePage class is a stateful widget that manages the app's state. It contains a boolean variable isObscurePassword that is used to toggle password visibility. The build method returns a Scaffold widget that provides the basic layout for the profile page. It has an AppBar widget with a title, a back button, and a settings button. The body of the Scaffold contains a Container widget with some padding and a ListView widget that displays the user's profile information.

Within the ListView, there is a GestureDetector widget that dismisses the keyboard when the user taps anywhere on the screen. The user's profile picture is displayed in a Container widget wrapped in a Stack. The picture is a DecorationImage with a NetworkImage source. A small edit icon is displayed at the bottom right of the picture. 

Next, there are two buildTextField widgets that display text input fields for the user's name and age. These widgets take in parameters such as the field's label text, placeholder text, and whether or not the field is a password field. 

Lastly, there is an ElevatedButton widget that allows the user to submit their profile information. The button is styled with a blue background, white text, and rounded edges.

![Screenshot_1683075293](https://user-images.githubusercontent.com/95832485/235817769-3a18ec46-f8ec-4a1d-95bd-36a468a70661.png)

![Screenshot_1683075315](https://user-images.githubusercontent.com/95832485/235817755-83cc8bc7-a621-4c37-91df-6d656472ed57.png)
