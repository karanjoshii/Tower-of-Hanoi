🗼 Tower of Hanoi – Interactive Web Game

An interactive browser-based implementation of the classic Tower of Hanoi problem built using HTML, CSS, and JavaScript.

This project visualizes recursion and demonstrates core Data Structures & Algorithms (DSA) concepts through a dynamic drag-and-drop interface.

🚀 Features

🎮 Drag-and-drop gameplay

🔁 Automatic recursive solution visualization

📊 Move counter tracking

🧮 Minimum move calculation using formula (2ⁿ − 1)

➕ Adjustable disk count (3 to 7 disks)

🔒 Rule enforcement (no larger disk on smaller disk)

⚡ Smooth animation using setTimeout()

📱 Responsive UI design

🧠 DSA Concepts Covered

This project demonstrates important Computer Science fundamentals:

✅ Recursion

✅ Divide and Conquer strategy

✅ Stack behavior using arrays (push() and pop())

✅ Recurrence relation

✅ Time complexity analysis

✅ Space complexity analysis

✅ Constraint-based problem solving

📌 Problem Overview

The Tower of Hanoi is a mathematical puzzle consisting of:

3 Towers (Start, Auxiliary, Destination)

N disks of different sizes

Rules:

Only one disk can be moved at a time.

Only the top disk of any tower can be moved.

A larger disk cannot be placed on a smaller disk.

Minimum Moves Formula

Minimum number of moves required:

2^n - 1

Where n is the number of disks.

🔁 Recursive Algorithm Used

To move n disks from Source → Destination using Auxiliary:

Move n-1 disks from Source → Auxiliary

Move the largest disk from Source → Destination

Move n-1 disks from Auxiliary → Destination

Recurrence Relation

T(n) = 2T(n-1) + 1

Time Complexity

O(2^n)

Space Complexity

O(n) (due to recursion stack depth)

🛠 Technologies Used

HTML5

CSS3

Vanilla JavaScript (ES6)

DOM Manipulation

Drag & Drop API

📂 Project Structure

Tower-of-Hanoi/
│
├── index.html
├── style.css
├── script.js
└── README.md

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/karanjoshii/Tower-of-Hanoi.git

Open index.html in your browser.

No additional setup required.

🎓 Learning Outcomes

Through this project, I strengthened my understanding of:

Recursive problem-solving

Algorithm visualization

JavaScript state management

Dynamic DOM rendering

Event-driven programming

💡 Future Improvements

Add iterative (non-recursive) solution implementation

Add recursion tree visualization

Add move history tracking

Improve animation performance for higher disk counts

Add sound effects

📌 Author

Developed as part of DSA and JavaScript learning practice.

⭐ If you found this project useful, feel free to star the repository!
