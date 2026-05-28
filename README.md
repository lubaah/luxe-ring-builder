# Luxe Ring Builder

Luxe Ring Builder is a responsive web application that allows users to design and customize a ring by selecting the metal type, stone option, stone type, ring size, and engraving text. The app includes a live design preview, a saved rings table, and a cart section so users can manage their custom designs in one place.

## Overview

This project was built as a jewelry customization interface for creating a personalized ring design experience. The layout is designed with a luxury-style theme and includes a large hero section, a product card, a dynamic preview panel, and organized tables for saved and cart items.

## Features

- Custom ring builder form.
- Live design preview that updates based on user selections.
- Different preview images for different metal types.
- Save ring designs to the database.
- Display saved rings in a table.
- Add ring designs to a cart.
- Remove items from the cart.
- Responsive layout for desktop and mobile screens.
- Elegant jewelry-inspired UI design.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Node.js
- Express.js
- SQLite

## Project Structure

```bash
project-folder/
├── images/
│   ├── hero.png
│   ├── ring.png
│   ├── preview-yellow.png
│   ├── preview-white.png
│   ├── preview-rose.png
│   └── preview-silver.png
├── css/
│   └── style.css
├── js/
│   └── script.js
├── index.html
├── app.js
├── package.json
└── README.md
```

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
```

### 2. Open the project folder
```bash
cd YOUR-REPO-NAME
```

### 3. Install dependencies
If your project uses Node.js, install the packages with:
```bash
npm install
```

### 4. Run the app
Start the server with:
```bash
node app.js
```

If your project uses a start script in `package.json`, you can also use:
```bash
npm start
```

### 5. Open in browser
Visit:
```bash
http://localhost:3000
```

## How to Use

1. Choose a metal type.
2. Select whether the ring should have a stone.
3. Choose the stone type.
4. Enter the ring size.
5. Add engraving text if needed.
6. View the live preview.
7. Save the ring or add it to the cart.

## Preview Images

The preview image changes based on the selected metal type. The hero image remains fixed and is separate from the ring preview area.

## Future Improvements

- Allow users to choose more ring shapes.
- Add more stone and metal options.
- Store cart items in the database instead of localStorage.
- Add user login and wishlist saving.
- Improve preview image variations for more realistic customization.

## Notes

- Make sure all image file names match the names used in the code.
- The `hero.png` image is used only in the top banner and does not change dynamically.
- Preview images are loaded from the `images` folder.

## License

This project is created for educational and demonstration purposes.
