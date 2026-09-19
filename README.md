# Ad-Free Iframe Player

> A lightweight web application that takes standard iframe media snippets and renders them in a clean, ad-free environment for uninterrupted viewing.

## Overview

Many embedded video players and live streams (especially sports and PPV events) come heavily bloated with pop-ups, overlays, and intrusive ads. This project provides a sanitized, distraction-free viewing container. By pasting an external iframe snippet into the site, the application strips away the surrounding web clutter and provides a seamless, responsive player focused entirely on the core media.

## Key Features

* **Ad-Free Rendering:** Isolates the video feed from external pop-ups and page-level advertisements.
* **Universal Iframe Support:** Accepts and processes standard HTML `<iframe>` embed codes from various streaming sources.
* **Responsive UI:** Scales automatically to fit desktop, tablet, and mobile screens without breaking the aspect ratio.
* **Dark Mode Default:** Designed with a theater-style dark UI to reduce eye strain and focus attention on the stream.
* **Secure Execution:** Sandboxes the iframe content to prevent malicious scripts from interacting with the parent page.

## Tech Stack

| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **Frontend** | HTML5, CSS3, JavaScript (Vanilla or React/Vue) | Handles user input and responsive player UI |
| **Styling** | Tailwind CSS / Bootstrap | Ensures a clean, modern aesthetic |
| **Deployment** | Vercel / Netlify / GitHub Pages | Hosts the static site globally |

## How It Works

1. The user pastes an `<iframe>` embed code into the input field.
2. The application sanitizes the input, ensuring only the necessary source (`src`) and media attributes are preserved.
3. The cleaned iframe is rendered dynamically on the page within a controlled container, bypassing the ad-heavy host websites.

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ad-free-iframe-player.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ad-free-iframe-player
   ```

3. Open `index.html` in your browser or run your local development server if using a framework.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/ad-free-iframe-player/issues).

## License

This project is licensed under the MIT License - see the LICENSE file for details.
