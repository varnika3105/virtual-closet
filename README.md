# Virtual Closet – AI-Powered Outfit Management System

The Virtual Closet is a full-stack web application that allows users to digitize their wardrobe, upload clothing images, organize outfits, and receive AI-based outfit recommendations. The project focuses on real-world features such as authentication, file uploads, cloud storage, database modeling, and optional machine learning integration.

---

## Features

### Wardrobe Management
- Upload clothing images  
- Automatic color and category detection (AI optional)  
- Manual tagging (season, style, type, color)  
- Filter and view wardrobe items

### AI Outfit Generator
- Outfit recommendations based on:  
  - Weather  
  - Occasion  
  - Color matching  
  - User preferences  

### Outfit Planner
- Add outfits to a calendar  
- Weekly and monthly planning views  
- Save and reuse past outfits  

### User Authentication
- JWT-based login and signup  
- Secure password handling  
- Personalized wardrobes

---

## Tech Stack

### Frontend
- React.js  
- Tailwind CSS or Bootstrap  
- React Router  
- Context API or Redux

### Backend
- Node.js  
- Express.js  
- MongoDB with Mongoose  
- Cloudinary (image upload and storage)

### AI and Utilities
- Basic color palette extraction  
- Optional clothing classification model  
- External Weather API

### Deployment
- Frontend: Vercel or Netlify  
- Backend: Render, Railway, or Vercel  
- Database: MongoDB Atlas

---

## Project Goals
- Build a functional full-stack application  
- Implement image upload and cloud-based storage  
- Practice database design and authentication  
- Integrate AI for tagging and recommendations  
- Collaborate efficiently using Git and GitHub

---

## Planned Folder Structure

```
virtual-closet/
 ├── client/
 │    └── src/
 │         ├── components/
 │         ├── pages/
 │         ├── context/
 │         ├── utils/
 │         └── assets/
 ├── server/
 │    ├── controllers/
 │    ├── models/
 │    ├── routes/
 │    ├── middleware/
 │    └── utils/
 └── README.md
```

---

## Team Members

| Name | Role | Responsibilities |
|------|------|------------------|
| Member 1 | Frontend Lead | UI, React components, routing |
| Member 2 | Backend Lead | API, authentication, DB models |
| Member 3 | AI / Integration Lead | Image tagging, recommendation logic |

(Add GitHub profile links once the repo is created.)

---

## Roadmap (Day-wise Plan)

### Day 1 – Setup
- Finalize requirements  
- Create GitHub repository  
- Add README  
- Plan folder structure  
- Assign roles  
- Initialize React and Node.js projects

### Day 2–3
- Build authentication system  
- Create database models

### Day 4–6
- Implement wardrobe CRUD  
- Configure image upload and Cloudinary

### Day 7–8
- Outfit planner  
- AI recommendation logic

### Day 9
- UI polish  
- Testing  
- Deployment

---

## License
MIT License
