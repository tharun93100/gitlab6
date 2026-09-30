<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Registration</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="container">
    <h1>Event Registration</h1>
    <p>Register for our upcoming event</p>

    <form id="registrationForm">

        <label for="name">Full Name</label>
        <input type="text" id="name" placeholder="Enter your name" required>

        <label for="email">Email</label>
        <input type="email" id="email" placeholder="Enter your email" required>

        <label for="phone">Phone Number</label>
        <input type="tel" id="phone" placeholder="Enter your phone number" required>

        <label for="event">Select Event</label>
        <select id="event" required>
            <option value="">-- Select Event --</option>
            <option value="Tech Workshop">Tech Workshop</option>
            <option value="Coding Competition">Coding Competition</option>
            <option value="DevOps Seminar">DevOps Seminar</option>
        </select>

        <label>Attendance Type</label>

        <div class="radio-group">
            <input type="radio" name="attendance" value="Online" required>
            <span>Online</span>

            <input type="radio" name="attendance" value="Offline">
            <span>Offline</span>
        </div>

        <label for="message">Comments</label>
        <textarea id="message" placeholder="Enter your comments"></textarea>

        <button type="submit">Register</button>
    </form>

    <div id="successMessage"></div>
</div>

<script src="script.js"></script>

</body>
</html>
