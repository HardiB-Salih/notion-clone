# Nimbus

Nimbus is a powerful and flexible clone of Notion, built with modern web technologies to provide a seamless and efficient experience for managing documents, notes, and tasks. Nimbus uses Next.js for the frontend, Shadcn UI for component styling, and Convex for the backend, offering a robust and scalable architecture.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Rich Text Editing**: Create and edit documents with a powerful WYSIWYG editor.
- **Document Management**: Organize your documents with folders, tags, and more.
- **Real-Time Collaboration**: Collaborate with others in real-time.
- **Dark/Light Mode**: Automatically adjusts based on the user's system preference or manually toggleable.
- **Responsive Design**: Fully responsive and accessible on all devices.
- **Search Functionality**: Quickly find documents and content with a powerful search tool.

## Tech Stack

### Frontend

- **Next.js**: A React framework for building fast, server-rendered applications.
- **Shadcn UI**: A collection of pre-styled UI components that make building interfaces easy and consistent.

### Backend

- **Convex**: A backend-as-a-service (BaaS) platform for building real-time applications.

## Installation

### Prerequisites

- Node.js (v14 or later)
- Yarn (or npm)
- Convex account and setup

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/nimbus.git
   cd nimbus
   ```

2. **Install dependencies:**

   ```bash
   yarn install
   # or
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env.local` file in the root directory and add the necessary environment variables:

   ```
   NEXT_PUBLIC_CONVEX_URL=<your_convex_url>
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
   ```

4. **Run the development server:**

   ```bash
   yarn dev
   # or
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) to see the app.

## Usage

Once the application is running, you can start creating and managing documents. The interface is intuitive and user-friendly, with support for creating rich text documents, organizing them into folders, and collaborating with others in real-time.

## Project Structure

- `pages/`: Contains the Next.js pages for different routes.
- `components/`: Reusable React components used throughout the application.
- `lib/`: Utility functions and libraries.
- `styles/`: Global and component-specific styles.
- `convex/`: Contains backend logic using Convex.

## Contributing

We welcome contributions to Nimbus! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. **Fork the repo and create your branch:**

   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Commit your changes:**

   ```bash
   git commit -m "Add some feature"
   ```

3. **Push to the branch:**

   ```bash
   git push origin feature/your-feature-name
   ```

4. **Create a Pull Request**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to modify and adapt Nimbus to suit your needs. We hope it helps you in your journey to build powerful and intuitive applications!
