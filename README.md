# Job Portal App with MERN Stack

A comprehensive job portal application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application allows users to browse job listings, apply for jobs, and manage their applications seamlessly.

## Features

- **User Authentication:** Secure authentication using JWT (JSON Web Tokens) for both job seekers and employers.
- **Job Listings:** Browse through a wide range of job listings fetched from MongoDB.
- **Application Management:** Job seekers can manage their job applications, and employers can view and manage received applications.
- **Responsive Design:** Ensures a seamless experience across all devices.

## Technologies Used

- **Frontend:** React.js, React Router, Bootstrap
- **Backend:** Node.js, Express.js, MongoDB
- **Authentication:** JWT (JSON Web Tokens), Bcrypt (for password hashing)
- **Image Upload:** Cloudinary for storing and managing uploaded images
- **Deployment:** Vercel (frontend), Render (backend), MongoDB Atlas (database)

## Getting Started

Follow these steps to set up the project locally.

### Prerequisites

- Node.js installed on your machine (latest version or v22.2.0 and above)
- MongoDB Atlas account (or local MongoDB server)
- Cloudinary account for image storage

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/vipranshanand/react-job-portal.git
   ```
2. Install dependencies:
   ```sh
   cd react-job-portal
   cd backend
   npm install
   cd ..
   cd frontend
   npm install
   ```
3. Set up environment variables:
   - Create a `config.env` file inside a `config` folder in the backend directory, containing the following variables:
   ```env
   PORT=
   CLOUDINARY_API_KEY=
   CLOUDINARY_API_SECRET=
   CLOUDINARY_CLOUD_NAME=
   FRONTEND_URL=
   DB_URL=
   JWT_SECRET_KEY=
   JWT_EXPIRE=
   COOKIE_EXPIRE=
   ```
   Replace each placeholder with your actual configuration values.

4. Run the application:
   ```sh
   npm run dev
   ```
5. Open your browser and navigate to `http://localhost:5173` to access the app.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request (we will merge within 24 hours)

## Support the Project

If you like this repository, please give it a **star** ⭐ on GitHub.

## Contact

Vipransh Anand - [GitHub](https://github.com/vipranshanand)

Project Link: [https://github.com/vipranshanand/react-job-portal.git](https://github.com/vipranshanand/react-job-portal.git)

