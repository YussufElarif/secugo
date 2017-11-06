---
featured_image: "test"
---
<div class="text-center">
    <ul class="text-center">
        <li class="col-xs-3"><span class="circle fa fa-lock"></span></li>
        <li class="col-xs-3"><span class="circle fa fa-key"></span></li>
        <li class="col-xs-3"><span class="circle fa fa-video-camera"></span></li>
        <li class="col-xs-3"><span class="circle fa fa-home"></span></li>
    </ul>
</div>

<style>
    ul.text-center {
        display: inline-block;
        padding: 0;
    }

    li {
        list-style: none;
    }

    ul li .circle {
        border: 3px solid #38393a;
        border-radius: 100%;
        height: 48px;
        width: 48px;
        line-height: 45px;
        float: left;
        color: #38393a;
        cursor: pointer;
    }

    ul li .circle:active {
        border-color: rgba(0, 0, 0, 0.5);
        color: rgba(0, 0, 0, 0.5);
    }

    @media (min-width: 415px) {
        ul li .circle {
            width: 75px;
            height: 75px;
            line-height: 75px;
            font-size: 150%;
        }
    }

    @media (min-width: 768px) {
        ul li .circle {
            width: 100px;
            height: 100px;
            line-height: 100px;
            font-size: 175%;            
        }
    }

    @media (min-width: 992px) {
        ul li .circle {
            width: 125px;
            height: 125px;
            line-height: 125px;
            font-size: 200%;            
        }
    }
</style>