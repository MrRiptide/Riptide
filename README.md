# Riptide
* {
    padding: 0;
    margin: 0;
}
.game {
    width: 600px;
    height: 200px;
    border: 1px solid #000000;
    margin: auto;
}
#dino {
    width: 70px;
    height: 70px;
    background-image: url(t-rex.png);
    background-size: auto 70px;
    position: relative;qtop: 143px;
}
.jump {
    animation: jump 0.3s linear;
}
@keyframes jump {
    0% {
        top: 143px; /*distance from the top of the parent element*/
    }
    30% {
        top: 115px;
    }
    50% {
        top: 70px;
    }
    80% {
        top: 115px;
    }
    100% {
        top: 143px;
    }
}
#cactus {
    width: 20px;
    height: 40px;
    position: relative;
    top: 91px;
    left: 580px; /*width of frame - width of cactus*/
    background-image: url(cactus.png);
    background-size: 20px 40px;
    animation: cactus-block 1.2s infinite linear;
}
@keyframes cactus-block {
    0% {
        left: 600px;
    }
    100% {
        left: -20px;
    }
}
