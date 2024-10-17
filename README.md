# Hotel Chatbot

## Objective
To build a simple chatbot for a hotel that can efficiently handle the following functionalities:

### 1. Book Room
- Allows users to book rooms by providing room numbers and types.
- Confirms reservations and thanks users for their bookings.

### 2. Request Room Cleaning
- Enables guests to request room cleaning services.
- Confirms immediate or scheduled cleaning requests.

### 3. Handle FAQs
- Responds to frequently asked questions regarding hotel services, policies, and facilities.
- Provides information on check-in/out times, Wi-Fi availability, and cancellation policies.

### 4. Handle Greetings
- Engages users with friendly greetings and prompts for assistance.

### 5. Transportation Services
- Provides information about transportation options available, including taxi services.
- Confirms bookings for transportation.

### 6. Gym Services
- Informs users about gym availability and hours.
- Responds to inquiries regarding gym facilities.

### 7. Spa Services
- Provides details about the spa and its treatments.
- Directs users to the spa menu available on the hotel website.

### 8. Laundry Services
- Informs users about laundry services available at the hotel.
- Answers questions related to laundry policies.

### 9. Pet Policy
- Informs users about the hotel's pet-friendly policy and any associated fees.
- Directs users to the website for more detailed information.

## Implementation Overview

### Room Booking
- **Intents:** Book room, provide room number and type.
- **Responses:** Confirms booking details and thanks the user.

### Room Cleaning Requests
- **Intents:** Request cleaning, specify timing.
- **Responses:** Confirms cleaning requests.

### FAQs Handling
- **Intents:** Answer common questions (e.g., check-in times, Wi-Fi).
- **Responses:** Provides relevant information to users.

### Greeting Handling
- **Intents:** Greet the user.
- **Responses:** Welcomes the user and prompts for assistance.

### Transportation Services
- **Intents:** Inquire about transportation options.
- **Responses:** Provides information and confirms bookings.

### Gym Services
- **Intents:** Ask about gym hours and facilities.
- **Responses:** Confirms gym availability and hours.

### Spa Services
- **Intents:** Inquire about spa services.
- **Responses:** Provides information and directs users to the website.

### Laundry Services
- **Intents:** Ask about laundry services.
- **Responses:** Provides details on available laundry options.

### Pet Policy
- **Intents:** Inquire about pet policies.
- **Responses:** Informs users and directs them to the website for more info.

# Note 
It is a chatbot build on RASA framework. For [Demo](https://www.youtube.com/watch?v=fBmFP3hhJik)

Prerequisite: RASA, python

To interact with the chatbot in the terminal run command "rasa actions & rasa shell"
