void main() {
  // Integer data type
  int myInt = 77;
  print('Integer: $myInt');

  // Double data type
  double myDouble = 9.35;
  print('Double: $myDouble');

  // String data type
  String myString = 'Explore Dart with Flutter!';
  print('String: $myString');

  // List data type
  List<int> myList = [21, 14, 99, 06, 25];
  print('List: $myList');

  // Map data type
  Map<String, dynamic> myMap = {
    'name': 'Waruku',
    'age': 57,
    'isGrandfather': false,
  };
  print('Map: $myMap');

  // Accessing elements in the list
  print('Accessing elements in the list:');
  for (int i = 0; i < myList.length; i++) {
    print('Element at index $i: ${myList[i]}');
  }

  // Accessing elements in the map
  print('Accessing elements in the map:');
  myMap.forEach((key, value) {
    print('$key: $value');
  });
}
