# Blood_Donation_Software.Base.
User-friendly application that efficiently connects blood donors with recipients

# 🩸 Blood Donation Management System

A simple and functional PHP & MySQL-based Blood Donation Management System for managing donors, patients, and donation records.

## 📁 Project Structure

```
Blood_Donation_Software.Base-Project-Topic/
│
├── css/                 # Stylesheets
├── header/              # Header components
├── img/                 # Images and media
│
├── about.php            # About page
├── blood.php            # Blood info handler
├── blood_donation.sql   # Database schema file
├── connection.php       # Database connection setup
├── delete.php           # Delete operation
├── donation.php         # Blood donation form/page
├── donationlist.php     # List of donations
├── donorlist.php        # List of donors
├── header.php           # Page header
├── home.php             # Home/landing page
├── index.php            # Main entry point
├── login.php            # Login page
├── logout.php           # Logout handler
├── map.php              # Donor location map (if integrated)
├── nav2.php             # Secondary navigation bar
├── navbar.php           # Main navbar
├── patientlist.php      # List of patients
├── reg.php              # Donor registration
├── reg2.php             # Patient registration
```

## ⚙️ Features

- ✅ Donor and patient registration
- ✅ Login and logout system
- ✅ List views for donors, patients, and donation records
- ✅ Delete functionality for managing records
- ✅ Map integration placeholder
- ✅ Reusable header and navbar components
- ✅ SQL schema included

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS
- **Backend**: PHP (Core PHP)
- **Database**: MySQL

## 🚀 Getting Started

### Prerequisites

- [XAMPP](https://www.apachefriends.org/) or any local server with PHP & MySQL
- A browser
- Git (optional)

### Setup Instructions

1. **Clone the repository** or download the ZIP:

   ```bash
   git clone https://github.com/yourusername/Blood_Donation_Software.Base-Project-Topic.git
   ```

2. **Move the project folder** into your web server directory:

   - For XAMPP: `C:/xampp/htdocs/`

3. **Import the database**:

   - Open `phpMyAdmin`
   - Create a new database (e.g., `blood_donation`)
   - Import the `blood_donation.sql` file located in the project root

4. **Configure database connection**:

   - Open `connection.php` and update the credentials:
     ```php
     $conn = mysqli_connect("localhost", "root", "", "blood_donation");
     ```

5. **Run the project**:

   - Visit `http://localhost/Blood_Donation_Software.Base-Project-Topic/index.php` in your browser

## 📌 Notes

- Improve form validation and security for production use
- Consider adding session checks for restricted pages
- Optional: Add user roles (admin, donor, patient)

## 🧑‍💻 Author

Developed as part of a basic PHP-MySQL based software project:  
**Blood_Donation_Software.Base-Project-Topic**

## 📄 License

This project is open-source and free to use for learning and development purposes.
