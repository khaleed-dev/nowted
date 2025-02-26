# Note taking app (Nowted)

## Core Features:

    - User authentication (register/login)
    - CRUD operations for notes
    - File uploads for note attachments
    - Basic realtime updates (online status)
    - Database relationships (users ↔ notes)

**Design from [Figma](https://www.figma.com/design/HU6G1MiZhnsPK4d8pc7FCS/Nowted-%E2%80%93%C2%A0A-Note-taking-App-(Community)?node-id=0-1&p=f&t=KjVQrn03GKKxjjiK-0)**

## Tech stack #1 (VanillaJS):
    Frontend: Vanilla JS + Pico.css (minimal CSS framework)
    Backend: Node.js + Express
    Database: SQLite (file-based, no server needed)
    Auth: Session cookies
    File Storage: Local filesystem

**Key Learnings:**
- Manual DOM manipulation

- REST API concepts

- Form handling/file uploads

- Session-based auth

- SQL database operations

---

## Tech stack #2 (React):
    Frontend: React + React Router
    Styling: Tailwind CSS (easy utility-first)
    Backend: Same Express API
    State Management: Context API

**Key Learnings:**
- Component architecture

- React state management

- Client-side routing

- API integration patterns

- Context API for auth

---

## Tech stack #3 (NextJS):

    Framework: Next.js 15 (App Router)
    Database: PostgreSQL + Prisma
    Auth: NextAuth.js
    Realtime: Supabase
    Storage: Supabase Storage

**Key Learnings:**
- App Router architecture

- Server Actions

- ORM usage

- Third-party service integration

- Edge runtime considerations

- Authentication patterns
---