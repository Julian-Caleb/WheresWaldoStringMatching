# Where's Waldo — String Matching

IF2211 — Algorithm Strategy

## Short Description
This project locates Waldo in puzzle images using string-matching techniques. Puzzle images are converted to bitmaps and represented as binary strings; pattern samples are 80×80 pixel center crops of Waldo faces, also converted to binary strings. The program supports multiple matching algorithms and lets the user choose the method.

## Key Features
- Image preprocessing: convert puzzle images to bitmap and then to a binary string representation for matching.
- Pattern preparation: use several 80×80 center-cropped samples of Waldo as binary-string patterns.
- Algorithms: selectable matching algorithms — Brute Force, Knuth–Morris–Pratt (KMP), and Boyer–Moore (BM).
- Easy to run: add test puzzle images to the tc folder and run the main program in src.

## Usage
1. Clone the repository:
```
git clone https://github.com/Julian-Caleb/Makalah_Stima.git
```
2. Place the puzzle image(s) you want to search into the tc/ folder.
3. Run the main program located in the src/ folder.

![4yRcS2Zo_400x400](https://github.com/Julian-Caleb/Makalah_Stima/assets/90737534/27ae98c7-48a3-4b71-823a-721adcf733b3)
