# Styled_Profile_Card
## Date:

## Objective:
To practice HTML and CSS fundamentals by designing a visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques.

## Tasks:
#### 1. Create the HTML Structure:
Use ```<!DOCTYPE html>, <html>, <head>, and <body>``` to define the structure.
Add a ```<title>``` like "My Profile Card".

#### 2. Add Content:
Include name, title (e.g., Developer, Student), and a short bio using semantic tags such as ```<h1>```, ```<h2>```, and ```<p>```.

#### 3. Add a Profile Image:
Use the ```<img>``` tag to include a profile picture with appropriate alt, width, and height attributes.

#### 4. Apply Background Color:
Use a CSS class to style the card with a background color.

#### 5. Style Typography:
Use CSS to apply different font families, sizes, and text colors for the name and bio.

#### 6. Add Spacing:
Apply margin and padding to improve spacing between elements using CSS.

#### 7. Center the Card:
Use flexbox or margin: auto to center the card vertically and horizontally on the page.

#### 8. Add Hover Effects:
Enhance interactivity with simple hover effects like border changes or background transition using CSS.

## HTML Code:
```

<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="style.css">
  <title>My Profile</title>
</head>
<body>

  <header>
    <h1>G SAMUVEL</h1>
    <h2>Student</h2>
    <h3>Web Developer</h3>
  </header>

  <hr>
  <section>
    <img src="SAM.png" alt="Profile picture of G SAMUVEL" width="200" height="200">
    <p>Hi! I'm a passionate learner exploring the world of web development. I enjoy solving algorithmic problems. My current focus is on building strong foundations in HTML, CSS, and JavaScript.</p>
  </section>

  <hr>

  <section>
    <h2>Interests</h2>
    <ul>
      <li>Full-Stack Web Development (HTML, CSS, JavaScript)</li>
      <li>Java Programming</li>
      <li>Android development</li>
      <li>Flutter</li>
    </ul>
  </section>

</body>
</html>
```

## CSS Code:
```
/* Reset some default spacing */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
  color: #333;
  line-height: 1.6;
  padding: 20px;
}

/* Header styling */
header {
  text-align: center;
  background-color: #4a90e2;
  color: white;
  padding: 20px 0;
  border-radius: 10px;
}

header h1 {
  margin: 0;
  font-size: 36px;
}

header h2, header h3 {
  margin: 5px 0;
  font-weight: normal;
}

/* Image and description section */
section img {
  display: block;
  margin: 20px auto;
  border-radius: 50%;
  box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}

section p {
  max-width: 600px;
  margin: 0 auto 20px auto;
  text-align: center;
  font-size: 18px;
}

/* Interests section */
section ul {
  max-width: 600px;
  margin: 0 auto;
  padding-left: 20px;
}

section ul li {
  margin: 10px 0;
  font-size: 16px;
}

/* Horizontal lines */
hr {
  margin: 40px auto;
  width: 80%;
  border: 1px solid #ccc;
}
```
## Live Web Page:
https://samjxdev.github.io/Styled_Profile/
## Output:
![127 0 0 1_5500_index html](https://github.com/user-attachments/assets/03019785-e3ec-460e-8a1b-04e494546dd0)

## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
