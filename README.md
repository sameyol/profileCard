🌟 Profile App — React + Tailwind CSS + React Router

A fully accessible, responsive, and semantic multi-page React application built using modern frontend patterns.
This project includes a Profile Card, a Contact Us page with form validation, and an About Me page for reflection. All designed with great UX/UI and test-ready data-testid attributes.

✨ Features

✅ Profile Card — displays user info, bio, hobbies, dislikes, social links, and a live timestamp
✅ Contact Us Page — includes accessible form validation with success and error states
✅ About Me Page — semantically structured reflection sections
✅ Accessible by Design — semantic HTML, keyboard navigation, ARIA labels
✅ Responsive Layout — mobile-first with Tailwind Flex/Grid
✅ Dynamic Routing — powered by React Router’s <NavLink>
✅ Clean UI/UX — simple, modern, and easy to navigate
✅ Automated Test Support — every interactive or visible element has a data-testid

🧩 Pages Overview
🏠 Profile Card Page (/)

Displays user avatar, name, bio, current time, social links, hobbies, and dislikes

Live time updates every second

Semantic structure with <article>, <figure>, <section>, etc.

📩 Contact Us Page (/contact)

Form fields with validation:

Full name (test-contact-name)

Email (test-contact-email)

Subject (test-contact-subject)

Message (test-contact-message)

Validation messages (e.g. test-contact-error-email)

Displays a success message on valid submission (test-contact-success)

All inputs are labeled, ARIA-linked, and keyboard accessible

🧘 About Me Page (/about)

Structured into reflective sections:

Bio (test-about-bio)

Goals (test-about-goals)

Low confidence areas (test-about-confidence)

Note to future self (test-about-future-note)

Extra thoughts (test-about-extra)

Fully semantic using <main> and <section>

🎨 UI & Accessibility

Built with mobile-first Tailwind responsive utilities

Keyboard navigable — tab-friendly forms and links

Semantic HTML elements (<main>, <header>, <section>, <figure>, <nav>)

Color contrast and spacing ensure readability

Works smoothly on mobile, tablet, and desktop
