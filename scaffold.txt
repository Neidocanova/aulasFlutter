import 'package:flutter/material.dart';

void main() {
  const myIcon = Icon(
    // Change the icon below (See linked site)
    Icons.waving_hand,
    // Change the color below
    color: Colors.yellow,
    // Change the size below
    size: 100.0,
  );
  runApp(
    const MaterialApp(
      home: Scaffold(
        body: myIcon
        )
      )
  );
}
