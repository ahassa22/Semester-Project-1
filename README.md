
Reception Management Dashboard

## Project Overview
The Reception Management Dashboard is designed to streamline staff management and delivery tracking operations for WeDeliverTECH. It allows the receptionist to monitor staff statuses, manage deliveries, and receive real-time alerts for overdue tasks.

## Features

### 1. Staff Management
- View a list of staff members with their current status (In/Out).
- Track out-time, expected return time, and duration of absences.
- Receive alerts for late staff members who have not returned within the specified time.

### 2. Delivery Management
- Add delivery tasks with details such as vehicle type, contact information, delivery address, and return time.
- View all scheduled deliveries and manage them on a dedicated delivery board.
- Receive alerts for late deliveries when a driver has not returned by the specified time.

### 3. Clock and Alerts
- Display a real-time digital clock with the current date and time in "Day, Month, Year, Hour:Minute:Second" format.
- Dynamic toast notifications for late staff or delivery drivers, ensuring quick action.

### 4. Navigation and Usability
- Dropdown menu for seamless navigation between dashboard sections.
- Direct row selection for managing tasks within the table.
- Responsive design and hover animations to enhance user experience.

### 5. Object-Oriented Programming (OOP) Design
- Centralized management of dashboard functionality via a `Dashboard` class.
- Encapsulation of logic into methods for modular and reusable code.

## Technologies Used

### Frontend
- HTML5, CSS3 for structuring and styling the web application.
- Bootstrap 5 for responsive design.
- FontAwesome for consistent iconography.

### Scripting
- JavaScript (ES6+) for dynamic interactions.
- Object-Oriented Programming (OOP) principles for modularity.
- jQuery for DOM manipulation and event handling.

### APIs
- Random User API for generating mock staff data.

## Setup Instructions

### Prerequisites
Ensure the following software is installed on your machine:
- A modern web browser (e.g., Chrome, Firefox).
- A code editor (e.g., VSCode, Sublime Text).

### Steps to Run the Application
1. Clone the repository from GitHub:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd ReceptionManagementDashboard
   ```
3. Open the `index.html` file in your web browser to launch the application.

4. Ensure an active internet connection for fetching mock data from the Random User API.

## File Structure

```
ReceptionManagementDashboard/
|-- css/                   # Stylesheets for the application.
|-- images/                # Assets and images used in the project.
|-- js/                    # JavaScript files for dynamic functionality.
|-- index.html             # Main HTML file.
|-- WeDeliverTech_Dynamic_Project/ (Optional legacy or additional files)
```

## Known Issues and Limitations
- The system relies on accurate manual input for delivery management. Incorrect entries may cause errors.
- Notifications are generated based on fixed thresholds and may require additional customization for varying use cases.

## Future Enhancements
- Implement real-time database integration to persist data.
- Add role-based access control for multi-user functionality.
- Extend the dashboard to include inventory management and order tracking.

## References
- Random User API: https://randomuser.me/
- Bootstrap Documentation: https://getbootstrap.com/
- MDN Web Docs: https://developer.mozilla.org/
