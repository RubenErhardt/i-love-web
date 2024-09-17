<header class="header">
    <p>Ruben Erhardt's Digital Garden</p>
    <p>
        <a href="https://github.com/rubenerhardt" target="_blank" rel="noopener noreferrer">Github
        </a>
    </p>
  </header>
  
  <section class="more-info">
    <img src="/plant_01.png" alt="" width="300" height="200">
    <div class="tekst-info">
    <h2>Ruben Erhardt's Digital Garden</h2>
    <p>Notities over het web, WELOVEWEBS en dingen die ik heb geleerd</p>
</div>
    <img src="/59a81a86259965.5d940fbcbdefa-removebg-preview.png" alt="" width="300" height="200" class="wifi">
  </section>

  <section class="latest">
        <p class="latest-text">Latest: Digital gardening &nbsp;&nbsp; | Sveltekit leren &nbsp;&nbsp; | Projectboard &nbsp;&nbsp; | Updated: 17-09-2024</p>
  </section>
  
  <div class="container">
    <main class="main-content">
        <a href="/nodejs" class="article-link">
        <article class="article">
            <div class="img-container">
            <img src="/1_TY9uBBO9leUbRtlXmQBiug.png" alt="Node JS">
        </div>
            <h2>Recap Node JS</h2>
            <p>"Node.js is een JavaScript-runtime waarmee je een server kunt opzetten om je frontend code te verbinden met een database."</p>
        </article>
    </a>
        <article class="article">
            <img src="" alt="">
            <h2>Article Title</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </article>
        <article class="article">
            <img src="" alt="">
            <h2>Article Title</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </article>
        <article class="article">
            <img src="" alt="">
            <h2>Article Title</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </article>
        <article class="article">
            <img src="" alt="">
            <h2>Article Title</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </article>
        <article class="article">
            <img src="" alt="">
            <h2>Article Title</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </article>
        <article class="article">
            <img src="" alt="">
            <h2>Article Title</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </article>
        <article class="article">
            <img src="" alt="">
            <h2>Article Title</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </article>
        <article class="article">
            <img src="" alt="">
            <h2>Article Title</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </article>
        <article class="article">
            <img src="" alt="">
            <h2>Article Title</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </article>
        <article class="article">
            <img src="" alt="">
            <h2>Article Title</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </article>
    </main>
  </div>
  
  <style>
    .header {
      grid-area: header;
      color: black;
      padding: 20px;
      display: flex;
    justify-content: space-between; /* Space between the items */
    align-items: center;
      outline: 2px solid black;
    }
  
    .header p {
      margin: 0;
      font-size: 0.8em;
    }

    .header a{
        text-decoration: none;
        color: inherit;
        cursor: pointer;
    }

    .more-info{
        padding: 20px;
        outline: 2px solid black;
        display: flex;
    }
    
    .tekst-info{
        display: flex;
        align-items: center;
        width: 600px;
        flex-wrap: wrap;
    }

    .wifi{
        margin-left: 300px;
    }

    .tekst-info h2{
        margin-bottom: -100px;
    }

    .latest {
    overflow: hidden; /* Hides the overflow content */
    background-color: black;
    color: #fff; /* Text color */
    outline: 2px solid black;
    white-space: nowrap; /* Prevents line breaks */
}

.latest-text {
    display: inline-block;
    padding-left: 50%; /* Start the text off-screen */
    animation: latest 20s linear infinite; /* Animation settings */
}

@keyframes latest {
    from {
        transform: translateX(100%); /* Start from the right */
    }
    to {
        transform: translateX(-100%); /* End on the left */
    }
}
  
    .main-content {
      padding: 20px;
      gap: 10px;
      justify-content: flex-start;
      outline: 2px solid black;
      background-color: #fff;
      display: flex;
            flex-wrap: wrap;
    }

    .article {
            border: 1px solid #ddd;
            padding: 15px;
            margin-bottom: 10px;
            border-radius: 5px;
            height: 300px;
            cursor: pointer;
            width: 200px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .article-link {
    text-decoration: none; /* Verwijdert de onderlijning */
    color: inherit; /* Zorgt ervoor dat de link de tekstkleur van het artikel overneemt */
    display: block; /* Zorgt ervoor dat het hele artikel klikbaar is */
}

        .article img {
            width: 150px;
            height: 150px;
            object-fit: cover;
        }

        .img-container{
            display: flex;
    justify-content: center; /* Center image horizontally */
    width: 100%;
    margin-bottom: 20px;
        }

        .article h2, .article p {
            margin: 10px 0;
            font-size: 1em;
        }

        .article p {
            flex: 1; /* This makes the paragraph take up the remaining space */
        }
  </style>
  