# 🚉 Travel-Hub

**Travel-Hub** is a Python-based multi-service travel booking platform developed using [Streamlit](https://streamlit.io/). It provides users with a centralized place to search and book train, metro, flight, cab services, and even order food from local restaurants. It is integrated with a MySQL database and includes authentication functionality (login/signup).

## 🛠️ Tech Stack

- **Frontend & UI**: Streamlit
- **Backend**: Python
- **Database**: MySQL
- **Others**: Pillow, QR Code Generator

---

## 🔐 Features

- **User Authentication**:
  - Login and Signup pages integrated with MySQL database.

- **Multi-Page Interface**:
  - **Home Page**:
    - Search available trains by route.
    - Book tickets for multiple passengers.

  - **Restaurant Services**:
    - Search restaurants in a selected city.
    - Options: Dine-in, Takeaway, Seat Service.

  - **Flight Ticket Booking**

  - **Metro Ticket Booking**

  - **Cab Booking**

---

## 🚀 Getting Started

### 📦 Installation

Install the required dependencies:

"pip install streamlit mysql-connector-python streamlit-qrcode pillow"

*before running the project do the 
## 💾Database Setup
Open MySQL Command Line Client:
  CREATE DATABASE irctc;

before searching for trains run following command in mysql command line to add dummy train data

  INSERT INTO trains VALUES
('Rajdhani Express', '12301', 'Delhi', 'Patna', '17:15', '08:45', '15h 30m', '2025-04-20', '1A, 2A, 3A', 'SL', 'GN', 'CC'),
('Shatabdi Express', '12023', 'Patna', 'Howrah', '05:30', '13:30', '8h 00m', '2025-04-21', 'CC', 'EC', '', ''),
('Vikramshila Express', '12367', 'Bhagalpur', 'Anand Vihar', '11:00', '06:10', '19h 10m', '2025-04-22', '1A, 2A, 3A', 'SL', 'GN', ''),
('Magadh Express', '20801', 'Islampur', 'New Delhi', '15:30', '10:50', '19h 20m', '2025-04-23', '1A, 2A', '3A', 'SL', 'GN'),
('Maurya Express', '15027', 'Hatia', 'Gorakhpur', '19:10', '13:30', '18h 20m', '2025-04-24', '2A', '3A', 'SL', 'GN'),
('Patna Jan Shatabdi', '15125', 'Patna', 'Banaras', '05:30', '10:30', '5h 00m', '2025-04-25', 'CC', '2S', '', ''),
('Tejas Rajdhani', '12309', 'Rajendra Nagar', 'New Delhi', '19:10', '07:40', '12h 30m', '2025-04-26', '1A, 2A, 3A', '', '', ''),
('Patliputra Express', '18622', 'Patna', 'Howrah', '15:20', '06:10', '14h 50m', '2025-04-27', '2A', '3A', 'SL', ''),
('Humsafar Express', '22354', 'Patna', 'Bangalore', '20:00', '10:30', '38h 30m', '2025-04-28', '3A', 'SL', '', ''),
('Gaya Express', '12397', 'Gaya', 'New Delhi', '14:30', '07:45', '17h 15m', '2025-04-29', '1A, 2A', '3A', 'SL', 'GN'),
('Vande Bharat', '22436', 'Varanasi', 'Patna', '06:00', '10:00', '4h 00m', '2025-04-30', 'EC', 'CC', '', ''),
('Intercity Express', '13247', 'Rajgir', 'Howrah', '06:00', '16:45', '10h 45m', '2025-05-01', '2A', '3A', 'SL', ''),
('Pataliputra Exp', '12141', 'Mumbai', 'Patna', '23:30', '07:00', '31h 30m', '2025-05-02', '2A', '3A', 'SL', 'GN');



👨‍💻 Contributors
Ayush Raj Pathak | Linkedin:https://www.linkedin.com/in/ayush-raj-pathak05
📬 Contact
📧 ayushpathak602@gmail.com

