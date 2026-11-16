# 🌍 Family Travel Tracker

Family Travel Tracker is a multi-user web application built to help family members track their travel journeys and explore the countries they have visited on an interactive world map.

Each family member has their own profile and unique color, and their visited countries are highlighted on the map, making it easy to visualize everyone's travel history.

## ✨ Features

- **Multi-User Support:** Multiple family members can use the application.
- **Individual Profiles:** Each family member has a separate profile.
- **Unique Color Identification:** Every family member is assigned a unique color.
- **Interactive World Map:** Displays the countries visited by family members.
- **Visited Countries Tracking:** Highlights visited countries on the world map.
- **Database Integration:** Stores family members and travel information using PostgreSQL.

## 🛠️ Technologies Used

- **Backend:** Node.js, Express.js
- **Frontend:** EJS, HTML, CSS
- **Database:** PostgreSQL
- **Styling:** CSS
- **Version Control:** Git and GitHub

## 📁 Project Structure

```text
Family-Travel-Tracker/
│
├── public/
│   └── styles/
│
├── views/
│
├── index.js
├── queries.sql
├── package.json
├── package-lock.json
└── .gitignore
```

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/anvi-mittall/Family-Travel-Tracker.git
```

### 2. Navigate to the Project Folder

```bash
cd Family-Travel-Tracker
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure PostgreSQL

- Make sure PostgreSQL is installed and running.
- Create the required database.
- Configure the database connection.
- Execute the SQL queries provided in `queries.sql`.

### 5. Start the Application

```bash
npm start
```

Open your browser and visit:

```text
http://localhost:3000
```

## 🎯 Project Objective

The main objective of this project is to develop a shared family travel tracking platform where multiple family members can maintain their individual travel records and visualize their visited destinations on an interactive world map.

The application provides an easy and engaging way to keep track of family adventures and travel memories.