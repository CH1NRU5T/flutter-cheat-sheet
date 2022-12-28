# Flutter Cheat Sheet

## SVG in flutter

Use the following package: `flutter_svg`

```dart
SvgPicture.asset(
    iconPath, // enter full path
    color: iconColor,
    width: 25,
),
```

## TextButton with Icon

![textbutton with icon](./images/textbutton%20with%20icon.png)

```dart
TextButton.icon(
      onPressed: () {},
      icon: // type : widget
      // google icon
      label: Text('hello'),
      style: TextButton.styleFrom(
        padding: EdgeInsets.symmetric(
          vertical: 15,
          horizontal: horizontalPadding,
          // take horizontal padding from constructor
        ),
        shape: RoundedRectangleBorder(
          borderRadius: BorderRadius.circular(10),
          side: const BorderSide(
            width: 3,
            color: Colors.grey,
          ),
        ),
      ),
    );
```
