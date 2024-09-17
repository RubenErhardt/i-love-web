<header class="header">
    <p>Ruben Erhardt's Digital Garden</p>
    <p>
        <a href="https://github.com/rubenerhardt" target="_blank" rel="noopener noreferrer">Github</a>
    </p>
    <!-- Walking Guy -->
    <div class="walking-guy-header" id="walking-guy-header"></div>
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
    </main>
  </div>
  
  <style>
    .header {
      padding: 20px;
      position: relative;
      display: flex;
      overflow: hidden;
    justify-content: space-between; /* Space between the items */
    align-items: center;
      outline: 2px solid black;
    }

    /* Walking Guy Styles for Header */
.walking-guy-header {
    position: absolute;
    top: 50%; /* Position the guy vertically centered */
    right: -60px; /* Starting position from outside the right edge */
    transform: translateY(-50%); /* Center it vertically */
    width: 50px; /* Width of the walking guy */
    height: 50px; /* Height of the walking guy */
    background: url('/pngtree-boy-pixel-little-man-illustration-image_1433979-removebg-preview.png') no-repeat; /* Replace with your walking guy image */
    background-size: cover; /* Ensure the background fits */
    animation: walk-header 20s linear infinite; /* Animation duration and looping */
}

/* Walking Animation for Header */
@keyframes walk-header {
    0% {
        transform: translateY(-50%) translateX(100%);
    }
    100% {
        transform: translateY(-50%) translateX(-100vw); /* Walks from right to left across the viewport */
    }
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
        position: relative;
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
  