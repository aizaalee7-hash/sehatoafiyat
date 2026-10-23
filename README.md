# Sehat o Afeyat — صحت و عافیت

### A Healthcare & Blood Donation Management Platform

Sehat o Afeyat is a healthcare platform designed to connect patients, blood donors, hospitals, NGOs, and other healthcare organizations in one place. Its goal is to make healthcare assistance and blood donation more accessible and organized.

## Key Features

- **Patient Dashboard:** Manage patient information and healthcare requests.
- **Blood Donor Matching:** Help patients find suitable blood donors.
- **Hospital Dashboard:** Support hospitals in managing healthcare requests.
- **NGO Support:** Connect NGOs with patients and community healthcare needs.
- **Request Management:** Create and track blood and healthcare requests.
- **AI-Powered Report Analysis:** Help users understand medical reports in simpler language.
- **Notifications:** Keep users informed about requests and updates.
- **User Authentication:** Support account registration and login.

## Technology Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js and Express.js
- API: REST API
- AI Integration: AI-powered medical report analysis
- Deployment: Render
- Version Control: GitHub

## Project Structure

```text
sehat-o-afeyat/
├── backend/
│   ├── server.js
│   ├── package.json
│   ├── .env.example
│   └── README.md
└── README.md
```

*Note: The frontend file structure may vary depending on the current implementation.*

## How to Run Locally

1. Install Node.js.
2. Open the backend folder in your terminal.
3. Install dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file using `.env.example` as a reference.
5. Start the server:

   ```bash
   npm start
   ```

6. Open `http://localhost:3000/` in your browser.

## API Health Check

Visit:

```text
http://localhost:3000/api/health
```

A successful response should look like:

```json
{
  "ok": true
}
```

## Deployment

The backend can be deployed using Render by connecting this GitHub repository and configuring the appropriate root directory, build command, start command, and environment variables.

## Important Note

This project is developed for hackathon and demonstration purposes. Medical report analysis is informational only and is not a substitute for professional medical advice. Do not use demo storage for real patient or donor information.

## Project Goal

**Connecting people, saving lives, and making healthcare assistance more accessible through technology.**

