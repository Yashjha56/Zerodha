# Zerodha Clone - Web Interface

This is a simple HTML/CSS-based project inspired by the Zerodha platform. The layout features a navigation bar, a banner image, and a call-to-action section, designed to simulate the user interface of an online investment platform.

## Features
- **Header Navigation**: A flexible navigation bar with clickable links for 'Sign up', 'About Us', 'Product', 'Pricing', and 'Support'.
- **Main Banner**: A central image and informative text to attract users to the platform.
- **Call-to-Action**: A prominent button encouraging users to sign up for the platform.
- **Responsive Design**: Basic CSS styling is used to ensure the layout is visually appealing.

## Code Breakdown

### 1. Header Section
The header contains a logo and navigation links. The logo is placed on the left and the links (`Sign up`, `About Us`, `Product`, `Pricing`, `Support`) are arranged on the right side using flexbox.

```html
<div style="display: flex; justify-content: space-between; margin-left: 100px; padding-right: 100px; box-shadow: 2px 1px 2px #eee;">
    <img src="https://zerodha.com/static/images/logo.svg" width="150" height="20px" style="padding-top: 20px"/>
    <div style="display: flex;">
        <div style="padding: 20px;color: #666; cursor: pointer;">Sign up</div>
        <div style="padding: 20px;color: #666; cursor: pointer;">About us</div>
        <div style="padding: 20px;color: #666; cursor: pointer;">Product</div>
        <div style="padding: 20px;color: #666; cursor: pointer;">Pricing</div>
        <div style="padding: 20px;color: #666; cursor: pointer;">Support</div>
    </div>
</div>
