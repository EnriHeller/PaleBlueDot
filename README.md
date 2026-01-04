# Pale Blue Dot - Astronomy Website

Pale Blue Dot is a website dedicated to astronomy and space exploration, inspired by Carl Sagan's famous "Pale Blue Dot" photograph taken by Voyager 1. The site features episodes, guest speakers, topics, and information about our place in the universe.

## Features

- **Episodes**: Browse and listen to astronomy-related episodes.
- **Guests**: Profiles of guest speakers and experts.
- **Topics**: Explore various astronomical themes.
- **About Us**: Information about the project and team.
- **Responsive Design**: Optimized for desktop and mobile.

## Repository Structure

- **`index.html`**: Main page.
- **`images/`**: Image assets.
  - `invitados/`: Guest images.
  - `navbar/`: Navigation icons.
  - `otras/`: Miscellaneous images.
  - `temas/`: Theme-related images.
- **`styles/`**: CSS and SCSS files.
  - `style.css`: Compiled CSS.
  - `style.scss`: Main SCSS file.
  - `sass/`: Partial SCSS files.
    - `_episodios.scss`: Episodes styling.
    - `_footer.scss`: Footer.
    - `_header.scss`: Header.
    - `_invitados.scss`: Guests.
    - `_main.scss`: Main content.
    - `_mixins.scss`: SCSS mixins.
    - `_nosotros.scss`: About us.
    - `_presentacion.scss`: Presentation.
    - `_topicos.scss`: Topics.
    - `_variables.scss`: Variables.

## Prerequisites

- A modern web browser.

## Installation and Execution

1. Clone the repository:
   ```bash
   git clone https://github.com/EnriHeller/PaleBlueDot.git
   cd PaleBlueDot
   ```

2. Open `index.html` in a web browser:
   ```bash
   open index.html
   # Or double-click the file
   ```

3. For development, use a local server:
   ```bash
   python -m http.server 8000
   # Open http://localhost:8000
   ```

## Technologies Used

- **HTML5**: Structure.
- **CSS3/SCSS**: Styling and responsive design.

## Author

- **Enrique Heller** - [EnriHeller](https://github.com/EnriHeller)

## License

This repository is for educational purposes. Use and modify freely, but cite the source.

## Contributing

Suggestions and improvements are welcome via issues or pull requests.