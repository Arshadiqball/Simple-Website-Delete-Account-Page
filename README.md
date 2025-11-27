# Account Deletion Request Page

This project is a simple, responsive HTML page that allows users to submit an **account deletion request**.  
It uses **Bootstrap 5** for styling and layout, and displays a **success modal** when the user clicks the “Delete Account” button.

> Note: This is a front-end–only implementation. You still need to connect the form to a back-end endpoint to actually process deletion requests.

---

## Features

- Centered, card-style layout with a max width of **600px**, suitable for embedding or standalone use.
- Custom-styled **“Delete Account”** button using Bootstrap’s `.btn-primary`.
- User input fields:
  - Name
  - Email
  - Phone Number
  - Message (reason / additional details)
- Bootstrap **modal** that shows a confirmation message:  
  _“Successfully Deleted the account!”_
- Mobile-friendly layout using Bootstrap’s grid system.

---

## Tech Stack

- **HTML5**
- **CSS3** (inline and `<style>` block)
- **Bootstrap 5.3.8** (via CDN)
- **JavaScript** (Bootstrap bundle via CDN for modal behaviour)

No build tools or frameworks are required.

---

## File Structure (single file)

All code is contained in a single HTML file:

- Layout wrapper using `<table>` for a fixed-width “card” (600px wide).
- Top banner image:
  ```html
  <img src="new_logo.png" ... />
