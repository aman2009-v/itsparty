# ANTRAAL MUN Website - Setup Guide

## Assets to Add

Place the following files in the `assets` folder:

1. **logo.png** - Official ANTRAAL MUN logo
2. **banner.png** - Hero section background/banner image  
3. **upi-qr.png** - UPI payment QR code for registration

## Core Team Images

Add team member photos to `assets/team/`:

- **yashveer.jpg** - Secretary General (Yashveer)
- **member1.jpg**, **member2.jpg**, **member3.jpg** - The three team members below Yashveer

Update the Core Team page (`core-team.html`) with:
- Correct names and designations
- Instagram handles in the `data-insta` attribute of each flip card

## Form Submission (Optional Upgrade)

The registration form currently uses `mailto:` - it opens the user's email client with the form data. For a better experience:

1. Sign up at [Formspree.io](https://formspree.io) (free)
2. Create a new form and add `yadavamanjeet317@gmail.com` as the recipient
3. Copy your form ID from the form endpoint (e.g., `https://formspree.io/f/xyz123`)
4. In `registration.html`, replace the form's JavaScript to use Formspree instead of mailto

## Social Media Links

Update the footer links in all HTML files:
- Replace `#` in the Instagram and LinkedIn links with your actual profile URLs

## Running the Website

Open `index.html` in a web browser. No server required - it's a static site.
