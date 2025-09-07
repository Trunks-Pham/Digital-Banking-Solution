# Digital Banking Solution by Pham Minh Thao

The **Digital Banking Solution** is a comprehensive online banking ecosystem that integrates **Mini Banking Solution (Version 1 - 2022)** and **MTPE Digital Bank (Version 2 - 2023)**, combining **web, mobile, backend, and admin services** into a unified platform. This repository serves as the central hub for the **Digital Banking Solution**, built with modern technologies to deliver a secure, scalable, and user-friendly banking experience.

**Watch the Introduction Video:**  
[![Digital Banking Introduction Video](https://img.youtube.com/vi/3zBvXEDJb-w/0.jpg)](https://www.youtube.com/watch?v=3zBvXEDJb-w)

---

## Digital Banking Ecosystem Overview

The Digital Banking Solution is composed of two main projects, each contributing to a robust banking platform:

- **Mini Banking Solution (Version 1 - 2022)** → [Mini-Banking-Solution](https://github.com/Trunks-Pham/Mini-Banking-Solution)  
  A desktop-based banking application built with **C#**, focusing on core banking operations like account management and transactions.

- **MTPE Digital Bank (Version 2 - 2023)** → [MTPE-Digital-Bank](https://github.com/Trunks-Pham/MTPE-Digital-Bank)  
  An advanced online banking system built with **PHP (Laravel)**, **Hack**, **CSS**, and **JavaScript**, offering a responsive web interface and enhanced features.

- **Core Infrastructure**  
  - **MySQL** → Primary relational database for storing user and transaction data (Version 1 & 2).   

**Architecture Diagram:**  
![Ecosystem Architecture](https://github.com/Trunks-Pham/images/blob/master/digital_banking_architecture.png?raw=true)

---

## Database Structure

**Entity Relationship Diagram (ERD):**  
![Database ERD](https://github.com/Trunks-Pham/images/blob/master/digital_banking_erd.png?raw=true)

**Key Tables**  
- `users`: Stores user accounts, personal info, and authentication details.  
- `accounts`: Manages bank accounts, balances, and types (savings, checking, etc.).  
- `transactions`: Records financial transactions (transfers, deposits, withdrawals).  
- `transaction_history`: Detailed logs for auditing and user history viewing.  
- `security_logs`: Tracks login attempts and security events (Version 2).  

---

## Features

### User Functions
- **Account Management:** Create, update, and manage bank accounts (both versions).  
- **Money Transfers:** Securely transfer funds between accounts with real-time confirmation.  
- **Transaction History:** View and filter detailed transaction logs.  
- **User Information Security:** Robust encryption and security measures (e.g., 2FA in Version 2).  
- **Responsive Design:** Accessible on desktop (Version 1) and web/mobile (Version 2).  
- **Authentication:** Email/password login (both versions).   

---

## Prerequisites

For **Mini Banking Solution (Version 1)**:  
- **Visual Studio** (with .NET Framework support)  
- **MySQL**  
- **Git**

For **MTPE Digital Bank (Version 2)**:  
- **PHP** (>= 7.4)  
- **Composer**  
- **MySQL** (>= 5.7)  
- **Web server** (e.g., Apache, or PHP's built-in server)  
- **Git**

---

## Installation

### Mini Banking Solution (Version 1)
1. **Fork the Repository**:  
   - Navigate to [Mini Banking Solution](https://github.com/Trunks-Pham/Mini-Banking-Solution) and click "Fork".

2. **Clone the Repository**:  
   ```bash
   git clone https://github.com/Trunks-Pham/Mini-Banking-Solution.git
   ```

3. **Open the Project**:  
   - Open `MiniBanking.sln` in Visual Studio.

4. **Build the Project**:  
   - Select `Build` > `Build Solution` in Visual Studio.

5. **Run the Project**:  
   - Select `Debug` > `Start Debugging`.

### MTPE Digital Bank (Version 2)
1. **Fork the Repository**:  
   - Navigate to [MTPE Digital Bank](https://github.com/Trunks-Pham/MTPE-Digital-Bank) and click "Fork".

2. **Clone the Repository**:  
   ```bash
   git clone https://github.com/Trunks-Pham/MTPE-Digital-Bank.git
   ```

3. **Install Dependencies**:  
   - Navigate to the project directory and run:
     ```bash
     composer install
     ```

4. **Configure the Database**:  
   - Create a MySQL database and import the provided SQL schema.  
   - Update `config.php` with database credentials (hostname, database name, username, password).

5. **Start the Server**:  
   - Use a web server or start PHP’s built-in server:
     ```bash
     php -S localhost:8000
     ```

6. **Verify Setup**:  
   - Ensure dependencies and database are correctly configured.  
   - Check for error logs in the console or server.

---

## Usage

### Mini Banking Solution (Version 1)
- Access the application via Visual Studio’s interface.  
- Register a new account or log in.  
- Perform banking functions like transferring money and viewing transaction history.  

### MTPE Digital Bank (Version 2)
- Access the application at `http://localhost:8000`.  
- Register a new account or log in with existing credentials.  
- Perform core functions:  
  - Transfer funds between accounts.  
  - View and filter transaction history.  
  - Update personal information securely.  
- **Security Tips**:  
  - Enable two-factor authentication (2FA).  
  - Use strong, unique passwords.  
  - Log out after each session.  

---

## Impressive Display

### Mini Banking Solution (Version 1)
- **Registration Screen**:  
  ![Registration Screen](https://github.com/Trunks-Pham/Mini-Banking-Solution/blob/main/%C4%90%C4%83ng_k%C3%BD_nh%E1%BA%ADp.png)  
- **Home and Information Page**:  
  ![Home and Information Page](https://github.com/Trunks-Pham/Mini-Banking-Solution/blob/main/trang_ch%E1%BB%A7_th%C3%B4ng_tin.pn)

### MTPE Digital Bank (Version 2)
- **Main Interface**:  
  ![Main Interface](https://github.com/Trunks-Pham/MTPE-Digital-Bank/blob/main/MTPE-BANK.png)

---

## Contributing

We welcome contributions to both projects! To contribute:  
1. **Fork the Repository**: Create a copy in your GitHub account.  
2. **Clone Your Fork**:  
   ```bash
   git clone https://github.com/<your-username>/Mini-Banking-Solution.git
   ```
   or
   ```bash
   git clone https://github.com/<your-username>/MTPE-Digital-Bank.git
   ```
3. **Create a Branch**:  
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Commit Changes**:  
   ```bash
   git commit -m "Add your descriptive message here"
   ```
5. **Push to GitHub**:  
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Submit a Pull Request**: Navigate to the original repository and submit a pull request.

---

## Code of Conduct

- Be respectful and inclusive in all interactions.  
- Follow best practices for coding, documentation, and testing.  
- Report issues or bugs via GitHub Issues.  

---

## Contact

- **Author**: Pham Minh Thao  
- **GitHub**: [Trunks-Pham](https://github.com/Trunks-Pham)  
- **Email**: For inquiries, please open an issue on GitHub.  

---

## Acknowledgments

- Thanks to the open-source community for providing tools and libraries.  
- Special appreciation to contributors and testers of the Mini Banking Solution and MTPE Digital Bank projects.
