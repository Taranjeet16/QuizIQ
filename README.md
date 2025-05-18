# QuizIQ – The Adaptive AI Quiz Platform

## Overview

QuizIQ is an adaptive AI-driven quiz platform designed to enhance learning through personalized quizzes. It leverages AI to tailor quizzes to users' knowledge levels and preferences, providing a dynamic and engaging quiz experience. The platform features user dashboards, real-time performance insights, admin management, and customizable quiz creation.

---

## Features

* **Adaptive Quizzes:** AI-powered quizzes adjust difficulty based on user performance.
* **User Dashboard:** Track performance, badges, recommended topics, and leaderboards.
* **Admin Panel:** Manage questions, view user statistics, and analyze engagement.
* **Custom Quiz Creator:** Create tailored quizzes by selecting categories and difficulty.
* **Authentication & Profiles:** Secure login with personalized user profiles.
* **Responsive Design:** Mobile-friendly interface with theme toggling support.
* **Analytics:** Detailed quiz analytics for users and admins.
* **FAQ and Help Sections:** Easily accessible support and information.

---

## Technology Stack

* **Frontend:** React + TypeScript
* **Styling:** Tailwind CSS
* **State Management:** React Context API
* **Build Tool:** Vite
* **Linting:** ESLint
* **UI Components:** Custom-built reusable components

---

## Installation & Setup

1. Clone the repository:

   ```bash
   git clone <repo-url>
   cd quiziq
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173` (or the port Vite chooses).

---

## Folder Structure

```
src/
  components/    # UI components and feature modules (Admin, Dashboard, Quiz, Auth, Layout)
  contexts/      # React Contexts for state management (QuizContext, UserContext)
  data/          # Static data like dummy database JSON
  hooks/         # Custom React hooks (use-mobile, use-toast)
  lib/           # Utility functions
  pages/         # Route components (Admin, Dashboard, Quiz, Profile, etc.)
public/          # Static assets like favicon
```

---

## Usage

* Register or login to start taking adaptive quizzes.
* Use the dashboard to view performance insights and recommended topics.
* Admin users can manage questions and view platform analytics.
* Create custom quizzes by selecting categories and difficulty levels.
* Access help and FAQ pages for assistance.

---

## Contributing

Contributions are welcome! Please open issues or pull requests with proposed improvements or bug fixes.

---

## License

This project is licensed under the MIT License.

---
