---
featured_image: "http://www.centrum-security.co.uk/wp-content/uploads/2017/03/shop-banner-2.jpg"
---
<div class="index text-center">
    <section>
        <h1>Title</h1>
        <hr/>
        <p class="col-xs-12 col-sm-8 col-sm-offset-2">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus sodales sed est a sollicitudin. Nam at laoreet nunc. Fusce efficitur orci non felis viverra ullamcorper. Aliquam non felis a leo ultrices placerat. Sed vel tortor eget magna mattis laoreet euismod sit amet libero. Suspendisse congue nisl sem, eget porta magna tristique nec. Etiam consequat ex diam, id condimentum nibh venenatis eu.
        </p>
    </section>
    <section>
        <ul>
            <li class="col-xs-4 col-sm-2 col-sm-offset-1 text-center">
                <span class="circle fa fa-lock"></span>
                <p>Security</p>
            </li>
            <li class="col-xs-4 col-sm-2 text-center">
                <span class="circle fa fa-key"></span>
                <p>Safety</p>
            </li>
            <li class="col-xs-4 col-sm-2 text-center">
                <span class="circle fa fa-video-camera"></span>
                <p>Surveilance</p>
            </li>
            <li class="col-xs-4 col-xs-offset-2 col-sm-2 text-center">
                <span class="circle fa fa-home"></span>
                <p>Protected</p>
            </li>
            <li class="col-xs-4 col-sm-2 text-center">
                <span class="circle fa fa-fire"></span>
                <p>Risk free</p>
            </li>
        </ul>
    </section>
    <section class="more-info">
        <div class="jumbotron">
            <div class="triangle"></div>
            <div class="container">
                <img class="col-xs-12 col-sm-6" src="http://175.107.187.79/~briggselectrical/wp-content/uploads/2016/10/briggs_home-alarm-systems_03.jpg" />
                <div class="col-xs-12 col-sm-6">
                    <h2>Security Installments</h2>
                    <hr/>
                    <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus sodales sed est a sollicitudin. Nam at laoreet nunc. Fusce efficitur orci non felis viverra ullamcorper. Aliquam non felis a leo ultrices placerat. Sed vel tortor eget magna mattis laoreet euismod sit amet libero. Suspendisse congue nisl sem, eget porta magna tristique nec. Etiam consequat ex diam, id condimentum nibh venenatis eu.
                    </span>
                </div>
            </div>
        </div>
    </section>
</div>

<script>
    var circle = document.querySelectorAll("li span.circle");
    var triangle = document.querySelector("div.triangle");
    circle[0].className += " active"
    triangle.style.left = circle[0].getBoundingClientRect().left - (circle[0].getBoundingClientRect().width) - 43;

    window.addEventListener('resize', function(e) {
        var position = document.querySelector("li span.circle.active").getBoundingClientRect();
        triangle.style.left = position.left + (position.width/2) - (triangle.getBoundingClientRect().width/2) + 10;
    });
    
    circle.forEach(function (value) {
        value.addEventListener('click', function(e) {
            circle.forEach(function (value) {
                if (value.className.indexOf("active") !== -1) {
                    value.className = value.className.split(/\bactive\b/).join();
                } 
            });
            var keyword = "active";
            var index = value.className.indexOf(keyword);
            value.className = index !== -1 ? value.className : value.className + " " + keyword;
            var position = value.getBoundingClientRect();
            triangle.style.left = position.left + (position.width/2) - (triangle.getBoundingClientRect().width/2) + 10;
        });
    });
</script>

<style>
    hr {
        width: 50%
    }
    
    .triangle {
        height: 50px;
        width: 50px;
        background: #EEE;
        -ms-transform: rotate(45deg); /* IE 9 */
        -webkit-transform: rotate(45deg); /* Chrome, Safari, Opera */
        transform: rotate(45deg);
        bottom: -25px;
        left: 25px;
        position: absolute;
        top: -25px;
    }

    .index h1, index. h2 {
        margin-bottom: 20px
    }

    .index section {
        padding: 10px 0;
        display: inline-block;
        width: 100%;
    }

    .index .more-info {
        height: 550px;
        width: 100%;
    }

    .index .more-info .jumbotron {
        position: absolute;
        left: 0;
        right: 0;
        height: 500px;
    }
    .index .more-info .jumbotron img {
        max-height: 450px;
        max-width: 500px;
    }

    .index ul {
        display: inline-block;
        padding: 0;
        width: 100%;
    }
    .index li {
        list-style: none;
    }
    .index ul li .circle {
        border: 3px solid #38393A;
        border-radius: 100%;
        height: 48px;
        width: 48px;
        line-height: 45px;
        color: #38393A;
        cursor: pointer;
    }
    .index ul li .circle:active {
        border-color: rgba(0, 0, 0, 0.5);
        color: rgba(0, 0, 0, 0.5);
    }

    .index ul li .circle.active {
        border-color: #2196f3;
        color: #2196f3;
    }

    .index ul li p {
        padding-top: 10px;
    }

    @media (min-width: 415px) {
        .index ul li .circle {
            border-width: 4px;            
            width: 75px;
            height: 75px;
            line-height: 75px;
            font-size: 150%;
        }
    }

    @media (min-width: 768px) {
        .index ul li .circle {
            border-width: 5px;            
            width: 100px;
            height: 100px;
            line-height: 100px;
            font-size: 175%;            
        }
        .col-xs-offset-2 {
            margin-left: 0;   
        }
    }

    @media (min-width: 992px) {
        .index ul li .circle {
            border-width: 6px;            
            width: 125px;
            height: 125px;
            line-height: 125px;
            font-size: 200%;            
        }
        .col-xs-offset-2 {
            margin-left: 0;   
        }
    }
</style>