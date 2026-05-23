# 😊 Turtle Emoji Face

A simple and beginner-friendly Python project that draws a smiley emoji using the built-in Turtle Graphics library.

---

## 📌 Features

* Draws a yellow emoji face
* Creates smiling mouth expression
* Adds black eyes
* Beginner-friendly project
* Uses Python Turtle Graphics
* Easy to customize and modify

---

## 🛠️ Technologies Used

* Python
* Turtle Graphics Library

---

## 📂 Project Structure

```text id="0xy9mv"
emoji-face/
│── emoji.py
│── README.md
```

---

## ▶️ How to Run the Project

### Step 1: Install Python

Download and install Python from:

```text id="3zv8gb"
https://www.python.org/downloads/
```

---

### Step 2: Save the Code

Save the Python code in a file named:

```text id="pwf06c"
emoji.py
```

---

### Step 3: Run the Program

Open terminal or command prompt and run:

```bash id="8m5rrh"
python emoji.py
```

---

## 💻 Python Code

```python id="x8z6th"
import turtle

emo = turtle.Turtle()

emo.up()
emo.goto(0, -100)
emo.down()

# Face
emo.begin_fill()
emo.fillcolor('yellow')
emo.circle(100)
emo.end_fill()

# Smile
emo.up()
emo.goto(-67, -48)
emo.setheading(-60)
emo.width(5)
emo.down()
emo.circle(80, 120)

# Eyes
for i in range(-35, 105, 70):
    emo.up()
    emo.goto(i, 35)
    emo.setheading(0)
    emo.down()
    emo.begin_fill()
    emo.fillcolor("black")
    emo.circle(10)
    emo.end_fill()

emo.penup()
emo.goto(0, -150)

turtle.mainloop()
```

---

## 📸 Output

The program generates a smiling emoji face using Turtle Graphics.

---

## 🚀 Future Improvements

* Add animated emoji expressions
* Add eyebrows and nose
* Create multiple emoji moods
* Add colorful backgrounds
* Add blinking eye animation

---

## 🎯 Learning Outcomes

This project helps beginners understand:

* Turtle Graphics basics
* Python loops
* Coordinates and movement
* Shapes and filling colors
* Drawing using programming

---

## 👩‍💻 Author

**Sara Manocha**
Made with ❤️ using Python Turtle Graphics.
