# GoalSense - A Web App for Tracking Goals and Habits

GoalSense is a user-friendly web application designed to help individuals in the neurodivergent community track their goals and habits effortlessly. The user interface is designed with a low perceptual load to ensure ease of use and reduce cognitive strain.

## Features

- Create and manage personal goals and habits.
- Keep goals private or allow public views.
- Track progress through an intuitive and clutter-free interface.
- Quickly analyze data visually with our easy to read calendar.
- Personalize the app's appearance according to individual preferences.
- Responsive design for seamless use across different devices.
- Follow other users with the ability to 'like' and comment their public goals.
- 'Feed' view based on followed users.

Coming soon:

- Pomodoro timer to help with finding balance betwen focus and healthy breaks.
- Set reminders and notifications to stay on track.

## How It's Made:

**Tech used:**

Backend:

- Node.js: Backend server environment for building scalable web applications.
- Express.js: Web application framework for Node.js, used to handle routing and server-side logic.
- MVC (Model-View-Controller) Architecture
- JSON Web Token stored in secure httpOnly cookie for authentication
- MongoDB: NoSQL database for storing user data securely.
- Mongoose: straight-forward, schema-based solution for modeling application data.
- Cloudinary: Digital Asset Management (DAM) focused on flexibility, intelligent automation, and scale.
- Custom Error Handler -

Frontend:

- JavaScript: Programming language for implementing interactive functionality.
- Tailwind CSS: Utility-first CSS framework for easy and consistent UI design.

## Optimizations

- Authentication/Route Protection:
  Changed from original authentication/session strategy to JSON Web Token within Secure httpOnly cookie to reduce storage needs. Cookie is stored in the browser instead of session information being stored in the DB. Upon logout, the cookie is destroyed. Authentication middleware ensures that the routes are protected.

## Lessons Learned/Reinforced:
