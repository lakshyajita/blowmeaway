<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blow Me Away</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        /* Smooth Scrolling */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <nav class="navbar">
        <div class="logo">
            <a href="#home">Blow Me Away</a>
        </div>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#doctors">Doctors</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#appointment">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="overlay"></div>
        <div class="hero-content">
            <h1>Welcome to Blow Me Away</h1>
            <p>Your beauty, our passion.</p>
            <a href="#appointment" class="btn">Book an Appointment</a>
        </div>
    </section>

    <!-- Doctors Section -->
    <section id="doctors" class="doctors">
        <h2>Skin Surgeon Doctor</h2>
        <div class="doctor-list">
            <div class="doctor">
                <img src="https://img.freepik.com/premium-photo/indian-doctor-wearing-white-coat-with-stethoscope_85574-3676.jpg?w=2000" alt="Doctor 1">
                <h3>Prof. Dr. Shipra Maharana</h3>
                <p>Shipra Maharana is a Dermatologist in Bhawanipatna. She has been practicing medicine for over 18 years.</p>
            </div>  
            <div class="doctor">
                <img src="https://thumbs.dreamstime.com/z/traditional-indian-female-doctor-working-her-desk-woman-79590386.jpg" alt="Doctor 2">
                <h3>Dr. Shakti Pradhan</h3>
                <p> Shakti Pradhan is a Dermatologist in Bhubaneswar. She has been practicing medicine for over 14 years.</p>
            </div>
            <div class="doctor">
                <img src="https://c8.alamy.com/comp/E0120B/female-doctor-using-tablet-computer-E0120B.jpg" alt="Doctor 3">
                <h3>Dr. Arpita Gupta</h3>
                <p>Dr. Arpita Gupta is highly rated in 30 conditions and has been practicing medicine for 14 years.</p>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="services-container">
            <div class="service">
                <img src="https://t3.ftcdn.net/jpg/01/83/61/50/360_F_183615058_PQQHofmIq2EnOM277vxfUJ6aZTRIe1Pu.jpg" alt="Eyebrow Shaping">
                <h3>Eyebrow Shaping & Tinting</h3>
                <p>Enhance brows with precise shaping and long-lasting tint for definition.</p>
            </div>
            <div class="service">
                <img src="https://w7.pngwing.com/pngs/212/709/png-transparent-beauty-logo-face-care-logo.png" alt="Facial Treatments">
                <h3>Facial Treatments</h3>
                <p>Revitalize your skin with our refreshing and nourishing facial treatments.</p>
            </div>
            <div class="service">
                <img src="https://t4.ftcdn.net/jpg/01/76/12/05/360_F_176120504_6QvTPWB0kCwqfXhWnoDXdCDElPRZ2BSz.jpg" alt="Haircut">
                <h3>Haircut & Styling</h3>
                <p>Trendy haircuts and styling for a fresh, confident new look!</p>
            </div>
            <div class="service">
                <img src="https://www.shutterstock.com/image-vector/ipl-laser-hair-removal-verctor-260nw-2145187339.jpg" alt="Hair Removal">
                <h3>Hair Removal</h3>
                <p>Smooth, painless hair removal for silky, flawless skin every time!</p>
            </div>
        </div>
    </section>

    <!-- Appointment Section (Unchanged) -->
    <section id="appointment" class="contact">
        <h2>Let's not wait for the <span>"Perfect Look"</span></h2>
        <p>Book An Appointment Now!</p>
        
        <form class="contact-form" action="https://submit-form.com/a3Lyar1ru" method="POST">
            <div class="form-group">
                <label><i class="fas fa-user"></i> Name*</label>
                <input type="text" name="name" placeholder="Your Name" required>
            </div>
            <div class="form-group">
                <label><i class="fas fa-venus-mars"></i> Gender*</label>
                <select name="gender" required>
                    <option value="" disabled selected>Select Gender</option>
                    <option>Male</option>
                    <option>Female</option>
                    <option>Other</option>
                </select>
            </div>
            <div class="form-group">
                <label><i class="fas fa-phone"></i> Contact*</label>
                <input type="tel" name="contact" placeholder="Your Contact" required>
            </div>
            <div class="form-group">
                <label><i class="fas fa-cut"></i> Service Type</label>
                <input type="text" name="service_type" placeholder="Service Type">
            </div>
            <div class="form-group">
                <label><i class="fas fa-envelope"></i> Email Id</label>
                <input type="email" name="email" placeholder="Your Email">
            </div>
            <div class="form-group">
                <label><i class="fas fa-calendar"></i> Preferred Date*</label>
                <input type="date" name="preferred_date" required>
            </div>
            <div class="form-group">
                <label><i class="fas fa-map-marker-alt"></i> City*</label>
                <select name="city" required>
                    <option value="" disabled selected>Select City</option>
                    <option>Delhi</option>
                    <option>Bhubaneswar</option>
                    <option>Bhawanipatna</option>
                </select>
            </div>
            <div class="form-group">
                <label> Location*</label>
                <input type="text" name="location" placeholder="Your Location" required>
            </div>
            <div class="form-group">
                <label><i class="fas fa-clock"></i> Preferred Time*</label>
                <select name="preferred_time" required>
                    <option value="" disabled selected>Select Time</option>
                    <option>AM</option>
                    <option>PM</option>
                </select>
            </div>
            
            <button type="submit" class="btn">Submit</button>
        </form>
    </section>

</body>
</html>


/* General Styles */
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background-color: #ffc8dd;
    color: #333;
}

/* Navigation Bar */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgba(255, 255, 255, 0.9);
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 1000;
    padding: 10px 15px; /* Reduced padding */
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}

/* Salon Name (Logo) */
.logo a {
    font-size: 22px;
    font-weight: bold;
    text-decoration: none;
    color: #ffafcc;
    font-family: 'Poppins', sans-serif;
    transition: 0.3s ease-in-out;
}
.logo a:hover {
    color: #a2d2ff;
}

/* Navigation Links */
.nav-links {
    list-style: none;
    display: flex;
    flex-wrap: wrap; /* Ensures wrapping instead of overflow */
    gap: 10px; /* Reduced gap to fit items */
    padding: 0;
    margin: 0;
    overflow-x: auto; /* Scrolls if items don't fit */
}

.nav-links li {
    display: inline-block;
}

.nav-links li a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
    padding: 8px 10px; /* Reduced padding */
    transition: 0.3s ease-in-out;
    white-space: nowrap; /* Prevents text wrapping */
}

.nav-links li a:hover {
    background: #ffafcc;
    border-radius: 5px;
    color: white;
}

/* Responsive Fix */
@media (max-width: 1024px) {
    .nav-links {
        font-size: 14px;
    }
}
@media (max-width: 850px) {
    .navbar {
        flex-direction: column;
        text-align: center;
    }
    .nav-links {
        flex-direction: column;
        align-items: center;
        gap: 5px;
    }
}

/* Hero Section */
.hero {
    height: 90vh;
    background: url('https://i.ibb.co/GwVJ4qM/head-img.jpg') no-repeat center center/cover;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    position: relative;
    color: white;
}
.hero .overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.4);
}
.hero-content {
    position: relative;
    z-index: 1;
}
.hero .btn {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 25px;
    background: #ffafcc;
    color: white;
    border-radius: 25px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s ease;
}
.hero .btn:hover {
    background: #ff79a6;
}

/* Doctors Section */
.doctors {
    text-align: center;
    padding: 60px 20px;
    background: #ffafcc;
}
.doctors h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}
.doctor-list {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
}
.doctor {
    background: white;
    padding: 20px;
    border-radius: 15px;
    width: 250px;
    text-align: center;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    transition: 0.3s ease;
}
.doctor:hover {
    transform: scale(1.05);
}
.doctor img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    object-fit: cover;
}
.doctor h3 {
    margin-top: 10px;
    font-size: 1.2rem;
    color: #333;
}
.doctor p {
    font-size: 0.9rem;
    color: #666;
}

/* Services Section */
.services {
    text-align: center;
    padding: 60px 20px;
    background: #ffc8dd;
}
.services h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}
.services-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    justify-items: center;
}
.service {
    background: white;
    padding: 20px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    width: 250px;
    transition: 0.3s ease;
}
.service:hover {
    transform: translateY(-5px);
}
.service img {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 10px;
}
.service h3 {
    font-size: 1.2rem;
    color: #333;
}
.service p {
    font-size: 0.9rem;
    color: #666;
}

/* Responsive Design */
@media (max-width: 768px) {
    .doctor-list {
        flex-direction: column;
        align-items: center;
    }
    .services-container {
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    }
}
/* Contact Section */
.contact {
    text-align: center;
    padding: 60px 20px;
    background: white;
}
.contact h2 {
    font-size: 2rem;
    font-weight: bold;
    color: #333;
}
.contact h2 span {
    color: #ff79a6;
}
.contact p {
    font-size: 1.2rem;
    margin-bottom: 30px;
    color: #666;
}

/* Contact Form */
.contact-form {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    max-width: 800px;
    margin: auto;
}
.form-group {
    display: flex;
    flex-direction: column;
    text-align: left;
}
.form-group label {
    font-size: 1rem;
    font-weight: bold;
    color: #333;
    margin-bottom: 5px;
}
.form-group i {
    color: gold;
    margin-right: 5px;
}
.form-group input,
.form-group select {
    width: 100%;
    padding: 10px;
    font-size: 1rem;
    border: none;
    border-bottom: 2px solid #333;
    background: transparent;
    outline: none;
}
.btn {
    grid-column: span 2;
    padding: 12px;
    background: #ff79a6;
    color: white;
    font-size: 1rem;
    font-weight: bold;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    transition: 0.3s ease;
}
.btn:hover {
    background: #ff4d7d;
}

/* Responsive */
@media (max-width: 768px) {
    .contact-form {
        grid-template-columns: 1fr;
    }
    .btn {
        grid-column: span 1;
    }
}
