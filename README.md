# berlin-permaculture-map

![Contribute_Page](/assets/images/home-bites.webp?raw=true "General Appearance")

![Contribute_Page](/assets/images/contribute-bites.webp?raw=true "General Appearance")

![About_Us_Page](/assets/images/about-us-bites.webp?raw=true "General Appearance")

## User Experience (UX) Section

### Objective

is to showcase numerous successful examples of regenerative urban food production from Berlin using an interactive map. Our project serves as a powerful tool to connect and educate individuals passionate about sustainable urban living, ultimately contributing to making Berlin a greener and more environmentally conscious city.

### Target Groups

consists of nature lovers, individuals passionate about a healthy lifestyle and diet, advocates and activists of environmental movements, but also all the citizens of the capital city Berlin who are looking for a green oasis amidst the concrete jungle due to various needs.

### Users Benefits and Goals

#### A) For the first-time user

the site allows for a straightforward search of all permaculture projects in Berlin, achieved through an interactive Story Map technology of ArcGIS [ArcGIS StoryMaps](https://storymaps.arcgis.com/ "ArcGIS StoryMaps"). It allows the combination of cartographic, textual, and audiovisual material to transmit compelling stories. A Contribute page enables users to enter information about new permaculture projects in Berlin to support the extension and updating of the map.

#### For returning visitors

the site allows utilizing the designated communication channel (Contribute Page, Contact Us page with contact details, links to social media channels in Footer) on our website to effectively engage and align contributions with the organization's objectives.

#### For Frequent User

The site serves as a permanent source of textual and geographical information for permaculture projects in Berlin.

### Design

#### Home Page

When users enter the site, they encounter a **clickable logo** of the NGO [Peace of Land](http://www.peaceof.land "Peace of Land") "POL" – Berlin that stands behind this project.

In continuation, an easily readable **Navigation bar** is positioned on all three pages to allow the users to reach the desired addresses: _Home_, _Contribute_, and _About Us_. The navigation bar is responsive thanks to the usage of CSS-flexbox. At the breakpoint of 375px, the position of three links changes from vertical to horizontal. Besides, the Logo and Navigation bar change their position or size to improve the readability and aesthetic value of the product. Moreover, CSS-pseudo-selectors are here for the sake of dynamic experience.

Underneath, there is a motivating **Hero Image** accompanied by the **Title** and **Subtitle**.

By scrolling down, users can read a brief **Paragraph** to gain insight into the site's purpose.

The **Map Section** is designed to motivate users to actively delve into the interactive Story map, captivating with its rich textual and audiovisual content. An engaging mix of informative, educational, and inspirational elements is intended to foster a positive user experience and prompt visitors to return to the site multiple times. An embedded scrollbar remains part of the map to enhance the user experience.

![Esri Story Map](/assets/images/esri-story-map.webp?raw=true "General Appearance")

An additional **CTA** in the form of a CONTRIBUTE! button. The link is incorporated into the map, inviting users to share their valuable insights and information about ongoing permaculture projects on the site's **Contribute page**

The **footer section** hosts links to Peace of Land's pertinent social media platforms on all three pages. This section is crucial as it enables users to stay informed about the various activities of Peace of Land.

#### Contribute Page

Information gathered in this manner will be integrated into the map by our web page administrators. This section holds value for users as it allows them to contribute to the evolving environmental movement in Berlin personally.

Input and Textarea fields adjust responsively, taking up less container space as screen size grows. On screens >700px, a circular nature-motif photo starts filling the container's right, shifting and resizing with screen expansion.

Currently, the data from the Contribute Page goes to [Form Dump](https://formdump.codeinstitute.net/ "Form Dump"). In the future, we'll introduce a Thank-you page for enhanced user experience. As the site reaches full functionality, we'll integrate features for secure data collection.

#### About Us Page

describes the principal objectives and activities of POL, an NGO that operates the site "BERLIN-PERMACULTURE-MAP". This page showcases a responsive collage of photos and informative texts. A particular text field displays attractive logos in a list, adding to the dynamic visual appeal of the page. An important part is at least one link to relevant educational resources.

## Workflow and Alterations

In the course of delivering the project, as a result of time limitations and unplanned implementation of new technical solutions, a few significant modifications occurred. For instance:

1. The hamburger menu was abandoned;
1. Introduction of responsive photo for the Contribute Page (for the formats iPad and 1024px). We believe that these decisions have been instrumental in finalizing the project and enhancing its overall quality. Thanks to the mentor who has already provided instructions, the “Hamburger Menu” will be introduced in upcoming projects.

##Technologies Used
HTML, CSS

### Typography:

[Google Fonts](https://fonts.google.com/” "Google Fonts") was used to link the 'urbanist' and “roboto” fonts into all three HTML files, as suggested by the mentor to improve the upload time. These have been used on all pages throughout the project. Sans Serif is the fallback font.

[Balsamiq](https://balsamiq.com/ "Balsamiq") - used for wireframing: Initial design for three pages:

![Home Page](/assets/images/home-page.webp?raw=true "Home Page Design")

![Form Page](/assets/images/form_page.webp?raw=true "Form Page Design")

![About Us Page](/assets/images/about_us.webp?raw=true "About Us Page Design")

### Design

- Coolors: delivered this color palette:
  ![Home_Page](/assets/images/coolors_palette.webp?raw=true "General Appearance") "Color palette used in this project")

Explanation: a combination of a green, grey and brown color resembles the green oasis in the middle of the “concrete jungle”.

- Chrome Dev-Tool color picker

- [color-contrast-checker](https://accessibleweb.com/color-contrast-checker/ "color-contrast-checker").

![Color Contrast Checker Results for gray background and black letters](/assets/images/contrast-ratio-1.webp?raw=true "Color palette used in this project")

![Color Contrast Checker Results for red background color and black letters](/assets/images/contrast-ratio.webp?raw=true "Color palette used in this project")

- Photos: The written [permission](https://github.com/VladaAlek/berlin-permaculture-map/blob/main/assets/images/photo-permission-POL.webp "permission") to use photos from the Peace of Land library acquired from this NGO.

[Font Awesome](https://fontawesome.com/ "Font Awesome") - Font Awesome icons were incorporated across the website on all pages to enhance aesthetics and user experience.

[Faststone Image Viewer](https://www.faststone.org/ "Faststone Image Viewer") - was utilized for logo creation, image resizing, and photo editing for the website.

[Git](https://github.com/ "Git")
-Version control was managed using Git, with commits executed via the Gitpod terminal and pushes directed to GitHub.

[GitHub](https://github.com/ "GitHub")
-The project's code is stored on GitHub after being pushed from Git.

#### Familiarized, but not used, learning sources and coding tools:

- [Box-shadow Generator](https://html-css-js.com/css/generator/box-shadow/"Box-shadow Generator")

- [CSS-Gradient](https://cssgradient.io/ "CSS-Gradient")

### Accessibility and readability

Several [Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp "Semantic Elements") guidelines and principles have been implemented in the project.

For optimal user experience, a parallax component is integrated into the landing section. Note: This feature is active only for screen sizes 1024px and above due to compatibility issues with certain smartphones and tablets.
[Parallax Tutorial](https://www.w3schools.com/howto/howto_css_parallax.asp "Parallax Tutorial")

## Testing

- [W3C Markup Validator](https://validator.w3.org/ "W3C Markup Validator")

[Home_Page](https://github.com/VladaAlek/berlin-permaculture-map/blob/main/assets/images/html_validator_home.webp "Home_Page")

[Contribute_Page](https://github.com/VladaAlek/berlin-permaculture-map/blob/main/assets/images/html_validator_contribute.webp "Contribute_Page")

[About_Us_Page](https://github.com/VladaAlek/berlin-permaculture-map/blob/main/assets/images/html_validator_about_us.webp "About_Us_Page")

[Cover_Letter](https://github.com/VladaAlek/berlin-permaculture-map/blob/main/assets/images/cover-letter.webp "Cover_Letter")

[Workflow](https://github.com/VladaAlek/berlin-permaculture-map/blob/main/assets/images/workflow_example.webp "Workflow")

- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input "W3C CSS Validator") -[Result](https://github.com/VladaAlek/berlin-permaculture-map/blob/main/assets/images/css-validator.webp "Result")

### Testing User Stories from the UX Section

#### First-Time Visitor Goals

1. First-Time Visitor Experience on the Website

   -As a first-time visitor, clarity and quick understanding are paramount. Right off the bat, the site welcomes users with a clear navigation bar, directing them effortlessly to their desired page. Directly below, a compelling hero image paired with a concise title and subtitle captures the essence of the organization.

2. First-Time Visitor Navigation Experience

   -As a first-time visitor, seamless site navigation is essential. The website is designed with a clear and intuitive navigation bar, ensuring users can effortlessly locate and access desired content without confusion.

#### Returning Visitor Goals

1. For returning visitors, the website clearly displays the organization's contact methods for quick inquiries.

   -The "Contribute" and "About Us" pages are prominently featured on the navigation bar. The layout of the latter includes both the “Contact Section” and “Bank Account” sections.

   -The footer includes links to the organization's social media platforms.
   -The Home Page features a "Contribute!" button.

#### Frequent User Goals

1. For frequent users, the site offers an easy way to identify new contributions added to the Berlin Permaculture Map or reliable sources of geographical locations.

   -The Home Page prominently displays the Berlin Permaculture Map, streamlining navigation for users.

## Further Testing

-The Website was tested on Google Chrome and Firefox
-The project was designed for the following screen sizes: smartphone (375 x 700px); iPad (768 x 1024) and 1024 x 700px. The website was viewed and responsiveness controlled on a variety of devices of various screen sizes (smartphone, tablet, 1024px).
-Extensive testing was conducted to verify correct linking across all pages.

## Known Bugs

-The “CONTRIBUTE!” button on the Home Page might not function properly due to interference from an iframe.
-The SUBMIT button has a tendency to be positioned not in accordance with my style rules.
-About Us Page - to big viewport for big size screens

### Acknowledgments

-my CI Mentor Narender Singh
-CI students: David Calikes, Craig Hudson and James Paliga
-Footer design is based on CI tutorials

##### -Youtube tutorials

    -[Navigation Bar](https://www.youtube.com/watch?v=UYvwb6pBvg8 "Navigation Bar")
    -[About Us page:](https://css-tricks.com/auto-sizing-columns-css-grid-auto-fill-vs-auto-fit/ "css-grid-auto-fill-and-auto-fit")
