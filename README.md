<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            text-align: center;
            padding: 30px;
            background-color: #333;
            color: #fff;
        }

        section {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1, h2, p {
            margin-bottom: 20px;
        }

        .tap-animation {
            display: inline-block;
            cursor: pointer;
            transition: transform 0.2s ease-in-out;
        }

        .tap-animation:hover {
            transform: translateY(-5px);
        }
    </style>
</head>
<body>

    <header>
        <h1>Your Name</h1>
        <p>Web Developer | Designer</p>
    </header>

    <section>
        <h2>About Me</h2>
        <p>Your introduction and brief description about yourself. Highlight your skills and interests.</p>
    </section>

    <section>
        <h2>Accomplishments</h2>
        <p>Your notable achievements and projects. You can add more sections based on your needs.</p>
    </section>

    <section>
        <h2>Contact</h2>
        <p>Email: your.email@example.com<br>
        LinkedIn: linkedin.com/in/your-profile<br>
        GitHub: github.com/yourusername</p>
    </section>

    <footer>
        <p>© 2023 Your Portfolio. All rights reserved.</p>
    </footer>

    <!-- Adding tapping animation to the footer text -->
    <script>
        document.querySelector('footer p').addEventListener('click', function() {
            this.classList.add('tap-animation');
            setTimeout(() => {
                this.classList.remove('tap-animation');
            }, 200);
        });
    </script>

</body>
</html>
