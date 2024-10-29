# Sangam Verse - Social Media Website
Sangam Verse is a social media platform that connects users through secure login, user profiles, and interactive content sharing, including posts, comments, and likes. Users can follow others, engage with posts, and receive real-time notifications. With email OTP verification, Sangam Verse prioritizes user authenticity, providing a dynamic space for connection and communication.

## Features
- **User Authentication:** Secure registration and login with OTP verification via email.
- **Profile Management:** Users can create and manage profiles.
- **Post Creation & Sharing:** Users can create, edit, and share posts with the community.
- **Real-Time Comments:** Interactive commenting on posts.
- **Follow System:** Follow other users to stay updated on their activities.
- **Interactive Notifications:** Real-time notifications for new followers, comments, and likes.
- **Responsive Design:** Adaptable, responsive UI for both desktop and mobile devices.

## Technology Used
- **Backend:** PHP for server-side logic.
- **Frontend:** HTML, CSS, JavaScript for user interface.
- **Database:** MySQL to manage and store user data, posts, comments, and follow relationships.

## Architecture
The architecture of Sangam Verse includes:
1. **Frontend Layer:** HTML, CSS, JavaScript for a responsive, user-friendly interface.
2. **Backend Layer:** PHP for managing server-side data processing and business logic.
3. **Database Layer:** MySQL for structured data management.
4. **Email Verification:** Send email OTPs for secure account verification.

<img width="950px;" src="https://res.cloudinary.com/cloud-alpha/image/upload/v1730099811/PHP_Project/php-sangam_verse-architecture_vqzrrc.png"/>

## Entities and Relationships Diagram (ERD)
The ER diagram below illustrates key entities and relationships, including Users, Posts, Comments, and Follow relationships.

<img width="950px;" src="https://res.cloudinary.com/cloud-alpha/image/upload/v1730099815/PHP_Project/php-sangam_verse_ERD_mydqq2.png"/>

## Website Snapshot
#### Create an Account:
<img width="950px;" src="https://res.cloudinary.com/cloud-alpha/image/upload/v1730099771/PHP_Project/php_create-new-account_i7wlrn.png"/>

#### Login:
<img width="950px;" src="https://res.cloudinary.com/cloud-alpha/image/upload/v1730099771/PHP_Project/php_login_lhupcr.png"/>

#### Home Dashboard:
<img width="950px;" src="https://res.cloudinary.com/cloud-alpha/image/upload/v1730099783/PHP_Project/php_home-dahboard_z8xbws.png"/>

#### Add New Post:
<img width="950px;" src="https://res.cloudinary.com/cloud-alpha/image/upload/v1730099779/PHP_Project/php_add-new-post_e0apdi.png"/>

#### Profile Dashboard:
<img width="950px;" src="https://res.cloudinary.com/cloud-alpha/image/upload/v1730099778/PHP_Project/php_profile-dashboard_bexzr2.png"/>

#### Edit Profile:
<img width="950px;" src="https://res.cloudinary.com/cloud-alpha/image/upload/v1730099772/PHP_Project/php_edit-profile_t0djj1.png"/>

#### Notifications:
<img width="950px;" src="https://res.cloudinary.com/cloud-alpha/image/upload/v1730099781/PHP_Project/php_notifications_n2opjh.png"/>

#### OTP Received on Email:
<img width="950px;" src="https://res.cloudinary.com/cloud-alpha/image/upload/v1730225699/PHP_Project/php_otp-recived-on-email_vmrutz.png"/>

## Prerequisites
- *PHP*
- *HTML, CSS & JavaScript*
- *MySQL*
- *XAMPP Apache Server*


## Installation
1. **Clone the project**: `git clone https://github.com/raushan-kumar7/sangamverse.git`
2. **Move files to XAMPP directory**:
  - Copy the entire project folder and place it inside the `htdocs` folder in the XAMPP directory.
3. **Set up your database in XAMPP server**:
  - Open [phpMyAdmin](http://localhost/phpmyadmin) from the XAMPP control panel.
4. **Import the database schema**:
  - In phpMyAdmin, create a new database (e.g., `sangam_verse`).
  - Import the SQL schema:
    1. Select the newly created database.
    2. Go to the "Import" tab.
    3. Choose the `sangam_verse.sql` file from the project directory and import it.