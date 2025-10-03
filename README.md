**Purpose of This Project**:
The goal is to create a simple, responsive blog website layout that can be viewed on desktop, tablet, or mobile. It includes:
Navigation Bar
A set of blog post cards
A footer with social links
This type of layout is often used for:
Personal blogs
News or article websites
Portfolio blog sections
Mockups for learning Bootstrap
**✅ Navbar (Top Menu)**
<nav class="navbar ...">
Fixed to the top of the page (fixed-top)
Contains links like Home, Posts, About, and Contact
Collapes into a hamburger menu on small screens (responsive)
**✅ Main Content – Blog Cards**:
<div class="container my-5">
  <div class="row g-4">
    <div class="col-md-6 col-lg-4">
      <div class="card">
Uses Bootstrap Grid to make a 3-column layout on large screens and 2-column on medium screens
**Each card includes:**
A placeholder image
A blog post title
A short description
**✅ Footer (Bottom Section)**:
<footer class="py-4 text-center">
Shows social media links (Facebook, Twitter, etc.)
Displays copyright
Styled with a light background
**✅ Styling**
You’re using:
Bootstrap CSS for layout, spacing, buttons, and cards
A small amount of custom CSS (inside <style> tag):
body {
  padding-top: 56px;
}
footer {
  background-color: #f8f9fa;
}
This prevents the navbar from overlapping content, and gives the footer a light background.
A "Read More" button
➡️ These could be linked to full blog pages in a real project.
