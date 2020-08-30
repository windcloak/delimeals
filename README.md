# delimeals
This is a meal recipe app with filters and navigation. You can change the filters to only look at certain types of receipes (e.g. vegan only), and you can add recipes to your Favorites section.

I followed Adademind's Flutter & Dart- The Complete Guide tutorial to make this. This is part of his Navigation module.

# How to Install
Open in Visual Studio Code, and run `flutter pub get` to get packages

Ctrl + F5 or `flutter run` to open the app on a real android/iphone device or a simulator.

# Preview
You can favorite a meal.
<img src="assets/images/demo1.gif">

Or you can filter the meals.
<img src="assets/images/demo2.gif">

# Navigation basics
- Screens (or Routes, Pages) are widgets
- Flutter Navigator lets you switch (push/pop/replace) between pages
- Named routes (preferred) or unnamed routes
- Named route: Make new dart file and give it a name (like title in webpage)
```static const routeName = '/meal-detail';```

# Passing Data
- Data can be passed via arguments
- Data can be passed back too (read via Future)
- Futures are objects that allow you to specify a function once they're done with a certain operation (eg the operation is displaying a page we're going to)
- Data can be strings, ints, objects (anything)

# Tabs
- You can add tabs in AppBar or at bottom of page (like a footer)
- Tabs let you switch between different stacks (no popping)

# Drawers and Dialogs
- Drawers (side menus, similar to navbar) let you switch between different stacks
- Drawers and other dialogs (alerts, modal bottom sheet) can be closed via Navigator.pop() 