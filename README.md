# LearnHub – Online Learning Management Platform

## Project Overview

LearnHub is a responsive web-based online learning management platform designed to provide accessible, high-quality educational opportunities. It allows learners to browse and enroll in courses, access interactive video lessons, join collaborative discussion forums, interact with instructors, earn certificates of completion, and track their learning progress through an intuitive and modern interface.

## Key Features

- **Course Catalog & Listings:** Browse and explore a variety of programming and tech courses.
- **Course Enrollment & Payment:** Seamless enrollment workflow with course pricing and payment interface.
- **Interactive Video Lessons:** Learn through structured video lectures with an embedded player.
- **Discussion Forums:** Support collaborative learning, student discussions, and peer Q&A.
- **Instructor Interaction:** Direct access and engagement with course instructors.
- **Certification of Completion:** Generate and download certificates upon course completion.
- **Progress Tracking & Reviews:** Monitor course progress and read/submit student reviews.
- **Responsive Design:** Optimized layout for desktops, tablets, and mobile devices.

## Technology Stack

### Languages
- **HTML5** – Semantic markup
- **CSS3** – Custom styling and layout
- **JavaScript (ES6)** – Dynamic client-side functionality
- **SASS** – Syntactically Awesome Style Sheets

### Frameworks & Libraries
- **Bootstrap 5** – Responsive grid and component framework
- **jQuery** – DOM manipulation and event handling
- **ScrollReveal.js** – Scroll-triggered animations
- **Swiper.js** – Responsive touch-enabled sliders for courses and testimonials

### Design & Assets
- **Figma** – UI/UX design and wireframing
- **Font Awesome 6** – Vector icons
- **Bootstrap Icons** – Supplemental icon set

### Version Control
- **Git**
- **GitHub**

## Project Structure

```text
learning_app/
│
├── assets/
│   ├── css/              # Compiled stylesheets
│   ├── images/           # Site assets, category icons, logos
│   │   ├── collaborators/
│   │   ├── home_images/
│   │   ├── icons/
│   │   ├── instructor/
│   │   └── logo/         # LearnHub brand logos & favicon
│   ├── js/               # Application logic (data, lectures, home)
│   ├── pic/              # Course banners and previews
│   ├── scss/             # SASS source stylesheets
│   └── svg/              # UI vector icons
│
├── view/                 # Application views & dashboards
│   ├── certification.html# Certificate generator & download
│   ├── dashboard.html    # Student dashboard
│   ├── detail.html       # Course detail view
│   ├── discussion.html   # Discussion forum
│   ├── lecture.html      # Course lecture & video player
│   ├── login.html        # User login portal
│   ├── payment.html      # Checkout & payment page
│   ├── review.html       # Student course reviews
│   └── signup.html       # User registration
│
├── about.html            # About Us page
├── contact.html          # Contact page
├── index.html            # Homepage
├── package.json          # Node dependencies & metadata
├── package-lock.json     # Lockfile
└── README.md             # Project documentation
```

## Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/DevGeeksMyanmar/learning_app.git
cd learning_app
```

### 2. Optional: Install Dependencies
To compile or modify SASS stylesheets:
```bash
npm install
```

### 3. Run with Live Server in Visual Studio Code
1. Open the project folder in **Visual Studio Code**:
   ```bash
   code .
   ```
2. Install the **Live Server** extension (by Ritwick Dey) from the VS Code Extensions Marketplace (`Ctrl+Shift+X` and search for `Live Server`).
3. Right-click on `index.html` in the Explorer pane and click **"Open with Live Server"** (or click the **"Go Live"** button in the VS Code status bar at the bottom right).
4. The application will launch in your default web browser at `http://127.0.0.1:5500/index.html`.

---

## Original Contributors & Credits
## Developed By

**Seeja K**

Computer Science and Engineering

### Project Ownership

LearnHub – Online Learning Management Platform

Designed and developed by Seeja K, featuring a responsive learning interface, course catalog, video lessons, user registration, enrollment, discussion forums, and learning progress tracking.

### Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Bootstrap 5
- SASS
- jQuery
- Swiper.js
- ScrollReveal.js

## License Attribution

- This customized project is based on the open-source **Dev Geeks Learning Web Application** by [DevGeeksMyanmar](https://github.com/DevGeeksMyanmar/learning_app).
- Preserved under the original license terms (see [LICENSE](LICENSE)).