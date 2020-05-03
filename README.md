# -site-de-merda

    
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}
body {
    margin: 01;
    padding: 01;
}
header {
    min-height: 700px;
    background-image: url("../images/ff2.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: bottom;
    position: relative;
}

header . {
    min-height: 10px;
    width: 10%;    
    background: -moz-linear-gradient(top, rgba(0,0,0,0.65) 0%, rgba(0,0,0,0) 100%);
    background: -webkit-linear-gradient(top, rgba(0,0,0,0.65) 0%,rgba(0,0,0,0) 100%); 
    background: linear-gradient(to bottom, rgba(0,0,0,0.65) 0%,rgba(0,0,0,0) 100%);
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#FFFF00', endColorstr='#FFFF00',GradientType=0 );
}

header .header-border {
    display: flex;
    border-bottom: rgba(255,255,255,.30) 10px solid;
}

header #logo {
    width: 200px;
    color: #fff;
    line-height: 60px;
    text-align: center;
    font-size: 2em;
    font-weight: bold;
    text-shadow: #FFFF00 1px 1px 8px;
} 

}
.menu ul {
    display: flex;
    justify-content: flex-end;
    list-style:nome ;
    padding: 0;
}
.menu li {
    min-width: 1px;
    line-height: 28px;
}
.menu a {
    color: #FFFF00;
    text-decoration: none;
    font-weight: bold;
    padding: 20px;
}

#register {
    background-color: #151515;
    width: 100%;
    height: 400px;
    max-width: 350px;
    position: absolute;
    bottom: 0;
    right: 10vw;
    box-shadow: 0 0 2.1875rem rgba(140,152,164,.125);
    border-top-left-radius: 0.25rem;
    border-top-right-radius: 0.25rem;
    padding: 3px;
    color: #FFFF00;
}

#register p {
    font-size: 1.5em;
    font-weight: bold;
    margin-bottom: 10px;
}

#register .field {
    width: 100%;
    margin-bottom: 30px;
}

#register input {
    width: 100%;
    padding: .75rem 1rem;
    border-radius: 4px;
    border: #CCC 1px solid;
}

#register input[type=radio] {
    width: 25px;
}

#register button {
    width: 100%;
    border: none;
    background-color:#FF0000;
    color: #151515;
    padding: .75rem;
    font-size: 1.2em;
}

.container {
    max-width: 960px;
    margin: auto;
    width: 100%;
    padding-left: 15px;
    padding-right: 15px;
}

.title h1 {
    font-size:3em;
    border-bottom: #CCC 1px solid;
    padding-bottom: 1rem;
}
.home p fdsfdgdfgdfhdfhdghdfhdfh{
    text-align: center;
}

footer {
    background-color:#FF0000;
    color: #6c757d;
    font-size: .8em;
}

footer p {
    line-height: 35px; 
}

footer .container {
    display: flex;
}

footer .menu a {
    color: #6c757d;
}

.menu .open-menu {
    display: none;    
}

.backdrop {
    display:none;
}
.close-menu {
    display: none;
}

@media(max-width: 450px) {
    .menu .close-menu {
        display: block;
        text-align: right;
        background-color:#FF0000;
    }
    .menu .close-menu button {
        background: none;
        border: none;
        font-size: 2em;
        padding: .75rem 1rem;
    }
    .menu.open .backdrop {
        opacity: .5;
        display: block;
    }
    .menu .backdrop {
        opacity: 0;
        background-color: #000;
        transition: opacity .15s linear;
        position: fixed;
        width: 100%;
        height: 100vh;
        z-index: 1;
        left: 0;
        top: 0;
    }
    header .header-border {
        justify-content: space-between;
    }
    .menu ul {
        display: block;
        position: fixed;
        top: 0;
        right: -80vw;
        width: 80vw;
        height: 100vh;
        background-color: #fff;
        z-index: 2;
        margin: 0;
        transition: right .2s linear;
    }
    .menu.open ul {
        right: 0;
    }
    .menu.open a {
        color: #151515;
        padding: 20px;
        display: block;
        font-weight: 100;
        border-bottom: #ccc 1px solid;
    }
    .menu {
        width: 60px;
        flex: initial;
    }
    .menu .open-menu {
        display: block;
        font-size: 2em;
        padding: .9rem;
        flex: 1;
        background: none;
        border: none;
        color: #FF0000;
    }
    #register {
        width: 90%;
        margin: 0 5%;
        max-width: initial;
        right: initial;
    }
}
