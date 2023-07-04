# Tatyanna_Art
Style Guide Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://use.typekit.net/urz2aoc.css">
<link rel="stylesheet" href="https://use.typekit.net/urz2aoc.css">

    <title>StyleGuid-TatyanaArt</title>

</head>

*  body {
    font-family: 'Brandon Grotesque', sans-serif;
    margin: 0 10%;
}

h1 {
    display: block;
    font-size: 2em;
    margin-block-start: 0.67em;
    margin-block-end: 0.67em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bold;
}

div {
    display: block;
}


.container {
    border: 2px solid #a2a2a6;
    padding: 10px;
    margin: 10px auto;
}

h2 {
    display: block;
    font-size: 1.5em;
    margin-block-start: 0.83em;
    margin-block-end: 0.83em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bold;
}


/* Colors */
.color-container {
    width: 100%;
}

.color-panel {
    display: inline-block;
    width: 32%;
    text-align: center;
    margin: 20px auto;
    min-height: 100px;
}

/* .color-panel :hover {
    border: 1px solid #d0d0d0;
    border-radius: 10px;
    
}  */
.color-container .color-panel:hover{
    border: 1px solid #5e531980;
    border-radius: 10px;
}
/* Primary */
.primary {
    background-color: #AC6021;
    color: #fff;
}


p {
    display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
}

/* Secondary */
.secondary {
    background-color: #B8871A;
    color: #000;
}

/* Brand gradient */
.brand-gradiant-linear {
    background: linear-gradient(#B8871A, #AC6021);
}

/* Black */
.black {
    background-color: #292520;
    color: #fff;
}

.black-75 {
    background-color: rgba(41, 37, 32, 75%);
    color: #fff;
}

.black-50 {
    background-color: rgba(41, 37, 32, 50%);
    color: #fff;
}

.black-25 {
    background-color: rgba(41, 37, 32, 25%);
    color: #000;
}

.black-10 {
    background-color: rgba(41, 37, 32, 10%);
    color: #000;
}

.black-5 {
    background-color: rgba(41, 37, 32, 5%);
    color: #000;
}

.error {
    background-color: #C24E1B;
    color: #000;
}



/* Fonts */
.font-panel {
    width: 45%;
    display: inline-block;
}

.font-label {
    font-size: 20px;
    text-decoration: underline;
}

.brandon-grotesque {
    font-family: 'Brandon Grotesque', sans-serif;
}

.regular {
    font-style: normal;
}

.bold {
    font-weight: 700;
}

.italic {
    font-style: italic;
}


.proxima-nova {
    font-family: 'Proxima Nova', serif;
}



/* Text Styles */
.text-panel h1 {
    font-weight: 700;
    font-size: 32px;
    font-family: 'Brandon Grotesque', sans-serif;
}

ul {
    display: block;
    list-style-type: disc;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    padding-inline-start: 40px;
}

li {
    display: list-item;
    text-align: -webkit-match-parent;
    font-family: 'Proxima Nova', serif;
}

/* ::marker {
    unicode-bidi: isolate;
    font-variant-numeric: tabular-nums;
    text-transform: none;
    text-indent: 0px !important;
    text-align: start !important;
    text-align-last: start !important;
} */

.text-panel p {
    font-weight: 400;
    font-size: 14px;
    font-family: 'Proxima Nova', serif;
}


<body>

    <h1>Style Guide TatyanaArt</h1>
    <div class="container">
        <h2>Colors</h2>
        <div class="color-container">
            <div class="color-panel primary">
                <p class="color-label">Primary</p>
                <p class="color-hex">#AC6021</p>
            </div>
            <div class="color-panel secondary">
                <p class="color-label">Secondary</p>
                <p class="color-hex">#B8871A</p>
            </div>
            <div class="color-panel brand-gradiant-linear">
                <p class="color-label">Brand gradiant linear</p>
                <p class="color-hex">#B8871A</p>
            </div>
            <div class="color-panel black">
                <p class="color-label">Black</p>
                <p class="color-hex">#292520</p>
            </div>
            <div class="color-panel black-75">
                <p class="color-label">Black-75</p>
                <p class="color-hex">rgba(41, 37, 32, 75%)</p>
            </div>
            <div class="color-panel black-50">
                <p class="color-label">Black-50</p>
                <p class="color-hex">rgba(41, 37, 32, 50%)</p>
            </div>
            <div class="color-panel black-25">
                <p class="color-label">Black-25</p>
                <p class="color-hex">rgba(41, 37, 32, 25%)</p>
            </div>
            <div class="color-panel black-10">
                <p class="color-label">Black-10</p>
                <p class="color-hex">rgba(41, 37, 32, 10%)</p>
            </div>
            <div class="color-panel black-5">
                <p class="color-label">Black-5</p>
                <p class="color-hex">rgba(41, 37, 32, 5%)</p>
            </div>
            <div class="color-panel error">
                <p class="color-label">Error</p>
                <p class="color-hex">#C24E1B</p>
            </div>
            
        </div>

    </div>

    <div class="container">
        <h2>Fonts</h2>
        <div class="font-container">
            <div class="font-panel">
                <p class="font-label brandon-grotesque">Brandon Grotesque</p>
                <p class="regular brandon-grotesque">The quick brown fox jumps over the lazy dog.</p>
                <p class="bold brandon-grotesque">The quick brown fox jumps over the lazy dog.</p>
                <p class="italic brandon-grotesque">The quick brown fox jumps over the lazy dog.</p>
            </div>
            <div class="font-panel">
                <p class="font-label proxima-nova">Proxima Nova</p>
                <p class="regular proxima-nova">The quick brown fox jumps over the lazy dog.</p>
                <p class="bold proxima-nova">The quick brown fox jumps over the lazy dog.</p>
                <p class="italic proxima-nova">The quick brown fox jumps over the lazy dog.</p>
            </div>
            
        </div>
    </div>

   
   <!-- Test Styles -->
    <!-- /* use ::marker here */ -->
    <div class="container">
        <h2>Text Styles</h2>
        <div class="text-panel">
            <h1>H1: Main page heading</h1>
            <ul>
                <li>
                    Font-weight: 700 (bold)
                </li>
                <li>
                    Font-size: 26px
                </li>
                <li>
                    Font-family: Brandon Grotesque
                </li>
            </ul>
        </div>
        <div class="text-panel">
            <h2>H2: Subheading</h2>
            <ul>
                <li>
                    Font-weight: 500
                </li>
                <li>
                    Font-size: 18px
                </li>
                <li>
                    Font-family: Brandon Grotesque
                </li>
            </ul>
        </div>
        <div class="text-panel">
            <p>P: Paragraph text</p>
            <ul>
                <li>
                    Font-weight: 400 (regular)
                </li>
                <li>
                    Font-size: 14px
                </li>
                <li>
                    Font-family: Proxima Nova
                </li>
            </ul>
        </div>
        

    </div>
    
</body>
</html>
