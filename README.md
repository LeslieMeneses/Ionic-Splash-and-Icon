# Ionic
Make your Splash and icon

# Make your splash and icon
http://blog.ionic.io/automating-icons-and-splash-screens/ </br>
1.  make the image splash.png icon.png in a resources directory.

    ./resources

    $ ionic resources

command will generate the icons and splash screen images for each platform setup in the project
If you only need to update one of the resources, or you only want to generate icons and not both, the ionic resources command has two flags that allow you to target each asset, instead of generating both.
    
    $ ionic resources --icon
    $ ionic resources --splash
 
 
