# Date Difference Calculator

A lightweight and user-friendly web application that calculates the exact difference between two dates in **Years, Months, and Days** using pure HTML, CSS, and JavaScript.

## 📋 Features
- Select a Start Date and End Date
- Calculate duration in:
  - Years
  - Months
  - Days
- Input validation
- Handles leap years automatically
- Responsive and simple user interface
- No external libraries or frameworks required
- Runs directly in the browser

## 🚀 Demo

Enter a start date and an end date, then click **Calculate** to view the exact date difference.

### Examples

| Start Date | End Date | Result |
|------------|----------|---------|
| 2020-01-15 | 2026-06-19 | 6 Years, 5 Months, 4 Days |
| 2024-01-01 | 2025-01-01 | 1 Year, 0 Months, 0 Days |

## 📂 Project Structure

```text
date-difference-calculator/
│
├── index.html      # Main application UI
├── style.css       # Styling
├── script.js       # Date calculation logic
└── README.md       # Project documentation
```

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)

## 📦 Installation

### Option 1: Clone Repository

```bash
git clone https://github.com/your-username/date-difference-calculator.git
cd date-difference-calculator
```

### Option 2: Download ZIP

1. Download the repository ZIP file.
2. Extract it.
3. Open `index.html` in your browser.

## ▶️ Usage

1. Open the application.
2. Select the Start Date.
3. Select the End Date.
4. Click the **Calculate** button.
5. View the result displayed below the form.

## 🧮 Calculation Logic

The application calculates:

1. Total year difference.
2. Remaining month difference.
3. Remaining day difference.
4. Adjusts values when days or months become negative.
5. Produces an accurate calendar-based duration.

Example:

```text
Start Date: 15-Jan-2020
End Date:   19-Jun-2026

Output:
6 Years, 5 Months, 4 Days
```

## ⚠️ Validation Rules

- Both dates must be selected.
- End Date cannot be earlier than Start Date.
- Invalid inputs are rejected with a user-friendly message.

## 🎯 Future Enhancements

- Calculate total days between dates
- Calculate total weeks
- Time difference support (hours, minutes, seconds)
- Dark mode
- Export results to PDF
- Multi-language support
- Date presets (Today, Last Month, Last Year)

## 📸 Screenshot

```text
+--------------------------------+
| Date Difference Calculator     |
+--------------------------------+
| Start Date: [2020-01-15]       |
| End Date:   [2026-06-19]       |
|                                |
| [ Calculate ]                  |
|                                |
| Result:                        |
| 6 Years, 5 Months, 4 Days      |
+--------------------------------+
```

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

## 🐛 Bug Reports

If you find a bug, please create an issue describing:

- Steps to reproduce
- Expected behavior
- Actual behavior
- Browser and version

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

Developed using HTML, CSS, and JavaScript.


⭐ If you found this project useful, consider giving it a star on GitHub.
