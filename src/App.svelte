<script></script>

<header>
    <h1 class="title">Svelte download guide</h1>
</header>

<main>
    <div class="container">
        <div class="sectionSelector">
            <!-- Section Selector -->
            <h1>Sections of the course</h1>
            <nav>
                <a href="#introduction" class="sectionSelectLink">Introduction</a>
                <a href="#downloadingGit" class="sectionSelectLink">Downloading Git</a>
                <a href="#downloadingNodeJS" class="sectionSelectLink">Downloading NodeJS</a>
                <a href="#downloadingSvelte" class="sectionSelectLink">Downloading Svelte</a>
            </nav>
        </div>
        <section id="introduction">
            <!-- Introduction section -->
            <h1>Introduction</h1>
            <p>Welcome! This guide will show you how to download and set up Svelte, a powerful tool for building fast and efficient websites. <br> Don't worry if you're new to this, I'll walk you through each step, from installing the necessary software to running your first Svelte project.</p>
            <p>You can find more information about svelte here: <a href="https://svelte.dev/docs/svelte/overview">Svelte Docs</a></p>
            <p>By the end of this guide, you'll have everything ready to start creating with Svelte. Let's get started!</p>
            <p>(By the the way, I assume you already have basic knowlege about HTML, CSS and JavaScript before you start, if you don't have that i recommend you learn that first.)</p>
        </section>
        <section id="downloadingGit">
            <!-- Downloading Git section -->
            <h1>Downloading Git</h1>
            <p>So, to start off we will need something called Git. It is what we will use to get access to GitHub resources to download Svelte. <br> So, click on this link <a href="https://git-scm.com/">Git download</a> and follow the download instructions. After downloading Git, we will need something called NodeJS.</p>
            <img src="" alt="">
        </section>
        <section id="downloadingNodeJS">
            <!-- Downloading NodeJS -->
            <h1>Downloading NodeJS</h1>
            <p>
                Now you will need something called NodeJS, why do you need it? <br>
                Developers use NodeJS to create server-side web applications, and it is perfect for data-intensive applications since it uses an asynchronous, event-driven model.
            </p>
            <img src="" alt="">
            <p>
                To download NodeJS you can head over to their website and download the latest version <a href="https://nodejs.org/en">NodeJS</a>. When you press download wait for it to download then open it and follow the instructions and install it.
            </p>
        </section>
        <section id="downloadingSvelte">
            <!-- Downloading Svelte -->
            <h1>Downloading Svelte</h1>
            <p>
                So, to start downloading Svelte, you will need to open the command prompt. To do so, press the Windows Key, then type “cmd.”
            </p>
            <img src="" alt="">
            <p>
                Now that you are in the command prompt, we will need to start by downloading a package called Degit. What this package does is that it allows you to easily clone the latest commits from a GitHub repository.
            </p>
            <p>
                So now to download the package type in the command prompt “npm install -g degit” then press the enter key. This should pop up on the screen.
            </p>
            <img src="" alt="">
            <p>
                Now that you have downloaded degit, it’s time to clone a template from the GitHub repository. So, before you do that you’ll need to be in the correct directory where you want to clone the template. To do this you can close the command prompt and open your file explorer and go to the place where you want the file, then where the directory link is removing the link and type “cmd”, like this.
            </p>
            <img src="" alt="">
            <p>
                After you have opened the command prompt in the correct directory it’s time to download the Svelte template. To do that type “npm install sveltejs/ template (filename). So, what we’re doing is downloading a template from a digit repository, and where it says (filename) means you can call your project whatever you want. And now it should look like this. 
            </p>
            <img src="" alt="">
            <p>
                Now what you’ll need to do I change the directory into the newly created file, to do that type “cd (NameOfTheFile)”, and then press enter. Cd stands for “change directory”. When you’re located in the directory of the newly created file, we will need to download modules. To download the required modules type “npm install” in the command prompt, it should look like this.
            </p>
            <img src="" alt="">
            <p>
                Were technically done installing all the acquired packages. So you can now get started with Svelte, so to start type “code .” to open Visual Studio Code, then type “npm run dev” to open a test server on your computer. Copy the link (should look something like this) “https://localhost:(IP address)”, copy the link and paste it into your web browser. Now you’re ready to start making websites.
            </p>
        </section>
    </div>
</main>

<footer></footer>

<style>
    /* Color */
    :root{
        --primary-color: #343434;
        --secondary-color: #161616;
        --third-color: #3f3f3fd9;
    }

    /* Styling */
    header, main, footer{
        width: 100%;
        display: flex;
        flex-direction: column;
    }
    header{
        height: 10vh;
        justify-content: center;
        background-color: var(--secondary-color);
    }
    footer{
        height: 8vh;
        background-color: var(--secondary-color);
        margin-top: 5vh;
    }
    .title{
        padding-left: 8vw;
        font-size: 30px;
    }
    .container{
        align-items: center;
        padding-top: 5vw;
        display: flex;
        flex-direction: column;
        gap: 50vh;
    }
    section, .sectionSelector{
        background-color: var(--third-color);
        border-radius: 20px;
        padding: 20px;
        display: flex;
        flex-direction: column;
        gap: 20px;
        width: 100%;
        max-width: 80vw;
    }
    section{
        justify-content: center;
    }
    .sectionSelectLink{
        font-size: 25px;
    }
    nav{
        display: flex;
        flex-direction: column;
        gap: 10px;
    }
    img{
        width: 100%;
    }
</style>