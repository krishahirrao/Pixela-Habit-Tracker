# 🚴 Pixela Habit Tracker

A Python application that tracks your daily cycling distance using the **Pixela API**. Log your workouts, visualize your progress on a graph, and manage your habit data with simple API requests.

---

## ✨ Features

- 🚴 Log your daily cycling distance
- 📈 Store progress on a Pixela graph
- ✏️ Update existing records
- 🗑️ Delete records when needed
- 📅 Automatically uses the current date

---

## 🛠️ Built With

- Python 3
- Requests
- Datetime
- Pixela API

---

## 📂 Project Structure

```
.
├── main.py
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/pixela-habit-tracker.git
cd pixela-habit-tracker
```

### 2. Install dependencies

```bash
pip install requests
```

---

## 🔑 Setup

Create a Pixela account at:

https://pixe.la

Replace the placeholders in `main.py` with your own credentials:

```python
USERNAME = "YOUR_USERNAME"
TOKEN = "YOUR_GENERATED_TOKEN"
GRAPH_ID = "YOUR_GRAPH_ID"
```

---

## ▶️ Usage

Run the script:

```bash
python main.py
```

Enter the distance you cycled for the day:

```
How many kilometers did you cycle today?
```

The script will submit the data to your Pixela graph automatically.

---

## 📊 Example

Input:

```
How many kilometers did you cycle today?
5.8
```

Result:

```
{"message":"Success.","isSuccess":true}
```

Your graph will update on Pixela.

---

## 📌 API Operations

This project demonstrates how to:

- ✅ Create a pixel (daily record)
- ✏️ Update a pixel
- 🗑️ Delete a pixel

---

## 📚 Technologies

- Python
- Requests Library
- Pixela REST API

---

## 💡 Future Improvements

- Track multiple habits
- Command-line menu
- Weekly and monthly statistics
- Automatic reminders
- GUI with Tkinter or Streamlit

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository and submit a pull request.


## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
