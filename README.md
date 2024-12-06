# CSRF (Cross-Site Request Forgery) Demonstration

This project provides two practical examples illustrating Cross-Site Request Forgery (CSRF) vulnerabilities, demonstrating how attackers can trick users into performing unintended actions on a trusted website.

## CSRF Example 1: Bank Website Vulnerability

### Prerequisites
- Web browser
- Live server extension (e.g., Live Server for VS Code)

### Setup and Execution
1. Clone the repository
2. Open `csrf_example.html` using a live server
3. Observe the CSRF attack mechanism in action

### Vulnerability Demonstration
This example shows how a malicious website can trigger unauthorized actions on a trusted bank website without the user's explicit consent.

## CSRF Example 2: Account Balance Manipulation

### Prerequisites
- Node.js
- npm (Node Package Manager)

### Setup and Execution
1. Navigate to the `example2` directory
   ```bash
   cd example2
   ```
2. Install dependencies and start the server
   ```bash
   npm start
   ```
3. Open browser tabs:
   - Tab 1: `localhost:3000` 
     - Login with username: `bob`
     - Password: `test`
   - Tab 2: `localhost:3001`
     - Refresh or click link to demonstrate CSRF attack
     - Observe unauthorized account balance reduction

