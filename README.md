# Question Management Web

## Description
**Question Management Web** is a web-based platform designed to manage and organize questions efficiently. This application allows users to create, categorize, and track questions, making it useful for educational institutions, online quizzes, and knowledge management.

## Features
- **Question Creation**: Add and edit questions with different formats (MCQs, True/False, Descriptive, etc.).
- **Category & Tagging**: Organize questions by categories and tags for easy retrieval.
- **User Management**: Role-based access control for admins and contributors.
- **Search & Filter**: Quickly find questions based on keywords, categories, or difficulty levels.
- **Question Bank**: Store and retrieve questions for assessments or practice tests.
- **Analytics & Reports**: Track question usage and user interactions.

## Installation
### Prerequisites
- Node.js 16+
- MongoDB (Self-hosted or MongoDB Atlas)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/amitavrchy/question-management-web.git
   cd question-management-web
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables:
   - Copy `.env.example` to `.env`
   - Configure MongoDB connection and other required settings
4. Run the development server:
   ```sh
   npm run dev
   ```
5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage
- **Admins**: Manage users, create categories, and oversee question organization.
- **Contributors**: Add and edit questions within assigned categories.
- **Users**: Search and access questions for learning or assessment purposes.

## Technologies Used
- **Next.js** – Framework for frontend and server-side rendering.
- **MongoDB** – NoSQL database for scalable question storage.
- **Tailwind CSS** – Styling for a clean and modern UI.
- **NextAuth** – Authentication system without Mongoose.

## Contributing
1. Fork the repository.
2. Create a new branch (`feature-xyz`).
3. Commit and push your changes.
4. Create a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Support
For issues and feature requests, please open an issue in this repository.

---

**Developed by:** Amitav Roy Chowdhury, Mahadi Zulfiker

