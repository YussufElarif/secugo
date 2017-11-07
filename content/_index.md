---
featured_image: "test"
---
<div class="index text-center">
    <section>
        <h1>Title</h1>
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
            <div class="container">
                <img class="col-xs-12 col-sm-6" src="http://via.placeholder.com/300.png" />
                <div class="col-xs-12 col-sm-6">
                </div>
            </div>
        </div>
    </section>
</div>

<style>  
    .index .more-info {
        height: 500px;
    }
    .index .more-info .jumbotron {
        position: absolute;
        left: 0;
        right: 0;
        height: 500px;
    }
    .index .more-info .jumbotron img {
        max-height: 450px;
        max-width: 450px;
        min-height: 400px;
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
        border: 3px solid #38393a;
        border-radius: 100%;
        height: 48px;
        width: 48px;
        line-height: 45px;
        color: #38393a;
        cursor: pointer;
    }
    .index ul li .circle:active {
        border-color: rgba(0, 0, 0, 0.5);
        color: rgba(0, 0, 0, 0.5);
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