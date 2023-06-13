@import url('https://fonts.googleapis.com/css2?family=Lato:wght@100;300;400;700;900&family=Open+Sans:wght@300;400;700;800&display=swap');


   <div class="boxtitle">
        <h1>
            <span class="boldtitle">&lt;</span>
            <span class="lighttitle">drondio</span> <br>
            <span class="boldtitle"> dev.</span> <br>
            <span class="boldtitle2">portfolio &gt;</span>
        </h1>
    </div>



    :root {
    --white: white;
    --lato: 'Lato', sans-serif;
    --opensans: 'Open Sans', sans-serif;
}

/** STYLE PAR DEFAUT **/
.boxtitle {
    padding: 0;
    margin: 0;

}


/**  TITLE   **/
h1 {
    /* position: absolute; */
    color: #777;
    font-family: var(--lato);
    left: 50%;
    width: fit-content;
    text-transform: uppercase;
    text-align: center;
    font-size: 22px;
}



.boldtitle {
    font-weight: 600;
}

.boldtitle2 {
    font-weight: 600;
    transform: translateX(40%);
    display: flex;
}

.lighttitle {
    font-weight: 100;
    text-decoration: line-through;

}

.boldtitle2::before {
    content: '_____';
    position: absolute;
    transform: translate(-96%, -38%);
    display: inline-block;
    font-weight: 600;
}