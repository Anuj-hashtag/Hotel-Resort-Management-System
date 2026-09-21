# Hotel and Resort Management System

A beginner-level frontend project for a Hotel and Resort Management System.

## Project Scope

This version uses only HTML and CSS. It represents the frontend of a system for rooms, guests, reservations, check-in/check-out, billing and administrative management.

The project is based on the submitted synopsis. Backend processing, database storage and real authentication are not included in this frontend version.

## Project Structure

```text
Hotel-Resort-Management-System/
├── index.html
├── about.html
├── services.html
├── gallery.html
├── contact.html
├── login.html
├── booking/
│   ├── rooms.html
│   ├── room-details.html
│   ├── booking.html
│   └── booking-confirmation.html
├── staff/
│   ├── dashboard.html
│   ├── reservations.html
│   ├── rooms.html
│   ├── guests.html
│   └── checkin-checkout.html
├── admin/
│   ├── dashboard.html
│   ├── guests.html
│   ├── billing.html
│   └── reports.html
├── css/
│   ├── style.css
│   ├── rooms.css
│   ├── staff.css
│   └── admin.css
├── team-files/
│   ├── Arush/
│   ├── Anshu/
│   ├── Anuj/
│   └── Arti/
├── .gitignore
└── README.md
```

## Team Work Division

### Arush Dishal

Public website and authentication interface.

Assigned files:

- index.html
- about.html
- services.html
- gallery.html
- contact.html
- login.html
- css/style.css

Arush is responsible for the customer-facing introduction of the project, navigation, public information pages, contact page and the basic login interface.

### Anshu Yadav

Room listing and reservation workflow.

Assigned files:

- booking/rooms.html
- booking/room-details.html
- booking/booking.html
- booking/booking-confirmation.html
- css/rooms.css

Anshu is responsible for displaying room information, room details, facilities, prices and the frontend booking flow.

### Anuj Kumar

Hotel staff operations.

Assigned files:

- staff/dashboard.html
- staff/reservations.html
- staff/rooms.html
- staff/guests.html
- staff/checkin-checkout.html
- css/staff.css

Anuj is responsible for staff-side reservation management, room status, guest records and check-in/check-out information.

### Arti

Administrative management and billing.

Assigned files:

- admin/dashboard.html
- admin/guests.html
- admin/billing.html
- admin/reports.html
- css/admin.css

Arti is responsible for the administration dashboard, guest records, billing information and basic reports.

## Technology

- HTML
- CSS

No JavaScript, framework or database is used in this frontend version.

## Git Workflow

Each team member should commit their own assigned files.

Example:

```bash
git add index.html about.html services.html gallery.html contact.html login.html css/style.css
git commit -m "Add Arush frontend pages"
git push origin main
```

Anshu:

```bash
git add booking/ css/rooms.css
git commit -m "Add room and booking pages"
git push origin main
```

Anuj:

```bash
git add staff/ css/staff.css
git commit -m "Add staff management pages"
git push origin main
```

Arti:

```bash
git add admin/ css/admin.css
git commit -m "Add admin management pages"
git push origin main
```

The commands assume the repository is already created and cloned.
