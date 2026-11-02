# Web Development Projects

A collection of beginner-level web development mini-projects created using **HTML5** and **CSS3**. This repository documents three webpages: a restaurant menu, a personal hobbies page, and an introductory HTML audio-page example.

> **Documentation note:** The uploaded project report contains the projects **Delicious Restaurant**, **My Hobbies**, and **Audio Webpage**. It does not describe projects named FITZONE, College Website, or Student Dashboard. This README follows the actual report and source code.

## About This Repository

This repository presents three simple webpages developed to practise the fundamentals of web development. The projects demonstrate how HTML structures page content and how CSS controls colors, typography, spacing, borders, alignment, and layout.

The supplied pages cover:
- Restaurant information and menu presentation.
- A personal page describing hobbies and leisure activities.
- An HTML audio-player example whose supplied source currently has markup and media-resource issues.

## Student Details

| Field | Details |
|---|---|
| Name | G LOKESH |
| Roll Number | 26001209 |
| Section | CSM06 |
| Course | B.Tech – CSE (AI & ML) |
| University | Dr. RVR NRI University |
| Subject | Web Development |

**Student details updated as requested:** Name, roll number, and section are shown above. The course is taken from the uploaded report.

## Technologies Used

| Technology / Tool | Usage documented in the report |
|---|---|
| HTML5 | Structures webpage content using headings, paragraphs, lists, divisions, images, and an audio element. |
| CSS3 | Embedded styles control fonts, colors, margins, padding, borders, rounded corners, image dimensions, and text alignment. |

**Implementation notes**
- CSS is embedded inside `<style>` elements in the Restaurant Menu and My Hobbies HTML files.
- No separate `.css` stylesheet was supplied.
- The report does not document JavaScript, a database, a backend framework, or an external CSS framework.
- VS Code, Git, and GitHub are not identified as tools used in the supplied report, so they are not listed as confirmed project technologies.

## Project 1 – Delicious Restaurant

### Description

The Delicious Restaurant webpage presents a restaurant introduction, food categories with prices, a special-food photograph, and contact information. The page uses Arial text and a warm light-cream background (`#fff3e0`).

### Objectives

- Practise organizing restaurant information with HTML headings, paragraphs, and lists.
- Present menu categories and item prices clearly.
- Display a local food image using the HTML image element.
- Apply CSS to style page sections, borders, spacing, and colors.

### Features

- **Header:** Brown banner with the title “Delicious Restaurant” and the tagline “Fresh Food, Great Taste!”.
- **About Us:** Restaurant introduction inside a white rounded section.
- **Starters:** Unordered list containing Veg Soup, French Fries, and Paneer Tikka with prices.
- **Main Course:** Ordered list containing Veg Biryani, Chicken Biryani, and Paneer Curry with prices.
- **Desserts:** Unordered list containing Ice Cream, Chocolate Cake, and Gulab Jamun with prices.
- **Our Special Food:** Displays the supplied food photograph at 300 × 200 pixels with an orange border and rounded corners.
- **Contact Us:** Displays the Vijayawada, Andhra Pradesh address and the phone number written in the source.
- **Footer:** Brown banner with “Thank you for visiting!”.

### Technologies

- HTML5
- CSS3 (embedded in the HTML file)

### Output Screenshot

The report includes a rendered output for the Restaurant Menu webpage. A separate screenshot image file was not supplied with the documentation, so the path below is a **placeholder**. Replace it with the actual image committed to your repository.

![Delicious Restaurant webpage output](screenshots/delicious-restaurant.png)

> Screenshot placeholder: `screenshots/delicious-restaurant.png`

## Project 2 – My Hobbies

### Description

The My Hobbies webpage introduces personal interests and describes how hobbies can be useful. It uses Arial/sans-serif text, a light-blue page background, and vertically arranged content sections.

### Objectives

- Practise using headings, paragraphs, unordered lists, and division elements.
- Organize personal interests into readable sections.
- Apply CSS colors, spacing, borders, and typography.
- Present information in a simple, visually separated layout.

### Features

- **Main Heading:** “My Hobbies”, centered in dark blue on a light-yellow background.
- **Introduction:** Explains that hobbies are enjoyable free-time activities that help with learning.
- **Reading Books:** Describes reading storybooks and novels and improving knowledge and vocabulary.
- **Playing Sports:** Describes outdoor games and their role in keeping a person healthy and active.
- **My Favorite Hobbies:** Lists reading books, listening to music, playing cricket, drawing pictures, and watching movies.
- **Footer:** Dark-blue banner containing “Thank you for visiting my webpage!”.

### Technologies

- HTML5
- CSS3 (embedded in the HTML file)

### Output Screenshot

The report includes a rendered output for the My Hobbies webpage. A separate screenshot image file was not supplied with the documentation, so the path below is a **placeholder**. Replace it with the actual image committed to your repository.

![My Hobbies webpage output](screenshots/my-hobbies.png)

> Screenshot placeholder: `screenshots/my-hobbies.png`

## Project 3 – Audio Webpage

### Description

The supplied file `Untitled-1.html` appears intended to demonstrate an HTML audio control for a song. It contains an `<audio>` element with controls and a source reference. However, the referenced MP3 file was not supplied, and the HTML contains syntax and markup issues.

### Objectives

- Explore the HTML audio element and its controls.
- Understand that media playback requires valid HTML markup and an available media resource.
- Observe and document the browser output produced by the supplied source.

### Features / Current Status

- Contains an audio element intended to display browser audio controls.
- Includes a source reference intended for an MP3 resource.
- The referenced MP3 file is missing from the supplied materials.
- The source contains malformed HTML, including an incomplete doctype declaration, an incomplete HTML start tag, a misplaced body closing tag, a misspelled autoplay attribute, and an incomplete source tag.
- The captured output is a blank page; a working audio player could not be verified.

**Important:** The blank output is the result of the supplied source and missing audio resource. It is not a completed or intentionally designed audio-player interface. The original source is documented without silently correcting it.

### Technologies

- HTML audio and source elements (as attempted in the supplied HTML)
- No CSS styling is documented for this page.

### Output Screenshot

The report shows the supplied Audio Webpage rendering as a blank page. The path below is a **placeholder** for a separately exported screenshot.

![Audio Webpage supplied output](screenshots/audio-webpage.png)

> Screenshot placeholder: `screenshots/audio-webpage.png`

## Project Screenshots

The documentation contains rendered output images for all three supplied pages. However, those images were included in the PDF and were **not supplied as separate image files**. The following Markdown image paths are placeholders; add the corresponding screenshot files to the `screenshots/` folder for them to display on GitHub.

| Project | Expected screenshot path |
|---|---|
| Delicious Restaurant | `screenshots/delicious-restaurant.png` |
| My Hobbies | `screenshots/my-hobbies.png` |
| Audio Webpage | `screenshots/audio-webpage.png` |

## Project Documentation

The source document supplied for preparing this README is:

- `Web_Development_Project_Report_G_Lokesh (1).pdf` — uploaded project report.

A repository path for the Word/PDF report was not provided. Therefore, no GitHub documentation link is claimed here. If you add the PDF to your repository, update this section with its actual committed path, for example `docs/project-report.pdf`.

## How to Run

1. Download the repository using **Code → Download ZIP**, or clone it:

   ```bash
   git clone <your-repository-url>
   ```

2. If you downloaded the ZIP file, extract it.
3. Open the project folder on your computer.
4. Locate the relevant HTML file:
   - Restaurant Menu: `restorent.html`
   - My Hobbies: `my hobbies.html`
   - Audio Webpage: `Untitled-1.html`
5. Double-click an HTML file, or right-click it and choose a web browser to open it.

**Resource note:** Keep `retorent.jpg` in the location expected by `restorent.html` so the restaurant image can load. The report also mentions `images.jpg`, but that image is not referenced by the supplied HTML pages. The Audio Webpage will not provide working playback unless its HTML issues are corrected and the referenced MP3 resource is supplied.

## Learning Outcomes

Through these projects, the work demonstrates practice with:

- Creating the basic structure of an HTML document.
- Organizing content using headings, paragraphs, divisions, ordered lists, and unordered lists.
- Applying CSS styles for colors, fonts, spacing, borders, rounded corners, and alignment.
- Displaying a local image in a webpage.
- Exploring the HTML audio element and understanding the need for valid markup and available media files.
- Reviewing webpage output in a browser and identifying issues that affect rendering.

## Future Improvements

The following items are **future plans identified in the project report**, not features already implemented:

- Add a navigation bar and responsive layout to the Restaurant Menu and My Hobbies pages.
- Move embedded CSS into separate stylesheet files for easier maintenance.
- Add the missing MP3 file and correct the HTML structure and audio attributes in the Audio Webpage.
- Add mobile-friendly styling using CSS media queries.
- Improve accessibility with valid language attributes, meaningful alternative text, and semantic HTML elements.

## Author Details

**G LOKESH**  
Roll Number: 26001209  
Section: CSM06  
B.Tech – CSE (AI & ML)  
Dr. RVR NRI University  
Subject: Web Development

---

*Prepared from the supplied Web Development Project Report. Project descriptions and current implementation status are based on that report; screenshot and documentation repository paths must be updated when the corresponding files are added to GitHub.*
