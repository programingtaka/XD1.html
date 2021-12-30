<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="XD.css">
    <title>XD</title>
</head>
<body>
    <header id="header">
        <h1 class="site-title"><a href="#">クリ☆スタ</a></h1>
        <div class="nav-wrapper">
            <nav class="header-nav">
                <ul class="nav-list">
                    <li class="nav-item"><a href="#">About</a></li>
                    <li class="nav-item"><a href="#">Service</a></li>
                    <li class="nav-item"><a href="#">Contents</a></li>
                </ul>
            </nav>
        </div>
    </header>
<main>
    <div class="fv">
        <p class="main-copy">Cresta.Design</p>
    </div>

    <section class="section-wrapper" id="about">
        <h2 class="section-title">About</h2>
        <h3 class="about-title">ミニマルで<br>洗練されたデザインを</h3>
        <p class="text_about">
            近年、ミニマルなデザインが流行しています。そこで弊社では、
            クライアント企業様新規サービス等の課題に対してミニマルで洗練されたデザインを実現させることで解決のサポートを致します。
            もちろん全てのサービスにおいてミニマルなデザインが課題解決になるわけではないので、
            課題や今後のサービスの展開等しっかりとヒアリングを行なった上でご提案させて頂きます。
        </p>
    </section>

    <section class="section-wrapper" id="service">
        <h2 class="section-title">Service</h2>
        <div class="content-inner">
            <div class="text-wrapper_service">
                <h3 class="service-title">
                    リリース時のサポートで<br>サービスのブランディングを
                </h3>
                <p class="section-text_service">
                    弊社では、リリース時もサポートさせて頂きます。
                    プレスリリース用のサイトや動画制作を通して、
                    サービスのブランディングを行わせて頂きます。
                </p>
            </div>
            <div class="img-wrapper_service">
                <img src="service-image.png" alt="">
            </div>
        </div>
        <div class="content-inner reverse">
            <div class="text-wrapper_service">
                <h3 class="service-title">リリース後のサポートで<br>効果を最大化させる</h3>
                <p class="section-text_service">
                    弊社では、リリース後もサポートさせて頂きます。
                    サービスはリリース後に様々な課題にぶつかります。
                    そこでクライアント様と一緒に改善を行うことで、
                    デザインの効果を最大化させます。
                </p>
            </div>
            <div class="img-wrapper_service">
                <img src="service-image.jpg" alt="">
            </div>
        </div>
    </section>

    <section class="section-wrapper" id="news">
        <h2 class="section-title">News</h2>
        <ul class="card-list">
            <li class="card-item">
                <a href="#">
                    <div class="card-img">
                        <img src="card-image1.png" alt="">
                    </div>
                    <p class="text_news">
                        新規サイトを公開しました。
                        今回のサイトは白と黒を基調にした
                        ミニマルなデザインになっています。
                    </p>
                </a>
            </li>
            <li class="card-item">
                <a href="#">
                    <div class="card-img">
                        <img src="card-image2.png" alt="">
                    </div>
                    <p class="text_news">
                        新規サイトを公開しました。
                        今回のサイトは白と黒を基調にした
                        ミニマルなデザインになっています。
                    </p>
                </a>
            </li>
            <li class="card-item">
                <a href="#">
                    <div class="card-img">
                        <img src="card-image3.png" alt="">
                    </div>
                    <p class="text_news">
                        新規サイトを公開しました。
                        今回のサイトは白と黒を基調にした
                        ミニマルなデザインになっています。
                    </p>
                </a>
            </li>
        </ul>
    </section>

    <section class="section-wrapper">
        <h2 class="section-title">Contact</h2>
        <form action="" class="form">
            <div class="form-part">
                <label for="input-name">担当者名</label>
                <input type="text" id="input-name">
            </div>
            <div class="form-part">
                <label for="input-tel">電話番号</label>
                <input type="text" id="input-tel">
            </div>
            <div class="form-part">
                <label for="input-mail">メールアドレス</label>
                <input type="text" id="input-mail">
            </div>
            <div class="form-part">
                <label for="detail">お問い合わせ内容</label>
                <textarea name="detail" id="detail"  cols="30" rows="10"></textarea>
            </div>
            <div class="form-send">
                <input type="submit" value="送信" class="form-btn">
            </div>
        </form>
    </section>
</main>

<footer class="footer">
    <small>©︎crest.design all rights reserved</small>
</footer>
</body>
</html>
