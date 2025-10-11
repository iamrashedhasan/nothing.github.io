# Nothing to See Here

A minimalist, animated "404-like" webpage built with HTML and CSS, featuring a typing animation with a glowing gradient text effect. The page uses the Space Mono font and is fully responsive for various screen sizes.

## Features

- **Typing Animation**: Simulates a typing effect for the message "Sorry, nothing is here!" with a blinking cursor.
- **Gradient Text Effect**: Applies a smooth gradient transition to the text using CSS background clipping.
- **Responsive Design**: Adapts to different screen sizes (mobile, tablet, desktop) using media queries and `clamp` for fluid typography.
- **Custom Styling**: Uses CSS custom properties (variables) for easy theme adjustments.
- **Google Fonts**: Integrates the Space Mono font for a modern, monospaced aesthetic.

## Demo

You can view the live demo by opening `index.html` in a web browser or hosting it on a static server.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/nothing-to-see-here.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd nothing-to-see-here
   ```

3. **Open the Page**:
   Open `index.html` in a web browser directly, or use a local server (e.g., with VS Code's Live Server extension or a simple HTTP server).

## Usage

- The page is self-contained in `index.html` and requires no additional dependencies beyond an internet connection to load the Google Fonts stylesheet.
- Customize the colors by modifying the CSS custom properties in the `:root` selector (e.g., `--bg-color`, `--gradient-color-1`, `--gradient-color-2`, `--cursor-color`).
- Adjust the message by editing the `<h1 class="message">` content in `index.html`.

## File Structure

```
nothing-to-see-here/
│
├── index.html       # Main HTML file with styles and content
└── README.md        # Project documentation
```

## Technologies Used

- **HTML5**: For structure.
- **CSS3**: For styling, animations, and responsive design.
- **Google Fonts**: For the Space Mono font.

## Customization

To modify the animation or styling:
- **Typing Speed**: Adjust the `animation` duration in the `.message` class (e.g., `typing 3.5s`).
- **Gradient Colors**: Update `--gradient-color-1` and `--gradient-color-2` in the `:root` selector.
- **Font Size**: Modify the `font-size` in the `.message` class or media queries for different screen sizes.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Google Fonts](https://fonts.google.com/) for the Space Mono font.
- Inspired by minimalist and animated 404 page designs.
