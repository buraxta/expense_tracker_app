# Expense Tracker App

This is a simple **Expense Tracker Application** built using **Flutter**. The app is designed to help users manage their expenses effectively by providing features to add, remove, and visualize expenses. It is a great project for beginners learning Flutter, as it covers core concepts like state management, theming, and working with widgets.

---
<div style="display: flex; gap: 10px; ">
  <img src="https://github.com/buraxta/expense_tracker_app/blob/master/ss/1.png?raw=true " />
  <img src="https://github.com/buraxta/expense_tracker_app/blob/master/ss/2.png?raw=true" />
</div>


---

## Features

1. **Add Expenses**:  
   Users can add new expenses by providing details such as the title, amount, date, and category. The app supports categories like Food, Travel, Leisure, and Work.

2. **Remove Expenses**:  
   Users can remove expenses from the list. If a user accidentally removes an expense, they can undo the action using a snackbar prompt.

3. **Expense Visualization**:  
   The app includes a chart that visually represents the expenses based on their categories. This helps users understand their spending patterns at a glance.

4. **Dark and Light Themes**:  
   The app supports both dark and light themes, which automatically adapt to the system's theme settings. The theming is consistent and visually appealing.

5. **User-Friendly Interface**:  
   The app has a clean and intuitive interface, making it easy for users to navigate and manage their expenses.

---

## How It Works

- The app starts with a list of sample expenses, which users can modify by adding or removing items.
- Users can add a new expense by clicking the "Add" button, which opens a modal bottom sheet with a form.
- Expenses are displayed in a list format, and users can swipe or use a button to remove them.
- A chart is displayed at the top of the screen, showing the distribution of expenses across different categories.

---

## Why This Project?

This project is an excellent way to learn and practice Flutter development. It covers essential topics such as:

- **State Management**: Using `setState` to manage the list of expenses.
- **Theming**: Implementing light and dark themes using `ThemeData`.
- **Widgets**: Working with core Flutter widgets like `AppBar`, `ListView`, `SnackBar`, and `BottomSheet`.
- **Charts**: Integrating a simple chart to visualize data.

---

## How to Run the Project

1. Clone the repository or download the source code.
2. Open the project in your preferred IDE (e.g., Android Studio or VS Code).
3. Run `flutter pub get` to install dependencies.
4. Use `flutter run` to launch the app on an emulator or physical device.

---

## Future Improvements

- **Persistent Storage**: Integrate a database (e.g., SQLite or Firebase) to save expenses permanently.
- **Expense Filtering**: Add filters to view expenses by date range or category.
- **Budget Tracking**: Allow users to set budgets and track their spending against them.
- **Export Data**: Add an option to export expenses as a CSV or PDF file.

---

## Conclusion

The **Expense Tracker App** is a practical and beginner-friendly project that demonstrates the power of Flutter for building cross-platform applications. It is a great starting point for anyone looking to learn Flutter and improve their app development skills.
