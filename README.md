---
tags: Android, XML, layout
language: java
---

Android-AboutMe
===============

### Skills: Android XML Layout System, Android Studio 

## Instructions

The attached project has an Activity called ProfileActivity, which inflates a view onto it's fragment.  For this lab, you won't need to modify the ProfileActivity.  Instead, you'll need to create an XML Layout called `fragment_profile.xml` which will contain the layout for a single view.  The layout will present the following information: 

 - Name
 - Photo
 - Height
 - Birthday 
 - Favorite movie 

 Your `fragment_profile.xml` file should contain the following structure.  

```xml
 <LinearLayout>
 	<TextView>
 	<ImageView>
 	<TextView>
 	<TextView>
 	<TextView>	
 </LinearLayout> 
```

Make sure to use your projects Strings.xml file to define static strings for your TextViews.  

![AboutMeUI](AboutMeScreenshot.png)