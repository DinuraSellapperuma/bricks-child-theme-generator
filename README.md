# Bricks Child Theme Generator

A **one-page** generator to quickly create a WordPress child theme for [Bricks Builder](https://bricksbuilder.io).  

**Live Demo:** [Bricks Child Theme Generator](https://bricks.dixy.page)

## Features

- **Automatic Theme Files**: Generates the necessary `style.css`, `functions.php`, and custom elements code.
- **Screenshot Upload**: Allows you to upload a PNG/JPG image to include as the theme screenshot.
- **Zip Download**: Instantly zip up your new child theme into a file ready for installation.

## How to Use

1. **Visit** the live demo at [https://bricks.dixy.page](https://bricks.dixy.page).  
2. Fill out all required fields:
   - **Theme Name**
   - **Version**
   - **Author**
   - **Author URI**
   - **Description**
   - **Folder Name**
   - And **upload** a theme screenshot (max size: **1 MB**, PNG or JPG).
3. Click **"Generate Theme 🚀"** to download your newly created ZIP.
4. **Install** the ZIP in WordPress as a new theme (upload it under `Appearance > Themes > Add New`).
5. **Activate** and enjoy your new child theme!

## Screenshot Requirements

- **File Size**: 1 MB or less.
- **Formats**: PNG or JPG.
- **Recommended Dimensions**: 1200×900 (or a similar aspect ratio).

## Local Development & Contribution

1. **Clone** this repository:
   ```bash
   git clone https://github.com/your-username/bricks-child-theme-generator.git

## Notes

- The generated child theme automatically references the `bricks` parent theme (`Template: bricks` in `style.css`).
- The included code in `functions.php` takes care of:
  - Enqueuing child theme CSS.
  - Registering a custom element, `title.php`, for Bricks Builder.
  - Deleting certain WordPress default files (like `license.txt` or `readme.html`) — remove or comment out if not desired.
  - Note: I have added code to delete these unnecessary files for WordPress security purposes. Deleting certain default WordPress files—like license.txt,       
    readme.html, wp-config-sample.php, and xmlrpc.php—for security purposes. Feel free to remove or comment out this feature if you don’t want to delete these 
    files.

## License

This project is open source under the [MIT License](LICENSE), but please note that Bricks Builder and WordPress are proprietary and/or GPL-licensed respectively. You must abide by their licenses when using them.

---

**Happy building!**
