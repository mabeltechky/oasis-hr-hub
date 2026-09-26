# Oasis HR Hub

## Overview

Oasis HR Hub is a responsive HR support platform designed for small businesses that need practical people-management support but may not have a dedicated in-house HR team.

The platform brings essential HR information and employee processes into one clear and accessible interface. Business owners and managers can explore support for recruitment, onboarding, policies and compliance, training and employee development, compare HR service packages, and find ways to contact the HR team. Employees are provided with a dedicated Employee Hub where they can access onboarding and other essential workplace actions.

This project is the first front-end version of a wider HR platform concept. It has been developed using HTML, CSS and Bootstrap, with a focus on responsive design, accessibility, intuitive navigation and user-centred design.

The current version demonstrates the user journeys and interface required for the platform without claiming functionality that requires a back-end or database. Features such as persistent employee records, authentication, document management and attendance tracking are therefore reserved for future development.

## Project Goals

The goal of Oasis HR Hub is to create a responsive and accessible front-end HR platform that balances the needs of small businesses with the needs of the employees who use their HR processes.

### Business Goals

The business goals are to:

- Provide practical HR support to small businesses that may not have a dedicated HR team.
- Clearly communicate the HR services, packages and pricing available.
- Build trust by providing clear information about the service and the HR team.
- Provide straightforward contact routes for prospective clients.
- Support customer acquisition and future revenue opportunities.
- Establish a foundation for a broader HR management platform.

### User Goals

Small-business owners and managers need to:

- Quickly understand what HR support is available.
- Find relevant information about recruitment, onboarding, policies, compliance and employee development.
- Compare available HR packages and pricing.
- Access clear contact information when further support is required.
- Provide employees with structured HR processes.

Employees need to:

- Access important HR actions from one clear location.
- Complete onboarding through a simple and structured process.
- Request leave or report an absence through clear forms.
- Receive clear feedback after submitting information.
- Use the platform comfortably across mobile, tablet and desktop devices.

### Project Objectives

To support these business and user goals, the project aims to deliver a clear, responsive and accessible interface with intuitive navigation, structured content and consistent user journeys.

The current project focuses on front-end functionality. Features requiring persistent data storage, authentication or back-end processing are reserved for future development.

## User Experience (UX)

The UX design of Oasis HR Hub was guided by the needs of two main user groups: small-business owners or managers seeking HR support, and employees who need to complete HR-related actions.

Understanding these different needs helped determine the content, navigation, features and user journeys included in the platform.

### Target Audience

The primary audience is small-business owners and managers who employ staff but may not have access to a dedicated internal HR department. They need practical HR information presented clearly, with straightforward routes to services, pricing and further support.

The secondary audience is employees who need a simple way to access essential HR processes such as onboarding, requesting leave and reporting an absence.

### User Personas

Two representative personas were developed to keep the needs of these audiences at the centre of the design process.

#### Sarah – Small-Business Owner/Manager

Sarah manages a small independent business with approximately eight employees. Without an internal HR department, she is responsible for recruitment, onboarding and other people-related responsibilities alongside the day-to-day running of the business.

**Goals:**
- Understand what HR support is available.
- Find practical guidance for key people processes.
- Compare HR service packages and pricing.
- Provide employees with a more organised HR experience.
- Contact an HR professional when additional support is required.

**Pain points:**
- Limited time to manage HR alongside other business responsibilities.
- HR information can feel complex or difficult to navigate.
- Inconsistent processes can make managing employees more time-consuming.

#### Daniel – New Employee

Daniel has recently accepted a role with a small business and needs to complete the required onboarding process before starting work.

**Goals:**
- Understand what information he needs to provide.
- Complete onboarding through a clear, structured form.
- Access employee actions without searching through unrelated business information.
- Receive clear confirmation after submitting a form.
- Use the platform easily from different devices.

**Pain points:**
- Long or poorly organised forms can be confusing.
- Unclear navigation can make HR processes difficult to find.
- Lack of feedback after submitting information can leave him unsure whether an action was completed.

### Five Planes of UX Design

The Five Planes of UX Design — Strategy, Scope, Structure, Skeleton and Surface — were used to guide the development of Oasis HR Hub from the initial idea through to the visual design.

Rather than selecting features or Bootstrap components first, decisions were based on the needs of the target users and the purpose of the platform. Each plane therefore builds on the decisions made in the previous stage.

#### Strategy

The Strategy Plane established the purpose of Oasis HR Hub and the needs of its users.

The key challenge identified was that small-business owners may need support with essential people processes without having access to a dedicated HR department. At the same time, employees need straightforward ways to complete HR-related actions.

The strategy therefore focused on creating a platform that could:

- Make essential HR support easier for small businesses to understand and access.
- Provide clear routes to HR services, pricing and professional support.
- Give employees a dedicated area for essential HR actions.
- Keep the experience straightforward and accessible across different devices.

The business goals, user goals and personas described above formed the basis for deciding what should be included in the first version of the platform.

#### Scope

The Scope Plane translated the needs identified during Strategy into the content and functionality required for the first version of Oasis HR Hub.

The aim was to create a useful front-end experience for both sides of the platform: business owners and managers seeking HR support, and employees completing essential HR processes. Features were therefore selected based on the user goals rather than simply to demonstrate particular technologies.

##### Features Included in the Current Scope

The first version of Oasis HR Hub includes:

- **HR Services** – information about Recruitment Support, Employee Onboarding, Policies & Compliance, and Training & Employee Development.
- **HR Packages and Pricing** – clear service options that allow prospective clients to compare available packages before making contact.
- **Employee Hub** – a dedicated area where employees can access onboarding, request leave and report an absence.
- **Employee Onboarding Form** – a structured form covering personal details, employment information, right-to-work information and emergency contact details.
- **Leave Request Form** – a front-end form allowing employees to provide their name, leave type and requested leave dates.
- **Absence Reporting Form** – a front-end form allowing employees to report an absence, provide the reason and indicate an expected return date where applicable.
- **Submission Confirmation** – a shared confirmation page that provides clear feedback after a form is submitted.
- **Frequently Asked Questions** – common HR questions presented in an accordion to allow users to find information without overcrowding the page.
- **Meet the Team** – HR team profiles presented in a carousel, allowing users to learn more about the people behind the service.
- **Contact and Business Information** – clear contact details, social links and business availability to support further enquiries.

The project therefore contains **three employee-facing forms**: Employee Onboarding, Leave Request and Absence Reporting. These forms demonstrate the intended user journeys but do not currently store or process submitted information through a database.

##### Future Scope

The wider Oasis HR Hub concept could develop beyond the current front-end implementation to include:

- User accounts and authentication.
- Persistent employee records and database storage.
- Document upload and management.
- Attendance and clock-in functionality.
- Leave balances and approval workflows.
- Training progress tracking.
- Employer-specific policy acknowledgement.
- Automated reminders, including right-to-work or visa-expiry reminders.

These features were intentionally excluded from the current version because they require back-end functionality and persistent data management. Keeping them within the future scope allows the first release to remain focused on delivering a complete, responsive and accessible front-end experience.

##### User Stories and MoSCoW Prioritisation

User stories were created to translate the requirements identified during the Strategy and Scope Planes into specific development tasks. Each story was written from the user's perspective and supported by developer tasks and acceptance criteria to provide a clear definition of what needed to be built and how successful implementation could be assessed.

The stories were prioritised using the **MoSCoW method**:

- **Must Have** – essential to the core user journeys and required for the first version of the platform.
- **Should Have** – valuable to the user experience but not essential to completing the primary journeys.
- **Could Have** – enhances the experience but can be delivered after the core requirements.
- **Won't Have (this release)** – functionality intentionally reserved for future development.

| ID | User Story | Priority |
| --- | --- | --- |
| US01 | Understand the HR Platform | Must Have |
| US02 | Understand Available HR Services | Must Have |
| US03 | Compare HR Packages and Pricing | Must Have |
| US04 | Navigate Consistently Across the Platform | Must Have |
| US05 | Access Employee Actions from the Employee Hub | Must Have |
| US06 | Complete Employee Onboarding | Must Have |
| US07 | Request Leave | Must Have |
| US08 | Report Absence | Must Have |
| US09 | Receive Submission Confirmation | Must Have |
| US10 | Find Answers to Common HR Questions | Should Have |
| US11 | Learn About the HR Team | Could Have |

The first nine stories were classified as **Must Have** because together they create the core journeys for business users and employees. The FAQ was classified as **Should Have**, as it improves access to common HR information without being required to complete a primary task. Meet the Team was classified as **Could Have**, as it supports trust and transparency but does not prevent users from accessing HR services or completing employee actions.

##### GitHub Project Board

The user stories were created as GitHub Issues and added to a GitHub Project board to support development planning and progress tracking.

The board uses **Todo**, **In Progress** and **Done** to show the development status of each story, while MoSCoW labels make the relative priority of each requirement visible.

![Oasis HR Hub GitHub Project board showing user stories and MoSCoW prioritisation](assets/images/documentation/user-stories-board.png)

#### Structure

The Structure Plane focused on organising the content and features identified during Scope into clear user journeys. The information architecture was designed to keep navigation simple while separating business-focused information from employee-focused actions.

Oasis HR Hub consists of six HTML pages:

| Page | Purpose |
| --- | --- |
| `index.html` | Introduces Oasis HR Hub and contains the main business-facing content, including services, pricing and contact information. |
| `employee-hub.html` | Provides a central location for employees to access onboarding, leave requests and absence reporting. |
| `onboarding.html` | Provides the full employee onboarding journey through a structured form. |
| `faq.html` | Provides answers to common HR and workplace questions. |
| `team.html` | Introduces the HR professionals behind Oasis HR Hub. |
| `success.html` | Provides confirmation after a user submits one of the front-end forms. |

##### Navigation Structure

A consistent navigation system was planned across the website:

**Home | Services | Employee Hub | Meet the Team | FAQ | Contact**

Services and Contact are sections of the homepage rather than separate pages. This keeps related business information together and allows users to move directly to the relevant content without introducing unnecessary pages.

Employee actions are grouped within the Employee Hub. From this central area, an employee can:

- Start the onboarding process.
- Request leave through a modal form.
- Report an absence through a modal form.

The more detailed onboarding process uses its own page because it requires substantially more information than the shorter leave and absence forms.

##### Key User Journeys

The structure supports different journeys depending on the user's goal.

**Business owner/manager:**

`Home → Services → Pricing → Contact`

This journey allows a prospective client to understand the platform, explore the support available, compare service options and then make contact.

**New employee:**

`Employee Hub → Start Onboarding → Complete Onboarding Form → Submission Confirmation`

This provides a focused route through the onboarding process without requiring the employee to navigate through unrelated business content.

**Existing employee:**

`Employee Hub → Request Leave / Report Absence → Submission Confirmation`

Keeping these actions together within the Employee Hub provides employees with a clear starting point for common HR tasks.

#### Skeleton

The Skeleton Plane translated the information architecture into page layouts and established where key content, navigation, forms and interactive elements would appear before development began.

Low-fidelity wireframes were created in Balsamiq for mobile, tablet and desktop layouts. Designing across different screen sizes at this stage helped establish how content should reorganise responsively before Bootstrap was used to implement the layouts.

##### Wireframes

The wireframes were developed from the user stories and planned user journeys rather than around specific Bootstrap components. This ensured that the required user experience determined the layout, while the framework would later be used to implement that layout.

[View the complete Oasis HR Hub wireframes](https://balsamiq.cloud/slnwkct/pvlb8jl)

Key layout decisions included:

- **Homepage** – content follows a natural journey from the introduction and primary onboarding call-to-action through services, pricing and contact information.
- **Services** – service information is presented as clearly separated content areas that can reorganise across different screen sizes.
- **Pricing** – packages are positioned for easy comparison while remaining readable when stacked on smaller devices.
- **Employee Hub** – onboarding, leave requests and absence reporting are grouped together to give employees one clear starting point for HR actions.
- **Onboarding** – the longer form is divided into logical sections to reduce cognitive load and make the information easier to complete.
- **FAQ** – questions use a single-column expandable structure to keep a potentially large amount of information manageable.
- **Meet the Team** – profiles are presented one at a time within a carousel to avoid overcrowding the page while still allowing users to browse the team.
- **Responsive forms** – related fields can appear alongside each other where sufficient space is available and stack vertically on smaller screens.

The wireframes provided the visual blueprint for development while leaving visual styling such as colour, typography and imagery to the Surface Plane.

#### Surface

The Surface Plane established the visual identity of Oasis HR Hub. The aim was to create an interface that feels professional and trustworthy while remaining warm, approachable and people-focused rather than overly corporate.

##### Visual Direction

The visual direction was inspired by a warm interior reference image featuring natural neutral tones, dark wood, greenery and terracotta accents. This provided the starting point for the colour palette and helped shape the overall character of the interface.

Colours from the reference were explored using an online image colour picker and then refined during development. The final choices were not based on appearance alone; readability, contrast, consistency and the intended use of each colour within the interface were also considered.

##### Colour Palette

The final palette combines warm neutrals with natural and earthy accent colours:

| Colour | Hex | Intended Use |
| --- | --- | --- |
| Deep Brown | `#3D1F14` | Primary headings and strong visual elements |
| Fresh Green | `#25D366` | Secondary brand colour and selected accents |
| Light Cream | `#FFF9F0` | Main page background |
| Warm Greige | `#CDC0B6` | Navigation and neutral interface areas |
| Terracotta | `#BF5E39` | Accent colour |

The palette was deliberately kept small to support visual consistency throughout the website. Deep brown provides a strong contrast against the light cream background, while the greige and natural accent colours maintain the warm visual direction established by the original inspiration.

##### Visual Direction

The visual direction for Oasis HR Hub was inspired by a warm interior image by **curaits**, sourced from Unsplash. The image combines warm neutral tones, natural wood, dark structural details, greenery and subtle terracotta/orange accents. These elements reflected the warm, professional and approachable character I wanted the HR platform to communicate.

Rather than reproducing the interior design itself, the image was used as a visual reference for developing the website's colour palette. Colours were sampled from the image using an online colour picker and were then refined during development based on their intended use, readability and contrast.

![Interior image used as colour palette inspiration for Oasis HR Hub](assets/images/documentation/colour-palette-inspiration.jpg)

[View the original inspiration image on Unsplash](https://unsplash.com/photos/living-room-with-sofa-and-partition-p_xTs-dajHk)

##### Colour Palette

The final palette combines warm neutrals with natural and earthy accent colours:

| Colour | Hex | Intended Use |
| --- | --- | --- |
| Deep Brown | `#3D1F14` | Primary headings and strong visual elements |
| Fresh Green | `#25D366` | Secondary brand colour and selected accents |
| Light Cream | `#FFF9F0` | Main page background |
| Warm Greige | `#CDC0B6` | Navigation and neutral interface areas |
| Terracotta | `#BF5E39` | Accent colour |

The palette was deliberately kept small to support visual consistency throughout the website. Deep brown provides a strong contrast against the light cream background, while the greige and natural accent colours maintain the warm visual direction established by the original inspiration.

##### Accessibility and Colour Contrast

Accessibility was considered alongside the visual design when deciding how colours would be used throughout the interface.

The WebAIM Contrast Checker was used during development to test foreground and background colour combinations. Testing helped distinguish between colours that worked well as part of the overall brand palette and combinations that were appropriate for readable text.

For example, the primary deep brown (`#3D1F14`) against the light cream background (`#FFF9F0`) achieved a contrast ratio of **14.28:1**, providing strong contrast for headings and other important text.

Some colour combinations explored during development did not provide sufficient contrast for normal-sized text. Rather than assuming that every colour in the palette could be used interchangeably, the results were used to guide where particular colours could be applied.

Navigation interaction was also considered during this process. An underline was used on hover rather than relying solely on a subtle colour change. This provides an additional visual indication that the navigation links are interactive without depending on colour alone.

![WebAIM contrast test showing deep brown against the light cream background](assets/images/documentation/contrast-brown-cream.jpg)

![WebAIM contrast test showing deep brown against the warm greige background](assets/images/documentation/contrast-brown-greige.jpg)

[Check colour contrast using WebAIM](https://webaim.org/resources/contrastchecker/)

##### Typography

**Inter** was selected as the primary typeface for Oasis HR Hub and is used consistently throughout the website.

The font was chosen for its clean and modern appearance and its readability across different screen sizes. Using a single font family also helps maintain visual consistency while different font weights create a clear hierarchy between headings and body content.

The typography uses:

- **400 (Regular)** for body text and general content.
- **600 (Semi-Bold)** for smaller headings and elements requiring additional emphasis.
- **700 (Bold)** for primary and secondary headings.

Inter is imported from [Google Fonts](https://fonts.google.com/specimen/Inter) and includes fallback to the generic `sans-serif` font family if the web font cannot be loaded.

##### Logo and Brand Identity

A custom logo was developed for **Oasis HR Hub** to create a recognisable and consistent visual identity across the platform.

The logo uses a circular emblem incorporating the letters **H** and **R**, directly representing the Human Resources focus of the platform. Human and botanical elements are incorporated into the design to reflect the wider themes of people, support, development and growth.

The colours used within the logo complement the Oasis HR Hub colour palette, helping to maintain consistency between the brand identity and the wider website design. The circular format also creates a compact and recognisable brand mark that works effectively within the navigation area.

##### Favicon

A favicon was included to provide a recognisable Oasis HR Hub identifier within browser tabs and supported device shortcuts.

The Oasis HR Hub brand image was used to create the favicon, helping to maintain visual consistency between the website and its browser identity.

[Favicon.io](https://favicon.io/) was used to generate three favicon sizes:

- `favicon-16x16.png` – for standard browser tabs.
- `favicon-32x32.png` – for higher-resolution browser displays.
- `apple-touch-icon.png` – for supported Apple devices and shortcuts.

The appropriate favicon files are linked within the `<head>` section of the website so that browsers and devices can select the suitable version.

##### Imagery

Imagery within Oasis HR Hub was used selectively so that it supports the purpose of the platform without distracting from the HR information and employee processes.

The main photographic imagery appears within the **Meet the Team** section, where professional portrait photographs are used to represent members of the HR team. Images with similar framing, lighting and professional presentation were selected to create a consistent and approachable appearance across the profiles.

The team photographs are presented within a Bootstrap carousel. This allows users to browse individual team members without displaying all profiles simultaneously and overcrowding the page. Manual previous and next controls are also provided so that users can return to a profile if they need more time to read its information.

Alternative text is provided for meaningful images to support users who rely on assistive technologies.

All team photographs were sourced from **Pexels**:

- [Photo by Kampus Production on Pexels](https://www.pexels.com/photo/woman-in-blue-long-sleeve-shirt-sitting-on-chair-8171170/)
- [Photo by Marcos Felipe on Pexels](https://www.pexels.com/photo/woman-in-black-dress-and-white-blazer-smiling-13331367/)
- [Photo by Joel Santos on Pexels](https://www.pexels.com/photo/smiling-woman-holding-chin-15780878/)
- [Photo by Ernest Flowers on Pexels](https://www.pexels.com/photo/professional-headshot-of-a-smiling-man-38677835/)
- [Photo by Tran Nhu Tuan on Pexels](https://www.pexels.com/photo/professional-woman-smiling-in-blue-business-suit-29995644/)

## Design

The visual and layout decisions for Oasis HR Hub were developed from the UX planning described above. Wireframes were created before development to provide a visual reference for page structure, content hierarchy and responsive behaviour.

### Wireframes

Low-fidelity wireframes were created using **Balsamiq** for mobile, tablet and desktop screen sizes.

Creating the wireframes before coding made it possible to explore how the planned content and user journeys would translate into page layouts before implementing them with HTML, CSS and Bootstrap.

The wireframes cover the key areas of the platform and demonstrate how layouts adapt across different viewport sizes.

[View the complete Oasis HR Hub wireframes in Balsamiq](https://balsamiq.cloud/slnwkct/pvlb8jl)

## Features

Oasis HR Hub includes a range of responsive features designed around the needs identified during the UX planning process. Each feature supports a specific user journey or business requirement rather than being included solely for visual or technical demonstration.

### Navigation Bar

A responsive navigation bar is provided across the platform to give users consistent access to the main areas of Oasis HR Hub.

The navigation includes:

- Home
- Services
- Employee Hub
- Meet the Team
- FAQ
- Contact

The Oasis HR Hub logo is positioned on the left as the primary brand identifier, while the navigation links are positioned on the right on larger screens.

On smaller screens, the navigation collapses into a Bootstrap hamburger menu to prevent the links from overcrowding the available space.

Services and Contact link directly to sections of the homepage, while Employee Hub, Meet the Team and FAQ lead to dedicated pages.

An underline appears when users hover over navigation links, providing an additional visual indication of interactivity rather than relying solely on a colour change.