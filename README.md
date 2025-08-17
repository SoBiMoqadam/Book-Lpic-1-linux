# 📅 Python Calendar

<div align="center">
<h1 style="color:#00ffff; font-family:monospace;">🗓 Python Calendar</h1>
<p style="font-family:monospace; font-size:16px; color:#9be7ff;">
A smart calendar to check dates, switch calendar types, and toggle themes effortlessly 🚀
</p>
</div>

---

## ✨ Features

- ✅ **Today's Date**: Quickly find the date of the day & month  
- 🔄 **Switch Calendar Type**: Toggle between Solar (Persian) & Gregorian  
- 🌗 **Themes**: Light and Dark background options  
- 🎨 **Clean Interface** with smooth interactions  

---

## 💻 Sample Code

<div style="background:#1e1e2f; padding:15px; border-radius:10px; color:#fff; font-family:monospace; line-height:1.5;">
<pre>
import tkinter as tk
from persiantools.jdatetime import JalaliDate
from datetime import date, datetime
import calendar

# Sample: Display today's date
current_date = JalaliDate.today()
print("Today's date:", current_date)

# Switch between calendar types
calendar_type = "jalali"  # or "gregorian"

# Toggle themes
theme = "light"  # or "dark"
</pre>
</div>

<p style="margin-top:10px; color:#333; font-family:monospace;">
You can continue writing explanations or notes here outside the code block.
</p>

---

## Download File

You can download the `main.py` file directly:

[Download main.py](https://raw.githubusercontent.com/SoBiMoqadam/Python-Calendar/main/main.py)

---

## 🛠 Installation / Setup

Clone this repository and run the script using terminal:

```bash
git clone https://github.com/SoBiMoqadam/Python-Calendar.git
cd Python-Calendar
python main.py
