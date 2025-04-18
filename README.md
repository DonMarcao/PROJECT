# SPFC Fan Page

**View the live site:** [https://donmarcao.github.io/PROJECT/index.html](https://donmarcao.github.io/PROJECT/index.html)

## Project Description

The SPFC Fan Page is a dedicated website for fans of São Paulo Futebol Clube (SPFC). It serves as a central hub for all things related to the club, providing users with up-to-date information, historical insights, media content, and a platform to connect with fellow supporters.

## UX (User Experience)

This section details the user-centric approach taken during the planning and design phase, following the principles of UX design.

### Project Goals
*   To create a visually engaging and informative online resource for SPFC fans.
*   To consolidate key information like news, history, fixtures, and results in one accessible location.
*   To build a responsive website that provides a seamless experience across desktop, tablet, and mobile devices.
*   To foster a sense of community among SPFC supporters.
*   To serve as a portfolio project demonstrating proficiency in HTML5 and CSS3.

### Target Audience
*   **New Fans:** Individuals recently interested in SPFC seeking foundational knowledge about the club's history, players, and current status.
*   **Casual Supporters:** Fans who follow the team but may not check for updates daily, looking for quick access to results, upcoming matches, and major news.
*   **Dedicated Fans:** Long-time supporters seeking the latest updates, deeper historical dives, media content, and connection with the club's identity.

### User Goals / User Stories
*   As a **new fan**, I want to easily find and read about the club's history so that I can understand its legacy and significance.
*   As a **casual supporter**, I want to quickly check the results of the last match and see when the next game is scheduled.
*   As a **dedicated fan**, I want access to the latest club news to stay informed about transfers, injuries, and team updates.
*   As **any fan**, I want to view photos and videos of memorable moments or highlights.
*   As **any user**, I want the website to load quickly and display correctly on my mobile phone while commuting.
*   As **any user**, I want to easily find links to the club's official social media pages.
*   As a **potential contributor/contact**, I want to find contact information easily.

### Strategy & Scope
*   **Strategy:** The website aims to be a comprehensive, reliable, and engaging fan portal for São Paulo Futebol Clube, enhancing the connection between the club and its supporters.
*   **Scope:** The site includes the following core features: Homepage (`index.html`), History (`history.html`), News (`news.html`), Media (`media.html`), and Contact (`contact.html`). Key functionalities include displaying news updates, historical information, an image/video gallery, fixture/result tables, contact methods, and social media links.

### Structure
*   A clear, multi-page structure was chosen, with each core topic (History, News, Media, Contact) given its own dedicated page accessible via a consistent top navigation menu present on all pages.
*   The homepage serves as a dashboard, providing immediate access to welcome information, upcoming fixtures, and recent results.
*   A standard footer containing social media links and copyright information is present on all pages for consistency and easy access.
*   The information hierarchy prioritizes easy scanning, with clear headings and distinct content sections.

### Skeleton
*   Wireframes were developed early in the process to map out the content placement and responsive behavior for mobile, tablet, and desktop screen sizes for all pages. This planning phase helped define the layout before coding began. See the [Wireframes](#wireframes) section for visual representations.

### Surface
*   **Color Scheme:** The design prominently features the official SPFC colors (Red, White, Black) applied through background gradients, text shadows, and animations to create a strong visual identity and immediate brand recognition. Grey tones are used for balance and text backgrounds where needed.
*   **Typography:** A clean, sans-serif font (Arial, fallback to generic sans-serif) is used for body text to ensure high readability across various screen sizes and resolutions. Headings are larger and bolded to create clear visual hierarchy.
*   **Imagery:** The homepage utilizes a dynamic, animated background featuring significant club-related images (stadium, celebrations) to create an immersive and engaging initial impression. Navigation links (on larger screens) incorporate related imagery to provide visual context. Other pages utilize relevant images within their content sections.
*   **Animations:** Subtle CSS animations are implemented on the site title (color cycling), hero background (fade transition), and footer (slide-in effect) to add visual interest and modernity without hindering usability or performance.

## Wireframes

Wireframes were created to plan the layout and ensure a responsive structure across devices.

### Homepage (`index.html`)
![Homepage Wireframes for Mobile, Tablet, and Desktop](assets/wireframes/homepage-wireframes.png)

* The page follow a vertically structure. (HOME, NAV LINKS, MAIN CONTENT and FOOTER).

### History Page (`history.html`)
### News Page (`news.html`)
### Media Page (`media.html`)
### Contact Page (`contact.html`)
* All pages follow basic structure of the main frames on index page. (HOME, NAV LINKS, MAIN CONTENT and FOOTER (vertically aligned)).

## Features

*   **News Section:** Provides the latest news and updates regarding the club.
*   **History Section:** Presents a detailed history of the club, including key moments and achievements.
*   **Media Gallery:** Showcases images and videos related to the club.
*   **Upcoming Matches & Results:** Displays upcoming match schedules and past results.
*   **Contact Section:** Allows users to contact the site administrators.
*   **Social Media Integration:** Links to the club's official social media channels in the footer.
*   **Responsive Layout:** Ensures optimal viewing on desktops, tablets, and mobile devices using CSS media queries and flexible layouts.
*   **Animated Elements:** Adds visual interest with CSS animations for the site title, hero section background images, and footer appearance.

## Technologies Used

*   **Core:** HTML5, CSS3
*   **Icons:** Font Awesome (via CDN) - Used for social media icons in the footer.
*   **Version Control:** Git, GitHub
*   **Development Tools:** VS Code, Browser Developer Tools (Opera GX)
*   **Deployment:** GitHub Pages

## Testing

The website underwent manual testing across different browsers and screen sizes to ensure functionality and visual consistency.

### Process
*   **Manual Testing:** Each page was navigated, links were clicked, content was reviewed for accuracy and display. Forms were checked for basic structure.
*   **Developer Tools:** Chrome and Firefox developer tools were used extensively to simulate various devices (iPhone, iPad, Android models, standard laptop/desktop dimensions) and test responsiveness. Layout shifts and element rendering were observed.
*   **Validation:** W3C HTML Validator and W3C CSS (Jigsaw) Validator were used to check for major syntax errors in the code.

### Browser Compatibility
*   The site was tested and confirmed to render correctly on the following browsers:
    *   Google Chrome (Latest Version)
    *   Opera GX (Latest Version)
    *   Microsoft Edge (Latest Version)
    

### Responsiveness
*   Layout adjustments were verified across common breakpoints:
    *   **Mobile (Under 768px):** Content stacks vertically, navigation collapses to a hamburger menu, images resize appropriately, tables stack or become scrollable.
    *   **Tablet (768px - 991px):** Two-column layouts may appear, navigation typically becomes horizontal, images and text adapt to medium width. Fixture tables arranged side-by-side.
    *   **Desktop (992px+):** Full multi-column layouts utilized, horizontal navigation fully visible with images, content uses available width effectively. Fixture tables side-by-side.

### User Story Validation
*   **"As a new fan, I want to easily find the club's history..."**: Successfully validated by clicking the 'HISTORY' link in the navigation and confirming the relevant historical content is displayed on the `history.html` page.
*   **"As a returning fan, I want to quickly see upcoming fixtures..."**: Successfully validated by observing the 'FIXTURES & RESULTS' section on the homepage (`index.html`), confirming tables for upcoming and past matches are present and legible.
*   **"As a dedicated fan, I want access to the latest club news..."**: Successfully validated by clicking the 'NEWS' link and verifying the display of news items on `news.html`.
*   **"As any fan, I want to view photos and videos..."**: Successfully validated by navigating to the 'MEDIA' page (`media.html`) and confirming the presence of a gallery or embedded media.
*   **"As any user, I want the website to load quickly and display correctly on my mobile..."**: Successfully validated by testing on simulated mobile devices in browser dev tools, observing acceptable load times (for a static site) and correct layout rendering.
*   **"As any user, I want to easily find links to the club's official social media..."**: Successfully validated by locating the social media icons (Facebook, Twitter, etc.) in the footer of each page and confirming they link to the respective platforms.
*   **"As a potential contributor/contact, I want to find contact information easily."**: Successfully validated by clicking the 'CONTACT' link and verifying that contact methods are presented on `contact.html`.

### Bugs / Issues Resolved
*  Initial mobile menu implementation using absolute positioning caused content overlap. Refactored using max-height transition for smoother display that pushes content down.
*   No major blocking bugs were encountered during development. Testing primarily involved minor CSS adjustments for alignment, spacing, and responsive behavior across different breakpoints.

## Installation / Local Viewing

To view this project locally:

1.  Clone the repository to your local machine:
    ```bash
    git clone https://github.com/DonMarcao/PROJECT.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd PROJECT
    ```
3.  Open the `index.html` file in your web browser.

## Future Enhancements

*   Implement a user comment section for news and media articles.
*   Integrate live match updates and potentially player statistics using an external API (would require JavaScript).
*   Add a dedicated fan forum or chat feature for enhanced community interaction.
*   Implement more advanced JavaScript for interactive elements like image sliders/carousels or dynamic content filtering.
*   Add a section linking to official club merchandise partners.
*   Develop a simple backend or use a CMS for easier content updates (currently static HTML).

## Credits / Attributions

Acknowledgement to the resources used in this project:

*   **Content:**
    *   Historical facts, news summaries, and club-specific information were researched from general knowledge and publicly available sources related to São Paulo Futebol Clube. All textual content was written by the project author unless otherwise specified.
*   **Media (Images & Audio):**
    *   Sourcing appropriate, freely licensed images and audio specific to São Paulo Futebol Clube presented a significant challenge for this educational project.
    *   The images and audio currently used serve primarily as **visual and auditory placeholders** to fulfill the design requirements and demonstrate the website's intended look, feel, and functionality within this specific learning context.
    *   It is acknowledged that for any deployment beyond this limited educational scope (e.g., public, commercial), **obtaining proper licenses or replacing these assets with verifiably licensed alternatives would be essential and mandatory.** This project prioritised showcasing HTML/CSS skills, with the understanding that asset licensing is a critical component of real-world development.
*   **Media (Video):**
    *   Videos embedded in the Media section are sourced from YouTube. Credit belongs to the original uploaders and respective copyright holders. YouTube is the hosting platform.
*   **Icons:**
    *   Social media icons in the footer are provided by [Font Awesome](https://fontawesome.com/) via CDN, used according to their free license terms.
*   **Code:**
    *   All HTML and CSS written by the project author, leveraging concepts learned during coursework and standard web development practices.
    *   CSS vendor prefixes potentially added by [Autoprefixer](https://autoprefixer.github.io/).

## Author

*   Marcus Machado

## License

Copyright (c) 2024 Marcus Machado. All Rights Reserved.