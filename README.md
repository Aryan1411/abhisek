# Dr. Abhisek — Portfolio Website

## Overview
This repository contains a fast, single-page portfolio website for Dr. Abhisek, a General Physician and MD in Medicine. It highlights clinical services, experience, testimonials, and provides simple booking and contact options, optimized for fast load and good accessibility.

Key features:
- One-page responsive layout with light/dark theme toggle
- Clear sections: About, Services, Experience, FAQs, Testimonials, Contact
- Appointment request form that opens a prefilled email (no backend needed)
- Telemedicine and WhatsApp quick-contact links
- SEO and social meta tags, plus JSON-LD schema for Physician
- Print-friendly profile/info sheet generation
- No external dependencies for fast loading (< 15s on typical connections)

## Setup
No build steps required.

- Clone or download this repository.
- Files included:
  - index.html (self-contained with inline CSS/JS)
  - README.md (this file, including license)
- Open index.html in any modern browser.

Optional deployment:
- GitHub Pages: push to a public repo and enable Pages.
- Netlify/Vercel: drag-and-drop the folder or point to the repo.

## Usage
- Update placeholder details (address, phone, email, residency names) in index.html to match real information.
- Appointment form: users fill in their details; clicking “Request Appointment” opens their email client with a pre-composed message to appointments@abhisekmed.com. You can change the target email by editing the mailto link in the script.
- Theme toggle: remembers the user’s preference across visits.
- Print/download: “Download Profile (PDF)” and “Print Info Sheet” use the browser’s print dialog; users can save to PDF.

Accessibility and performance tips:
- Keep images small or SVG-based to maintain fast load.
- Verify sufficient color contrast after customizing brand colors.
- Use descriptive link text and button labels when updating content.

## License (MIT)
Copyright (c) 2025 Dr. Abhisek

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.