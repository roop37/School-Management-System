````markdown
# School Management System

Welcome to the School Management System, a comprehensive MERN stack website designed to streamline school administration. This repository encompasses a range of features crucial for effective school management, with ongoing development to enhance its capabilities.

If you find this project beneficial, please consider giving it a star. Your support is highly appreciated and serves as motivation for future projects. Please note that the live URL is currently unavailable due to Heroku removing free services.

## Demo Credentials

To explore the full functionality of the system, log in as an administrator using the following credentials:

- **Email:** admin1@example.com
- **Password:** adminpassword1

## Usage

Begin by cloning the repository:

```bash
git clone https://github.com/upendradhamala/School-Management-System.git
```
````

### Getting Started

Navigate to the root folder and install backend dependencies:

```bash
npm install
```

Proceed to the frontend folder (`cd frontend`) and install frontend dependencies:

```bash
npm install
```

### Environment Variables

Create a `.env` file in the root directory and add the following variables (refer to `.env.example` for the format):

```bash
NODE_ENV=development
PORT=5000
MONGO_URI="Your MongoDB URI"
JWT_SECRET="YourSecretKey"
CLOUDINARY_URL ="Your Cloudinary URL"
CLOUDINARY_UPLOAD_PRESET = "Your Cloudinary Upload Preset"
```

Create another `.env` file in the frontend folder with the following variables:

```bash
REACT_APP_CLOUD_NAME="Your Cloud Name"
REACT_APP_CLOUD_PRESET="Your Cloud Preset"
```

### Running

In the root folder, seed the database:

```bash
npm run data:import
```

Once the seed is successful, run the following command to start both the backend and frontend concurrently:

```bash
npm run dev
```

### Homepage

[![Homepage Screenshot](https://i.postimg.cc/jjHs8psH/Screenshot-from-2021-04-30-16-59-15.png)](https://postimg.cc/67QJq14q)

Feel free to explore the user-friendly interface and manage school activities effortlessly!

```

```
