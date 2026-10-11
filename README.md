# Qurk Board

## Team Members

1. Valentina Bass
2. Marvin Canastuj
3. Thomas Barney
4. Charles Adam Davis

## Project Description

Qurk Board is a visual organization and planning tool that helps users collect ideas, manage notes, and visualize connections between related information. Users can create, edit, search, pin, move, and connect notes in an interactive workspace.

The application includes user registration, authentication, protected pages, and a profile where users can view their account information and update their username.

## Tech Stack

- Next.js App Router
- React and TypeScript
- Auth.js v5 for authentication
- MongoDB for user and profile data
- Tailwind CSS for styling
- Vercel for deployment

## Getting Started

### Prerequisites

- Node.js
- npm

### Deployment

The application is deployed on Vercel.

**Live Application:** https://qurk-board.vercel.app/


## Authentication and Access

The application uses Auth.js v5. Users can register, sign in, access protected pages, view their profile, and update their username.

TEST LOG IN:
Email: test@app.com
Password: testing123

## Main Features

- User registration and authentication
- Protected Board and Profile pages
- Profile information retrieved from MongoDB
- Username updates persisted to MongoDB
- Interactive note creation, editing, deletion, pinning, searching, and movement
- Connections between notes

## API Notes

- `GET /api/profile`: retrieves the authenticated user's profile.
- `PATCH /api/profile`: validates and updates the authenticated user's username.

The profile API uses the authenticated session and MongoDB to retrieve and update user data.

## Known Issues and Future Improvements

- Add database-backed note and connection operations.

## GitHub Project Board

[Qurk Board Project Board](https://github.com/users/ThomasVanDoof/projects/1)

## Useful Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [Next.js Learn](https://nextjs.org/learn)
- [Next.js Deployment Documentation](https://nextjs.org/docs/app/building-your-application/deploying)
