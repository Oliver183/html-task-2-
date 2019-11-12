<!DOCTYPE html>

<html lang="en">

<head>
    <title>HTML Content Tests</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles/main.css">
    <link rel="stylesheet" href="https://code.jquery.com/qunit/qunit-2.9.2.css">
</head>

<body>
    <header>
        <nav id="navMain">
            <a href="index.html">Home</a> |
            <a href="wwwintro.html">WWW Intro</a> |
            <a href="htmlstructure.html">HTML Structure</a> |
            <a href="htmlcontent.html">HTML Content</a> |
            <a href="dataimport.html">Data Import Formats</a> |
            <a href="csspart1.html">CSS Part 1</a> |
            <a href="csspart2.html">CSS Part 2</a> |
            <a href="design.html">Design Issues</a>
        </nav>

    </header>
    <div id="divContent">
        <section id="sectionMain">
            <h1>HTML Structure</h1>
        </section>
        <section id="practicearea">
            <h2>Practice Area</h2>
            <section id="studentcode">
                <h2>Student Code</h2>
                <section id="textSection">
                    <h3>"Text Content"</h3>
                    <p id="paraText1"><b>Fermentum et sollicitudin ac orci. Congue eu consequat ac felis donec et.</b> Etiam tempor orci eu lobortis elementum nibh. <del>Sed blandit libero volutpat sed. Sit amet mauris commodo quis imperdiet massa.</del> Semper feugiat nibh sed pulvinar proin gravida. Semper viverra nam libero justo</p>
                    <p id="paraText2">nulla <i>fdgh;sahio</i>porttitor massa id. Nullam ac tortor vitae purus.<sub>fdkhfoidha</sub> Donec pretium vulputate sapien nec sagittis aliquam. Gravida quis blandit turpis cursus in hac habitasse</p>
                    <a href="#linkSection" id="link2">link2 </a>
                </section>
                <section id="listSection">
                    <ol id="ol1" type="I">
                        <li>1</li>
                        <li>2</li>
                        <li>3</li>
                    </ol>
                </section>
                <section id="linkSection">
                    <a href=" https://www.bournemouth.ac.uk" id="link1">link1</a>
                </section>
                <section id="imageSection">
                    <img src="images\sunset1.jpg" id="image1" alt="image of a sunset" width: 50%>
                </section>
                <section id="formSection">
                </section>
                <section id="formSection">
                    <form id="form1" method="GET" action="#">
                        <input type="submit" <input type="text" name="textInput" value="Hello World!">
                        <select name="cards">
                            <option value="hearts">hearts</option>
                            <option value="diamonds">diamonds</option>
                            <option value="spades">spades</option>
                            <option value="clubs">clubs</option>
                            <input type="submit" value="Submit">
                        </select>
                    </form>
                </section>
                <section id="mediaSection">
                    <video controls id="video1" source src="videos\video1.mp4" sour%ce src="videos\video1.ogg"></video>
                </section>
            </section>
        </section>
        
                   
                
            
       
        <aside id="asideMain">
            <div id="divAsideHeight">
                <h2>Tips/Links</h2>
                <quote class="tip">Don't forget to backup you work on a regular basis.</quote>
                <quote class="tip">Don't forget to use the Browser Developer Tools to help debug your code.</quote>
                <quote class="tip">Don't forget to make sure your code is <a href="https://validator.w3.org/" target="_blank">validated</a></quote>
                <p><a href="https://www.w3schools.com/html/html5_syntax.asp" target="blank">W3Schools Coding Conventions</a></p>
                <p><a href="https://loremipsum.io/generator/?n=2&t=p" target="_blank">Lorem ipsum Generator</a></p>
                <p><a href="https://validator.w3.org/#validate_by_input" target="_blank">W3C Validator</a></p>
            </div>
        </aside>
    </div>

    <footer id="footerMain">
        <nav id="navFooter">
            <a href="index.html">Home</a> |
            <a href="wwwintro.html">WWW Intro</a> |
            <a href="htmlstructure.html">HTML Structure</a> |
            <a href="htmlcontent.html">HTML Content</a> |
            <a href="dataimport.html">Data Import Formats</a> |
            <a href="csspart1.html">CSS Part 1</a> |
            <a href="csspart2.html">CSS Part 2</a> |
            <a href="design.html">Design Issues</a>
        </nav>
    </footer>
    <div id="qunit"></div>
    <div id="qunit-fixture"></div>
    <script src="https://code.jquery.com/qunit/qunit-2.9.2.js"></script>
    <script src="scripts/testsContent.js"></script>
</body>

</html>
