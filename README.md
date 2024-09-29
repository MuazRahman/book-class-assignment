# book-class-assignment
# Book Class in Dart

A simple Dart class that tracks the title, author, publication year, and pages read of a book. The class also calculates the book's age and keeps a count of the total books created.

## Features

- Track book details (title, author, publication year).
- Log the number of pages read.
- Calculate the age of the book.
- Maintain a static count of total books.

## Usage

```dart
Book book1 = Book("To Kill a Mockingbird", "Harper Lee", 1960);
book1.read(100);

print("Pages Read: ${book1.getPagesRead()}");
print("Book Age: ${book1.getBookAge()} years old");
```
## Requirements
- [Dart-SDK](https://dart.dev/get-dart) installed.
- A Dart-compatible IDE or text editor.
(Offline IDE: [Android Studio](https://developer.android.com/studio/install) or Online IDE: [DartPad](https://dartpad.dev/))
