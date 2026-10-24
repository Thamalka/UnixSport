# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

🛠️ Admin Dashboard Module

The **UniXsport Admin Dashboard** serves as the central control center for administrators, physical education instructors, and sports inventory officers at Rajarata University of Sri Lanka.

🌟 Key Admin Features

**📊 Real-time Overview Dashboard**
  * Live status counters for Total Students, Coaches, Equipment Inventory, and Damaged Items.
  * Interactive breakdown widget monitoring stock availability (*Available*, *Borrowed*, *Needs Repair*).
  * Quick-action shortcuts and recent announcement feed.

👥 User Management (Students & Coaches)
  * Full user account control with role filtering (`Student` vs `Coach`) and real-time name/email search.
  * RFID tag code tracking and role-based badge displays.
  * Direct CRUD operations (Add, Edit, Delete user profiles).

🏋️ Gym & Sports Equipment Inventory
  * Complete inventory tracking filtered by status (*Available*, *Borrowed*, *Damaged*) and venue/room (*Main Gym Hall*, *Badminton Court*, *Cricket Pavilion*, *Indoor Complex*).
  * Quantity tracking and color-coded condition badges.

📢 Notice & Broadcast Center
  * Publish sitewide announcements targetable by audience (*All*, *Students Only*, *Coaches Only*).
  * Priority level tagging (*Normal*, *High*, *Urgent*).

👤 Admin Profile & Account Settings
  * Profile picture upload with instant client-side preview.
  * Credentials management and password security updates.
