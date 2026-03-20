# &#x20;Apna Tuition - Connect with Expert Home Tutors

A comprehensive tuition management platform connecting students with qualified home tutors and online teachers across Pakistan.

[!\[Live Demo](https://img.shields.io/badge/demo-live-success)](https://apna-tuition.com)
[!\[TypeScript](https://img.shields.io/badge/TypeScript-79.4%25-blue)](https://www.typescriptlang.org/)
[!\[React](https://img.shields.io/badge/React-18.x-61dafb)](https://reactjs.org/)
[!\[Supabase](https://img.shields.io/badge/Supabase-Backend-green)](https://supabase.io/)

## &#x20;Features

### For Students \& Parents

* &#x20;**Request Tuition** - Submit tuition requirements easily
* &#x20;**Browse Qualified Tutors** - View tutor profiles with qualifications and experience
* &#x20;**Direct Contact** - Connect with tutors via WhatsApp
* &#x20;**Responsive Design** - Works seamlessly on all devices

### For Tutors

* &#x20;**Professional Profiles** - Create detailed tutor profiles
* &#x20;**Browse Opportunities** - Find tuition jobs matching your expertise
* &#x20;**Application Management** - Track tuition applications
* &#x20;**Approval System** - Admin-verified tutor profiles

### For Admins

* &#x20;**Admin Dashboard** - Manage tutors, tuitions, and requests
* &#x20;**Tutor Approval** - Review and approve tutor applications
* &#x20;**Analytics** - Track platform statistics
* &#x20;**Content Management** - Manage blog posts and FAQs

## &#x20;Tech Stack

* **Frontend**: React 18 + TypeScript + Vite
* **Styling**: Tailwind CSS + shadcn/ui
* **Backend**: Supabase (PostgreSQL + Auth + Edge Functions)
* **Routing**: React Router v6
* **Icons**: Lucide React
* **Deployment**: DigitalOcean App Platform

## &#x20;Installation

1. **Clone the repository**

```bash
   git clone https://github.com/ShababAkbar/Tuition-App.git
   cd Tuition-App
   ```

2. **Install dependencies**

```bash
   npm install
   ```

3. **Set up environment variables**

```bash
   cp .env.example .env
   ```

   Add your Supabase credentials:

   ```env
   VITE\_SUPABASE\_URL=your\_supabase\_url
   VITE\_SUPABASE\_ANON\_KEY=your\_supabase\_anon\_key
   ```

4. **Run database migrations**

   * Import migrations from `supabase/migrations/` to your Supabase project
5. **Start development server**

   ```bash
   npm run dev
   ```

6. **Build for production**

   ```bash
   npm run build
   ```

   ## &#x20;Project Structure

   ```
├── public/              # Static assets
├── src/
│   ├── components/      # Reusable React components
│   ├── pages/          # Page components
│   ├── lib/            # Utilities and configurations
│   ├── hooks/          # Custom React hooks
│   └── assets/         # Images and media
├── supabase/
│   ├── functions/      # Edge functions
│   └── migrations/     # Database migrations
└── email-templates/    # Email HTML templates
```

   ## &#x20;Security

* &#x20;Row Level Security (RLS) enabled on all tables
* &#x20;Secure authentication with Supabase Auth
* &#x20;Protected admin routes
* &#x20;Environment variables for sensitive data
* &#x20;Email verification for new users

  ## &#x20;License

  This project is for educational and commercial use.

  ## &#x20;Author

  **Shabab Akbar**

* Email: team.apnatuition@gmail.com
* Phone: +92 319 4394344

  ## &#x20;Contributing

  Contributions, issues, and feature requests are welcome!

  ## &#x20;Show your support

  Give a  if this project helped you!

  \---



  Made  in india

