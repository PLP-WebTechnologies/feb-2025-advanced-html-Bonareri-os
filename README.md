<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements Demo</title>
</head>
<body>
    <header>
        <h1>HTML5 Elements Demonstration</h1>
    </header>
    <section>
        <h2>Ordered List (Roman Numerals)</h2>
        <ol type="I">
            <li>Introduction to HTML5</li>
            <li>Working with Images</li>
            <li>Tables and Lists</li>
            <li>Forms and Input Types</li>
            <li>Multimedia Elements</li>
        </ol>
    </section>
    <section>
        <h2>Image from Pexels</h2>
        <img src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg" alt="Beautiful Landscape" width="600">
    </section>
    <section>
        <h2>Contact List</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Leone Aboki</td>
                    <td>Laikipia</td>
                    <td>+2547756483</td>
                    <td>leone@gmail.com</td>
                </tr>
                <tr>
                    <td>John Maina</td>
                    <td>Uganda</td>
                    <td>+25571638339</td>
                    <td>maina@gmail.com</td>
                </tr>
                <tr>
                    <td>Christine lukoko</td>
                    <td>Murang'a</td>
                    <td>+24555877338</td>
                    <td>christine@gmail.com</td>
                </tr>
                <tr>
                    <td>David Onyango</td>
                    <td>Kisumu Dala</td>
                    <td>+25498373833</td>
                    <td>david@gmail.com</td>
                </tr>
                <tr>
                    <td>Mary Macharia</td>
                    <td>Mombasa</td>
                    <td>+254739303039</td>
                    <td>Mary@gmail.com</td>
                </tr>
            </tbody>
        </table>
    </section>
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="6">
            <br><br>
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>
            <label for="gender">Gender:</label>
            <select id="gender" name="gender" required>
                <option value="">Select Gender</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
            <br><br>
            <label>Subscription Plan:</label><br>
            <input type="radio" id="basic" name="subscription" value="basic" required>
            <label for="basic">Basic</label>
            <input type="radio" id="premium" name="subscription" value="premium">
            <label for="premium">Premium</label>
            <br><br>
            <label>Interests:</label><br>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label>
            <input type="checkbox" id="reading" name="interests" value="reading">
            <label for="reading">Reading</label>
            <br><br>
            <input type="submit" value="Register">
        </form>
    </section>
    <section>
        <h2>Multimedia Elements</h2>
        <h3>Sample Audio</h3>
        <audio controls>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
        </audio>
        <h3>Sample Video</h3>
        <video width="600" controls>
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
        </video>
    </section>
</body>
</html>
