<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>About Me</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background: #f7f9fc;
        margin: 0;
        padding: 0;
    }
    .profile-card {
        max-width: 800px;
        margin: 50px auto;
        background: #fff;
        border-radius: 12px;
        padding: 30px;
        box-shadow: 0 4px 15px rgba(0,0,0,0.08);
    }
    .profile-header {
        text-align: center;
        border-bottom: 2px solid #eee;
        padding-bottom: 15px;
        margin-bottom: 20px;
    }
    .profile-header h1 {
        color: #2c3e50;
        margin: 0;
    }
    .profile-header p {
        font-size: 14px;
        color: #7f8c8d;
        margin-top: 8px;
    }
    .details {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
        gap: 15px;
    }
    .detail-item {
        background: #f8fbff;
        padding: 12px 15px;
        border-radius: 8px;
        border-left: 4px solid #3498db;
        transition: transform 0.25s ease, box-shadow 0.25s ease;
    }
    .detail-item:hover {
        transform: scale(1.05);
        box-shadow: 0 6px 15px rgba(0,0,0,0.1);
    }
    .detail-item strong {
        display: block;
        font-size: 14px;
        color: #34495e;
        margin-bottom: 4px;
    }
    .detail-item span, .detail-item a {
        font-size: 15px;
        color: #2c3e50;
        text-decoration: none;
    }
    .bio {
        margin-top: 25px;
        font-size: 15px;
        color: #555;
        line-height: 1.6;
        text-align: justify;
    }
</style>
</head>
<body>

<div class="profile-card">
    <div class="profile-header">
        <h1>UI/UX Designer & Web Developer</h1>
        <p>Creating functional, user-friendly, and visually engaging digital solutions.</p>
    </div>

    <div class="details">
        <div class="detail-item">
            <strong>Birthday</strong>
            <span>1 May 1995</span>
        </div>
        <div class="detail-item">
            <strong>Age</strong>
            <span>25</span>
        </div>
        <div class="detail-item">
            <strong>Website</strong>
            <a href="https://www.example.com" target="_blank">www.example.com</a>
        </div>
        <div class="detail-item">
            <strong>Degree</strong>
            <span>Master</span>
        </div>
        <div class="detail-item">
            <strong>Phone</strong>
            <span>+63 925 456 7890</span>
        </div>
        <div class="detail-item">
            <strong>Email</strong>
            <a href="mailto:email@example.com">email@example.com</a>
        </div>
        <div class="detail-item">
            <strong>City</strong>
            <span>CSFP, Philippines</span>
        </div>
        <div class="detail-item">
            <strong>Freelance</strong>
            <span>Available</span>
        </div>
    </div>

    <div class="bio">
        A passionate designer and developer focused on crafting interactive, accessible, 
        and high-performing websites and applications. Dedicated to blending creativity 
        with functionality to deliver exceptional user experiences.
    </div>
</div>

</body>
</html>
