# Streamify: A Full-Featured Twitch Clone

Streamify is a comprehensive project designed to replicate and enhance key features of Twitch. Built with a robust tech stack, Streamify includes advanced functionalities such as account verification, TOTP authentication, real-time streaming, chat systems, subscription management, and much more. This project delivers a rich user experience with customization options and integrations like Telegram bot notifications, making it an ideal platform for learning and showcasing full-stack development.

---

## 🚀 Features

### **Authentication & Authorization**

- **Session Management**: Authentication using Redis for session storage.
- **Account Verification**: Email-based account verification system.
- **TOTP Authentication**: Two-factor authentication for added security.
- **Password Recovery**: Easy password reset functionality.

### **Streaming Features**

- **Live Streaming**: Users can host and join live streams.
- **Subscriptions**: Implemented subscription system, including premium subscriptions for streamers.
- **Stream Chat**: Integrated real-time chat for live streams.

### **User Profiles**

- Fully customizable user profiles:
    - Display name.
    - Bio and social media links.
    - Change password and email.

### **Site Customization**

- **Themes**: Switch between light and dark modes.
- **Primary Color**: Choose a primary color for the interface.
- **Localization**: Supports English and Russian languages.

### **Telegram Bot Integration**

- Notifies users about new streams on their subscribed channels.
- Allows users to view their profile directly within Telegram.

### **Admin Features**

- Manage users, streams, and subscriptions through a dedicated admin panel.

---

## 🛠️ Tech Stack

Streamify is powered by a modern and scalable technology stack:

### **Backend**

- [**Nest.js**](https://nestjs.com/): Framework for building scalable server-side applications.
- **GraphQL**: API development for efficient client-server communication.
- [**Prisma**](https://www.prisma.io/): ORM for database interaction.
- **PostgreSQL**: Relational database for secure data storage.
- **Redis**: In-memory data structure store for sessions and caching.
- **Docker**: Containerized deployment for seamless scalability.
- **Telegraf**: Telegram bot framework.

### **Frontend**

- [**Next.js**](https://nextjs.org/): Framework for server-rendered React applications.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Apollo Client**: GraphQL client for state management.
- **Zustand**: State management library for React.
- **React Hook Form & Zod**: Form validation and type safety.
- **React Email**: For sending beautifully styled emails.

---

## 📦 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- Docker
- PostgreSQL
- Redis

### Installation

1. Clone the repository:
    
    ```
    git clone https://github.com/arslankamchybekov/streamify.git
    cd streamify
    ```
    
2. Install dependencies for both frontend and backend:
    
    ```
    cd server && npm install
    cd ../frontend && npm install
    ```
    
3. Configure environment variables:
    - Create `.env` files for both server and frontend based on the provided examples.
4. Start services:
    
    ```
    docker-compose up
    ```
    

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 📧 Contact

For any inquiries or support, reach out to kamchybekov.arslan.us@gmail.com.

Happy Coding!