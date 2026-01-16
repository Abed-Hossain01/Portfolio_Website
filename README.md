# Abed Hossain - Portfolio Website# Abed Hossain - Personal Portfolio Website



A modern, responsive personal portfolio website showcasing my skills, projects, and contact information.A modern, responsive personal portfolio website built with HTML5, CSS3, JavaScript, PHP, and MySQL.



## 🌐 Live Demo## 👤 About



Visit the live site: [Your GitHub Pages URL]This is the professional portfolio website of **Abed Hossain**, a 22-year-old Computer Science and Engineering student at Southeast University, Bangladesh. The website showcases skills, projects, and provides a way to get in touch.



## 🚀 Features## 🚀 Features



- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices

- **Modern UI/UX** - Clean and professional interface with smooth animations- **Smooth Navigation**: Sticky navbar with smooth scrolling and active link highlighting

- **Interactive Sections**:- **Dynamic Sections**:

  - Home - Welcome section with profile  - Home with introduction and call-to-action buttons

  - About - Personal information and background  - About section with personal information and interests

  - Skills - Programming languages and technologies  - Skills showcase with animated progress bars

  - Projects - Showcase of completed projects  - Project portfolio with detailed cards

  - Resume - Downloadable CV  - Resume download section

  - Contact - Functional contact form  - Contact form with backend integration

- **Form Handling**: Secure PHP backend with MySQL database storage

## 🛠️ Built With- **Modern UI**: Clean, professional design with animations and transitions

- **No Frameworks**: Built entirely with vanilla HTML, CSS, and JavaScript

- **HTML5** - Semantic markup

- **CSS3** - Modern styling with CSS Grid and Flexbox## 🛠️ Tech Stack

- **JavaScript** - Interactive features and animations

- **FormSubmit** - Contact form handling (no backend required)### Frontend

- HTML5

## 📁 Project Structure- CSS3 (Modern, responsive design)

- Vanilla JavaScript (ES6+)

```

portfolio/### Backend

├── index.html           # Main HTML file- PHP (Procedural, secure)

├── assets/- MySQL

│   ├── css/

│   │   └── sections/    # Modular CSS files### Environment

│   ├── js/- macOS

│   │   └── script.js    # JavaScript functionality- XAMPP

│   ├── images/          # Images and graphics- VS Code

│   └── cv/              # Resume/CV files

└── README.md            # Project documentation## 📁 Project Structure

```

```

## 🎨 Features Overview/portfolio

├── /assets

### Home Section│   ├── /css

- Eye-catching welcome message with robotic font│   │   └── style.css          # Main stylesheet

- Profile display│   ├── /js

- Quick action buttons (Download CV, Contact Me)│   │   └── script.js          # JavaScript functionality

│   ├── /images               # Image assets

### Projects Section│   └── /cv

- Hover effects on project cards│       └── Abed_Hossain_CV.pdf  # Resume PDF

- Tech stack tags├── /includes

- Project descriptions and details│   ├── header.php            # Header with navigation

│   ├── footer.php            # Footer section

### Contact Section│   └── db.php                # Database connection

- Beautiful gradient background├── /pages

- Functional contact form using FormSubmit│   └── contact.php           # Contact form handler

- Direct email integration├── index.php                 # Main landing page

- Social media links├── database.sql              # Database setup script

└── README.md                 # Project documentation

## 📧 Contact```



- **Email:** abedhossain494@gmail.com## 🔧 Installation & Setup

- **LinkedIn:** [Abed Hossain](https://www.linkedin.com/in/abed-hossain-5875202b6/)

- **GitHub:** [Abed-Hossain01](https://github.com/Abed-Hossain01)### Prerequisites

- XAMPP installed on macOS

## 📝 License- Web browser (Safari, Chrome, Firefox, etc.)



This project is open source and available under the [MIT License](LICENSE).### Step 1: Clone or Copy Files

Place the portfolio folder in your XAMPP htdocs directory:

## 🙏 Acknowledgments```

/Applications/XAMPP/xamppfiles/htdocs/portfolio

- Design inspiration from modern portfolio websites```

- Icons and emojis for visual enhancement

- FormSubmit.co for contact form handling### Step 2: Start XAMPP Services

1. Open XAMPP Control Panel

---2. Start Apache server

3. Start MySQL database

**Built with ❤️ by Abed Hossain**

### Step 3: Create Database
1. Open phpMyAdmin: `http://localhost/phpmyadmin`
2. Click on "SQL" tab
3. Copy and paste the contents of `database.sql`
4. Click "Go" to execute

Alternatively, use the terminal:
```bash
cd /Applications/XAMPP/xamppfiles/htdocs/portfolio
mysql -u root -p < database.sql
```

### Step 4: Configure Database Connection
The database configuration is already set in `includes/db.php`:
- Host: `localhost`
- Username: `root`
- Password: `` (empty by default in XAMPP)
- Database: `portfolio_db`

### Step 5: Add Your Resume
Place your CV PDF file at:
```
/assets/cv/Abed_Hossain_CV.pdf
```

### Step 6: Access the Website
Open your browser and navigate to:
```
http://localhost/portfolio
```

## 📋 Database Schema

### Messages Table
| Column | Type | Description |
|--------|------|-------------|
| id | INT | Auto-increment primary key |
| name | VARCHAR(100) | Sender's name |
| email | VARCHAR(100) | Sender's email |
| message | TEXT | Message content |
| created_at | TIMESTAMP | Submission timestamp |

## 🎨 Customization

### Colors
Edit the CSS variables in `assets/css/style.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --accent-color: #3b82f6;
    /* ... more colors */
}
```

### Content
- Edit sections in `index.php`
- Modify navigation links in `includes/header.php`
- Update footer information in `includes/footer.php`

### Skills
Adjust skill percentages in the skills section of `index.php`:
```html
<div class="skill-progress" style="width: 85%;"></div>
```

## 🔒 Security Features

- Prepared statements for SQL queries (prevents SQL injection)
- Input sanitization and validation
- XSS protection through PHP's built-in functions
- Email validation on both client and server side
- CSRF protection ready (can be enhanced)

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 481px - 768px
- **Mobile**: ≤ 480px

## 🌟 Key Features Explained

### Smooth Scrolling
JavaScript handles smooth scrolling to sections when clicking navigation links.

### Active Link Highlighting
The navbar automatically highlights the current section while scrolling.

### Form Validation
- Client-side validation with JavaScript
- Server-side validation with PHP
- Real-time feedback for form fields

### Mobile Menu
Responsive hamburger menu for mobile devices with smooth animations.

## 🐛 Troubleshooting

### Database Connection Error
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
