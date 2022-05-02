## AppBar Widget

<p> An app bar consists of a toolbar and potentially other widgets, such as a TabBar and a FlexibleSpaceBar. App bars typically expose one or more common actions with IconButtons which are optionally followed by a PopupMenuButton for less common operations (sometimes called the "overflow menu").</p>

### Commonly used properties
1. shape
2. backgroundColor
3. centerTitle
4. titleSpacing
5. shadowColor
6. title

### Shape
We will use the shape property to define the shape of the app bar's Material as well as its shadow.

```dart
Scaffold(
appBar: AppBar(
shape: const Border(top: BorderSide(color: Colors.green, width: 3)),
),
body:Container()
);
```

Output:

![image](https://user-images.githubusercontent.com/42006848/166158940-ff2a5cb5-6086-4d37-a204-93502e452ce0.png)

### backgroundColor

The color of the Material widget that underlies the entire Scaffold.

```dart
Scaffold(
appBar: AppBar(
backgroundColor: Theme.of(context).cardColor,
),
body:Container()
);
```

Output: 

![image](https://user-images.githubusercontent.com/42006848/166294275-0e732707-1e8d-493e-bd25-269a5e7149af.png)

### title

The primary widget displayed in the app bar.

Becomes the middle component of the NavigationToolbar built by this widget.

Typically a Text widget that contains a description of the current contents of the app.


```dart
Scaffold(
appBar: AppBar(
title: Text(widget.title),
),
body:Container()
);
```

Output:

![image](https://user-images.githubusercontent.com/42006848/166295487-aa472f9e-1bcb-469c-b80d-5bdb99ccd90a.png)




### centerTitle

Whether the title should be centered.

If this property is null, then AppBarTheme.centerTitle of ThemeData.appBarTheme is used. If that is also null, then value is adapted to the current TargetPlatform.

```dart
Scaffold(
appBar: AppBar(
title: Text(widget.title),
centerTitle: false,
),
body:Container()
);
```

Output:

![image](https://user-images.githubusercontent.com/42006848/166294585-f867ae4b-7b2f-489d-a593-e74b81d2dea5.png)


### titleSpacing

The spacing around title content on the horizontal axis. This spacing is applied even if there is no leading content or actions. If you want title to take all the space available, set this value to 0.0.

```dart
Scaffold(
appBar: AppBar(
title: Text(widget.title),
centerTitle: false,
titleSpacing: 20,
),
body:Container()
);
```

Output: 

![image](https://user-images.githubusercontent.com/42006848/166294953-c037d6db-f996-47e5-9c0b-07f64fc9ae3d.png)

### shadowColor

The color of the shadow below the app bar.

```dart
Scaffold(
appBar: AppBar(
title: Text(widget.title),
centerTitle: false,
titleSpacing: 20,
shadowColor: Theme.of(context).shadowColor,
),
body:Container()
);
```

Output:

![image](https://user-images.githubusercontent.com/42006848/166295270-10d657d5-b615-4792-96ce-c17e3a895241.png)

