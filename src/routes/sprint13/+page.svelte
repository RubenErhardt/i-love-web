
<div class="container">
    <main class="main-content">
        <a href="/nodejs" class="article-link">
        <article class="article">
            <div class="img-container">
            <img src="/1_TY9uBBO9leUbRtlXmQBiug.png" alt="Node JS">
        </div>
            <h2>Recap Node JS</h2>
            <p>"Node.js is een JavaScript-runtime waarmee je een server kunt opzetten om je frontend code te verbinden met een database."</p>
            <p class="datum">02-09-2024</p>
        </article>
    </a>
    <a href="/leervragen" class="article-link">
        <article class="article">
            <div class="img-container">
            <img src="/istockphoto-1389448437-612x612-removebg-preview.png" alt="leervragen">
        </div>
            <h2>Leervragen sprint 13</h2>
            <p>"Voor sprint 13 moesten wij een aantal leervragen bedenken. Die kan je hier zien.""</p>
            <p class="datum">02-09-2024</p>
        </article>
    </a>
    <a href="/frameworks" class="article-link">
        <article class="article">
            <div class="img-container">
            <img src="/svelte_logo.png" alt="leervragen">
        </div>
            <h2>Hoe omarm je nieuwe tools en frameworks?</h2>
            <p>"Voorbereiding op nieuwe tools en frameworks zoals sveltekit"</p>
            <p class="datum">02-09-2024</p>
        </article>
    </a>
    <a href="/gedaan" class="article-link">
        <article class="article">
            <div class="img-container">
            <img src="/cute-man-working-computer-with-coffee-cartoon-vector-icon-illustration-people-technology-icon-concept-isolated-premium-vector-flat-cartoon-style_138676-3868.avif" alt="leervragen">
        </div>
            <h2>Wat heb ik vandaag geleerd?</h2>
            <p>"Ik heb veel gedaan vandaag, wat heb ik geleerd?"</p>
            <p class="datum">03-09-2024</p>
        </article>
    </a>
    <a href="/leervragen" class="article-link">
        <article class="article">
            <div class="img-container">
            <img src="/istockphoto-1389448437-612x612-removebg-preview.png" alt="leervragen">
        </div>
            <h2>Leervragen sprint 13</h2>
            <p>"Voor sprint 13 moesten wij een aantal leervragen bedenken. Die kan je hier zien.""</p>
            <p class="datum">02-09-2024</p>
        </article>
    </a>
    <a href="/leervragen" class="article-link">
        <article class="article">
            <div class="img-container">
            <img src="/istockphoto-1389448437-612x612-removebg-preview.png" alt="leervragen">
        </div>
            <h2>Leervragen sprint 13</h2>
            <p>"Voor sprint 13 moesten wij een aantal leervragen bedenken. Die kan je hier zien.""</p>
            <p class="datum">02-09-2024</p>
        </article>
    </a>
    <a href="/leervragen" class="article-link">
        <article class="article">
            <div class="img-container">
            <img src="/istockphoto-1389448437-612x612-removebg-preview.png" alt="leervragen">
        </div>
            <h2>Leervragen sprint 13</h2>
            <p>"Voor sprint 13 moesten wij een aantal leervragen bedenken. Die kan je hier zien.""</p>
            <p class="datum">02-09-2024</p>
        </article>
    </a>
    </main>
  </div>
  
  <style>
  
    .main-content {
      outline: 2px solid black;
      display: flex;
    flex-wrap: wrap;
    }

    .article {
            border: 1px solid #000000;
            padding: 15px;
            height: 350px;
            cursor: pointer;
            width: 269px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: border-color 0.3s, box-shadow 0.3s;
        }

        .article-link {
    text-decoration: none; /* Verwijdert de onderlijning */
    color: inherit; /* Zorgt ervoor dat de link de tekstkleur van het artikel overneemt */
    display: block; /* Zorgt ervoor dat het hele artikel klikbaar is */
}

.article:focus-within,
.article:hover {
background-color: white;
color: black;
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