# Miwok Translator

This application helps teach the Miwok language. The app is an example of fragments coupled with an array adapter. It includes Miwok translations for colors, numbers, family members, and common phrases. These translations are accompanied by corresponding pictures and authentic Miwok audio pronunciations.

## Installation

Download Miwok Translator here:

[Miwok App](https://github.com/LaggerLimited/Android-Java-MiwokTranslation/blob/master/Miwok-debug.zip)

Install on the Android platform (minimum version 15)

## Usage

The application will display a list view populated with English words that can translated to the Miwok language. To navigate the app touch a category at the top of the screen or swipe left and right to view different categories. To hear the Miwok word be pronounced touch on the play button to the right of the word selection.

## Java Code

* [Main Activity](https://github.com/LaggerLimited/Android-Java-MiwokTranslation/blob/master/ud839_Miwok-3d00e8c7bb077adce9445212f785b79d0a906230/app/src/main/java/com/example/android/miwok/MainActivity.java): Initializes values, instantiates Views, and defines the tab layout.

* [Word Object](https://github.com/LaggerLimited/Android-Java-MiwokTranslation/blob/master/ud839_Miwok-3d00e8c7bb077adce9445212f785b79d0a906230/app/src/main/java/com/example/android/miwok/Word.java): Represents a vocabulary word to be listed in the list view.

* [Word Adapter](https://github.com/LaggerLimited/Android-Java-MiwokTranslation/blob/master/ud839_Miwok-3d00e8c7bb077adce9445212f785b79d0a906230/app/src/main/java/com/example/android/miwok/WordAdapter.java): Inflates the array with word objects and defines each list items' layout.

* [Category Adapter](https://github.com/LaggerLimited/Android-Java-MiwokTranslation/blob/master/ud839_Miwok-3d00e8c7bb077adce9445212f785b79d0a906230/app/src/main/java/com/example/android/miwok/CategoryAdapter.java): Defines the data each category will contain.

* [Colors Fragment](https://github.com/LaggerLimited/Android-Java-MiwokTranslation/blob/master/ud839_Miwok-3d00e8c7bb077adce9445212f785b79d0a906230/app/src/main/java/com/example/android/miwok/ColorsFragment.java): Fragment subclass for displaying Miwok color data.

* [Family Fragment](https://github.com/LaggerLimited/Android-Java-MiwokTranslation/blob/master/ud839_Miwok-3d00e8c7bb077adce9445212f785b79d0a906230/app/src/main/java/com/example/android/miwok/FamilyFragment.java): Fragment subclass for displaying Miwok family members data.

* [Numbers Fragment](https://github.com/LaggerLimited/Android-Java-MiwokTranslation/blob/master/ud839_Miwok-3d00e8c7bb077adce9445212f785b79d0a906230/app/src/main/java/com/example/android/miwok/NumbersFragment.java): Fragment subclass for displaying Miwok number data.

* [Phrases Fragment](https://github.com/LaggerLimited/Android-Java-MiwokTranslation/blob/master/ud839_Miwok-3d00e8c7bb077adce9445212f785b79d0a906230/app/src/main/java/com/example/android/miwok/PhrasesFragment.java): Fragment subclass for displaying Miwok common phrases data.

## XML Code

* [Screen Layout](https://github.com/LaggerLimited/Android-Java-MiwokTranslation/blob/master/ud839_Miwok-3d00e8c7bb077adce9445212f785b79d0a906230/app/src/main/res/layout/activity_main.xml): Defines the ListView and describes how each list item will be displayed.

* [List Item](https://github.com/LaggerLimited/Android-Java-MiwokTranslation/blob/master/ud839_Miwok-3d00e8c7bb077adce9445212f785b79d0a906230/app/src/main/res/layout/list_item.xml): Defines how the data will be displayed for each individual vocabulary word.

## Contributing
Pull requests are welcome. 

For major changes, please open an issue first to discuss what you would like to change.
