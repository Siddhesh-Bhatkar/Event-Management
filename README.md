# Event Management System

## Overview
The Event Management System is a web application designed to help users organize and manage events efficiently. It provides features such as event categorization, calendar view, filtering, and statistics.

### Features
- **Event Addition**: Add events with details like name, date, time, category, and description.
- **Event Categories**: Events can be categorized as `Work`, `Personal`, or `Other`.
- **Calendar View**: View events organized by month with a visual calendar.
- **Filtering**: Filter events by category (`All`, `Work`, `Personal`, `Other`).
- **Statistics**: View real-time statistics for total events and events by category.
- **Responsive Design**: Optimized for both desktop and mobile screens.
- **Local Storage**: Save events in the browser's local storage for persistence.

---

## Technologies Used

- **HTML**: For structuring the webpage.
- **CSS**: For styling the application, including responsive design.
- **JavaScript**: For implementing functionality like adding, deleting, and displaying events.
- **Moment.js**: For date manipulation and formatting.

---

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/enhanced-event-management.git
    ```

2. Navigate to the project directory:
    ```bash
    cd enhanced-event-management
    ```

3. Open the `index.html` file in any modern web browser.

---

## How to Use

1. **Adding an Event**:
    - Enter the event name, date, time, category, and an optional description in the form.
    - Click `Add Event` to save the event.

2. **Viewing Events**:
    - Navigate the calendar to view events on specific dates.
    - Events are displayed in the "Upcoming Events" section, sorted by date and time.

3. **Filtering Events**:
    - Use the dropdown in the "Filter Events" section to filter events by category.

4. **Deleting Events**:
    - Click the `Delete` button next to an event in the "Upcoming Events" section to remove it.

---

## File Structure

```plaintext
.
├── index.html       # Main HTML file for the application
└── README.md        # Documentation file
```

---

## Future Enhancements

- **Event Editing**: Allow users to edit existing events.
- **Notifications**: Add reminders/alerts for upcoming events.
- **Synchronization**: Enable syncing with Google Calendar or other services.
- **Multi-user Support**: Allow multiple users with authentication.

---

## License

This project is licensed under the [MIT License](LICENSE).
