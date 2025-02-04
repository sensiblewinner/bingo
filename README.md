<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bingo - Fun & Learning</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Welcome to Bingo!</h1>
        <p>Learn and have fun with exciting knowledge.</p>
    </header>

    <nav>
        <ul>
            <li><a href="#fun-facts">Fun Facts</a></li>
            <li><a href="#math-quiz">Math Quiz</a></li>
            <li><a href="#english-quiz">English Quiz</a></li>
        </ul>
    </nav>

    <section id="fun-facts">
        <h2>Did You Know?</h2>
        <p id="fact">Click the button to learn something new!</p>
        <button onclick="showFact()">Show Fun Fact</button>
    </section>

    <section id="math-quiz">
        <h2>Math Quiz</h2>
        <p>What is 5 + 3?</p>
        <input type="number" id="math-answer">
        <button onclick="checkMath()">Submit</button>
        <p id="math-result"></p>
    </section>

    <section id="english-quiz">
        <h2>English Quiz</h2>
        <p>What is the plural of "child"?</p>
        <input type="text" id="english-answer">
        <button onclick="checkEnglish()">Submit</button>
        <p id="english-result"></p>
    </section>

    <footer>
        <p>© 2025 Bingo | Fun & Learning for Kids</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
