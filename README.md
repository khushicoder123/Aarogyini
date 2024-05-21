# Aarogyni
![image](https://github.com/khushicoder123/Aarogyini/assets/115283596/cfbd15d2-a06f-4c9b-b8d7-10b6a772904b)
![image](https://github.com/khushicoder123/Aarogyini/assets/115283596/b6252f49-948a-4389-b666-188004f8b278)
![image](https://github.com/khushicoder123/Aarogyini/assets/115283596/afb34ed2-0aab-4c46-bdda-dbaa895a85f8)

Aarogyini is a dedicated platform designed to cater to the physical and mental health needs of women. It serves as a bridge connecting women with doctors, providing a comprehensive range of features to support women's health and wellness.

## Features

### AI Tools
Aarogyini integrates advanced AI tools for:
- Cervical cancer detection
- Breast cancer detection
- PCOS detection
![image](https://github.com/khushicoder123/Aarogyini/assets/115283596/07352a69-42c9-41a2-85ca-47d77f96e81d)

### One-on-One Interaction with Doctors
Women can sign up on the platform and have personalized interactions with doctors. This feature ensures that users receive the medical attention and advice they need in a confidential and supportive environment.

### Period Tracker
The period tracker helps women monitor their menstrual cycles, enabling them to plan and manage their activities accordingly.
![image](https://github.com/khushicoder123/Aarogyini/assets/115283596/c2c21e3b-603b-47da-b0c2-9b04ec0a920f)


### Mental Health Chatbot
Recognizing the prevalence of depression among women, Aarogyini offers a mental health chatbot. This chatbot engages in conversations with users, providing a comforting and supportive interaction similar to talking to a friend.

## User Roles

### Doctors
Doctors can sign up and manage their dashboards which include:
- A list of all their patients
- Current prescriptions for each patient
- Medical history of each patient
- ![image](https://github.com/khushicoder123/Aarogyini/assets/115283596/62bfd22e-1c45-4540-98a5-0e067743105c)


### Patients
Patients can sign up and access their dashboards which provide:
- Their current prescriptions
  ![image](https://github.com/khushicoder123/Aarogyini/assets/115283596/c2b2f5f6-fcc3-4bc6-8ba5-aaf6b2a5d07d)


## Getting Started

### Prerequisites
To run Aarogyini locally using XAMPP, ensure you have the following installed:
- XAMPP (which includes Apache, MySQL, PHP)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/aarogyini.git
   ```
2. Move the project directory to the `htdocs` folder in your XAMPP installation directory. For example:
   ```bash
   mv aarogyini /path/to/xampp/htdocs/
   ```
3. Start Apache and MySQL from the XAMPP Control Panel.

4. Set up the database:
   - Open your web browser and go to `http://localhost/phpmyadmin`.
   - Create a new database (e.g., `aarogyini_db`).
   - Import the provided SQL file (if available) to set up the required tables. You can find this file in the `database` folder of the project (e.g., `aarogyini.sql`).

5. Configure the database connection:
   - Open the `config.php` file located in the `aarogyini` directory.
   - Update the database connection details:
     ```php
     define('DB_SERVER', 'localhost');
     define('DB_USERNAME', 'your_db_username');
     define('DB_PASSWORD', 'your_db_password');
     define('DB_NAME', 'aarogyini_db');
     ```

### Running the Application
1. Open your browser and go to `http://localhost/aarogyini` to see the application in action.

## Contributing
We welcome contributions from the community. To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes.
4. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
5. Push to the branch:
   ```bash
   git push origin feature-name
   ```
6. Open a pull request.

---

Thank you for choosing Aarogyini to support your health and wellness journey!
