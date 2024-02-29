<body>
    <span class="custom-nav">
        <a href="#">Lumikha</a>
    </span>
    <div class="container">
        <div class="div-flex">
            <img src="tugon-logo.png" alt="">
            <span class="play-nav">
                <a href="#">MAGLARO</a>
            </span>
            <p>
                <a href="#ins">Paano laruin</a>
            </p>
        </div>
        <div class="div-text">
            <h1>Tungkol Saan</h1>
            <p>Ang larong ito ay nagtuturo sa mga Pilipino, lalo na sa mga estudyante at guro na malaman ang iba’t ibang salitang Filipino mapa ito man ay karaniwang ginagamit sa pang araw-draw o kalimitang nakikita sa mga akademikong teksto at minsan lang nagagamit ang mga ito.</p>
        </div>
        <div id="ins" class="div-text">
            <h1>Paano Laruin</h1>
            <p> Sa tulong ng Tugon, layunin nito na tulungan ang mga tao na magamit nang maayos ang mga salitang Filipino at mapa-igting ang kanilang kaalaman sa mga salitang mayroon tayo lalo na sa mga salitang hindi sila masyadong pamilyar o kanilang tinuturing na matalinghaga.</p>
        </div>
    </div>
</body>

<style>
    body {
        background-color: #F3F8FF;
        /* height: 200vh; */
        margin: 50px 25px;
    }
    * {
        font-family: "Lexend Giga", sans-serif;
    }
    img {
        width: 376px;
        height: 376px;
        padding-left: 27px;
    }
    p, p > a, h1 {
        color: #003274;
    }
    p, p > a {
        font-size: 24px;
    }
    h1, .div-text > p {
        font-size: 32;
        font-weight: 400;
    }
    h1 {
        margin-top: 80px;
    }
    .div-text > p {
        margin: 0 50px ;
        text-align: justify;
        text-indent: 50px;
        font-family: 'GlacialIndifference', arial;
        line-height: 2;
    }
    a {
        text-decoration: none;
        color: white;
    }   
    .container {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;       
    }
    .div-flex > p {
        margin: 16px 0 200px    ;  

    }
    .div-flex {
        display: inline-flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    span {
        background-color: #003274;
        border: 12px solid #003274;
        padding: 0 6px 0 6px;
    }
    .play-nav {
        font-size: 48px;
        border-radius: 24px;
    }
    .custom-nav {
        font-size: 16px;
        width: 176px;
        border-radius: 50px;
    }
</style>