# Sprout & Spark

![website-preview](https://github.com/user-attachments/assets/edb750fd-211a-423a-9c40-c3e265ffc827)


This fictional website is designed for children and their families to find creative and interesting workshops for their SEN children to attend, socialise, create and be a part of a safe space for all their learning needs. 

Required: HTML, CSS 
Optional: Bootstrap, favicon and other custom CSS libraries.

Please visit the deployed website [here](https://ctrlaltkismet.github.io/Sprout-and-Spark/) on github pages.

## Contents

- [UX and UI](#ux-and-ui)
  - [Project Goals](#project-goals)
  - [Player Goals](#player-goals)
  - [Parental Goals](#parental-goals)
  - [Developer and Business Goals](#developer-and-business-goals)
  - [Strategy](#strategy)
  - [User Stories](#user-stories)
  - [Site Structure](#site-structure)
  - [Wireframes](#wireframes)
  - [Design Choices](#design-choices)
  - [Layout and Components](#layout-and-components)

- [Features](#features)
- [Mock Ups](#mock-ups)

- [Testing](#testing)
  - [Lighthouse](#lighthouse)
  - [Contrast](#contrast)
  - [Validation](#validation)
  - [User Stories Check](#user-stories-check)
  - [Testing on Other Devices](#testing-on-other-devices)
  - [Testing on Other Browsers](#testing-on-other-browsers)
  
- [Technologies Used](#technologies-used)

- [Installation](#installation)
- [Deployment](#deployment)
- [Future Features](#future-features)
- [Bugs and Fixes](#bugs-and-fixes)
- [Credits](#credits)


---

## UX and UI


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


### Layout and Components

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
<br>&nbsp;
On tablet:

![image](https://github.com/user-attachments/assets/b5fee6ae-7b83-42e7-8b73-c615d1c86dac)
<br>&nbsp;
On mobile:

![image](https://github.com/user-attachments/assets/dc0daf1a-3d63-4503-a527-ec6afe571dd6)

## Introduction

The introduction on this page includes another image on the right hand side alongisde some text to introduce the user to the website. The address and phone number is also included in this section.

On desktop:
![image](https://github.com/user-attachments/assets/82016b4e-5b2a-47a3-9073-e02e1b92a97b)
<br>&nbsp;
On tablet:

![image](https://github.com/user-attachments/assets/84251776-61a0-4eec-8e7d-571522c9f794)
<br>&nbsp;
On mobile:

![image](https://github.com/user-attachments/assets/82c397f8-f97f-4d52-92c1-8f7becd5ea14)

## Workshop Preview

The workshop preview is sectioned off to allow each section to breathe. The previews are placed in cards which gives a brief, one-sentence overview and includes buttons which can take the user straight to the events page.

On desktop:
![image](https://github.com/user-attachments/assets/4699d3eb-cfca-4c57-a00a-e60d6869a30f)
<br>&nbsp;
On tablet:

![image](https://github.com/user-attachments/assets/161bf6cb-976c-4d5f-abe1-76a248d72dac)
<br>&nbsp;
On mobile:

![image](https://github.com/user-attachments/assets/57b5a7c8-0114-4c1b-938f-a0bbf5895b01)

## Footer

The footer is the same on every page and includes links for further information, all with the same red hover affect as other links and buttons on the web page. The functional social media icons have been enlarged and spaced out which makes it easier for mobile and tablet users to click on. (Note: to protect the privacy of children and the nature of this topic, all images on the website have been AI generated using Bing Image Creator).

On desktop:
![image](https://github.com/user-attachments/assets/62b19dc9-be08-4903-930d-d79eccbc1d17)
<br>&nbsp;
On tablet:

![image](https://github.com/user-attachments/assets/35eaf8fe-0e23-4773-a8fb-eebf84ed6052)
<br>&nbsp;
On mobile:

![image](https://github.com/user-attachments/assets/e1b1521c-6d5d-4573-b806-7703db774709)

### Gallery Page

All images on the gallery page are spaced evenly in a grid-like format, with the bottom image being the biggest image. When hovering over each picture with a mouse, the image enlarges ever-so-slightly to improve the interaction elements of the website.

On desktop:
![image](https://github.com/user-attachments/assets/95c6ad6f-2036-4948-8dfe-88003a3f8a40)
![image](https://github.com/user-attachments/assets/73b4bade-ea3b-4f27-b155-49f94dc532cc)
![image](https://github.com/user-attachments/assets/3835f7cb-6c77-4d3a-80b9-b2ddf1be8e54)
<br>&nbsp;
On tablet:

![image](https://github.com/user-attachments/assets/9eb2c480-56a4-4b93-ad19-acbbed042def)
<br>&nbsp;
On mobile:

![image](https://github.com/user-attachments/assets/52571be2-788b-46d5-afa5-817c1295e7d2)

### Events Page

All cards on the events page are spaced evenly and I have used a tiny amount of JavaScript to ensure that the cards are clickable to reveal more data; this has been extensively tested to ensure it works as intended on all screen formats.

On desktop:
![image](https://github.com/user-attachments/assets/541b21eb-fd26-455d-87a5-503aad940cdb)
![image](https://github.com/user-attachments/assets/6c756244-aefb-4037-8b10-5b4e1d5dd2f2)
![image](https://github.com/user-attachments/assets/c47866f5-381f-4288-b6b1-1b0e460225ee)
![image](https://github.com/user-attachments/assets/cface287-b1e7-4334-a7d6-df01de43fec0)


<br>&nbsp;
On tablet:

![image](https://github.com/user-attachments/assets/d92ac811-e6e1-4485-a437-f8d6efeff549)
![image](https://github.com/user-attachments/assets/3ae2e2f4-b97e-44f7-9c88-1fdd8bcba0f5)

<br>&nbsp;
On mobile:

![image](https://github.com/user-attachments/assets/0aa2eddd-6713-4cb3-801f-084e0f1a9674)
![image](https://github.com/user-attachments/assets/111c0b9e-aa96-45bc-b0b5-fe2f98a9b951)

### Support Page

The support page includes helpful links placed in interactive cards for families to find external support, alongside a contact us form which has a confirmation message when filled in. This contact form is also linked to the 'contact' in the footer as well.

On desktop:
![image](https://github.com/user-attachments/assets/34e01864-05d6-43b0-84cb-8ccefe5981b1)
![image](https://github.com/user-attachments/assets/703369a9-1d21-4e9c-986e-e65b1f42a1e6)
![image](https://github.com/user-attachments/assets/a0e0359d-0d86-42b5-9068-7b14e9e01ee4)

<br>&nbsp;
On tablet:

![image](https://github.com/user-attachments/assets/5e6ccddb-e72a-480d-8d4f-420d8ecfc732)
![image](https://github.com/user-attachments/assets/a9672de6-fb54-4491-882b-f0e51609dd7f)

<br>&nbsp;
On mobile:

![image](https://github.com/user-attachments/assets/8fac7ebe-dd0f-49d2-b2be-df29897d3151)
![image](https://github.com/user-attachments/assets/819a1288-42db-4499-888a-b3f7863430f6)
![image](https://github.com/user-attachments/assets/cd78a811-0e13-46aa-b059-efd70b5506a6)


### Sign Up Page

The sign up page just contains a form where each box must be filled in and will give a warning if there are any left blank. It features a drop down menu for all the advertised workshops that are currently on and will take the user to a success page upon completion.

On desktop:

![image](https://github.com/user-attachments/assets/1b93d975-3cc0-48f1-9882-53d3be8aa876)
![image](https://github.com/user-attachments/assets/a26cf6d1-dbc3-4a89-a547-209773177019)
![image](https://github.com/user-attachments/assets/b4109c77-e12e-43ac-9204-78902ff5fb77)


<br>&nbsp;
On tablet:

![image](https://github.com/user-attachments/assets/8add1d9f-38b7-4a1d-9125-d4e117e83646)
![image](https://github.com/user-attachments/assets/3f70871f-f30e-4ea1-bbcf-ba1a082296fc)


<br>&nbsp;
On mobile:

![image](https://github.com/user-attachments/assets/9c2c5878-efee-481a-97e9-4b32523e9e92)
![image](https://github.com/user-attachments/assets/5cf1c2dc-4652-4edb-8c47-8a313a2f92ab)
![image](https://github.com/user-attachments/assets/5014dc91-a465-4296-b741-23eab63a7a43)


### About us Page

The about us page contains a few sentences about what Sprout & Spark believe in followed by 4 images, placed in cards, of the individuals who teach each workshop as well as stating what their skills are.

On desktop:
![image](https://github.com/user-attachments/assets/81ec47a8-f7b3-4540-911c-8ce515d21e42)
<br>&nbsp;
On tablet:

![image](https://github.com/user-attachments/assets/fb88ef3f-5079-4fc2-9f8d-a119f69e393c)

<br>&nbsp;
On mobile:

![image](https://github.com/user-attachments/assets/74d9e9a1-dc5e-48b9-b503-1081797bd49c)
![image](https://github.com/user-attachments/assets/aeca670f-857c-4896-9cc2-0c6bb64f7c45)

### FAQs

The FAQs page is mostly a placeholder for now with future improvements in mind. For now, it consists of a simple interactive table for users to click on to reveal answers to questions they may have.

On desktop:
![image](https://github.com/user-attachments/assets/fd9d04f5-dc5f-4510-a29f-456f06fdd995)

<br>&nbsp;
On tablet:

![image](https://github.com/user-attachments/assets/988c638d-dfb7-4539-b7ed-2a23ff85b8e8)

<br>&nbsp;
On mobile:

![image](https://github.com/user-attachments/assets/6e8e4da5-71f9-489c-8d13-89c2edfff75a)

### Reviews
The reviews page is another placeholder page as ideally it should have stars out of 5 and be played on a carousel integrated on the homepage. However, this will be applied during future updates. For now, reviews are placed in 6 cards for users to have a good idea of what other families think of each workshop. The 'leave a review' button takes the user straight to the contact form on the support page.

On desktop:

![image](https://github.com/user-attachments/assets/833a65e4-65df-4878-9230-3645dffd9fe5)

<br>&nbsp;
On tablet:

![image](https://github.com/user-attachments/assets/e6bc56ca-b54f-4d41-ad58-95261402f5a0)

<br>&nbsp;
On mobile:

![image](https://github.com/user-attachments/assets/4da5f60c-c273-492d-bc30-737022037565)

### Fundraise 

The fundraising page tells the user how Sprout & Spark gain funds and supplies to continue running their workshop, with an optional "donate now" button which takes the user to PayPal.

On desktop:

![image](https://github.com/user-attachments/assets/a938934b-2973-4b5a-86b1-7f765e4572f7)

<br>&nbsp;
On tablet:

![image](https://github.com/user-attachments/assets/564e0b97-9ac7-494a-aab9-ecb4b1a848be)

<br>&nbsp;
On mobile:
![image](https://github.com/user-attachments/assets/bd0301ab-7b14-4dd0-b501-907025f82f47)

### 404

A 404 page has also been added to the website in case the wrong URL was inputted into the search bar.
![image](https://github.com/user-attachments/assets/06834d18-43cd-4f13-b7c7-3c8a0244ac56)



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
- A link to the homepage attached to the navbar logo for ease of use.

## Mock ups

Here are mock ups on most devices for each page of my website, these were created on [UI dev](https://ui.dev/amiresponsive?url=)

Home page:
![website-preview](https://github.com/user-attachments/assets/ce5d64c7-df94-488a-ae33-de41c531151e)

Gallery page:
![Gallery preview](https://github.com/user-attachments/assets/30bbe0ca-3e95-4861-ac37-e8b6c4d6a049)

Events page:
![Events preview](https://github.com/user-attachments/assets/91630aef-c245-4aff-a0f7-caf2f9fc0c77)

Support page:
![Support preview](https://github.com/user-attachments/assets/fd7e934a-b71f-4b17-80c2-17a6f7f2b99e)

Sign up page:
![Sign up Preview](https://github.com/user-attachments/assets/8171327b-4446-4341-9930-0002c64750ea)

About us page:
![about us preview](https://github.com/user-attachments/assets/2e30572c-7477-4a51-b0af-cd3e87b52434)

FAQs page:
![FAQs preview](https://github.com/user-attachments/assets/e165a156-4c00-4025-a7f2-b83ce5dfb8bb)

Reviews page:
![reviews preview](https://github.com/user-attachments/assets/d6874dd4-8417-4b92-9349-04338d7b97c2)

Fundraise page:
![fundraise preview](https://github.com/user-attachments/assets/b09b8401-0860-4f90-b203-b6a762bce2d6)

## Testing

Throughout this project, I have used a variety of tools to test the websites functionality, contrast, code validation, ensured all 'must-have' user stories are checked, and tested on other physical devices to ensure the website is fully functional on various hardware. Throughout this process, I have corrected and documented a variety of changes based on errors and recommendations.

## Lighthouse

Any lighthouse corrections made for performance was mostly due to the image sizes. As all of my images have been AI generated, their image sizes sometimes exceeded 2MB which impacted performance, I corrected these by resizing them using the paint tool on Microsoft Windows which would bring some files from 2MB down to 70KB. This drastically improved the performance for my website.

Index page:
![image](https://github.com/user-attachments/assets/726d395d-2031-4f29-856d-67a5f144b479)
<br>&nbsp;
Gallery page after changing images from PNG to JPG and resizing:
![image](https://github.com/user-attachments/assets/a911437b-d0d6-4c96-bbd6-6761dd70f3f8)
<br>&nbsp;
Events page after resizing images:
![image](https://github.com/user-attachments/assets/5e34fadb-ab81-47dc-b0c1-b843a240755e)
<br>&nbsp;

Support page:
![image](https://github.com/user-attachments/assets/eaf8ff3b-534f-4a03-aeb8-6a019a8fbf3f)
<br>&nbsp;

Sign up page:
![image](https://github.com/user-attachments/assets/306d7fda-e91c-4350-9d35-76033ad3afcd)
<br>&nbsp;

About us page:
![image](https://github.com/user-attachments/assets/38fbb0ec-e159-473c-be76-d6ce792fb8be)
<br>&nbsp;

FAQs page:
![image](https://github.com/user-attachments/assets/c3a0ba9c-18c7-4706-a547-1f99fe816381)
<br>&nbsp;

Reviews page:
![image](https://github.com/user-attachments/assets/29dd68df-4bab-4e21-b7f9-125b8e1ed6e5)
<br>&nbsp;

Fundraising page:
![image](https://github.com/user-attachments/assets/45ef8952-70a7-4ae3-a01e-0c4932715792)

## Contrast

Using the 'Wave' extension for Chrome, I tested the contrast for each of my web pages. Due to the nature of my website design and colour choices, no pages came back with any contrast errors due to its simplistic design.
![image](https://github.com/user-attachments/assets/f7d70716-cf92-43a8-bdad-461c8254be51)
![image](https://github.com/user-attachments/assets/f8ee4b40-02a9-4472-8b4d-652f6362c39a)
![image](https://github.com/user-attachments/assets/c6f38b8e-7913-4c29-8091-7fa61b08d5d3)
![image](https://github.com/user-attachments/assets/0c9e5cc4-f991-4cc0-b1c0-184eec4a6547)
![image](https://github.com/user-attachments/assets/255629ae-4f1a-4be4-b053-914a9816f8f0)
![image](https://github.com/user-attachments/assets/a4fe678e-ec98-4b2a-a50e-fce8d4ae0cb4)
![image](https://github.com/user-attachments/assets/c17e0c58-8551-472c-9528-adc01f2f44ed)
![image](https://github.com/user-attachments/assets/8d2e8050-0879-4f0f-94e5-762c821211ca)
![image](https://github.com/user-attachments/assets/e9f4994e-40d3-40d3-9002-bc4a58e1d1da)

## Validation

To validate my code, I used W3C Markup Validation for my HTML code and the W3C CSS validation too. It did come back with some errors which were promptly fixed.

### HTML Validation

Index page:
The index page came back with 5 errors and 2 warnings, mostly due to duplicate ID's which were fixed by removing and instead using classes -- the custom CSS was also modified to reflect these changes. Section was also changed to div as suggested by the validator.
![image](https://github.com/user-attachments/assets/3957e298-2061-462e-ac8d-1465fa0e6068)

After changes were made, there were no more errors:
![image](https://github.com/user-attachments/assets/2d247b47-fdf3-48d5-a49d-e28b4aba665d)

Gallery page:
The gallery page came with just 2 errors and 1 warning, which was due to unclosed elements and a section lacking a heading. I used the same div fix as before to ensure all elements were closed.
![image](https://github.com/user-attachments/assets/9619bba7-fa4f-42ad-8b1b-4d7e11291fd2)

After changes were made, there were no more errors:
![image](https://github.com/user-attachments/assets/a6287c3f-fb9d-4352-95ee-ac5454b7dcc6)

Events page:
The events page showed a total of 26 errors including: the main element must not appear as a descendent of the header element (fixed by moving main from beneath the header to above it) duplicate IDs (removed), the end tag section seen but a div element was still open (closed element with another div) and a header missing before my section which was promptly added.
![image](https://github.com/user-attachments/assets/e2ba00e7-c864-49f7-b22b-2f8ef6a4929a)

After changes were made, there were no more errors:
![image](https://github.com/user-attachments/assets/4ef8b5ba-5796-47e3-a38e-ad3e33dc5046)

Support page:
The support page showed some errors; the main and footer should not appear as a descendent of the header element (fixed by moving the elements around accordingly) and unclosed elements (fixed by closing elements):
![image](https://github.com/user-attachments/assets/20f23356-cb0d-4c58-be05-6d16da7a8541)

After changes were made, there were no more errors:
![image](https://github.com/user-attachments/assets/7e300d1a-5e6f-403c-864e-d7763898f698)

Sign up page:
The sign up page had duplicate IDs , the element of the footer appearing as the descendent of the header element and more unclosed elements. I used the same fixes as before, using the validator to locate which lines these errors had appeared on.
![image](https://github.com/user-attachments/assets/647ea372-862f-4a49-b8cb-d43f7ee9a72e)

After changes were made, there were no more errors:
![image](https://github.com/user-attachments/assets/21f67e74-2762-4817-8163-29f504ab3a3f)

Success page:
There were no errors on the success page:
![image](https://github.com/user-attachments/assets/4db4f198-64a0-4ca5-bd89-845946625367)

About us page:
The about us page didn't show any errors in the code:
![image](https://github.com/user-attachments/assets/413d7ceb-06e2-4dba-9daf-ae631b1ed21c)

FAQs page:
The FAQs page didn't show any errors in the code:
![image](https://github.com/user-attachments/assets/2c0a352b-1676-4ad8-8358-9b98af329f8e)

Reviews page:
The reviews page didn't show any errors in the code:
![image](https://github.com/user-attachments/assets/838a62f0-f805-47e3-9120-f7089f2874a5)

Fundraising page:
There were no errors in the code:
![image](https://github.com/user-attachments/assets/32257d8d-7b66-425d-978c-cf093272369e)

### CSS Validation

Using the W3C CSS Validatin service, my CSS came back with only 1 error. The 31 warnings were due to using CSS variables which cannot be checked due to the interchangeability of these variables. After researching, I had found that this is a warning for the W3C validation service and not for my code. I fixed the error "text-decoration bold" to the appropriate syntax of "font-weight".

![image](https://github.com/user-attachments/assets/3e86073e-1ccd-4aba-8004-a4d6126c4445)

After using the correct syntax, no more errors were found:
![image](https://github.com/user-attachments/assets/5880cf12-0b4b-4f27-95f9-442b877bf943)

## User Stories Check

To ensure my website had achieved all outcomes, I tracked the progress of my user stories and checked off each checkbox after I had achieved the desired outcome. I could not start the 'should-haves' for the website due to time constraints but have plans to add these in the future. All 'must-have' user stories were completed:

![image](https://github.com/user-attachments/assets/6a530b2e-8687-43c8-9930-97d293fcc97e)
![image](https://github.com/user-attachments/assets/fe5cc644-089c-43e1-a6c4-745c27055fe4)
![image](https://github.com/user-attachments/assets/1a97acd8-1fc5-4de4-b21f-a324c5a8168e)
![image](https://github.com/user-attachments/assets/636a7313-1649-4445-b151-bf9e3569290a)
![image](https://github.com/user-attachments/assets/43ae6fab-e5ce-473a-acbf-c62ee5c30b9b)
![image](https://github.com/user-attachments/assets/172562ac-7972-42d9-bcff-a60ef08f50f4)
![image](https://github.com/user-attachments/assets/9d6d2fca-104a-4bc2-997f-0cbfd968e171)
![image](https://github.com/user-attachments/assets/6e0a158c-d04b-4f06-a3d1-2393a75796eb)

## Testing on Other Devices

To ensure the website was responsive on other physical devices, I tested the accessibility and functionality of my website on both an iPhone 16 and iPad Pro. The website worked exactly as intended with images appearing instantly and all links functional.

Screenshots taken directly from iPad:
![IMG_0337](https://github.com/user-attachments/assets/bd11011c-073f-4f8a-92ac-ef6d7e8a323d)
![IMG_0338](https://github.com/user-attachments/assets/2a17a12d-9356-437f-8bbd-3e138d93b319)
![IMG_0339](https://github.com/user-attachments/assets/ef77087b-a6e0-4dd8-88e5-428142609529)
![IMG_0340](https://github.com/user-attachments/assets/480d1bd6-a7bc-4d5a-b69e-9b589e877f83)
![IMG_0341](https://github.com/user-attachments/assets/ae97fa1a-9810-45e2-964d-1f675872916b)
![IMG_0342](https://github.com/user-attachments/assets/9510cfe4-36d6-4e11-ab16-e25f727345cb)
![IMG_0343](https://github.com/user-attachments/assets/0d2364b0-1805-43d5-b4aa-cea9ec91620c)
![IMG_0344](https://github.com/user-attachments/assets/56cdac2b-f247-4ff0-ba4a-a16dca16cf32)
![IMG_0345](https://github.com/user-attachments/assets/cc89a2a3-e40c-4011-8b33-b214c8c82b43)
![IMG_0350](https://github.com/user-attachments/assets/2bf2731a-fe82-47d2-8e98-ce35c8f6af0b)
![IMG_0349](https://github.com/user-attachments/assets/39f09422-203e-4cc8-9f10-01a62669f676)
![IMG_0348](https://github.com/user-attachments/assets/cb0a1ed2-562d-4c43-be21-80c306f3a6ea)
![IMG_0347](https://github.com/user-attachments/assets/4afd445c-63bd-4356-b2e9-0e6ab417eb79)
![IMG_0346](https://github.com/user-attachments/assets/aaeb6625-c85b-439c-95f7-c51f5cc89744)

Screenshots taken directly from iPhone:
![IMG_2551](https://github.com/user-attachments/assets/92db3ff8-2597-439f-bf1c-8e9fbd48af8c)
![IMG_2550](https://github.com/user-attachments/assets/963d63dd-91f0-4d31-8875-8efcead56fd0)
![IMG_2549](https://github.com/user-attachments/assets/7ce1c4ef-563d-4b71-bde8-48e58f3c63c8)
![IMG_2548](https://github.com/user-attachments/assets/06828283-5500-44f0-90f1-5004c3ba764d)
![IMG_2547](https://github.com/user-attachments/assets/e159dd38-f938-4f01-8396-70c26b06345b)
![IMG_2546](https://github.com/user-attachments/assets/dd6cf71c-ffcc-4e9a-845f-0909a8ebad92)
![IMG_2545](https://github.com/user-attachments/assets/6c752797-e362-4da9-96f8-3bc6a1680776)
![IMG_2544](https://github.com/user-attachments/assets/0476357f-1bec-4b83-b913-6ce3dbe2298c)
![IMG_2543](https://github.com/user-attachments/assets/755de3cf-ca40-4004-a594-6d49fdf830c5)
![IMG_2542](https://github.com/user-attachments/assets/e0a134f6-e12e-4826-a509-4204b7f705bf)
![IMG_2541](https://github.com/user-attachments/assets/1c8a7400-4ce8-4179-ab69-315bc25b4d2b)
![IMG_2540](https://github.com/user-attachments/assets/a9d78435-52cc-4bdf-817c-e06b4b15bd3d)
![IMG_2539](https://github.com/user-attachments/assets/62683662-a63b-4cd0-8a02-e00e239b17f2)
![IMG_2538](https://github.com/user-attachments/assets/b10c75df-f201-4090-a91e-aa2bac91298d)
![IMG_2537](https://github.com/user-attachments/assets/0614e646-060b-422c-ad40-b0d506f09997)
![IMG_2536](https://github.com/user-attachments/assets/6a04ea95-4e85-4d06-b44c-7c1fa96a2fd1)
![IMG_2535](https://github.com/user-attachments/assets/7e0bfdc5-73b9-4c69-b5fa-9b4e59c6a171)
![IMG_2534](https://github.com/user-attachments/assets/f1767944-65ca-4a2a-857a-bbaf3eabce46)
![IMG_2533](https://github.com/user-attachments/assets/a257c4ed-893d-43e6-bb1e-51e722f6eb2f)
![IMG_2532](https://github.com/user-attachments/assets/cde8a9a4-119e-49cb-971a-624324f0efbb)
![IMG_2531](https://github.com/user-attachments/assets/64d75da1-4bb4-4820-ac66-8f20fe1de834)
![IMG_2530](https://github.com/user-attachments/assets/1a6fc0fa-d75d-48bf-94f7-ea0d9289ef47)
![IMG_2529](https://github.com/user-attachments/assets/40e2b675-f59b-4587-8c56-6b2a1c415245)
![IMG_2528](https://github.com/user-attachments/assets/236441db-cfb6-4ce9-82de-84b0b17634c0)
![IMG_2527](https://github.com/user-attachments/assets/73e0551c-48b2-4cbc-b84f-7a8d67540864)


## Testing on Other Browsers

To ensure each page works as it should with the correct font and design, I tested each web page on a few browser. It was already tested on Chrome as that was the primary browser I used while coding, but I also tested it on Microsoft Edge, FireFox, and used Brave due to that browser in particular not being as well known as the usual web browsers we tend to use. There were no changes to the websites layout and all fonts and images appear as should as can be seen in the screenshots shown below.

Edge testing:
![image](https://github.com/user-attachments/assets/6e17e0dc-01e4-47d4-924f-8ea2382fc80f)
![image](https://github.com/user-attachments/assets/669b4d52-5f3d-4ef4-9120-1d98d0f2e05e)
![image](https://github.com/user-attachments/assets/7c98cb72-51ca-4c81-bf06-453dc17d9e20)
![image](https://github.com/user-attachments/assets/4ee945bb-8ed1-4c8a-a110-81c3da32e75f)
![image](https://github.com/user-attachments/assets/3e0d50f6-475a-46ce-a2ca-d519b3786a33)
![image](https://github.com/user-attachments/assets/fca7aa48-da02-4a36-bc86-c54ffcbd9333)
![image](https://github.com/user-attachments/assets/eacd8145-fdc4-4ca1-92d0-5180f6d5ce34)
![image](https://github.com/user-attachments/assets/d947f0ef-f172-4b8e-948e-628c21123894)
![image](https://github.com/user-attachments/assets/f4f29580-40ec-4f23-9026-af82f5efb36c)

FireFox testing:
![image](https://github.com/user-attachments/assets/a3906f74-a465-4c71-a803-28481c08dcd1)
![image](https://github.com/user-attachments/assets/d0ea6625-7665-4459-8ff4-f657e337192c)
![image](https://github.com/user-attachments/assets/b0c5959c-d694-49f4-a76d-aab5904a9aac)
![image](https://github.com/user-attachments/assets/4c2e213d-a027-47dc-927c-20b26fad59dc)
![image](https://github.com/user-attachments/assets/ff160e79-9177-4358-9d10-3a2ed66a7173)
![image](https://github.com/user-attachments/assets/1d43b75a-b861-4707-9023-3c23c88a2d3d)
![image](https://github.com/user-attachments/assets/12f04c29-b127-47e2-88d0-df0e2f5af947)
![image](https://github.com/user-attachments/assets/a3ea256c-ea9f-4ded-afe5-92656bcb5227)
![image](https://github.com/user-attachments/assets/6c13d2b7-f656-4ebf-8657-585919691a35)

Brave testing:
![image](https://github.com/user-attachments/assets/fba6b1ca-3683-4307-81f4-46ce52a21676)
![image](https://github.com/user-attachments/assets/374b0280-b5cc-4925-9027-07856a281626)
![image](https://github.com/user-attachments/assets/f0ff376f-d308-457f-bb78-8e048cd71ceb)
![image](https://github.com/user-attachments/assets/c7a7da73-299f-47de-908c-6a2490892388)
![image](https://github.com/user-attachments/assets/74073021-18a3-489f-a089-b387226591ee)
![image](https://github.com/user-attachments/assets/5e89972a-6d1c-4871-be4e-edda498c3d7d)
![image](https://github.com/user-attachments/assets/0de66064-2031-4e01-8608-d7cdda1451a0)
![image](https://github.com/user-attachments/assets/7f77fbfa-a5ca-4fa0-aac7-b87c60ca7860)
![image](https://github.com/user-attachments/assets/8b6ba4bf-e167-4527-9be3-b2ad0cf8100e)


## Technologies Used

- HTML5 & CSS3
- [Google Fonts](https://fonts.google.com/) (Lexend & Roboto)
- [Bootstrap](https://getbootstrap.com/) (for navbar and cards -- see comments in code)
- [Font Awesome](https://fontawesome.com/) (for icons)
- [Image Colour Picker](https://imagecolorpicker.com/) (to find suitable colours for the website)
- [W3C CSS Validation](https://jigsaw.w3.org/css-validator/) (to validate CSS code)
- [W3C Validator](https://validator.w3.org/) (to validate HTML pages)
- [Stack Overflow](https://stackoverflow.com/questions) for troubleshooting 
- Lighthouse via Dev Tools
- GitHub Pages (for deployment)
- Bing AI image generator (for imagery)
- Wave (Chrome extension)
- Google Chrome, Microsoft Edge, FireFox, Brave (for website testing)
- iPhone 16 and iPad Pro (12.9-inch) (5th generation) (used for testing website on physical devices)

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

Deployed via GitHub Pages: [Sprout&Spark Homepage](https://ctrlaltkismet.github.io/Sprout-and-Spark/index.html)

---

## Future Features

- Calendar view of events  
- Embedded video previews of workshops  
- Parent testimonials  
- Workshop filtering by age/activity

---

## Bugs and Fixes

### Background of generated image taking up too much space in navbar

This was causing the background colour of the navbar to be much bigger than needed; to fix this, I removed the background of the photo using photoshop and resized the image appropriately with the use of dev tools.
![image](https://github.com/user-attachments/assets/a4a5be82-8a78-4c84-a03d-b056e3cb59a7)

---
### Text in navbar too large for smaller screens

On smaller screens, the text in the navbar had forced the background colour to not wrap correctly. This was fixed by ensuring flex-wrap was set to 'wrap' and the displau as flex. I used dev tools again to find an appropriate size for the logo and text on a smaller screen.
![image](https://github.com/user-attachments/assets/97fdc002-67e4-4795-b037-91cd1d730aaa)

---
### Boostrap cards forcing cards to appear on left of screen

Using bootstrap cards, each card automatically defaulted to a vertical position, this was fixed with flex (d-flex g-3) to place a gap between each card.
![image](https://github.com/user-attachments/assets/41185fbc-49e7-4809-9953-0e6f59481b7e)

---
### Search bar placement on smaller screens

I had to look at Stack Overflow for help with this as the Bootstrap search bar wasn't working. I had learned some JavaSript coding which helped to understand how search bars work within a website. I had used Devtools to check if the code was working as seen in the screenshot below. The searchbar is fully functional, however, it requires a live server (or live website connected to a server) to support this, GitHub pages in itself will not allow the searches to be fully functional.
![image](https://github.com/user-attachments/assets/9ed0065b-13c7-407f-b7ee-9d120e86ebf8)

The search bar and mobile needed media queries to adjust the placement of the search bar as well as the initial placement on desktop:
![image](https://github.com/user-attachments/assets/708a9d6b-e68b-4d81-8be8-d29524336536)
![image](https://github.com/user-attachments/assets/a503d8a6-5b5a-4370-9227-ce3a1c2e0e67)
![image](https://github.com/user-attachments/assets/fc4bbeb2-d1db-48f0-8004-43749f4c744e)

Upon attempting to recentre the navigation bar, it would quite freqently overlap my links to the right. 

**Fix:**  
This was resolved entirely with responsive CSS — no changes were needed to the HTML structure.

**What was done:**

- Applied `position: absolute` and `transform: translateX(-50%)` to center the search bar on large screens (≥1400px).
- Introduced multiple media queries to:
  - Reset `position` to `static` for smaller screens (≤1399px).
  - Allow the search bar to flow naturally beneath or between elements as needed.
  - Use `order`, `flex-wrap`, and `justify-content` to manage the visual stacking and spacing of elements.
  - Restrict the `#search-form` width (`max-width: 600px`) to avoid crowding.
  - Center everything using `margin: auto` and `text-align: center` as fallbacks.
- Ensured `flex-grow` and `flex-shrink` rules were used to prevent layout distortion across breakpoints.

**Result:**  
The search form now scales cleanly and repositions itself correctly across all screen sizes, preserving both aesthetic balance and usability.

---
### Navbar on gallery and index page floating off screen when trying to fix floating footer

**Fix:**
Used `z-index: 10` to place it above other elements without forcing it to be fixed or absolute. `Position: relative` to anchor the navbar properly against flow.

---
### White space in cards on gallery which expands when opening each card.

When users clicked the 'more' button on event cards, the additional text expanded, but the card height didn't adjust properly. This caused visible white space under adjacent cards, breaking the layout visually.

**Fix:**
- Removed `position: absolute` from `.event-more-wrapper`.
- Let the extra content expand naturally inside the card.
- Used `max-height` transitions to create a smooth open/close effect (`max-height: 0; overflow:hidden;` by default, then `max-height: 1000px;` when expanded)
---

## Credits

- **Fonts** by [Google Fonts](https://fonts.google.com/)  
- **Images** via Bing AI image creator  
- Workshops inspired by real-world SEN support needs
- Spencer_ci (mentor) for much needed advice, such as resizing the images and reminder to use Lighthouse to test each webpage.


