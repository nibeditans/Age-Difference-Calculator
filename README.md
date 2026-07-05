# Age Difference Calculator

A simple and interactive **Streamlit** web application that compares the ages of two people and calculates the exact difference between their dates of birth in **years, months, and days**.

Whether you're comparing your age with a friend, sibling, parent, or anyone else, this app provides a clean and human-readable result in just a few clicks.

## Live Web App: [Age-Difference-Calculator](https://nibeditans-Age-Difference-Calculator.hf.space/)

## Features

* 📅 Compare the ages of any two people
* 🧮 Calculates the exact difference in **years, months, and days**
* 🎉 Clearly tells who is **older** or **younger**
* ✅ Handles leap years and varying month lengths accurately using `python-dateutil`
* ✨ Proper singular and plural formatting (e.g., *1 day* vs. *2 days*)
* 🌐 Simple, responsive web interface built with Streamlit

Check out the complete walkthrough I've made on this repo: [Building Python Utilities for Accurate Age Calculations with Better Date Logic](https://nsdsda.medium.com/building-python-utilities-for-accurate-age-calculations-with-better-date-logic-61f4400a5628)

## Tech Stack

* **Python**
* **Streamlit**
* **python-dateutil**

## Project Structure

```text
Age-Difference-Calculator/
│
├── app.py                 # Streamlit user interface
├── age_difference.py      # Age comparison logic
├── utils.py               # Output formatting utilities
├── requirements.txt       # Project dependencies
└── README.md
```

## How It Works?

1. Enter your name and date of birth.
2. Enter the other person's name and date of birth.
3. Click **Compare Ages**.
4. The app calculates the exact calendar difference between the two birth dates and tells you who is older (or younger) and by how much.

If both people share the same birthday, the app displays a special message indicating that they are exactly the same age.

## Installation

Clone the repository:

```bash
git clone https://github.com/nibeditans/Age-Difference-Calculator.git
```

Move into the project directory:

```bash
cd Age-Difference-Calculator
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

## Why I Built This?

This project started as a natural extension of my earlier **Age Calculator** app.

After building a tool to calculate a person's exact age in years, months, and days, I wanted to solve a slightly different problem:

> **How much older or younger is one person than another?**

Instead of calculating each person's current age separately, this application directly compares the two dates of birth to determine the exact calendar difference between them.

The project focuses on writing clean, readable Python code while keeping the user experience simple and intuitive.

## Related Apps

* **[How Old Are You, Really?](https://github.com/nibeditans/Human-Age-Lens)** — Calculates a person's exact age in years, months, and days.
* **[Body Fat Calculator](https://github.com/nibeditans/Body-Fat-Calculator)** — Estimates body fat percentage and health category.

## License

This project is licensed under the **[MIT License](LICENSE)**.

If you enjoyed this project, feel free to ⭐ the repository and explore my other projects.
