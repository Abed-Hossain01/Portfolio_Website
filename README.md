# Abed Hossain - Portfolio Website# Abed Hossain - Portfolio Website



A modern, responsive personal portfolio website showcasing my skills, projects, and contact information.A modern, responsive personal portfolio website showcasing my skills, projects, and contact information.



## 🌐 Live Demo## 🌐 Live Demo



**Visit:** [https://abed-hossain01.github.io/Portfolio_Website/](https://abed-hossain01.github.io/Portfolio_Website/)**Visit:** [https://abed-hossain01.github.io/Portfolio_Website/](https://abed-hossain01.github.io/Portfolio_Website/)



## 👤 About Me## 👤 About Me



I'm **Abed Hossain**, a 22-year-old Computer Science and Engineering student at Southeast University, Bangladesh. This portfolio showcases my skills, projects, and provides a way to connect with me.I'm **Abed Hossain**, a 22-year-old Computer Science and Engineering student at Southeast University, Bangladesh. This portfolio showcases my skills, projects, and provides a way to connect with me.



## ✨ Features

## ✨ Features

- **Responsive Design** - Works perfectly on all devices (desktop, tablet, mobile)

- **Smooth Navigation** - Sticky navbar with smooth scrolling and active section highlighting- **Responsive Design** - Works perfectly on all devices (desktop, tablet, mobile)

- **Interactive Sections**:- **Smooth Navigation** - Sticky navbar with smooth scrolling and active section highlighting

  - Home with introduction and call-to-action buttons- **Interactive Sections**:

  - About section with personal background  - Home with introduction and call-to-action buttons

  - Skills showcase with animated progress bars  - About section with personal background

  - Project portfolio with detailed cards and hover effects  - Skills showcase with animated progress bars

  - Resume download section  - Project portfolio with detailed cards and hover effects

  - Contact form with email integration  - Resume download section

- **Modern UI** - Clean design with smooth animations and transitions  - Contact form with email integration

- **Fast Loading** - Optimized static files for quick page loads- **Modern UI** - Clean design with smooth animations and transitions

- **Fast Loading** - Optimized static files for quick page loads

## 🛠️ Tech Stack

## 🛠️ Tech Stack

- **HTML5** - Semantic markup

- **CSS3** - Modern styling with Flexbox and Grid- **HTML5** - Semantic markup

- **JavaScript** - Vanilla JS for interactivity (no frameworks)- **CSS3** - Modern styling with Flexbox and Grid

- **FormSubmit** - Contact form email delivery- **JavaScript** - Vanilla JS for interactivity (no frameworks)

- **FormSubmit** - Contact form email delivery

## 📁 Project Structure

- Hover effects on project cards│       └── Abed_Hossain_CV.pdf  # Resume PDF

```

portfolio/- Tech stack tags├── /includes

├── index.html              # Main HTML page

├── README.md               # Documentation- Project descriptions and details│   ├── header.php            # Header with navigation

├── .gitignore             # Git ignore file

└── assets/│   ├── footer.php            # Footer section

    ├── css/

    │   └── sections/      # Modular CSS files### Contact Section│   └── db.php                # Database connection

    │       ├── base.css

    │       ├── navigation.css- Beautiful gradient background├── /pages

    │       ├── home.css

    │       ├── about.css- Functional contact form using FormSubmit│   └── contact.php           # Contact form handler

    │       ├── skills.css

    │       ├── projects.css- Direct email integration├── index.php                 # Main landing page

    │       ├── resume.css

    │       ├── contact.css- Social media links├── database.sql              # Database setup script

    │       ├── footer.css

    │       ├── buttons.css└── README.md                 # Project documentation

    │       └── animations.css

    ├── js/## 📧 Contact```

    │   └── script.js       # JavaScript functionality

    ├── images/

    │   └── profile.jpg     # Profile image

    └── cv/- **Email:** abedhossain494@gmail.com## 🔧 Installation & Setup

        └── Abed_Hossain_CV.pdf

```- **LinkedIn:** [Abed Hossain](https://www.linkedin.com/in/abed-hossain-5875202b6/)



## 🎨 Sections Overview- **GitHub:** [Abed-Hossain01](https://github.com/Abed-Hossain01)### Prerequisites



### Home- XAMPP installed on macOS

- Welcome message with animated text

- Profile image## 📝 License- Web browser (Safari, Chrome, Firefox, etc.)

- Call-to-action buttons (Download CV, Contact Me)



### About

- Personal introductionThis project is open source and available under the [MIT License](LICENSE).### Step 1: Clone or Copy Files

- Background and interests

- Education detailsPlace the portfolio folder in your XAMPP htdocs directory:



### Skills## 🙏 Acknowledgments```

- **Programming Languages**: C, C++, Java, Python, Dart

- **Web Technologies**: HTML, CSS, JavaScript, PHP, MySQL/Applications/XAMPP/xamppfiles/htdocs/portfolio

- **Frameworks**: Flutter, Laravel

- **Tools**: Git, GitHub, VS Code- Design inspiration from modern portfolio websites```

- Animated progress bars showing proficiency levels

- Icons and emojis for visual enhancement

### Projects

- Interactive project cards with hover effects- FormSubmit.co for contact form handling### Step 2: Start XAMPP Services

- Technology stack tags

- Project descriptions1. Open XAMPP Control Panel

- Links to live demos and source code

---2. Start Apache server

### Resume

- Downloadable CV in PDF format3. Start MySQL database

- Quick access button

**Built with ❤️ by Abed Hossain**

### Contact

- Functional contact form### Step 3: Create Database

- Email integration via FormSubmit1. Open phpMyAdmin: `http://localhost/phpmyadmin`

- Social media links (LinkedIn, GitHub)2. Click on "SQL" tab

- Direct email: abedhossain494@gmail.com3. Copy and paste the contents of `database.sql`

4. Click "Go" to execute

## 🚀 Local Setup

Alternatively, use the terminal:

### Prerequisites```bash

- A web browser (Chrome, Firefox, Safari, etc.)cd /Applications/XAMPP/xamppfiles/htdocs/portfolio

- Git installed on your machinemysql -u root -p < database.sql

```

### Installation

### Step 4: Configure Database Connection

1. **Clone the repository**The database configuration is already set in `includes/db.php`:

   ```bash- Host: `localhost`

   git clone https://github.com/Abed-Hossain01/Portfolio_Website.git- Username: `root`

   ```- Password: `` (empty by default in XAMPP)

- Database: `portfolio_db`

2. **Navigate to the project**

   ```bash### Step 5: Add Your Resume

   cd Portfolio_WebsitePlace your CV PDF file at:

   ``````

/assets/cv/Abed_Hossain_CV.pdf

3. **Open the website**```

   - Simply open `index.html` in your browser

   - Or use a local server:### Step 6: Access the Website

     ```bashOpen your browser and navigate to:

     # Python 3```

     python3 -m http.server 8000http://localhost/portfolio

     ```

     # Then visit: http://localhost:8000

     ```## 📋 Database Schema



## 🎨 Customization### Messages Table

| Column | Type | Description |

### Updating Content|--------|------|-------------|

1. Edit `index.html` to modify text content| id | INT | Auto-increment primary key |

2. Replace `assets/images/profile.jpg` with your photo| name | VARCHAR(100) | Sender's name |

3. Update `assets/cv/Abed_Hossain_CV.pdf` with your resume| email | VARCHAR(100) | Sender's email |

| message | TEXT | Message content |

### Changing Colors| created_at | TIMESTAMP | Submission timestamp |

Modify the CSS variables in `assets/css/sections/base.css`:

- Primary colors (blues)## 🎨 Customization

- Background colors

- Text colors### Colors

- Accent colorsEdit the CSS variables in `assets/css/style.css`:

```css

### Adding Projects:root {

Add new project cards in the Projects section of `index.html` following the existing structure.    --primary-color: #2563eb;

    --secondary-color: #1e40af;

## 📱 Responsive Design    --accent-color: #3b82f6;

    /* ... more colors */

The website is fully responsive with breakpoints:}

- **Desktop**: > 768px - Full navigation, multi-column layouts```

- **Tablet**: 481px - 768px - Optimized layouts

- **Mobile**: ≤ 480px - Single column, hamburger menu### Content

- Edit sections in `index.php`

## 🌟 Key Features- Modify navigation links in `includes/header.php`

- Update footer information in `includes/footer.php`

### Smooth Scrolling

Click navigation links for smooth scrolling to sections### Skills

Adjust skill percentages in the skills section of `index.php`:

### Active Link Highlighting```html

The navbar automatically highlights the current section while scrolling<div class="skill-progress" style="width: 85%;"></div>

```

### Form Validation

- Client-side validation with JavaScript## 🔒 Security Features

- Email format validation

- Required field checks- Prepared statements for SQL queries (prevents SQL injection)

- Real-time error messages- Input sanitization and validation

- XSS protection through PHP's built-in functions

### Mobile Menu- Email validation on both client and server side

Responsive hamburger menu for mobile devices with smooth animations- CSRF protection ready (can be enhanced)



## 📧 Contact## 📱 Responsive Breakpoints



- **Email**: abedhossain494@gmail.com- **Desktop**: > 768px

- **LinkedIn**: [Abed Hossain](https://www.linkedin.com/in/abed-hossain-5875202b6/)- **Tablet**: 481px - 768px

- **GitHub**: [Abed-Hossain01](https://github.com/Abed-Hossain01)- **Mobile**: ≤ 480px



## 📄 License## 🌟 Key Features Explained



This project is open source and available for personal use. Feel free to fork and customize for your own portfolio.### Smooth Scrolling

JavaScript handles smooth scrolling to sections when clicking navigation links.

## 👨‍💻 Developer

### Active Link Highlighting

**Abed Hossain**The navbar automatically highlights the current section while scrolling.

- Age: 22

- University: Southeast University, Bangladesh### Form Validation

- Department: Computer Science and Engineering- Client-side validation with JavaScript

- Location: Tejgaon, Dhaka- Server-side validation with PHP

- Hometown: Lakshmipur, Chittagong- Real-time feedback for form fields

- Specialization: Flutter App Development | Full-Stack Web Development

### Mobile Menu

---Responsive hamburger menu for mobile devices with smooth animations.



Built with care using HTML5, CSS3, and JavaScript## 🐛 Troubleshooting



*Last Updated: January 2026*### Database Connection Error

- Ensure MySQL is running in XAMPP
- Check database credentials in `includes/db.php`
- Verify database exists: `portfolio_db`

### Form Not Submitting
- Check Apache is running
- Verify PHP is enabled in XAMPP
- Check file permissions

### CSS/JS Not Loading
- Check file paths are correct
- Clear browser cache
- Ensure files exist in correct directories

## 📧 Contact Form Testing

To test the contact form:
1. Navigate to the Contact section
2. Fill in all fields
3. Click "Send Message"
4. Check phpMyAdmin to verify data was stored

View submitted messages in phpMyAdmin:
```sql
SELECT * FROM messages ORDER BY created_at DESC;
```

## 🚀 Future Enhancements

Potential improvements:
- Email notifications when contact form is submitted
- Admin panel to view messages
- Project detail pages
- Blog section
- Dark mode toggle
- Multi-language support (English, German, Bangla)

## 📄 License

This is a personal portfolio project. Feel free to use it as inspiration for your own portfolio.

## 👨‍💻 Developer

**Abed Hossain**
- Age: 22
- University: Southeast University, Bangladesh
- Location: Tejgaon, Dhaka
- Origin: Lakshmipur, Chittagong
- Profession: CSE Student | Flutter App Developer | Full-Stack Web Developer

---

**Built with ❤️ using HTML, CSS, JavaScript, PHP, and MySQL**

*Last Updated: January 2026*
