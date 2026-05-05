# course-project-02
# 🏥 Health Monitoring System (C)

A simple console-based Health Monitoring System written in C that calculates BMI and analyzes basic health parameters like heart rate.

---

## 📌 Features

* 👤 User input (name, age, weight, height, heart rate)
* ⚖️ BMI calculation
* ❤️ Heart rate analysis
* 📊 Health status classification
* 🖥️ Simple and easy-to-use console interface

---

## 🧮 How It Works

The program:

1. Takes user details as input

2. Calculates **Body Mass Index (BMI)** using:

   ```
   BMI = weight / (height * height)
   ```

3. Classifies BMI into:

   * Underweight
   * Normal
   * Overweight
   * Obese

4. Evaluates heart rate:

   * Low (< 60 bpm)
   * Normal (60–100 bpm)
   * High (> 100 bpm)

---

## 💻 Technologies Used

* C Programming Language
* Standard C Libraries (`stdio.h`)

---

## ▶️ How to Run

### 1. Clone the repository

```
git clone https://github.com/your-username/health-monitoring-system.git
```

### 2. Navigate to the folder

```
cd health-monitoring-system
```

### 3. Compile the program

```
gcc health.c -o health
```

### 4. Run the program

```
./health
```

---

## 📷 Sample Output

```
=== Health Monitoring System ===
Enter your name: John
Enter age: 22
Enter weight (kg): 70
Enter height (meters): 1.75
Enter heart rate (bpm): 72

Hello, John (Age: 22)

--- Health Report ---
BMI: 22.86
BMI Status: Normal
Heart Rate: 72 bpm
Heart Rate Status: Normal
```

---

## 📁 Project Structure

```
health-monitoring-system/
│── health.c
│── README.md
```

---

## 🚀 Future Improvements

* Add file handling to store patient records
* Support multiple users
* Include blood pressure and temperature tracking
* Create menu-driven interface
* Add graphical interface (GUI)

---

## 🤝 Contributing

Feel free to fork this repository and improve the project. Pull requests are welcome!

---

## 📄 License

This project is open-source and available under the MIT License.
