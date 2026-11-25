# Kargar Admin Panel

The web admin panel for **Kargar**, a service-finder app that connects people in Afghanistan with local workers such as electricians, carpenters, painters and drivers. Admins use it to verify new workers before they appear in the public app.

## Features

- **Dashboard** with counts of pending, approved, flagged and rejected workers
- **Review queue**: open a worker's profile, work details and Tazkira (ID) photos, then approve, flag or reject
- **Filters and search** across all registrations
- **Photo lightbox** for checking ID documents
- **Secure sign-in** with Supabase Auth; every admin page is behind a protected route

## Tech stack

| Area | Tools |
|---|---|
| UI | React, React Router, CSS Modules |
| Build | Vite |
| Backend | Supabase (Postgres, Auth, Storage) |
| Hosting | Vercel |

## Run locally

```bash
npm install
cp .env.example .env   # add your Supabase URL and anon key
npm run dev
```

Create an admin user in the Supabase dashboard (Authentication → Users), then sign in.

Related: the Kargar mobile app is built with React Native and Expo.

---

Built by **Abdul Rahman Rahimi**, Software Developer & Geospatial Analyst, [Rahimi Tech Solution](https://github.com/AbdulRahmanRahimi).
