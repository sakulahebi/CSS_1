# CSS_1

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" type="text/css" href="rest.css">
    <style>
        .head{
            display: flex;
            background: black;
            padding: 6px 10px;

        }
        .head .logo{
            display: inline-block;
            padding: 10px 0 ;
        }
        .head nav{
            text-align: right;       
            width: 100%;
            font-size: 0px;
        }
        .head nav a{
            font-size: 16px;
            color: #ffffff;
            display: inline-block;
            line-height: 52px;
            text-decoration: none;
            padding: 0 10px;
        }
        .head nav a:hover{
            background: rosybrown;
        }
        .banner img{
            width: 100%;
        }
        .path{
            display: flex;
        }
        .path li{
            position: relative;
            padding: 6px 8px;
        }
        .path li a{
            color: royalblue;
            text-decoration: none;
            font-size: 14px;
        }
        .path li + li::before{
            content:'/';
            color: sandybrown;
            position: absolute;
            left: 0;
        }
        .item h3{
            font-size: 36px;
            padding: 0 0 30px;
        }
        .warp{
            width: 960px;
            margin: auto;
        }
        .about{
            padding: 40px 0 60px;
        }
        .about .warp{
            display: flex;
        }
        .about .warp .item{
            width: 300px;
            margin: 0 10px;
            text-align: center;
        }
        .about .warp .item img{
            border-radius: 50%;
        }

        .about > h2{
            width: 100%;
            padding: 20px 0;
            font-size: 42px;
            text-align: center;
        }
        .about > p{
            width: 760px;
            margin: auto;
            padding: 0 0 40px;
            text-align: center;
        }
        .products{
            background: #eeeeee;
        }
        .products .wrap{
            display: flex;
        }
        .products .item{
            width: 50%;
        }
        .products .item img{
            width: 100%;
            vertical-align: bottom;
        }

        .products .text{
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 0 20px;
            text-align: center;
        }

        .service{
            padding: 40px 0;
            background-color: #ffa;
        }
        .service .wrap{
            display: flex;
        }
        .service > h2{
            width: 960px;
            margin: auto;
            text-align: center;
            font-size: 42px;
            padding: 20px 0;
        }
        .service > p{
            width: 960px;
            margin: auto;
            text-align: center;
            padding-bottom: 40px;
        }
        .service .item{
            margin: 0 10px;
            width: 300px;
            text-align: center;
        }
        .service .item h3{

        }
        .service .item p{

        }
        .service .item img{
            width: 100%;
        }


        .footer{
            text-align: center;
            background: #000000;
            padding: 20px 0;
            color: #ffffff;
        }
    </style>
</head>
<body>
    <div class="head">
        <a href="#" class="logo"><img src="https://picsum.photos/80/30?reandom=1" alt=""></a>
        <nav>
            <a href="#">home</a>
            <a href="#">aboutl</a>
            <a href="#">shop</a>
            <a href="#">ex</a>
        </nav>
    </div>


    <div class="banner">
        <img src="https://picsum.photos/1200/300?random=2" alt="">
    </div>

    <ul class="path">
        <li><a href="#">home</a></li>
        <li><a href="#">new</a></li>
        <li><a href="#">home</a></li>
    </ul>

    <div class="about">
            <h2>關於我們</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus ullam blanditiis facilis, voluptas tenetur dolorem.</p>
        <div class="warp">
            <div class="item"><img src="https://picsum.photos/100/100?random=3" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci, impedit numquam libero fuga dolor assumenda. Officia ab perferendis unde alias consequatur repellendus numquam officiis, quasi debitis, voluptas illum minus sit?</p>
            </div>
            <div class="item"><img src="https://picsum.photos/100/100?random=3" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci, impedit numquam libero fuga dolor assumenda. Officia ab perferendis unde alias consequatur repellendus numquam officiis, quasi debitis, voluptas illum minus sit?</p>
            </div>
            <div class="item"><img src="https://picsum.photos/100/100?random=3" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci, impedit numquam libero fuga dolor assumenda. Officia ab perferendis unde alias consequatur repellendus numquam officiis, quasi debitis, voluptas illum minus sit?</p>
            </div>
        </div>
    </div>

    <div class="products">
        <div class="wrap">
            <div class="item pic">
                <img src="https://picsum.photos/500/500?random=3" alt="">
            </div>
            <div class="item text">
                <h3>title</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur incidunt dolores animi officia veniam sed.</p>
            </div>
        </div>
    </div>

    <div class="service">
        <h2>服務項目</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi unde odit, accusamus illum perspiciatis sapiente consectetur, laboriosam fugit nulla facere temporibus labore, praesentium est autem nam eos ab ipsa reiciendis.</p>
        <div class="wrap">
            <div class="item">
                <img src="https://picsum.photos/id/684/600/400" alt="">
                <h3>title</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam, odit.</p>
            </div>
            <div class="item">
                <img src="https://picsum.photos/id/684/600/400" alt="">
                <h3>title</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam, odit.</p>
            </div>
            <div class="item">
                <img src="https://picsum.photos/id/684/600/400" alt="">
                <h3>title</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam, odit.</p>
            </div>
            <div class="item">
                <img src="https://picsum.photos/id/684/600/400" alt="">
                <h3>title</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam, odit.</p>
            </div>
        </div>
    </div>



    <div class="footer">
        &copy; by CSS
    </div>



</body>
</html>
