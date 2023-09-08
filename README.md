# permaculture-map-berlin

## User Experience (UX) Section

### Objective

is to showcase numerous successful examples of regenerative urban food production from Berlin using an interactive map. Our project serves as a powerful tool to connect and educate individuals passionate about sustainable urban living, ultimately contributing to making Berlin a greener and more environmentally conscious city.

### Target Groups

consists of nature lovers, individuals passionate about a healthy lifestyle and diet, advocates and activists of environmental movements, but also all the citizens of the capital city Berlin who are looking for green oases amidst the concrete jungle due to various needs.

### Users Benefits

#### A)

is straightforward search of all permaculture projects in Berlin, achieved through an interactive Story Map technology of ArcGIS [ArcGIS StoryMaps](https://storymaps.arcgis.com/ "ArcGIS StoryMaps"). It allows the combination of cartographic, textual, and audio-visual material to transmit compelling stories.

#### B)

A Contribute page will allow users to enter information about new permaculture projects in Berlin to support the extension and updating of the map.

### Features

#### Home Page

When users enter the site, they encounter a **clickable logo** of the NGO [Peace of Land](http://www.peaceof.land "Peace of Land") "POL" - Berlin that stands behind this project.

In continuation, an easily readable **Navigation bar** is positioned on all three pages to allows the users to reach to the desired addresses: *Home*, *Contribute*, and *About Us*. Navigation bar is responsive thanks to the usage of CSS-flexbox.  At the breakpoint of 375px the position of three links changes from vertical to horizontal. Besides, the Logo and Navigation bar change their position or size to improve the readability and aesthetic value of the product. Besides, CSS-pseudo-selectors are here for the sake of dynamic experience.
Underneath, there is a motivating **Hero Image** accompanied by the **Title** and **Subtitle**.
Only for the screen sizes 1024 and more parallax effects have been introduced, as some smart-phone devices and tablets are not compatible with this feature. [Parallax Tutorial](https://www.w3schools.com/howto/howto_css_parallax.asp "Parallax Tutorial") Acknowledgments to my CI Mentor Narender Singh.
By scrolling down, users can read a brief **Paragraph** to gain insight into the site's purpose.
**Map Section** is designed to motivate users to actively delve into the interactive Story map, captivating with its rich textual and audio-visual content. An engaging mix of informative, educational, and inspirational elements is intended to foster a positive user experience and prompt visitors to return to the site multiple times. An embedded scrollbar remains part of the map to enhance the user experience.
![Esri Story Map](/assets/images/esri-story-map.webp?raw=true "General Appearance")

An additional **CTA** in the form of a CONTRIBUTE! button is incorporated into the map, inviting users to share their valuable insights and information about ongoing permaculture projects in the site's **Contribute page**
The **footer section** hosts links to Peace of Land's pertinent social media platforms on all three pages. This section is crucial as it enables users to stay informed about the various activities of Peace of Land.

#### ContributePage

Information gathered in this manner will be integrated into the map by our web page administrators. This section holds value for users as it allows them to personally contribute to the evolving environmental movement in Berlin.
Input and Textarea fields adjust responsively, taking up less container space as screen size grows. On screens >700px, a circular nature-motif photo starts filling the container's right, shifting and resizing with screen expansion.
Currently the data from the Contribute Page goes to [Form Dump](https://formdump.codeinstitute.net/ "Form Dump"). In the future, we'll introduce a Thank You page for enhanced user experience. As the site reaches full functionality, we'll integrate features for secure data collection.

#### About Us Page

describes the principal objectives and activities of POL, an NGO that operates the site "BERLIN-PERMACULTURE-MAP".This page showcases a responsive collage of photos and informative texts. A particular text field displays attractive logos in a list, adding to the dynamic visual appeal of the page. Important part is at least one link to relevant educational resources.

Under the hood is [css-grid-auto-fill-and-auto-fit](https://css-tricks.com/auto-sizing-columns-css-grid-auto-fill-vs-auto-fit/ "css-grid-auto-fill-and-auto-fit") approach to coding responsive web products.

## Workflow and Alterations

In the course of delivering the project, as a result of time limitation and unplanned implementation of new technical solutions a few significant modifications occurred. For instance: a) hamburger-menu abandoned; b) introduction of responsive photo for the Contribute Page (for the formats iPad and 1024px). We believe that these decisions have been instrumental in finalizing the project and enhancing its overall quality. Thanks to the mentor who has already provided instructions, the "Hamburger Menu" will be introduced in upcoming projects.

Used external sources and programs:

Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.

[Balsamiq](https://balsamiq.com/ "Balsamiq") - used for wireframing: Initial design for three pages:

![Home Page](/assets/images/home-page.webp?raw=true "Home Page Design")

![Form Page](/assets/images/form_page.webp?raw=true "Form Page Design")

![About Us Page](/assets/images/about_us.webp?raw=true "About Us Page Design")

### Design

- Coolors: delivered this color palette:
![Palette used](/assets/images/coolors_palette.webp?raw=true "Color palette used in this project")
Explanation: combination of a green, gray and brown color resembles the green oasis in the middle of the “concrete jungle”.
- Chrome Dev-Tool color picker
- [color-contrast-checker](https://accessibleweb.com/color-contrast-checker/ "color-contrast-checker").

![Color Contrast Checker Results for green and black](/assets/images/contrast-ratio-1.webp?raw=true "Color palette used in this project")

![Color Contrast Checker Results for red and black](/assets/images/contrast-ratio.webp?raw=true "Color palette used in this project")

For enhanced readability, a parallax component has been incorporated into the landing section.

- Photos: The written permission (mail: ) to use photos from the Peace of Land library acquired from this NGO.

[Google Fonts](https://www.google.com/search?client=firefox-b-e&q=google+fonts "Google Fonts")
    - Google fonts were used to import the 'Roboto' and Urbanist font into the style.css file

[Font Awesome](https://fontawesome.com/ "Font Awesome")
    - Font Awesome icons were incorporated across the website on all pages to enhance aesthetics and user experience.

[Faststone Image Viewer](https://www.faststone.org/ "Faststone Image Viewer")
    - was utilized for logo creation, image resizing, and photo editing for the website.

### Accessibility

[Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp "Semantic Elements")

### Testing

- W3C Markup Validator - results
- W3C CSS Validator - results

Known Bugs
Smartphones:

Contribute Page - the viewport is too big -

- Rotated screen size - only the central portion of the screen visible
		
About Us Page - the height of the viewport is reduced cousin the overlapping of text.

Familiarized, but not used learning sources and coding tools:

- [Box-shadow Generator](/*<https://html-css-js.com/css/generator/box-shadow/>*/ "Box-shadow Generator")
- [CSS-Gradient](https://cssgradient.io/ "CSS-Gradient")

////////////////////////////////////////////////////////////////////
<abbr title="Mozilla Developer Network">
