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
We will use the shape property to give the define the shape of the app bar's Material as well as its shadow.

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

