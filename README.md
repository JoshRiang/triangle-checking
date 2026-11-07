# Triangle Checker

A web app that classifies triangles based on three side lengths. Uses the triangle inequality theorem to validate input, then identifies the triangle type.

![Triangle Checker](https://user-images.githubusercontent.com/placeholder/triangle-checker.png)

## Features

- **Live Validation** - Results update as you type
- **Triangle Classification**:
  - Equilateral (Segitiga Sama Sisi) - all sides equal
  - Isosceles (Segitiga Sama Kaki) - two sides equal
  - Scalene (Segitiga Sembarang) - all sides different
  - Not a triangle (Bukan Segitiga) - violates triangle inequality

## How It Works

Enter three side lengths. The app checks:
1. **Triangle inequality**: no side may be ≥ sum of the other two
2. **Side comparison**: classifies by equal/unequal sides

## Tech Stack

- **Frontend**: HTML5, JavaScript (jQuery)
- **UI Framework**: Bootstrap 5, Font Awesome

## Project Structure

```
├── index.html            # Main interface
├── main.js               # Classification logic
└── jquery-3.6.0.min.js   # jQuery library
```

## Usage

Open `index.html` in any browser. No server required.

## License

MIT License