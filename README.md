# ⏰ Countdown Timer in Python

A simple Python project that counts down from a user-defined number of seconds to zero.  
This project is beginner-friendly and helps understand loops, user input, and the `time` module.

---

## 📌 Features
- User enters countdown time in seconds
- Displays remaining time every second
- Prints a message when time is up

---

## 🛠️ Technologies Used
- Python 3
- `time` module

---

## 💻 Source Code

```python
import time

print("=== Countdown Timer ===")

seconds = int(input("Enter time in seconds: "))

while seconds > 0:
    print("Time left:", seconds, "seconds")
    time.sleep(1)
    seconds -= 1

print("⏰ Time's up!")
