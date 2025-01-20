# 🚗 Vehicle Reservation Request System

## 📌 Project Overview

The **Vehicle Reservation Request System** is a web-based application that allows users to reserve vehicles by submitting a form with their preferences and contact information. The system validates the inputs and redirects users to a confirmation page upon successful submission. This project demonstrates the use of client-side validation, dynamic feedback, and responsive design.

## 🚀 Features

- **User-Friendly Form Interface**:
  - Users can select vehicle type, engine type, and color preferences.
  - Allows users to specify pickup dates, rental duration, and contact details.
- **Dynamic Form Validation**:
  - Validates inputs such as dates, numeric fields, email, and phone numbers.
  - Provides real-time error feedback to guide users.
- **Responsive Design**:
  - Ensures usability across different screen sizes and devices.
- **Confirmation Page**:
  - Displays a success message thanking users and confirming their reservation request.

## 📂 Project Structure

```
📁 vehicle_reservation
 ├── 📁 imgs/                # Image assets (backgrounds, icons, etc.)
 ├── 📄 index.html           # Main reservation form
 ├── 📄 response.html        # Confirmation page
 ├── 📄 reservation.css      # Stylesheet for layout and design
 ├── 📄 reservation.js       # JavaScript for validation logic
```

## 🛠 Technologies Used

- **HTML5**: Structures the form and confirmation pages.
- **CSS3**: Provides styling and responsive layout.
- **JavaScript (ES6)**: Implements validation logic and dynamic behavior.
- **jQuery**: Simplifies event handling and DOM manipulation.

## 📝 Validation Details

The system ensures users provide valid input for the following fields:

1. **Pickup Date**:
   - Must be in `MM/DD/YYYY` format.
   - Checks for valid date ranges.
2. **No. of Days**:
   - Requires numeric input for rental duration.
3. **Name**:
   - Ensures the field is not empty.
4. **Email**:
   - Validates format using regex.
5. **Phone**:
   - Requires format `999-999-9999`.

Validation errors are displayed in real time, preventing form submission until all errors are resolved.

## 🏃‍♂️ How to Use the Application

1. **Open the Application**:
   - Launch the `index.html` file in a web browser.

2. **Fill Out the Form**:
   - Enter the required information, including preferences and contact details.

3. **Submit the Form**:
   - Click the **"Submit Request"** button.
   - If all inputs are valid, the user is redirected to the confirmation page (`response.html`).

4. **View Confirmation**:
   - The confirmation page thanks the user and provides a message about the next steps.

## 🌟 Future Improvements

- **Server-Side Validation**:
  - Add back-end validation to enhance security and handle edge cases.
- **Database Integration**:
  - Store reservation requests for administrative purposes.
- **Advanced Date Picker**:
  - Replace manual date input with a modern date picker widget.
- **Email Notification**:
  - Send confirmation emails upon successful reservation requests.

## 📜 License

This project was developed for educational purposes as part of a **college assignment**.

---

💼 **Author:** Juan Jacobo Florez Monroy | 🚀 Portfolio: [Portfolio Website or GitHub]