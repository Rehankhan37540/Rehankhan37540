
#  Student & Teacher Appointment Booking System

A web-based appointment scheduling application where **students can book appointments with teachers** based on their availability. The system ensures smooth academic interactions by avoiding double bookings and managing time efficiently.

---

##  Problem Statement

In many institutions, students often face challenges in booking appointments with teachers. Miscommunication, time clashes, or informal methods lead to confusion and delays. This system helps streamline appointments by offering:

- Teacher availability schedules
- Real-time booking slots
- Notifications and appointment history

---

##  Features

###  Teacher Panel:
- Login/Signup
- Set available time slots
- View upcoming bookings
- Accept/Reject bookings
- View appointment history

###  Student Panel:
- Login/Signup
- View available teachers
- Book appointment based on availability
- Cancel/reschedule appointments
- View appointment status

---

##  Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla or with Frameworks)**
- **Firebase (Auth + Firestore)**
- Optionally: EmailJS for notifications

---

##  Project Structure

---

##  Sample Test Cases

| Role     | Action                     | Expected Output                           |
|----------|----------------------------|-------------------------------------------|
| Student  | Book a slot                | Appointment created, status "Pending"     |
| Teacher  | Accept appointment         | Appointment status updates to "Confirmed" |
| Student  | Cancel a booking           | Slot becomes available again              |
| Teacher  | View appointment history   | Displays list of past appointments        |

---

##  Security

- Authenticated access only (Firebase Auth)
- Students cannot modify others' bookings
- Teachers can only update their own availability

---

## Firebase Services Used

- **Authentication**: Secure login for students and teachers
- **Firestore Database**: Store users, bookings, and time slots
- **(Optional)**: Firebase Functions for automation like reminders

---

##  Optimization & Improvements

- Modular JavaScript structure
- Separate dashboards for different user types
- Error handling and input validations
- Mobile-responsive design using Flexbox/Grid


## How to Run Locally

1. Clone the repo:
```bash
git clone https://github.com/Rehankhan37540/appointment-system.git


