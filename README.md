# DontStealMyKey - reads values from an "external" file so you can keep your keys safe

A basic proof of concept for reading values into gradle, such as api keys, so that you can keep your keys safe when publishing your work.

<img src="art/image1.png" width="50%" />

# Summary
Reads a file through gradle and populates BuildConfig variables so they can be accessed in your app.
This project is just a basic proof of concept and just exists for easy reference in future.
Because there isn't really anything related to the UI for this example, the only reasonable thing to do was to add a picture of a cat.

# How it's done
The project makes use of an "external" file, a standard file you add to the project but you can add this to your gitignore so that it isn't tracked. Through gradle, 
this file then gets read as a key-value pair and you can then access these variables through BuildConfig fields you can define.

The majority of the project sits in Build.Gradle

# How would you run this ? 
You can simply clone this from github and open the project using android studio (the `master` branch is usually where the latest stable build can be found, `dev` is where I work on new features)  there shouldn't be any additional requirements or configurations needed.
