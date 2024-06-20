
<body>
    <div class="container">
        <h1>Git Tutorial</h1>
        <p><strong>Apu Deb Chowdhury</strong><br>
        Sylhet, Bangladesh</p>

        <p>I recently completed my undergraduate degree in computer science and engineering at Leading University(LU),Sylhet.</p>

        <h2>Git Uses</h2>
        <p>Git is a tool used for:</p>
        <ul>
            <li>Version control system</li>
            <li>Keeping track of changes</li>
            <li>Collaboration on projects</li>
        </ul>
        <p>Similar tools include:</p>
        <ul>
            <li>GitLab</li>
            <li>Beanstalk</li>
            <li>PerForce</li>
            <li>Bitbucket</li>
        </ul>
        <p>More than 70% of developers use Git.</p>

        <h2>Git & GitHub Difference</h2>
        <ul>
            <li>GitHub is a service; Git is a tool.</li>
            <li>GitHub provides a GUI interface; Git provides a CLI (Command Line Interface).</li>
            <li>GitHub is maintained on the web or cloud; Git is installed and maintained locally.</li>
        </ul>

        <h2>GitHub Version Check</h2>
        <p>Check Git version:</p>
        <pre><code>git --version</code></pre>

        <h2>VS Code GitHub Account Configuration</h2>
        <p>To check your username:</p>
        <pre><code>git config user.name</code></pre>
        <p>To check your email:</p>
        <pre><code>git config user.email</code></pre>
        <p>To configure your username:</p>
        <pre><code>git config --global user.name "imdeb99"</code></pre>
        <p>To configure your email:</p>
        <pre><code>git config --global user.email "apudeb2000@gmail.com"</code></pre>

        <h2>Git Project Push to GitHub</h2>
        <ol>
            <li><strong>Git Initialization:</strong>
                <pre><code>git init</code></pre>
            </li>

            <li><strong>Git Add:</strong>
                <> <code> git add [file name]   // to add a specific file
                
                <pre> git add . </pre>         // to add all files</code> <>

                <p>Check file status (modified or not):</p>
                
                <pre><code>git status</code></pre>
                <p>Restore file status:</p>
                <pre><code>git restore [file name]</code></pre>
                <p>Check differences:</p>
                <pre><code>git diff</code></pre>
            </li>
            <li><strong>Git Commit:</strong>
                <pre><code>git commit -m "first commit"   // send a message like 'first commit'
                            -m refers to the message</code></pre>
                <p>Check commit history:</p>
                <pre><code>git log</code></pre>
                <p>Check commit history with summary:</p>
                <pre><code>git log --oneline</code></pre>
                <p>Get commit ID in log:</p>
                <pre><code>git log --oneline</code></pre>
                <p>Reset to a previous commit:</p>
                <pre><code>git reset --soft [commit id]</code></pre>
                <p>Checkout a specific commit:</p>
                <pre><code>git checkout [commit id]</code></pre>
                <p>Check remote origin:</p>
                <pre><code>git remote -v</code></pre>
            </li>
            <li><strong>Create and switch to main branch:</strong>
                <pre><code>git branch -M main</code></pre>
            </li>
            <li><strong>Push to GitHub:</strong>
                <pre><code>git push -u origin main</code></pre>
            </li>
        </ol>

        <h2>Create a New Repository on the Command Line</h2>
        <pre><code>echo "# git-tutorial" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/imdeb99/git-tutorial.git
git push -u origin main</code></pre>

        <h2>Push an Existing Repository from the Command Line</h2>
        <pre><code>git remote add origin https://github.com/imdeb99/git-tutorial.git
git branch -M main
git push -u origin main</code></pre>
    </div>
</body>


</html>
