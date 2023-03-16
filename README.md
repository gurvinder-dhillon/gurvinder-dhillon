<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Profile</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-2icxKbIgR6TwO8Pv74aV7J03nxHT+bU6KkLe6MslGqf3xqrjlOwWYl8Kv09s9XZ43erhNOupW2hz8LrBvTbBqw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    /* Main styles */
    body {
      font-family: 'Helvetica Neue', sans-serif;
      font-size: 16px;
      line-height: 1.5;
      color: #333;
      background-color: #f7f7f7;
      margin: 0;
      padding: 0;
    }
    
    h1, h2, h3, h4, h5, h6 {
      font-family: 'Montserrat', sans-serif;
      margin: 0;
    }
    
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 40px 20px;
    }
    
    /* Header section */
    .header {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      margin-bottom: 40px;
    }
    
    .profile-pic {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      object-fit: cover;
      margin-right: 20px;
    }
    
    .profile-info {
      flex: 1;
      max-width: 400px;
    }
    
    .profile-name {
      font-size: 36px;
      font-weight: bold;
      margin-bottom: 10px;
    }
    
    .profile-bio {
      font-size: 18px;
      font-style: italic;
      margin-bottom: 20px;
    }
    
    .profile-links {
      display: flex;
      flex-wrap: wrap;
    }
    
    .profile-links a {
      display: inline-block;
      margin-right: 10px;
      margin-bottom: 10px;
      padding: 10px;
      border: 2px solid #333;
      border-radius: 5px;
      color: #333;
      text-decoration: none;
      transition: all 0.3s ease;
    }
    
    .profile-links a:hover {
      background-color: #333;
      color: #fff;
    }
    
    /* Skills section */
    .skills {
      margin-bottom: 40px;
    }
    
    .skills h2 {
      font-size: 28px;
      margin-bottom: 20px;
    }
    
    .skill {
      display: flex;
      align-items: center;
      margin-bottom: 10px;
    }
    
    .skill i {
      margin-right: 10px;
      font-size: 24px;
      color: #333;
    }
    
    .skill-name {
      font-size: 18px;
      font-weight: bold;
    }
    
    .skill-bar {
      flex: 1;
      height: 5px;
      background-color: #f7f7
