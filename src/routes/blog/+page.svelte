<div class="header">
    <article>
        <section>
            <h1>Welcome to this?</h1>
        </section>
</div>

<div class="container">
    <article>
        <section>
            <h2 class="title">
                <a class="link" href="/blog/posts/test">Test</a>
            </h2>
            <p class="desc">
                Hello, this is just a test :D
            </p>
        </section>
    </article>
</div>


<style>
    @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@100&display=swap');

    .header {
        background-color: rgb(245, 245, 245);
        display: flex;
        font-size: 3vh;
        justify-content: center;
        border: 10px rgb(70, 75, 92);
        font-family: 'IBM Plex Mono', monospace;
        color:rgb(23, 32, 60);
        border-radius: 10px;
        padding: 3px;
        margin: 10px;
    }

    .title {
        color:rgb(76, 85, 112);
        font-size: xx-large;
        display: flex;
        justify-content: center;
    }

    .desc {
        color:rgb(22, 28, 49);
        font-size: larger;
    }

    .link {
        text-decoration: none;
        font-family: 'IBM Plex Mono', monospace;
        color:rgb(76, 85, 112);
    }

    :hover.link {
        color: rgb(22, 28, 49);
    }

    .container {
        background-color: rgb(237, 237, 237);
        display: grid;
        justify-items: center;
        font-family: 'IBM Plex Mono', monospace;
        color:rgb(23, 32, 60);
        border-radius: 10px;
        padding: 3px;
    }
</style>