<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Identification Card</title>
<style>
.card {
  width: 300px;
  background-color: #f9f9f9;
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.profile-pic {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  margin-bottom: 10px;
}

.name {
  font-size: 24px;
  font-weight: bold;
}

.job-title {
  color: #888;
  margin-bottom: 10px;
}

.contact {
  color: #333;
}

.button {
  background-color: #3498db;
  color: #fff;
  padding: 10px 20px;
  border-radius: 5px;
  text-decoration: none;
}
</style>
</head>
<body>

<div class="card">
  <img src="profile-pic.jpg" alt="Profile Picture" class="profile-pic">
  <h2 class="name">John Doe</h2>
  <p class="job-title">Software Developer</p>
  <p class="contact">Email: johndoe@example.com</p>
  <p class="contact">Phone: +1234567890</p>
  <a href="#" class="button">View Profile</a>
</div>

</body>
</html>
