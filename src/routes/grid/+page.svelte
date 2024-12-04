<div class="container">
    <div class="grid-container">
        <div class="item grid-item-1">1</div>
        <div class="item grid-item-2">2</div>
        <div class="item grid-item-3">3</div>
        <div class="item grid-item-4">4</div>
        <div class="item grid-item-5">5</div>
        <div class="item grid-item-6">6</div>
    </div>
    <div class="explanation">
        <h3>CSS Grid Uitleg</h3>
        <ul>
            <li><strong>Grid-container:</strong> Gebruik `display: grid;` om een grid-layout te activeren.</li>
            <li><strong>Kolommen:</strong> De eigenschap `grid-template-columns` definieert hoeveel kolommen er zijn.</li>
            <li><strong>Rijen:</strong> Gebruik `grid-template-rows` om rijen in te stellen.</li>
            <li><strong>Positionering:</strong> Gebruik `grid-column` en `grid-row` om items te plaatsen.</li>
            <li>https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout</li>
        </ul>
    </div>
</div>

<style>
    .grid-container {
    display: grid;
    grid-template-columns: repeat(3, 100px); /* Drie kolommen van elk 100px breed */
    grid-gap: 10px; /* Afstand tussen de grid-elementen */
    background-color: #e1e5ee;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

.container {
    display: flex;
    gap: 20px;
}

.item {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #76c7c0;
    color: white;
    font-size: 20px;
    font-weight: bold;
    height: 100px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}

/* Specifieke positionering van grid-items */
.grid-item-1 {
    grid-column: span 3; /* Neemt 2 kolommen in */
}

.grid-item-2{
    grid-column: span 2;
}

</style>