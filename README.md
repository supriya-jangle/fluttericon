import 'package:flutter/material.dart';
void main() => runApp(MyApp());
class MyApp extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return MaterialApp(
 home: IconDemo(),
 );
 }
}
class IconDemo extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return Scaffold(
 appBar: AppBar(title: Text('Flutter Icons Example')),
 body: Center(
 child: Column(
 mainAxisAlignment: MainAxisAlignment.center,
 children: <Widget>[
 Icon(
 Icons.home, // Flutter's built-in icon for home
 size: 50.0, // Icon size
 color: Colors.blue, // Icon color
 ),
 SizedBox(height: 20),
 Icon(
 Icons.favorite, // Flutter's built-in icon for favorite
 size: 50.0,
 color: Colors.red, // Icon color
 ),
 SizedBox(height: 20),
 Icon(
 Icons.search, // Flutter's built-in icon for search
 size: 50.0,
 color: Colors.green, // Icon color
 ),
 ],
 ),
 ),
 );
 }
}
