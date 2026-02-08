# Advent Calendar App

A full-stack web application that allows users to create customizable digital advent calendars with daily surprises, images, videos, and messages.

## My Contributions

Forked project where I implemented the complete backend infrastructure and state management:

### Backend Infrastructure (Firebase)
- **Authentication**: Email/password registration and login with automatic user document creation in Firestore
- **Firestore Database**: Schema design and CRUD operations for user and calendar data persistence
- **Cloud Storage**: Image and video upload/deletion management with automatic cleanup

### State Management (Redux)
- Built Redux store with 40+ reducers managing complex nested state for calendar/hatch configurations, styling, media uploads, and positioning


### Additional Contributions
- UI components and routing

## Technologies Used
**Backend:** Firebase (Firestore, Storage, Authentication)   
**Frontend:** React.js, Redux Toolkit, Material-UI

## Installation
```bash
git clone https://github.com/KozhInna/advent-calendar-app.git advent
cd advent
npm install  # in /client and /server
npm run dev  # in /client
```

## Screenshots
![Register](./client/src/assets/register.png)
![Hatch Editor](./client/src/assets/hatcheditor.png)

## Team
Team project at Business College Helsinki:

- **Inna Kozhina** - Backend Infrastructure, Firebase Integration & State Management
- Wen Yan - Design, Frontend
- Emmanuel Monle Nyode - Frontend
- Md Mohsin - Frontend
