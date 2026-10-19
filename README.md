# YouTube Homepage Clone

A static, front-end clone of the YouTube homepage built entirely with HTML and CSS. This project was created to practice modern web development layout techniques and responsive design principles.

## 📝 Description

This project replicates the core visual elements of the YouTube desktop interface. It focuses heavily on structuring complex page layouts without the use of external CSS frameworks (like Bootstrap or Tailwind) or JavaScript. It serves as a practical exercise in semantic HTML and intermediate CSS styling.

## 🚀 Features

*   **Fixed Navigation Bar:** A top header containing the logo, search bar, and user profile icons that stays pinned to the top of the screen during scrolling.
*   **Persistent Sidebar:** A left-hand navigation menu featuring icons and links for Home, Explore, Subscriptions, and more.
*   **Responsive Video Grid:** A fluid grid layout displaying video thumbnails, channel avatars, video titles, and statistics that adjust to the screen size.
*   **Custom Styling:** Extensive use of CSS Flexbox and CSS Grid to recreate YouTube's specific spacing and alignment.
*   **Google Fonts Integration:** Utilizes the Roboto font family to match YouTube's typography.

## 🛠️ Technologies Used

*   **HTML5:** Semantic structure for headers, sidebars, buttons, and image containers.
*   **CSS3:** 
    *   Flexbox (for header alignment and internal video card layouts)
    *   CSS Grid (for the main video display area)
    *   Positioning (Fixed and Absolute for tooltips and headers)
    *   Custom SVG icons

## 📁 Project Structure

*   `youtube.html`: The main HTML document containing the page structure.
*   `/styles/`: Directory containing all modular CSS stylesheets (`video.css`, `genera.css`, `header.css`, `sidebar.css`).
*   `/icons/`: Directory containing all SVG icons used in the header and sidebar.
*   `/thumbnails/`: Directory containing placeholder webp images for the video cards.
*   `/channels/`: Directory containing placeholder channel avatar images.

## 💻 How to Run Locally

Since this is a static website, no build tools or servers are required to view it.

1.  Clone this repository to your local machine.
2.  Open the project folder.
3.  Double-click the `youtube.html` file to open it in your default web browser.
4.  *(Optional)* For the best development experience, open the folder in Visual Studio Code and use the "Live Server" extension to view changes in real-time.

## 🔮 Future Improvements

While this clone focuses on the static layout, future iterations could include:
*   Adding media queries to make the sidebar collapsible on mobile devices.
*   Adding JavaScript to make the hamburger menu toggle the sidebar.
*   Implementing interactive hover states for the video thumbnails (e.g., auto-playing a silent GIF).
*   Adding a functional dark mode toggle.
