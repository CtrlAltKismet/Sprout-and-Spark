﻿# Sprout-and-Spark

## Contents

- [UX/UI](#uxui)
- [Features](#features)
- [User Stories](#user-stories)
- [Design Choices](#design-choices)
- [Wireframes](#wireframes)
- [Technologies User](#technologies-used)
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

## Design Choices

### Fonts

As the website boasts inclusivity for SEN children, it is important to choose a font that is readable for children with dyslexia or Irlen's Syndrome. As Open Dyslexia is unavailable on Google Fonts, research suggests Lexend to be the next best font for readability.

- **Lexend** - Primary font, chosen for its accessibility and readability benefits.
- **Roboto** - Backup font for modern, clean support.

### Colour Palette

- Soft, friendly colours chosen to be welcoming and sensory-considerate.
- High contrast for readability, without stimulaton.

### Layout & Components

- Card layout for workshop previews.
- Accesible navigation bar with hover over each link to encourage further readability.
- Expandable/collapsible cards for workshop information.
- Large buttons and touch-friendly elements for mobile and tablet users.

---

## Wireframes

![Index Page Wireframe](https://github.com/user-attachments/assets/8ccdf390-3c81-4018-9e17-418864cd1bf6)
![Gallery Page Wireframe](https://github.com/user-attachments/assets/aee6fdfe-9d69-46ec-9f26-7bb84a0dab34)
![Events Page Wireframe](https://github.com/user-attachments/assets/d88f2683-ee78-4381-a7eb-79d39f04ab11)
![Support Page Wireframe](https://github.com/user-attachments/assets/7cb457fd-7766-4671-a950-f4ef271c61ef)
![Sign Up Page Wireframe](https://github.com/user-attachments/assets/e51854bf-7d56-4885-81ac-6f76d1492079)



## Technologies Used

- HTML5 & CSS3
- [Google Fonts](https://fonts.google.com/) (Lexend & Roboto)
- [Bootstrap](https://getbootstrap.com/) (for navbar and cards -- see comments in code)
- [Font Awesome](https://fontawesome.com/) (for icons)
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
