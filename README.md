<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lucas's GitHub Profile</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #495057;
        }

        header {
            text-align: center;
            padding: 50px;
            background-color: #007bff;
            color: white;
        }

        h1, h3 {
            margin: 0;
        }

        main {
            padding: 20px;
        }

        .social-media a {
            text-decoration: none;
            color: #007bff;
        }

        .programming-languages img {
            margin: 5px;
        }

        .github-stats {
            display: flex;
            justify-content: space-around;
            max-width: 800px;
            margin: 20px auto;
        }

        .github-stats img {
            margin: 10px;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .repository {
            animation: fadeInUp 0.5s ease-out;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 20px;
            padding: 15px;
            max-width: 300px;
        }
    </style>
</head>
<body>
    <header>
        <a href="https://github.com/TheGeekLucas" target="_blank" rel="noreferrer">
            <img src="https://cdn.discordapp.com/attachments/1113841675723345930/1136344618020130816/nature.gif" alt="MasterHead" />
        </a>
        <h1>Hello, My Name Is Lucas.</h1>
        <h3>Programmer | UI Designer</h3>
        <div class="social-media">
            <a href="https://discord.com/invite/YOUR_INVITE_LINK" target="_blank" rel="noreferrer">Discord: thegeeklucas</a>
        </div>
    </header>

    <main>
        <h3>Programming Languages</h3>
        <div class="programming-languages">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/lua/lua-original.svg" alt="lua" width="40" height="40"/>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/>
        </div>

        <h3>Github Stats</h3>
        <div class="github-stats">
            <img src="https://github-readme-stats.vercel.app/api/top-langs?username=thegeeklucas&show_icons=true&locale=en&layout=compact" alt="Top Languages" />
            <img src="https://github-readme-stats.vercel.app/api?username=thegeeklucas&show_icons=true&locale=en" alt="GitHub Stats" />
        </div>

        <h3>Repositories</h3>
        <div class="repository">
            <h4>Repository 1</h4>
            <p>Description of Repository 1.</p>
        </div>
        <div class="repository">
            <h4>Repository 2</h4>
            <p>Description of Repository 2.</p>
        </div>
        <!-- Add more repositories as needed -->
    </main>

    <script>
        window.addEventListener('scroll', function() {
            var repositories = document.querySelectorAll('.repository');
            repositories.forEach(function(repo, index) {
                setTimeout(function() {
                    repo.style.opacity = 1;
                    repo.style.transform = 'translateY(0)';
                }, index * 200);
            });
        });
    </script>
</body>
</html>
