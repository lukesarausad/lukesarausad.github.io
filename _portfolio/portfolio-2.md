---
title: "Tennis-Queue"
excerpt: "Web Application that allows users to book times at public tennis courts <br/><img src='/images/Tennis-Queues.png'>"
collection: portfolio
link: "https://luke.sarausad.com/portfolio/portfolio-2/"
sublink: "https://issaquah-tennis-queue.vercel.app/"
---

This project is a full-stack web application built to simplify the court reservation process at local parks, eliminating the need for individuals to physically visit each park to check for court availability. The application employs a queue-based data structure to manage reservations efficiently, ensuring a fair and transparent booking system for users.

**Frontend Development:**
- **Technology Used:** React.js
- **Functionality:** The frontend offers users an intuitive interface to select a park and view the availability of its courts. Users can easily choose a park, view available courts, and book a time slot directly through the application. The interface updates in real-time, reflecting changes in availability as bookings are made or canceled. The design is responsive, ensuring seamless access across various devices, including desktops, tablets, and smartphones.

**Backend Development:**
- **Technology Used:** Node.js with Express.js
- **Functionality:** The backend handles the data and logic for court reservations. Each park is represented by a set of queues, with each queue corresponding to a specific court. The system tracks the order of bookings for each court, ensuring that reservations can only be made when a court is available. An API facilitates communication between the frontend and backend, processing requests to book, view, or cancel reservations. The application also includes robust error handling and validation to maintain data integrity and provide a smooth user experience.

**Key Features:**
- **Real-time Availability:** Users can view up-to-date court availability without manually refreshing the page.
- **Queue Management:** Each court operates as a queue, processing reservations in the order they are received, preventing double bookings and allowing for clear tracking of court usage.
- **User Notifications:** The system can notify users about their booking status, confirmations, and cancellations, enhancing the overall user experience.
- **Scalable Architecture:** The system is designed to handle multiple parks and courts, making it scalable for use in various communities or cities.

**Project Impact:**
This application greatly improves the user experience for park-goers by providing a digital solution for court reservations. It saves time and reduces the frustration of arriving at a park only to find that no courts are available. The use of modern web technologies ensures that the system is both efficient and user-friendly, catering to a broad audience.
