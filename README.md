# Sprout & Spark

![website-preview](https://github.com/user-attachments/assets/edb750fd-211a-423a-9c40-c3e265ffc827)


This fictional website is designed for children and their families to find creative and interesting workshops for their SEN children to attend, socialise, create and be a part of a safe space for all their learning needs. 

Required: HTML, CSS 
Optional: Bootstrap, favicon and other custom CSS libraries.

Please visit the deployed website [here](https://ctrlaltkismet.github.io/Sprout-and-Spark/) on github pages.

## Contents

- [UX/UI](#uxui)
- [Strategy](#strategy)
- [Features](#features)
- [User Stories](#user-stories)
- [Site Structure](#site-structure)
- [Wireframes](#wireframes)
- [Design Choices](#design-choices)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Deployment](#deployment)
- [Future Features](#future-features)
- [Credits](#credits)

---

## UX/UI

### Project Goals

The primary goal of this website is to create a neurodiverse-friendly website created to promote and support free workshops and events for families with children who have Special Educational Needs (SEN). The website should offer a welcoming space for children ages 6 and up to participate in hands-on creative activities, such as painting and drawing, and older children ages 10 and up other activities such as woodworking and clay modelling. The website and events included are designed to provide a support network for parents. The two main target audiences are children ages 6 and up and their parents. The website aims to create a safe space for both children and adults with external information accessible for adults who may need further support and guidance caring for their children.

- To promote sensory-considerate, hands-on workshops for SEN children.
- To provide a safe, welcoming space for families.
- To support children's development with gross motor skills and socialisation.
- To offer information and emotional support for parents.
- To sustain the project through cmomunity donations and engagement.

### Player Goals

The main target audience for this website are both children ages 6 and up and adults who can assit them to these workshops and events.

- To feel excited and safe when viewing the website.
- To see images of fun and creative activities accessible through a gallery of recent workshop photography.
- To understand what to except from the events in a gentle and visual way.

### Parental Goals

The parents of these children should be able to access the website accordingly and sign up to the events their children are interested in. Parents will be expected information to be laid out accorindlgy including; what happens at each event, what SEN accomodations are available at these events, what date and time each event is on, and swiftly sign up to each event on an intuitive and simple form with submission confirmation.

- To easily browse and register for workshops/events.
- To access clear, compassionate information about SEN accomodations available at the events.
- To find external support links and guidance.
- To navigate the site stress-free on all platforms including mobile and tablet.
- To be able to navigate the suit intuitively and expect to find required information within a couple of clicks.

  ### Developer and Business Goals

- To build a responsive and accessible website with a clean design, many pictures and appropriate for all screen sizes.
- To use clear calls to action to drive event registrations.
- To keep all information in one place for easy maintenance.
- To future-proof with modular content such as a calendar and videos.

---

## Strategy

The Sprout & Spark website is designed to support and informa families of children with Special Education Needs (SEN) by showcasing the free creative workshops the organisation offers. These workshops will focus on inclusive, hands-on activities such as painting, clay modelling, and wood carving to help children build motor skills, express themselves creatively, and improve social interaction. The website aims to serve both new and returning families by providing clear, accessible information about the sessions, the support network available, and the positive mpact these activities can have on wellbeing.

Visitors will be bale to explore workshop details, meet the facilitators, and see photo examples of past activities to get a sense of what to expect. Practical features like contact forms, intuitive interactivity and layouts, and accessible information will help families plan their visit with confidence. Accessibility is key priority, so the website will use inclusive design principles -- such as a neurodiverse-friendly layout and colour scheme with high contrast, readable fonts (Lexend and Roboto), and alt text fror images -- to ensure it meets the needs of a wide audience.

Social media links will also be included to keep users informed about upcoming events and ongoing fundraising efforts. Testimonials from participating families will provide reassurance and insight into the experience, helping to build trust and encourage new visitors to get involved.

The fictional organisers behind Sprout & Spark would find this website valuable not only as a promotional tool but as a means to connect with the community, grow their reach, and secure ongoing support. By making the information welcoming, easy to navigate, and visually calm, the website becomes a reliable resource for those seeking creative and supportive environments for their children.

The main audience includes parents and carers of children with SEN, educators, and community supporters who wish to learn more, get involved, or donate to help sustain the service.

## Features

- Accessible navigation on all pages.
- Visual, engaging workshops listings.
- SEN support information for each activity.
- Easy-to-use booking form.
- Fully mobile and tablet responsive.
- Alt-text for all images.
- Fonts optimized for readability.
- A complementative colour pallete across all web pages.
- Links to external websites for further support for families.
- A gallery updated after each event to encourage website engagement.
- Links to social media for further visual content such as photos and videos.

---

## User Stories

### User Story 1: Homepage Navigation
**As a parent visiting the site,** I want to easily find information about available workshops, so I can quickly understand what’s on offer.

**Acceptance Criteria:**
- The homepage has a clear call-to-action linking to the workshops section.
- The navigation menu is visible on all pages and easy to understand.
- The homepage clearly communicates what the site offers (workshops for SEN children).

**Tasks:**
- Design and build a homepage with intro text/banner.
- Add a top navigation bar with links: home, gallery, events, support, sign up.
- Add a hero section with a brief overview of the workshops and who they’re for.
- Ensure navigation is consistent across all pages.

---

### User Story 2: Workshop Listings
**As a user,** I want to view a list of available workshops, so I can choose one that suits my child’s interests and needs.

**Acceptance Criteria:**
- Workshops are listed in a clear, visually engaging format.
- Each listing includes activity type, age, range, short description, and SEN features.
- Users can search workshops by activity type or age group.

**Tasks:**
- Create an “Events” page with a card or grid layout.
- Add workshops preview cards (image, name, age, activity, short blurb).
- Ensure cards are clickable to expand text and key details.

---

### User Story 3: Workshop Details
**As a parent,** I want to quickly view key information about each workshop without needing to click into a separate page, so I can make decisions faster and easier.

**Acceptance Criteria:**
- All key details (age range, activity type, SEN features, location, time) are visible on the events page itself.
- Each workshop card or section includes enough information to help a parent decide whether to book.
- Users do not need to navigate away from the page to get essential details.

**Tasks:**
- Expand each workshop card or listing to include: Full description, activity type, age range, SEN accommodations, date/time and location, booking button which links to “sign up”.
- Use collapsible sections or expandable cards (optional) to keep the layout tidy.
- Remove need for individual detail pages for now – keep everything on one page.

---

### User Story 4: Accessibility & SEN-Focused Info
**As a parent of a child with specific needs,** I want to see how the workshops accommodate SEN children, so I can feel reassured.

**Acceptance Criteria:**
- Each workshop clearly lists its SEN accommodations.
- Site includes an overview of how it supports children with autism, ADHD, and other conditions.
- SEN info is easy to locate and written with empathy and clarity.

**Tasks:**
- Add badges/icons for SEN features (e.g. autism-friendly, small group)
- Write a section/page explaining general SEN support philosophy (to be added to the “support” page)
- Add testimonials or quotes from parents if available.

---

### User Story 5: Booking or Registration
**As a user,** I want to book or register my child for a workshop easily, so I don’t have to contact someone manually.

**Acceptance Criteria:**
- Each workshop has a visible “Book Now” or “Register” button.
- The form collects key information (child name, age, parent contact, selected workshop)
- Submitting the form provides confirmation to the user.

**Tasks:**
- Add a booking form.
- Include name, age, workshops selection, email/phone.
- Add validation (e.g. required fields)
- Show success message upon submission.

---

### User Story 6: Child-Friendly Content
**As a child exploring the site with my parent,** I want to see fun images and activity previews, so I get excited about the workshops.

**Acceptance Criteria:**
- The website uses visuals that are engaging for children (e.g. colours, illustrations).
- Images of the activities (e.g. painting, clay, woodworking) are included to visually show what workshops are like.
- Language is friendly, clear and non-intimidating, even if it’s written primarily for adults.

**Tasks:**
- Choose a playful, welcoming colour palette (without overwhelming sensory input).
- Use AI-generated photos (Bing image creator) of children participating in activities.
- Write descriptions with a positive, encouraging tone (e.g. “explore your creativity!” instead of “improve fine motor skills”.)
- Include large, easy-to-read fonts and accessible design for visual clarity.

---

### User Story 7: Mobile & Accessibility Optimisation
**As a parent using my phone,** I want the site to be easy to use on mobile and other smaller devices, so I can browse and sign up without frustration.

**Acceptance Criteria:**
- All pages are responsive and functional on mobile devices.
- Text is readable and buttons are easily tappable.
- Images include alt text, and site uses accessible fonts/colours.

**Tasks:**
- Implement responsive layouts for all pages (tested using Dev Tools)
- Use accessible colours, large fonts and high-contrast design.
- Add alt text for all images and icons.
- Test form functionally on mobile.

---

### User Story 8 (Should Have): Calendar View
**As a parent,** I want to view upcoming workshops in a calendar layout, so I can easily plan around my schedule.

**Acceptance Criteria:**
- A calendar view shows dates and times of all upcoming workshops.
- Clicking a date shows workshop info.
- Optional: Users can filter by workshop type or age group.

**Tasks:**
- Integrate a basic calendar component (or use a plugin).
- Link calendar entries to workshop info on the same page.
- Highlight today/upcoming sessions visually.

---

### User Story 9 (Could Have): Workshop Preview Video
**As a parent or child,** I want to watch a short video showing a workshop in action, so I can better understand what to expect.

**Acceptance Criteria:**
- A 30–60 second video clip is available on the homepage or workshops page.
- The video shows kids engaged in activities in a relaxed and friendly setting.

**Tasks:**
- Embed a video in a prominent place on the site.
- Add captions or brief text alongside to explain the activity.


---

## Site Structure

The *Sprout & Spark* website has a consistent and user-friendly layout, following the same colour scheme off an off-white and blue with red accent colours. There are key navigation links located in the sticky navigation bar at the top of every page, which utilises a hamburger icon on smaller screens. The website logo, which is also located in the navigation bar, can be clicked at any time to return the user to the homepage.

1. The **home page** can be accessed by clicking the first link in the navigation bar. This page introduces visitors to Sprout & Spark, explaining the purpose of the workshops, and highlights the inclusive values of the business. It provides a welcoming overview of what families can expect with appealing images to further provide a warm and welcoming environment for the user. There are cards located near the footer of the page with buttons which can be clicked to take the user to the events page. Like all buttons on the website, they have a hover effect on computers which turn red, once again utilising perfect contrast and accessibility for the user.
   
2. The **gallery page** can be accessed by clicking the second link in the navigation bar. this page showcases a variety of images from past workshops, helping users get a visual feel for the creative activities offered and the engaging environment provided for children with SEN. The images provided are inclusive and diverse, showcasing families of different cultural backgrounds so all families feel welcome and involved within the community.
   
3. The **events page** can be accessed by clicking the third link in the navigation bar. This page provides information about upcoming workshops including; dates, times, recommended ages, duration of event and group size. Key details also include accessibility features and location support for each individual event.

4. The **support page** can be accessed by clicking the fouth link in the navigation bar. This page offers information about different types of support available for both children and their parents or carers, as well as signposting to additional services and networks.

5. The **sign up page** can be accessed by clicking the fifth and final link in the navigation bar. This page allows users to resgister interest in upcoming workshops, providing an easy way to book a place or contact the business with general query's. All fields on the contact form must be filled out and the user is taken to a success page to confirm their form submission.

6. The **about us page** can be accessed by clicking the first link in the footer. This page shares its mission and mentions how donations and fundraising efforts help keeps the charity alive. This page includes images of each person who runs Sprout & Spark and briefly states what their role is for the charity.

7. The **contact us page** can be accessed by clicking the second link in the footer. This takes the user to the contact form on the support page.

8. The **FAQs page** can be accessed by clicking the third link in the footer. This page answers common questions that families may have about accessibility, age ranges, workshop structure and how to get involved.

9. The **reviews page** can be accessed by clicking the fourth link in the footer. This page features testimonials from families who have attended previous workshops, helping to build trust and encourage new visitors to take part.

10. The **fundraise page** can be accessed by clicking the fifth link in the footer. This page explains how Sprout & Spark is funded and includes a link to donate to the business via PayPal as well as accepting donated supplies and partnering with businesses for support.


![Website Structure chart](https://github.com/user-attachments/assets/7f39a4e3-c190-47b3-a1c5-59f1756f4c8a)

---

## Wireframes

Balsamiq was used to generate each wireframe. (please note: the wireframes for the footer links were not generated as they were initially intended to be placeholders)

Index page:
![Index Page Wireframe](https://github.com/user-attachments/assets/8ccdf390-3c81-4018-9e17-418864cd1bf6)

Gallery Page:
![Gallery Page Wireframe](https://github.com/user-attachments/assets/aee6fdfe-9d69-46ec-9f26-7bb84a0dab34)

Events page:
![Events Page Wireframe](https://github.com/user-attachments/assets/d88f2683-ee78-4381-a7eb-79d39f04ab11)

Support page:
![Support Page Wireframe](https://github.com/user-attachments/assets/7cb457fd-7766-4671-a950-f4ef271c61ef)

Sign up page:
![Sign Up Page Wireframe](https://github.com/user-attachments/assets/e51854bf-7d56-4885-81ac-6f76d1492079)


Note: There were minor discrepencies in the layout between the wireframes and when coding the website. These discrepencies made the website look better and more intuitive. 

---

## Design Choices

### Fonts

As the website boasts inclusivity for SEN children, it is important to choose a font that is readable for children with dyslexia or Irlen's Syndrome. As Open Dyslexia is unavailable on Google Fonts, research suggests Lexend to be the next best font for readability.

- **Lexend** - Primary font, chosen for its accessibility and readability benefits.
![image](https://github.com/user-attachments/assets/e4fcdd73-b963-45e6-abe0-381c625d4421)

- **Roboto** - Backup font for modern, clean support.
![image](https://github.com/user-attachments/assets/51b05419-1a75-4e8b-afac-3aecd1440d71)


Fonts for headers and navbar links have been either put in bold or capitalised to enhance readability, with suitable spacing within the navbar to ensure all components can be easily read and understood with younger eyes.

### Colour Palette

Not all colours have been used but were taken from the hero image for selective choice. Mostly the light blue, dark blue and red highlight colours were chosen and the plain white background suited the light blue nav bar and divs on each page. This choice makes the website look professional, readable and child friendly as it remains vibrant and eye-catching. Furthermore, keeping the colour palette to a minimum ensures it appeals to individuals who may experience some colour-blindness and ensures text is not lost, keeping it high contrast.

- Soft, friendly colours chosen to be welcoming and sensory-considerate.
- High contrast for readability, without stimulaton.

![image](https://github.com/user-attachments/assets/835e8f8d-a4e7-41db-8f22-85f0d89628e4)


### Layout & Components

- Card layout for workshop previews on index page, with images to show the user what the room layout will look like on entering the premises.
- Accesible navigation bar with search bar so users are able to search on the current webpage or other webpages within the website.
- Expandable/collapsible cards for workshop information.
- Large buttons and touch-friendly elements for mobile and tablet users.
- Hovering over nav links and buttons changes the colour to red so the user is aware they are on the correct link. The hover transitions over 0.3 seconds so it is not too jarring.
- Many pictures have been placed throughout the index page to keep it as eye catching as possible and keep it user friendly for younger audiences.
- Text has large gaps between each section to ensure readability for audiences with dyslexia/Irlens.
- A logo has been used instead of text in the navbar as images are much more recognisable and users can immediately recognise the company.

## Homepage

### Navigation Bar

On desktop, the navigation bar remains at the top of the website at all times. The logo is located on the left, with a search bar in the middle, mostly as a placeholder for a functioning searchbar, and links on the right. Each link turns red when highlighted and the logo always links back to the homepage.

Navigation bar on desktop:
![image](https://github.com/user-attachments/assets/3d01a997-c160-4245-b76f-0b0b5235d490)



Navigation bar on tablet devices with hamburger icon and drop down menu:

![image](https://github.com/user-attachments/assets/bae60a67-7da1-4e82-8f80-914637992d9a)
![image](https://github.com/user-attachments/assets/ddfc91a8-d5ae-470d-b6bb-99e5b7753804)



Navigation bar on mobile devices with hamburger icon and drop down menu:

![image](https://github.com/user-attachments/assets/5584650f-466f-40e8-8ffb-d2e02fc12c73)
![image](https://github.com/user-attachments/assets/0e7b2c88-d6f5-4087-9cf3-c8f66baf27d9)

## Hero Image

The hero image used is where the primary colour of light blue comes from, using a colour picker service such as imagecolorpicker.com. On desktop, the image primarily focuses on the boy and what he is doing. However, the image will scale on smaller devices such as on mobile the entire picture can be seen clearly. The image is also styled with a shadow beneath it to make it pop out more from the page.

On desktop:
![image](https://github.com/user-attachments/assets/9dd9b0ba-e179-463c-a545-044051b1e5ee)



On tablet:
![image](https://github.com/user-attachments/assets/b5fee6ae-7b83-42e7-8b73-c615d1c86dac)



On mobile:
![image](https://github.com/user-attachments/assets/dc0daf1a-3d63-4503-a527-ec6afe571dd6)

## Introduction

The introduction on this page includes another image on the right hand side alongisde some text to introduce the user to the website. The address and phone number is also included in this section.

On desktop:
![image](https://github.com/user-attachments/assets/82016b4e-5b2a-47a3-9073-e02e1b92a97b)


On tablet:
![image](https://github.com/user-attachments/assets/84251776-61a0-4eec-8e7d-571522c9f794)


On mobile:
![image](https://github.com/user-attachments/assets/82c397f8-f97f-4d52-92c1-8f7becd5ea14)

## Workshop Preview

The workshop preview is sectioned off to allow each section to breathe. The previews are placed in cards which gives a brief, one-sentence overview and includes buttons which can take the user straight to the events page.

On desktop:
![image](https://github.com/user-attachments/assets/4699d3eb-cfca-4c57-a00a-e60d6869a30f)




On tablet:
![image](https://github.com/user-attachments/assets/161bf6cb-976c-4d5f-abe1-76a248d72dac)




On mobile:
![image](https://github.com/user-attachments/assets/57b5a7c8-0114-4c1b-938f-a0bbf5895b01)

## Footer

The footer is the same on every page and includes links for further information, all with the same red hover affect as other links and buttons on the web page. The functional social media icons have been enlarged and spaced out which makes it easier for mobile and tablet users to click on. (Note: to protect the privacy of children and the nature of this topic, all images on the website have been AI generated using Bing Image Creator).

On desktop:
![image](https://github.com/user-attachments/assets/62b19dc9-be08-4903-930d-d79eccbc1d17)




On tablet:
![image](https://github.com/user-attachments/assets/35eaf8fe-0e23-4773-a8fb-eebf84ed6052)



On mobile:
![image](https://github.com/user-attachments/assets/e1b1521c-6d5d-4573-b806-7703db774709)

## Gallery Page

All images on the gallery page are spaced evenly in a grid-like format, with the bottom image being the biggest image. When hovering over each picture with a mouse, the image enlarges ever-so-slightly to improve the interaction elements of the website.

On desktop:
![image](https://github.com/user-attachments/assets/95c6ad6f-2036-4948-8dfe-88003a3f8a40)
![image](https://github.com/user-attachments/assets/73b4bade-ea3b-4f27-b155-49f94dc532cc)
![image](https://github.com/user-attachments/assets/3835f7cb-6c77-4d3a-80b9-b2ddf1be8e54)




On tablet:
![image](https://github.com/user-attachments/assets/9eb2c480-56a4-4b93-ad19-acbbed042def)




On mobile:
![image](https://github.com/user-attachments/assets/52571be2-788b-46d5-afa5-817c1295e7d2)





## Technologies Used

- HTML5 & CSS3
- [Google Fonts](https://fonts.google.com/) (Lexend & Roboto)
- [Bootstrap](https://getbootstrap.com/) (for navbar and cards -- see comments in code)
- [Font Awesome](https://fontawesome.com/) (for icons)
- [Image Colour Picker](https://imagecolorpicker.com/) (to find suitable colours for the website)
- [W3C CSS Validation](https://jigsaw.w3.org/css-validator/) (to validate CSS code)
- [W3C Validator](https://validator.w3.org/) (to validate HTML pages)
- Lighthouse via Dev Tools
- GitHub Pages (for deployment)
- Bing AI image generator (for imagery)

---

## Installation

Clone the repo:

```bash
git clone https://github.com/yourusername/sen-family-workshops.git
cd sen-family-workshops
```

Open `index.html` in your browser to run locally.

---

## Deployment

Deployed via GitHub Pages:

---

## Future Features

- Calendar view of events  
- Embedded video previews of workshops  
- Parent testimonials  
- Workshop filtering by age/activity

---

## Credits

- **Fonts** by [Google Fonts](https://fonts.google.com/)  
- **Images** via Bing AI image creator  
- Workshops inspired by real-world SEN support needs
