# OracleKass.github.io
UX Website
html,
body {
    width: 100%;
    height: 100%;
    font-family: 'Open Sans','Helvetica Neue',Arial,sans-serif;
}

a {
    color: yellowgreen;
    -webkit-transition: all .35s;
    -moz-transition: all .35s;
    transition: all .35s;
}

a:hover,
a:focus {
    color: forestgreen;
}

p {
    font-size: 16px;
    line-height: 1.5;
}

header {
    position: relative;
    width: 100%;
    min-height: auto;
    text-align: center;
    color: #fff;
    background-image: url('../images/header.jpg');
    background-position: center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    background-size: cover;
    -o-background-size: cover;
}

header .header-content {
    position: relative;
    width: 100%;
    padding: 100px 15px 70px;
    text-align: center;
}

header .header-content .header-content-inner h1 {
    margin-top: 0;
    margin-bottom: 20px;
    font-size: 50px;
    font-weight: 300;
}

header .header-content .header-content-inner p {
    margin-bottom: 50px;
    font-size: 16px;
    font-weight: 300;
    color: rgba(255,255,255,.7);
}

@media(min-width:768px) {
    header {
        min-height: 100%;
    }

    header .header-content {
        position: absolute;
        top: 50%;
        padding: 0 50px;
        -webkit-transform: translateY(-50%);
        -ms-transform: translateY(-50%);
        transform: translateY(-50%);
    }

    header .header-content .header-content-inner {
        margin-right: auto;
        margin-left: auto;
        max-width: 1000px;
    }

	header .header-content .header-content-inner h1 {
    	font-size: 100px;
		}

    header .header-content .header-content-inner p {
        margin-right: auto;
        margin-left: auto;
        max-width: 80%;
        font-size: 18px;
    }
}

.section-heading {
    margin-top: 0;
    margin-bottom: 20px;
}

.intro {
	color: #fff;
    background-color: yellowgreen;
    padding: 70px 0;
    text-align: center;
}

.content {
    padding: 100px 0;
}

.content-2 {
	color: #fff;
    background-color: #222;
}

.content-3 {
	padding: 20px 0 40px;
	text-align: center;
}

.promo,
.promo h3,
.promo a:link,
.promo a:visited,
.promo a:hover,
.promo a:active {
    color: white;
	text-shadow: 0px 0px 40px black;
    text-decoration: none;
}

.promo-item {
    height: 200px;
    line-height: 180px;
    text-align: center;
}

.promo-item:hover {
    background-size: 110%; 
    border: 10px solid rgba(255,255,255,0.3);
    line-height: 160px;
}

.promo-item h3 {
    font-size: 40px;
    display: inline-block;
    vertical-align: middle;
}

.item-1 {
	background: url('../images/writing.jpg');
	}
	
.item-2 {
	background: url('../images/concert.jpg');
	}
	
.item-3 {
	background: url('../images/pencil_sharpener.jpg');
	}
		
.item-1,
.item-2,
.item-3 {
	background-size: cover;
	background-position: 50% 50%;
	}

.page-footer {
	text-align: center;
	}

.page-footer .contact {
	padding: 100px 0;
	background-color: yellowgreen;
	color: #fff;
	}

.page-footer .contact p {
	font-size: 22px;
	font-weight: 300;
	}
	
.content-3 .glyphicon,	
.page-footer .contact .glyphicon {
	font-size: 32px;
	font-weight: 700;
	}
		
.page-footer .small-print {
	padding: 50px 0 40px;
	font-weight: 300;
	}

.text-light {
    color: rgba(255,255,255,.7);
}

.navbar-default {
    border-color: rgba(34,34,34,.05);
    background-color: #fff;
    -webkit-transition: all .35s;
    -moz-transition: all .35s;
    transition: all .35s;
}

.navbar-default .navbar-header .navbar-brand {
    color: yellowgreen;
}

.navbar-default .navbar-header .navbar-brand:hover,
.navbar-default .navbar-header .navbar-brand:focus {
    color: #eb3812;
}

.navbar-default .nav > li>a,
.navbar-default .nav>li>a:focus {
    color: #222;
}

.navbar-default .nav > li>a:hover,
.navbar-default .nav>li>a:focus:hover {
    color: yellowgreen;
}

.navbar-default .nav > li.active>a,
.navbar-default .nav>li.active>a:focus {
    color: yellowgreen!important;
    background-color: transparent;
}

.navbar-default .nav > li.active>a:hover,
.navbar-default .nav>li.active>a:focus:hover {
    background-color: transparent;
}

@media(min-width:768px) {
    .navbar-default {
        border-color: rgba(255,255,255,.3);
        background-color: transparent;
    }

    .navbar-default .navbar-header .navbar-brand {
        color: rgba(255,255,255,.7);
        letter-spacing: 0.5em;
    }

    .navbar-default .navbar-header .navbar-brand:hover,
    .navbar-default .navbar-header .navbar-brand:focus {
        color: #fff;
    }

    .navbar-default .nav > li>a,
    .navbar-default .nav>li>a:focus {
        color: rgba(255,255,255,.7);
    }

    .navbar-default .nav > li>a:hover,
    .navbar-default .nav>li>a:focus:hover {
        color: #fff;
    }

    .navbar-default.affix {
        border-color: #fff;
        background-color: #fff;
        box-shadow: 0px 7px 20px 0px rgba(0,0,0,0.1);
    }

    .navbar-default.affix .navbar-header .navbar-brand {
        letter-spacing: 0;
        color: yellowgreen;
    }

    .navbar-default.affix .navbar-header .navbar-brand:hover,
    .navbar-default.affix .navbar-header .navbar-brand:focus {
        color: #eb3812;
    }

    .navbar-default.affix .nav > li>a,
    .navbar-default.affix .nav>li>a:focus {
        color: #222;
    }

    .navbar-default.affix .nav > li>a:hover,
    .navbar-default.affix .nav>li>a:focus:hover {
        color: yellowgreen;
    }
}

.btn-default {
    border-color: #fff;
    color: #222;
    background-color: #fff;
    -webkit-transition: all .35s;
    -moz-transition: all .35s;
    transition: all .35s;
}

.btn-default:hover,
.btn-default:focus,
.btn-default.focus,
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
    border-color: #eee;
    color: #222;
    background-color: #eee;
}

.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
    background-image: none;
}

.btn-default.disabled,
.btn-default[disabled],
fieldset[disabled] .btn-default,
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus,
.btn-default.disabled:active,
.btn-default[disabled]:active,
fieldset[disabled] .btn-default:active,
.btn-default.disabled.active,
.btn-default[disabled].active,
fieldset[disabled] .btn-default.active {
    border-color: #fff;
    background-color: #fff;
}

.btn-default .badge {
    color: #fff;
    background-color: #222;
}

.btn-primary {
    border-color: yellowgreen;
    color: #fff;
    background-color: yellowgreen;
    -webkit-transition: all .35s;
    -moz-transition: all .35s;
    transition: all .35s;
}

.btn-primary:hover,
.btn-primary:focus,
.btn-primary.focus,
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
    border-color: limegreen;
    color: #fff;
    background-color: limegreen;
}

.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
    background-image: none;
}

.btn-primary.disabled,
.btn-primary[disabled],
fieldset[disabled] .btn-primary,
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus,
.btn-primary.disabled:active,
.btn-primary[disabled]:active,
fieldset[disabled] .btn-primary:active,
.btn-primary.disabled.active,
.btn-primary[disabled].active,
fieldset[disabled] .btn-primary.active {
    border-color: yellowgreen;
    background-color: yellowgreen;
}

.btn-primary .badge {
    color: yellowgreen;
    background-color: #fff;
}


.btn {
    border-radius: 300px;
    text-transform: uppercase;
}

.btn-lg {
    padding: 15px 30px;
}

::-moz-selection {
    text-shadow: none;
    color: #fff;
    background: #222;
}

::selection {
    text-shadow: none;
    color: #fff;
    background: #222;
}

img::selection {
    color: #fff;
    background: 0 0;
}

img::-moz-selection {
    color: #fff;
    background: 0 0;
}

.text-primary {
    color: yellowgreen;
}

.bg-primary {
    background-color: yellowgreen;
}
