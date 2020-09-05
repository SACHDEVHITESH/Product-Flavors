# Product-Flavors

Product flavor is a very powerful feature available in android gradle to manage different flavors of an app.
It’s basically used in when we need to maintain the paid and free version kind of thing.
Lets say I want to build an app with certain features only present in the paid versions so In that case I can use the product flavors.
Build Types is a feature like how we want to release the app i.e should we release the app in debug mode or release mode.
Debug mode is used for the testing purpose and the release mode is used for singing the apk and releasing it on playstore.

######To develop the project
1) In the app folder under gradle.build file add the product flavors(Like I have added free and paid)
2) In the src folder create a two folders free and paid( names have to be same what you added in step 1)
3) Then create a tree structure of the folders
4) Then you can edit the layout files and other folders based on the things you want to show in free and paid version of the app
5) Like here in the free version I have just shown three text boxes and paid version I have shown five text boxes.

######To run the app
1) In the left pane select build variants
2) Under Active Build Variant select freeDebug or freeRelease or paidDebug or paidRelease
3) Build the apk and run it

#Link to download the apk

https://drive.google.com/drive/folders/13oQmFpxNytAW6XfBXhScql34-p0YLrAB?usp=sharing


