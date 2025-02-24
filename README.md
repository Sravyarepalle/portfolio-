# portfolio-
I have built a portfolio website by using HTML



<!DOCTYPE html>
<html lang = "en">
    <head>
        <meta charset="UTF-8">
        <meta name ="wiewport" content="width-device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        <header>
            <h1> Welcome to protfolio</h1>
            <a href="">
             <button>
                 About
             </button>
             </a>
             <a href="">
                 <button>
                     Skills
                 </button>
                 </a>
                 <a href="">
                     <button>
                         Projects 
                     </button>
                     </a>
                     <a href="">
                         <button>
                            Contact
                         </button>
                         </a>
        </header>
        <main>
        <section id = "about">
            <h1>Sravya Repalle</h1>
            <img src="c:\Users\sravy\OneDrive\Documents\myimage.jpg" alt="A photo of me">
            <p>I am passionate web developer with a focus on front-end technologies.</p>
            <p>I am an B tech Graduate in the stream <em> ECE</em>in<em>Chalapthi Institue of Technology</em>Guntur.</p>
            <p>I have learnt web development from<br> Kodnest.</p>
            <p>you can <strong>Click here</strong> to check out what I have learnt in HTML, CSS, JS.</p>
    
        </section>
        <section id = "skills">
            <h1>My Skills</h1>
            <ol>
                <li>Java</li>
                <li>HTML basics</li>
                <li>CSS basics</li>
                <li>JavaScript basics</li>
            </ol>
    
        </section>
        <section id = "projects">
            <h1>My Projects</h1>
            <table border = "1">
                <tr></tr>
                <th>Project</th>
                <th>Description</th>
            </tr>
            <tr>
                <td>Portfolio Website</td>
                <td>I have built a portfolio website by using HTML</td>
            </tr>
            </table>
        </section>
        <section id = "contact">
            <h1>Contact Me</h1>
            <p>Feel free to get in touch with me using the form below</p>
            <form action="">
                <label for="name">Name:</label>
                <input type="text">
                <br>
                <label for="email">Email:</label>
                <input type="email">
                <br>
               <b>Chose your intrests:</b>
                <input type="radio" id="male" value="male">
                <label for="male">Male:</label>
                <input type="radio" id="female" value="female">
                <label for="female">FeMale:</label>
                <br>
            
                <b>Select Your Intrests:</b>
                <input type="checkbox" id="coding" value="coding">
                <label for="coding">Coding</label>
                <input type="checkbox" id="reading" value="reading">
                <label for="reading">Reading</label>
                <br>
            
                <label for="bio">Bio (up to 200 characters):</label>
                <input type="text">
                <br>
            
                <button type="submit">submit</button>
        
        </section>
        </main>
        <footer>

        </footer>

        
        </body>
</html>
