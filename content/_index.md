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
    <ul>
        <li class="col-xs-3 text-center"><span class="circle fa fa-lock"></span></li>
        <li class="col-xs-3 text-center"><span class="circle fa fa-key"></span></li>
        <li class="col-xs-3 text-center"><span class="circle fa fa-video-camera"></span></li>
        <li class="col-xs-3 text-center"><span class="circle fa fa-home"></span></li>
    </ul>
</div>

<style>
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
    }

    @media (min-width: 992px) {
        .index ul li .circle {
            border-width: 6px;            
            width: 125px;
            height: 125px;
            line-height: 125px;
            font-size: 200%;            
        }
    }
</style>