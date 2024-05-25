# 🎓 National Institute of Technology Patna Admin Portal 🌐

Welcome to the official repository for the National Institute of Technology Patna's admin portal. This repository contains all the source code, assets, and documentation needed to develop and maintain the admin portal.

## 📋 Table of Contents

- [Introduction](#introduction)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [License](#license)

## 📘 Introduction

This repository contains the source code and assets for the admin portal of the National Institute of Technology Patna (NIT Patna). The portal is built using Next.js and integrates Google Authentication.

## 🛠 Tech Stack

- **Framework**: Next.js
- **Authentication**: Google Auth
- **Language**: JavaScript
- **Server**: Node.js (v16.x)
- **Package Manager**: npm

## 🚀 Getting Started

To get a local copy of the project up and running, follow these steps:

1. **Clone the repository:**
 
   ```bash
   git clone https://github.com/nitp-website/NITP-Admin-Portal-EC2.git
   cd NITP-Admin-Portal-EC2
   ```

2. **Install dependencies:**
   
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the necessary environment variables as specified in the [Environment Variables](#environment-variables) section.

4. **Start the development server:**
   
   ```bash
   node server.js
   ```

5. **Access the admin portal:**
   Open your browser and navigate to `http://localhost:81`.

## 🌐 Environment Variables

Before running the application, you need to set up the necessary environment variables. Create a `.env` file in the root directory and add the following placeholders:

```bash
NEXTAUTH_URL=http://localhost:81
URL=http://localhost:81
DOMAIN=http://localhost:81
NEXT_GOOGLE_ID=
NEXT_GOOGLE_SECRET=
JWT_SECRET=
MYSQL_HOST=
MYSQL_DATABASE=
MYSQL_USERNAME=
MYSQL_PASSWORD=
MYSQL_PORT=
PORT=
TOKEN_PATH=
FOLDER_ID=
BROADCAST_EMAIL=
BROADCAST_EMAIL_PASS=
REDIRECT_URIS=https://developers.google.com/oauthplayground/
```

Replace the placeholder values with your actual credentials and configuration settings.

## 🤝 Contributing

We welcome contributions to improve the admin portal. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a pull request.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

For any questions or support, please contact the project maintainers.
