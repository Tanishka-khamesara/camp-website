# camp-website
https://tanishka-khamesara.github.io/camp-website/camp.html



![t1](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/e96a49c5-2316-4984-800c-e22dee42d644)
![t2](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/72c22b02-0559-4a78-bfba-36d5014bd880)
![t3](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/5dee6b4a-f543-44ae-a848-6ab2f7746a65)
![t4](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/67aa4ff6-9509-449d-a5a2-36ce1269677a)
![t5](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/41604ed3-8966-4e3d-bed5-012366594ca4)
![t6](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/32e6b351-1192-410c-8606-13f6ad627c0e)
![t7](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/88abb236-e565-4a8e-a4ca-2e52f6b625d3)
![t8](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/1695f594-d34c-4926-bd23-62e9843e6d58)
![t9](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/530d2d77-8788-4637-bf85-257908090780)
![t10](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/bba4fa13-ba62-4f54-ae62-aa5e653e8bcb)
![t12](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/608cacb3-3e23-4294-b198-dec03a7fd78b)
![t13](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/7dfcbf01-a626-4e68-85e6-eb1cbfd184f5)
![t14](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/f680cc28-2002-4306-a6b1-90d43e5db03b)
![t15](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/218520e0-2eea-4af2-a1cd-1750a6463e7d)
![t16](https://github.com/Tanishka-khamesara/camp-website/assets/127411985/2613b494-121f-4c19-916f-18754092ad26)
html code explaination:-
<link href="./style.css" rel="stylesheet">: Links an external CSS stylesheet called "style.css" to apply styles to the HTML content.

<body>: Contains the main content of the web page that is visible to users.

<div class="bg">: A container div for the background section of the webpage.

<div class="navbar font">: Defines a navigation bar section with the "font" class for typography.

<div class="logo">: Contains the logo for the website.

<h2>LOGO</h2>: Displays the website's logo text.
<div class="options">: Contains navigation links.

<a href="">Home</a>: A navigation link to the home section (empty href).

<a href="#services">Services</a>: A navigation link to the services section with the ID "services."

<a href="#portfolio">Portfolio</a>: A navigation link to the portfolio section with the ID "portfolio."

<a href="#aboutus">About Us</a>: A navigation link to the about us section with the ID "aboutus."

<a href="#contact">Contact Us</a>: A navigation link to the contact us section with the ID "contact."

<div class="blur">: A semi-transparent overlay div for the background section.

<div class="name font">: Contains the main content of the website's header.

<h1 class="head">Camping Gear and Essentials</h1>: Displays the website's main heading.

<p class="description">...: Provides a description of the website's services.

<a href=#services><button>OUR SERVICES</button></a>: Includes a button linked to the services section.

<div id="services" class="description">: A section with the ID "services" and a description class for styling.

<div class="second-page font">: Contains a heading for the services section.

<h1>Our Services</h1>: Displays a heading for the services section.

<p>Explore our wide range of camping gear services.</p>: Provides a brief description of the services.

<div class="cards font">: Contains a set of cards for different camping gear services.

Cards are repeated with images, headings, and descriptions for each service.
<div class="about font" id="aboutus">: A section with the ID "aboutus" for the "About Us" section.

<div class="us">: Contains a heading and a paragraph about the team.

<div class="height">: Contains subsections with headings and paragraphs describing the company's story, mission, vision, and team members.

<section class="contact font" id="contact">: The contact section with the ID "contact."

<h2>Contact Us</h2>: Displays a heading for the contact section.

<p>Reach out to us for any inquiries or feedback.</p>: Provides a brief description.

<div class="contact-box font ">: A container for contact information and a contact form.

Two divs with the class "box" contain contact information and a contact form.

The contact form includes fields for name, email, message, and a "Send Message" button. Each field is labeled and has placeholder text.

Contact information includes the address, email, phone number, and website URL, each displayed with an accompanying SVG icon.

The HTML structure creates a responsive webpage with navigation links that scroll to specific sections on the page. It also includes information about the company's services, team, and contact details.





css properties i used in respective classes:-
@import: Imports an external font stylesheet from Google Fonts to use the 'Poppins' font family.

*: Selects all HTML elements and sets some initial styles, such as resetting margins, using the border-box model for sizing, and setting padding to 0% (which may not have any effect).

body: Sets the background color for the entire document to a light grayish color (#f2f2f2).

.font: Specifies the 'Poppins' font family for elements with this class, ensuring consistent typography.

.bg: Defines styles for a background image, including its size, position, attachment, and a fixed background effect.

.navbar: Styles for a fixed navigation bar with a dark background, including its height, alignment, and color.

.logo > h2: Styles for the text inside the logo, setting the text color, font size, and padding.

.options: Styles for a flex container holding navigation links, including padding.

.options > a: Styles for navigation links within the options class, including padding, font size, color, and removal of underlines.

.blur: Creates a semi-transparent background overlay to add a visual effect on top of the background image.

.name: Styles for a section containing a name, including color, alignment, and centering of content.

.name > h1: Styles for a large heading within the name class, including font size and padding.

.name > p: Styles for a paragraph within the name class, setting font size, width, and text alignment.

.name > a > button: Styles for a button within a link within the name class, including button appearance and shadow.

.name > a: Styles for a link within the name class, including margin.

.second-page: Styles for a section on the second page, including margin and content alignment.

.description: Styles for a description within the second page, including margin.

.cards: Styles for a flex container holding cards, including layout and spacing.

.card-1: Styles for the individual cards, including size, background color, margins, and content alignment.

.tent: Styles for an image within a card, setting border-radius and object-fit.

.card-1 > h3: Styles for the heading within a card, including text alignment and font size.

.card-1 > p: Styles for paragraphs within a card, setting margins and text alignment.

.us: Styles for a section about "us," including layout, margin, and content alignment.

.us > h2: Styles for a heading within the "us" section, setting font size.

.height: Styles for a subsection, including margin and alignment.

.height > h3: Styles for a heading within the "height" section, setting margins.

.height > p: Styles for paragraphs within the "height" section, setting margins.

.contact: Styles for a contact section, including layout, margin, and content alignment.

.contact > h2: Styles for a heading within the contact section, setting font size.

.contact-box: Styles for a container within the contact section, including layout and alignment.

.box: Styles for boxes within the contact box, including padding.

form input: Styles for input fields within a form, including height, margins, padding, and border.

form textarea: Styles for a textarea within a form, including padding, font size, height, and border.

form button: Styles for buttons within a form, including margins, padding, font size, and color.

#services, #aboutus, #contact: Styles for specific sections identified by their IDs, adding padding to create spacing.

