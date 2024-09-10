# Available CDN lists:
 - ## [Instagram Embed Script ⏬](#instagram-embed-script)
 - ## [Auto-Scroll Page ⏬](#auto-scroll-page)

---

# Auto-Scroll Page

A Script file to implement smooth so-slow auto-scrolling on your webpage only when the user starts scrolling down and stops instantly when page is scrolled a little up. The script dynamically scrolls the page at a customizable speed and adjusts based on user interaction.

## Usage

1. **Include the Script**

   Add the following `<script>` tag to your HTML file to include the script:

   ```html
   <script src="https://cdn.jsdelivr.net/gh/quadqode/cdn@main/auto-scroll.js"></script>
   ```

2. **Define Custom Scroll Speed**
   You can define custom attributes in any HTML tag to control scroll speed. It sets the scroll speed to a ratio of the viewport height per frame.\
   12<=`scrollSpeedPercent`<∞ & by default value is 12.

    Example:

    ```html
    <script scrollSpeedPercent=40 src="https://cdn.jsdelivr.net/gh/quadqode/cdn@main/auto-scroll.js"></script>
    ```

---
# Instagram Embed Script


This repository provides a JavaScript file to embed Instagram posts with customizable styles. You can include this script in your project to dynamically load and style Instagram embeds.

## Usage

1. **Include the Script**

   Add the following `<script>` tag to your HTML file to include the script:

   ```html
   <script src="https://cdn.jsdelivr.net/gh/quadqode/cdn@main/embed-insta.js"></script>

2. **Define Custom Attributes**

    You can define custom attributes in any HTML tag to customize the Instagram embed. The script will look for these attributes and apply the corresponding styles.
    
    Example :
    ```html
    <script username="dharambirharyana" border-width="2px" border-radius="15px" border-color="#ff0000" src="https://cdn.jsdelivr.net/gh/quadqode/embed@main/embed-insta.js"></script>

You can define these custom attributes anywhere on the page, for example: `<div>`, `<meta>`, or any other tag.
