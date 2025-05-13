# CarePulse

<div align="center">
  <img src="https://www.markaustria.com/carepulse.png" alt="CarePulse" />

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)
</div>

## 🌐 Live Site

🚀 Here is a working live site: [carepulse.markaustria.com](https://carepulse.markaustria.com/)

🗒️ Check out the case study here: [markaustria.com/carepulse](https://www.markaustria.com/carepulse)

## 📝 Description

Welcome to CarePulse! A healthcare management system that streamlines the patient appointment process with real-time SMS notifications.

Healthcare appointments often involve long waiting times and inefficient processes. Patients typically spend hours waiting for their doctor's appointments, creating frustration and wasting valuable time. The existing manual systems lack real-time updates and proper communication channels between healthcare providers and patients.

The mission of the CarePulse project was to create a healthcare management system that streamlines the appointment process and improves communication between patients and healthcare providers.

The application features patient registration, appointment scheduling, and an admin dashboard for managing appointments with real-time SMS notifications.

**Technologies Used:** Next.js, TypeScript, Tailwind CSS, Shadcn UI, Appwrite, Twilio, Sentry, React Hook Form, Zod

## 📖 Table of Contents

- [Features](#-features)
- [Installation](#%EF%B8%8F-setup-project)
- [How to Contribute](#%EF%B8%8F-how-to-contribute)
- [Bug / Feature Request](#-bug--feature-request)
- [Future Enhancements](#-future-enhancements)
- [Acknowledgements](#-acknowledgements)

## ✨ Features

- **Advanced Form Management System:** Highly reusable form system with custom components for various input types including text fields, phone inputs, date pickers, file uploads, and more. This allows for complex multi-step registration forms while maintaining clean, maintainable code.

- **Real-time SMS Notifications:** SMS notifications using Appwrite and Twilio integration to keep patients informed about their appointment status. When an admin schedules or cancels an appointment, the patient receives an immediate notification with relevant details.

- **Comprehensive Admin Dashboard:** Feature-rich admin dashboard with appointment statistics, a data table for managing appointments, and functionality to schedule or cancel appointments. The dashboard provides a complete overview of all patient appointments with filtering and pagination capabilities.

## 🛠️ Setup Project

To get this project up and running in your development environment, follow these step-by-step instructions.

### 🍴 Prerequisites

We need to install or make sure that these tools are pre-installed on your machine:

- [Git](https://git-scm.com/downloads)
- [NodeJS](https://nodejs.org/en/download/)
- [NPM](https://docs.npmjs.com/getting-started/installing-node)

### 🚀 Install Project

1. Clone the Repository

   ```bash
   git clone https://github.com/mjaus29/carepulse.git
   ```

2. Navigate into the project directory

   ```bash
   cd carepulse
   ```

3. Install dependencies

   ```bash
   npm install
   ```

4. Set up environment variables

   - Create a .env.local file in the root directory.
   - Add the following environment variables:
     ```
     # Appwrite
     PROJECT_ID=your_appwrite_project_id
     API_KEY=your_appwrite_api_key
     DATABASE_ID=your_appwrite_database_id
     PATIENT_COLLECTION_ID=your_patient_collection_id
     DOCTOR_COLLECTION_ID=your_doctor_collection_id
     APPOINTMENT_COLLECTION_ID=your_appointment_collection_id
     NEXT_PUBLIC_BUCKET_ID=your_appwrite_bucket_id
     NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
     NEXT_PUBLIC_ADMIN_PASSKEY=your_admin_passkey
     ```

5. Start the application

   ```bash
   npm run dev
   ```

6. Open your web browser and navigate to <a href="http://localhost:3000" target="_blank">http://localhost:3000</a> to see the project running.

7. Test the application

   Run the test suite to ensure everything is working as expected.

   ```bash
   npm test
   ```

## ⚒️ How to Contribute

Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:

- Fork the repo
- Create a new branch (`git checkout -b improve-feature`)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (`git commit -am 'Improve feature'`)
- Push to the branch (`git push origin improve-feature`)
- Create a Pull Request

### 📩 Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/mjaus29/carepulse/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/mjaus29/carepulse/issues/new). Please include sample queries and their corresponding results.

### ✅ Future Enhancements

- [ ] Implement a doctor-specific interface for managing their own appointments
- [ ] Add video consultation capabilities for remote appointments
- [ ] Integrate with electronic health record (EHR) systems
- [ ] Implement automated appointment reminders at configurable intervals

### 📚 Acknowledgements

Special thanks to JSM for the inspiration and guidance on this project.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)
</div>
