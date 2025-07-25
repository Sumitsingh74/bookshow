# Bookshow 🎬

Bookshow is a full-stack movie booking application built with the MERN (MongoDB, Express, React, Node.js) stack. It provides a seamless movie booking experience with secure authentication, dynamic booking features, and an intuitive admin panel.

## 🚀 Live Demo

[Live Website](https://bookshow-eight.vercel.app/)

## 📂 Features

* **User Authentication:** Secure login/signup flows powered by Clerk.
* **Dynamic Movie Listings:** Browse and book available movie shows.
* **Real-time Seat Booking:** Instant booking confirmations.
* **Admin Panel:** Manage movies, showtimes, bookings, and receive real-time updates.
* **Responsive UI:** Built using React and Tailwind CSS for optimal viewing on all devices.

## 🛠️ Tech Stack

* **Frontend:** React, Tailwind CSS, Axios
* **Backend:** Node.js, Express
* **Database:** MongoDB
* **Authentication:** Clerk
* **Deployment:** Vercel

## 📁 Project Structure

```
client/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── admin/
│   │   ├── BlurCircle.jsx
│   │   ├── DateSelect.jsx
│   │   ├── FeaturedSection.jsx
│   │   ├── Footer.jsx
│   │   ├── HeroBanner.jsx
│   │   ├── HeroSection.jsx
│   │   ├── Loading.jsx
│   │   ├── MovieCard.jsx
│   │   ├── Navbar.jsx
│   │   └── TrailersSection.jsx
│   ├── context/
│   ├── lib/
│   └── pages/
│       ├── admin/
│       └── Favorite.jsx
```

## ⚙️ Installation

1. **Clone the repository:**

```sh
git clone https://github.com/Sumitsingh74/bookshow.git
```

2. **Navigate to project directory:**

```sh
cd bookshow
```

3. **Install dependencies:**

```sh
cd client && npm install
cd ../server && npm install
```

4. **Set up environment variables:**

Create `.env` files in the client and server directories to store configuration variables:

Example (`server/.env`):

```
MONGODB_URI=your_mongodb_uri
CLERK_SECRET_KEY=your_clerk_secret_key
```

Example (`client/.env`):

```
REACT_APP_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

5. **Run the project locally:**

* Backend:

```sh
cd server && npm run dev
```

* Frontend:

```sh
cd client && npm start
```

## 📌 Contribution

Contributions are welcome! Feel free to open issues or submit pull requests.
