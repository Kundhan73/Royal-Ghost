# 🧙‍♂️ Invisibility Cloak using OpenCV (Python)

This project implements a **real-time invisibility cloak effect** using **Python and OpenCV**.  
By detecting a specific color (red by default) in a live webcam feed, the program replaces that region with a previously captured background frame, creating the illusion of invisibility.

---

## 📌 How It Works

1. The webcam captures a **static background** without the user present.
2. Each video frame is converted from **BGR to HSV color space**.
3. A **color mask** is created to detect a specific cloak color (red).
4. The detected cloak area is **replaced with background pixels**.
5. The result is displayed in real time.

---

## 🧰 Technologies Used

- Python 3
- OpenCV (`cv2`)
- NumPy
- Webcam (built-in or external)
