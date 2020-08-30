# delimeals
 Meal recipe app with filters and navigation
Based off Max's Flutter & Dart- The Complete Guide on Udemy
Navigation module

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