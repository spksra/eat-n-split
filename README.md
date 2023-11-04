# the-ivory-bliss

Welcome to The Ivory Bliss Hotel Management Application. The Ivory Bliss is a user friendly, easy to handle and custom built application. This application is designed to manage hotel operations like user management, cabin management, booking management, sales statistics, and various customization options. It integrates authorized authentication, database storage, and dark mode feature. And so much more!

## Key Features 📝

### Authentication and Authorization

- Users of the app is Hotel Staff. They can log into the application to perform tasks.
- New users can only be signed up inside the applications (to guarantee that only actual hotel employees can access application).
- Users can upload an avatar, change their names and passwords.

### Dashboard

- The initial app screen is a dashboard, to display important highlights from the last 7, 30, or 90 days:
  - Statistics on recent bookings, sales, check-ins, and occupancy rate.
  - A list of guests checking in and out on the current day. Users can perform these tasks from here.
  - A chart showing statistics on stay durations, as this is an important metric for the hotel.
  - A chart showing all daily hotel sales, showing both "total" sales and "extras" sales (only breakfast at the moment).

### Cabins

- The app has a table view with all cabins, displaying the cabin photo, name, capacity, price, and current discount.
- Users can update, delete, duplicate and create new cabins (including uploading a photo).
- The table can be filtered (by "All, With discount, No-discount") and sorted (by "Name, Price and Capacity").

### Bookings

- The app has a table view with all bookings, showing arrival & departure dates, status, paid amount, as well as cabin and guest data.
- The booking status can be "unconfirmed" (booked but not yet checked in), "checked in" & "checked out".
- The table can be filtered (by status of "All, Confirmed, Checked-in, Unconfirmedand"), sort (by "Date & Amount") with pagination.
- Other booking data includes: the number of guests, number of nights, guest observations, whether they booked breakfast, breakfast price.

### Check In/Out

- Guests data contains Full Name, Email, National ID, Nationality, and a Country Flag for easy identification.
- Users can Delete, Check-In and Check Out a booking, as per the Guests request.
- During Check-in if not paid already, users need to accept payment (outside the app), and then confirm the payment received (inside the app).
- On check-in, the guest can add breakfast for the entire stay, if they hadn't already.

### Users

- Users can SignUp a new user into the Application using Full Name, Email and Password (with Confirm Password).

### Settings

- Users can define an application settings like Breakfast Price, Min and Max Nights/Bookings, Max Guests/Bookings

### Light and Dark Mode:

- As per covenience, users can opt for either Light or Dark Mode.

## 💻 Technology Used

The Ivory Bliss Hotel Management Application is built using the following technologies and libraries:

- **React**: JavaScript library for UI development.

- **styled-components**: CSS-in-JS library for styling React components.

- **react-hot-toast**: Customizable toast notification library for React.

- **react-router-dom**: Library for routing and navigation in React apps.

- **Supabase**: Cloud database service for real-time and secure data storage.

- **@tanstack/react-query**: Data-fetching and state management library for React.

- **date-fns**: JavaScript date utility library for parsing, formatting, and manipulating dates.

- **recharts**: Composable charting library for React.

- **react-icons**: Collection of customizable icons for React apps.

- **react-hook-form**: Library for form state management and validation in React.

## 🛠️ Installation Steps:

<p>1. Clone the repository</p>

---

git clone https://github.com/lgope/the-wild-oasis.git

---

<p>2. Install the required dependencies </p>

---

npm install

---

<p>3. Start the development server</p>

---

npm run dev

---

<p>4. Access the application at</p>

---

http://localhost:5173 or Your Local URL

---
