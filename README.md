# Face Recognition Based Attendance System

# Facial Recognition Based Attendance System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)](https://opencv.org/)

## 🚀 Overview

**Facial Recognition Based Attendance System** is a cutting-edge, automated solution for tracking student attendance using facial recognition technology. Built with Python and OpenCV, this system replaces traditional, error-prone manual attendance methods, ensuring accuracy, speed, and zero human intervention.

---

## 🌟 Features

- 🎯 **Automatic Attendance:** Takes attendance by recognizing student faces in real-time.
- 🖼️ **Facial Recognition:** Utilizes OpenCV's advanced algorithms for robust face detection and recognition.
- 📝 **Attendance Logs:** Stores attendance data securely for easy access and reporting.
- 🖥️ **Intuitive Web Interface:** User-friendly frontend built with HTML & CSS for seamless interaction.
- 🔒 **Secure & Private:** All facial data is processed securely; no cloud upload by default.
- 📈 **Scalable:** Easily add or remove students; suitable for classrooms, offices, and events.
- 💡 **Customizable:** Modify recognition thresholds, add new features, or integrate with existing systems.

---

## 📸 Demo

![Attendance Demo](assets/demo.gif) <!-- Replace with your actual demo image or GIF -->

---

## 🏗️ Project Structure

```
.
├── dataset/            # Stores images for training the model
├── attendance/         # Logs and CSV attendance records
├── static/             # CSS, images, JS files
├── templates/          # HTML frontend templates
├── main.py             # Main application script (Flask or Streamlit, etc.)
├── recognizer.py       # Facial recognition logic
├── trainer.py          # Model training script
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/KunalWadhai/Facial-Recongnition-Based-Attendance-System.git
   cd Facial-Recongnition-Based-Attendance-System
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare the Dataset**
   - Add student images to the `dataset/` folder, each in a separate subfolder named after the student.

4. **Train the Model**
   ```bash
   python trainer.py
   ```

5. **Run the Application**
   ```bash
   python main.py
   ```
   - Open `http://localhost:5000` in your browser to access the interface.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **OpenCV**
- **Flask / Streamlit** (Web Framework)
- **HTML5 & CSS3** (Frontend)
- **NumPy, Pandas** (Data handling)

---

## 🧑‍💻 Usage

1. **Register Students:** Upload new student photos via the web interface or directly in the `dataset/` folder.
2. **Take Attendance:** Start the attendance session; the camera will recognize faces and mark attendance.
3. **View Attendance:** Access attendance records in the `attendance/` directory or via the web dashboard.

---

## 📝 Contributing

Contributions are welcome! Please:
- Fork the repo
- Create a new branch
- Make your changes
- Submit a pull request

See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- [OpenCV](https://opencv.org/)
- [Flask](https://flask.palletsprojects.com/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)

---

## 💬 Contact

For questions, feedback, or suggestions, feel free to [open an issue](https://github.com/KunalWadhai/Facial-Recongnition-Based-Attendance-System/issues) or reach out at [KunalWadhai](https://github.com/KunalWadhai).

---
