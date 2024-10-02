
<div class="container">
    <main class="main-content">
        <article class="article">
            <div class="img-container">
            <img src="/Screenshot 2024-10-02 104205.png" alt="">
        </div>
            <h2>Vasilis van Gemert</h2>
            <ul>
                <li>"10 jaar les: enthousiast, geschiedenis van hem -- kunstenaar nieuwe css technieken proberen, trial and error </li>
                    <li>lovenonsense.com nutteloze dingen zijn nuttig nieuw iets kijken wat hij ermee kan </li>
                        <li>verschillende klokken vasilis.nl/ wowclock deze vond ik echt heel gaaf en goofy wtf! man houdt van klokken </li>
                            <li>toegankelijkheid uit de comfortzonen niet alleen de checklist. Website redesign voor blinde blinden hebben veel problemen met het web. </li>    
<li>   maak toffe dingen! wees uniek en denk aan toegankelijkheid"</li>
            
            </ul>
            <p class="datum">02-10-2024</p>
        </article>
    </main>
</div>

<div class="walking-guy-footer" id="walking-guy-footer"></div>

<style>


.walking-guy-footer {
            position: absolute;
            top: 96%;
            right: -60px;
            transform: translateY(-50%);
            width: 50px;
            height: 50px;
            background: url('/pngtree-boy-pixel-little-man-illustration-image_1433979-removebg-preview.png') no-repeat;
            background-size: cover;
            animation: walk-header 20s linear infinite;
        }



        @keyframes walk-header {
            0% {
                transform: translateY(-50%) translateX(100%);
            }
            100% {
                transform: translateY(-50%) translateX(-100vw);
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
          height: 575px;
          cursor: pointer;
          width: 400px;
          box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
          transition: border-color 0.3s, box-shadow 0.3s;
      }

.article:focus-within,
.article:hover {
background-color: white;
color: black;
}
 .article img {
          width: 500px;
          height: 200px;
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