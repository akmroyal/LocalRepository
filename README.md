# This is my Local repositry which is my Read me file 

this is a API for Language TR: https://api.mymemory.translated.net/get?q=${text}&langpair=${translateFrom}|${translateTo}



https://www.codewithrandom.com/2023/01/01/language-translator-using-javascript/    url of website 
Source File : CODEWITHRANDAOM

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>A Language Translator</title>
</head>

<body>
    <div class="container">
        <div class="wrapper">
            <div class="text-input">
                <textarea spellcheck="false" class="from-text" placeholder="Enter text"></textarea>
                <ul class="controls">
                    <li class="row from">
                        <div class="icons">
                            <ion-icon id="from" name="volume-medium-outline"></ion-icon>
                            <ion-icon id="from" name="copy-outline"></ion-icon>
                        </div>
                        <select></select>
                    </li>
                    <li class="exchange">
                        <ion-icon name="swap-vertical"></ion-icon>
                    <li class="row to">
                        <select></select>
                        <div class="icons">
                            <ion-icon id="to" name="volume-medium-outline"></ion-icon>
                            <ion-icon id="to" name="copy-outline"></ion-icon>
                        </div>
                    </li>
                </ul>
                <textarea spellcheck="false" readonly disabled class="to-text" placeholder="Translation"></textarea>
            </div>
        </div>
        <button>Translate it</button>
    </div>
    <script src="script.js"></script>
</body>

</html>
