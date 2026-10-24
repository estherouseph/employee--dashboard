# Employee Dashboard

A responsive employee dashboard built with React, Vite, React Router, Axios, and Bootstrap.

## Features
- Home dashboard fetches users from JSONPlaceholder.
- Table shows ID, name, and email.
- Employee form contains Name, Designation, Location, and Salary.
- React Router navigation between Home and Employee Form.
- Responsive Bootstrap styling.
- Loading, error, and empty states.
- No backend and no POST requests.

## Requirements
Node.js 18 or later and npm.

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite (usually http://localhost:5173).

## Production build
```bash
npm run build
npm run preview
```

## Routes
- `/` — Employee Dashboard
- `/employee-form` — Employee Form

## API
https://jsonplaceholder.typicode.com/users

JSONPlaceholder provides sample data. The form performs client-side required-field validation only; it does not store or send data to a server.

## Publish to GitHub
Create an empty repository on GitHub, then run the following commands from this folder (replace the URL):
```bash
git init
git add .
git commit -m "Build Employee Dashboard"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/employee-dashboard.git
git push -u origin main
```
