# Moya Auto Sales

Professional used car dealership website for Moya Auto Sales in Coachella, California.

## Stack

- Next.js 15 App Router
- React 19
- Tailwind CSS 4
- Supabase Auth, Database, and Storage
- Responsive public website and secure admin dashboard

## Setup

1. Create a Supabase project.
2. Run `supabase/schema.sql` in the Supabase SQL editor.
3. Create an owner user in Supabase Auth.
4. Copy `.env.example` to `.env.local` and fill in:
   - `NEXT_PUBLIC_SUPABASE_URL`
   - `NEXT_PUBLIC_SUPABASE_ANON_KEY`
   - `SUPABASE_SERVICE_ROLE_KEY`
   - `NEXT_PUBLIC_SITE_URL`
5. Install dependencies and run the app:

```bash
npm install
npm run dev
```

## Admin

Visit `/admin/login` and sign in with the Supabase Auth owner account.

The dashboard supports:

- Add vehicle
- Edit vehicle
- Delete vehicle
- Upload multiple actual inventory images
- Mark sold
- Hide from public site
- Feature on homepage
- View financing and contact leads
