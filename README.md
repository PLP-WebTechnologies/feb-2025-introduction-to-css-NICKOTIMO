<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia-Rich Webpage</title>
</head>
<body>

    <header>
        <h1>Welcome to My Web Page</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#registration">Register</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am learning HTML5 and building structured web pages with multimedia, forms, and tables.</p>
        <img src="rename.jpg" alt="My favorite food" width="300" height="200">
    </section>

    <section id="services">
        <h2>Services</h2>
        <ul>
            <li>Web Development</li>
            <li>Graphic Design</li>
            <li>SEO Optimization</li>
        </ul>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <h3>Featured Video</h3>
        <video width="400" controls>
            <source src="smart-farming-water-technique.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>

        <h3>Featured Audio</h3>
        <audio controls>
            <source src="kalimba.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    </section>

    <section id="registration">
        <h2>Registration Form</h2>
        <form action="submit-form.php" method="post">
            <fieldset>
                <legend>Personal Details</legend>

                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required><br><br>

                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required><br><br>

                <label for="gender">Gender:</label>
                <select id="gender" name="gender" required>
                    <option value="">Select Gender</option>
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="other">Other</option>
                </select><br><br>

                <label for="profile">Upload Profile Picture:</label>
                <input type="file" id="profile" name="profile" accept="image/*"><br><br>

                <input type="checkbox" id="agree" name="agree" required>
                <label for="agree">I agree to the terms and conditions</label><br><br>

                <button type="submit">Submit</button>
                <button type="reset">Reset</button>
            </fieldset>
        </form>
    </section>

    <section id="pricing">
        <h2>Pricing Table</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Service</th>
                    <th>Price</th>
                    <th>Duration</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Web Development</td>
                    <td>$500</td>
                    <td>2 Weeks</td>
                </tr>
                <tr>
                    <td>Graphic Design</td>
                    <td>$200</td>
                    <td>1 Week</td>
                </tr>
                <tr>
                    <td>SEO Optimization</td>
                    <td>$300</td>
                    <td>10 Days</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="send-message.php" method="post">
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" cols="30" placeholder="Write your message here" required></textarea><br><br>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 My Website. All Rights Reserved.</p>
    </footer>

</body>
</html>

