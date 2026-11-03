# Project Name Frontend

## Overview

Give quick overview on how it works and how the user can use it

## Live Application

- **Frontend:** Deployed frontend
- **Backend API:** Deployed Backend
- **Backend Repository:** Backend Github Repository

## Screenshots

### Home Page


### Feature Page

### Other pages



## Technologies Used

- React
- Vite
- React Router
- Axios
- CSS or CSS Modules

Only include ones you used on frontend

## Features

- User registration and login
- Protected routes
- etc.


## Project Structure

If you have different structure than this then add or remove from it

```text
src/
├── assets/
├── components/
├── context/
├── pages/
├── services/
├── styles/
├── App.jsx
└── main.jsx
```

## Getting Started

### Prerequisites

Install the following before running the project:

- node.js

The backend API has to be working. LINK TO THE BACKEND API

## Installation

### 1. Clone the repository

```bash
git clone FRONTEND_REPOSITORY_URL
cd FRONTEND_REPOSITORY_NAME
```

### 2. Install dependencies

```bash
npm install
```

### 3. Create the environment file

Create a `.env` file in the root directory:

```env
VITE_BACK_END_SERVER_URL=http://localhost:3000
```

### 4. Start the development server

```bash
npm run dev
```

Go to:

```text
http://localhost:5173
```


## Application Routes

| Route                       | Page              | Access         |
| --------------------------- | ----------------- | -------------- |
| `/`                         | Home page         | Public         |
| `/register`                 | Registration page | Public         |
| `/login`                    | Login page        | Public         |
| `/products`                 | Product list      | Public         |
| `/products/:productId`      | Product details   | Public         |
| `/products/new`             | Create product    | Authenticated  |
| `/products/:productId/edit` | Edit product      | Owner or admin |
| `*`                         | Not-found page    | Public         |


## User Stories


## Future Enhancements


## Team Members

| Name         | GitHub           |
| ------------ | ---------------- |
| Student Name | [GitHub profile] |
| Student Name | [GitHub profile] |


## Credits
