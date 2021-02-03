
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hey</title>
    <link rel="stylesheet" href="main.css">
</head>
<body>
    <div class="navbar">
        <div class="container">
            <a href="#" class="logo">Talk <span>Back</span></a>
            
            <img id="mobile-cta" class="mobile-menu" src="images/menu.svg" alt="drop-down-menu">

            <nav>
                <img id="mobile-exit" class="mobile-exit-menu" src="images/exit.svg" alt="exit_button">
                
                <ul class="primary-row">
                    <li class="current"><a href="#">Home</a></li>
                    <li><a href="#">Features</a></li>
                    <li><a href="#">Pricing</a></li>
                </ul>

                <ul class="secondary">
                    <li><a href="#">contact</a></li>
                    <li class="go-premium"><a href="#">Premium</a></li>
                </ul>
            </nav>
        </div>
    </div>

    <section class="hero">
        <div class="container">
            <div class="left-col">
                <p class="subhead">By Hemang &amp; Poonia</p>
                <h1>An Intelligent bot that talks back</h1>

                <div class="hero-cta">
                    <a href="#" class="primary-cta">try for free</a>
                    <a href="#" class="watch-video">
                        <img src="images/watch.svg" alt="watch-icon">
                        watch a video
                    </a>
                </div>
            </div>

            <img src="images/illustration.svg" class="hero-img" alt="illustrations">

        </div>
    </section>

    <section class="features-bullets">
        <div class="container">
            <ul class="list">
                <li>A1</li>
                <li>A2</li>
                <li>A3</li>
                <li>A4</li>
                <li>A5</li>
            </ul>

            <img class="section-img" src="images/holding-phone.jpg" alt="holding phone man">

        </div>
    </section>

    <section class="testimonials">
        <div class="container">
            <ul>
                <li>
                    <img src="images/person.jpg" alt="person1">
                    <blockquote>"its true"</blockquote>
                    <cite>-hemanga</cite>
                </li>
                <li>
                    <img src="images/person.jpg" alt="person1">
                    <blockquote>"its true"</blockquote>
                    <cite>-hemanga</cite>
                </li>
                <li>
                    <img src="images/person.jpg" alt="person1">
                    <blockquote>"its true"</blockquote>
                    <cite>-hemanga</cite>
                </li>
            </ul>
        </div>

    </section>

    <section class="contact-section">
        <div class="container">
            <div class="contact-left">
                <h2>contact</h2>

                <form action="">

                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" placeholder="your name">

                    <label for="email">E-mail</label>
                    <input type="email" id="email" name="email">

                    <label for="message">Message</label>
                    <textarea name="message" id="message" cols="30" rows="10">type here</textarea>
                
                    <input type="submit" class="send-message" value="SEND">
                </form>
            </div>
            <div class="contact-right">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d227748.99973965858!2d75.65046968942386!3d26.885141677004984!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x396c4adf4c57e281%3A0xce1c63a0cf22e09!2sJaipur%2C%20Rajasthan!5e0!3m2!1sen!2sin!4v1612210917951!5m2!1sen!2sin" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
            </div>
        </div>


    </section>

    <script>

        const mobileBtn = document.getElementById('mobile-cta')
             nav = document.querySelector('nav')
             mobileBtnExit = document.getElementById('mobile-exit');

        mobileBtn.addEventListener('click', () => {
            nav.classList.add('menu-btn');
        })
        
        mobileBtnExit.addEventListener('click', () => {
            nav.classList.remove('menu-btn');
        })

    </script>


    ABCDEF
    <a href=""></a>
</body>
</html>
