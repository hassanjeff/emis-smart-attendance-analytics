# EMIS Smart Attendance Analytics

A centralized online attendance monitoring system for the School Education
Department, Gilgit-Baltistan — replacing a manual, Excel-merge workflow with
a single web-based dashboard.

🔗 **Live site:** https://emis-smart-attendance-analytics.vercel.app/

## Overview

Built for the EMIS Section, Directorate of Education, Gilgit-Baltistan, this
system gives district and provincial staff a single place to upload, view,
and analyze school attendance data across all 10 districts of GB (Gilgit,
Ghanche, Skardu, Shigar, Kharmang, Hunza, Nagar, Ghizer, Diamer, Astore).

## Features

- 🔐 **Authentication** — secure login with password reset flow
- 👥 **Role-based access** — superadmins see all districts and manage users;
  district admins see only their own district's data
- 📊 **Analytics dashboard** — office- and institution-level drill-downs,
  with data-quality warnings for suspicious attendance numbers
- 📁 **Excel & CSV upload** — district staff upload attendance sheets
  directly, no manual merging
- 🛠️ **Admin panel** — superadmins manage user accounts and roles
- 📱 **Mobile-responsive** — usable on phones and tablets in the field

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript (vanilla)
- **Backend:** [Supabase](https://supabase.com/) (Postgres, Auth, Edge Functions)
- **Hosting:** [Vercel](https://vercel.com/)

## Project Status

Actively developed. Core login, role-based access, and admin/user management
are live. Ongoing work includes deeper historical reporting and automated
analytics.

## Author

Built and maintained by [Muhammad Hassan](https://github.com/hassanjeff),
IT & Data Analyst, EMIS Section, Directorate of Education, Gilgit-Baltistan.
