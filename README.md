<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Syed Fardeen Jeelani - Frontend Developer</title>
    <style>
        body {
            font-family: 'Consolas', 'Courier New', monospace;
            background-color: #1e1e1e;
            color: #d4d4d4;
            line-height: 1.6;
            padding: 20px;
            margin: 0;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background-color: #252526;
            border: 1px solid #3e3e42;
            border-radius: 5px;
            padding: 20px;
            box-shadow: 0 0 20px rgba(0,0,0,0.4);
        }
        h1, h2, h3 {
            color: #569cd6;
        }
        .comment {
            color: #608b4e;
        }
        .string {
            color: #ce9178;
        }
        .number {
            color: #b5cea8;
        }
        .keyword {
            color: #c586c0;
        }
        .function {
            color: #dcdcaa;
        }
        .variable {
            color: #9cdcfe;
        }
        .center {
            text-align: center;
        }
        .badge {
            display: inline-block;
            padding: 3px 7px;
            background-color: #3e3e42;
            color: #d4d4d4;
            border-radius: 3px;
            margin: 2px;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 10px;
        }
        .line-numbers {
            color: #858585;
            padding-right: 15px;
            text-align: right;
            user-select: none;
        }
        .code-block {
            display: flex;
            background-color: #1e1e1e;
            border: 1px solid #3e3e42;
            border-radius: 5px;
            overflow: hidden;
            margin: 20px 0;
        }
        .code-content {
            padding: 10px;
            flex-grow: 1;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        a {
            color: #4ec9b0;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="center">Syed Fardeen Jeelani</h1>
        <h3 class="center comment">// A passionate frontend developer from India</h3>
        
        <div class="center">
            <img src="https://i.giphy.com/aDS8SjVtS3Mwo.webp" alt="Coding gif" />
        </div>

        <div class="code-block">
            <div class="line-numbers">
                1<br>2<br>3<br>4<br>5<br>6<br>7<br>8<br>9<br>10<br>11<br>12
            </div>
            <div class="code-content">
                <span class="keyword">const</span> <span class="variable">developer</span> = {<br>
                &nbsp;&nbsp;<span class="variable">name</span>: <span class="string">"Syed Fardeen Jeelani"</span>,<br>
                &nbsp;&nbsp;<span class="variable">role</span>: <span class="string">"Frontend Developer"</span>,<br>
                &nbsp;&nbsp;<span class="variable">location</span>: <span class="string">"India"</span>,<br>
                &nbsp;&nbsp;<span class="variable">currentProject</span>: <span class="string">"HFAR"</span>,<br>
                &nbsp;&nbsp;<span class="variable">learning</span>: <span class="string">"Svelte"</span>,<br>
                &nbsp;&nbsp;<span class="variable">askMeAbout</span>: [<span class="string">"HTML"</span>, <span class="string">"CSS"</span>, <span class="string">"JavaScript"</span>, <span class="string">"React"</span>, <span class="string">"Next.js"</span>],<br>
                &nbsp;&nbsp;<span class="variable">contact</span>: <span class="string">"syedfardeenjeelani13@gmail.com"</span>,<br>
                &nbsp;&nbsp;<span class="variable">funFact</span>: <span class="string">"I'm also known as 'Hacker for a Reason' on YouTube!"</span><br>
                };<br>
                <br>
                <span class="function">console</span>.<span class="function">log</span>(<span class="string">"Welcome to my profile!"</span>);
            </div>
        </div>

        <h2>🚀 Skills</h2>
        <div class="skills">
            <span class="badge">HTML</span>
            <span class="badge">CSS</span>
            <span class="badge">JavaScript</span>
            <span class="badge">Tailwind CSS</span>
            <span class="badge">React.js</span>
            <span class="badge">TypeScript</span>
            <span class="badge">Next.js</span>
            <span class="badge">Firebase</span>
            <span class="badge">Swiper.js</span>
            <span class="badge">Formik</span>
            <span class="badge">TanStack Query</span>
            <span class="badge">Bootstrap</span>
            <span class="badge">React Hook Form</span>
            <span class="badge">React Context API</span>
            <span class="badge">Redux</span>
        </div>

        <h2>🔗 Connect with me</h2>
        <p>
            <a href="https://www.youtube.com/c/hacker for a reason" target="_blank">YouTube: Hacker for a Reason</a>
        </p>

        <h2>📊 GitHub Stats</h2>
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=syedfardeenjeelani&show_icons=true&locale=en&layout=compact&theme=dark" alt="Top Languages" />
        <img src="https://github-readme-stats.vercel.app/api?username=syedfardeenjeelani&show_icons=true&locale=en&theme=dark" alt="GitHub Stats" />
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=syedfardeenjeelani&theme=dark" alt="GitHub Streak" />

        <div class="code-block">
            <div class="line-numbers">1<br>2<br>3</div>
            <div class="code-content">
                <span class="keyword">if</span> (<span class="variable">you</span>.<span class="function">like</span>(<span class="variable">myProfile</span>)) {<br>
                &nbsp;&nbsp;<span class="function">followMe</span>();<br>
                }
            </div>
        </div>
    </div>
</body>
</html>
