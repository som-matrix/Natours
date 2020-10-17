<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <link href="https://fonts.googleapis.com/css?family=Lato:100,300,400,700,900" rel="stylesheet">

        <link rel="stylesheet" href="css/icon-fonts.css">
        <link rel="stylesheet" href="css/styles.css">
        <link rel="shortcut icon" type="image/png" href="img/favicon.png">

        <title>Natours | Exciting tours for adventurous people</title>
    </head>
    <body>
       <div class="navigation">
         <input type="checkbox" class="navigation__checkbox" id="navigation-toggle">
         <label for="navigation-toggle" class="navigation__button">
           <span class="navigation__icon">&nbsp;</span>
         </label>

          <div class="navigation__background">&nbsp;</div>
          <nav class="navigation__nav">
            <ul class="navigation__list">
              <li class="navigation__items"><a href="#" class="navigation__links"><span>01</span> About Natours</a></li>
              <li class="navigation__items"><a href="#" class="navigation__links"><span>02</span> Your Benefits</a></li>
              <li class="navigation__items"><a href="#" class="navigation__links"><span>03</span> Popular Tours</a></li>
              <li class="navigation__items"><a href="#" class="navigation__links"><span>04</span> Stories</a></li>
              <li class="navigation__items"><a href="#" class="navigation__links"><span>05</span> Book Now</a></li>
            </ul>
          </nav> 
       </div>
       <header class="header">
         <div class="header__logo-box">
           <img src="./img/logo-white.png" alt="logo" class="header__logo">
         </div>
         <div class="header__text-box">
           <h1 class="text-heading">
             <span class="text-heading--main">outdoors</span>
             <span class="text-heading--sub">is always what matters</span>
           </h1>

           <a href="#section-tours"class="btn btn--white btn--animated">discover tools</a>
         </div>
       </header>

       <main>
         <section class="section-about">
           <div class="u-center-text u-margin-bottom-big">
             <h2 class="heading-secondary">
               Exciting tours for adventorous people
             </h2>
           </div>
           
           <div class="row">
             <div class="col-1-of-2">
               <h3 class="heading-tertiary u-margin-bottom-small">Fall in love with nature</h3>
               <p class="paragraph">
                 Lorem ipsum dolor sit amet consectetur adipisicing elit.
                 Quaerat hic iusto omnis praesentium, unde recusandae veniam harum pariatur perspiciatis laboriosam.
                 Accusamus voluptas cupiditate, neque illum nulla fugiat nisi doloremque. Iusto.
               </p>
               <h3 class="heading-tertiary u-margin-bottom-small">Live adventure like you never had before</h3>
               <p class="paragraph">
                 Lorem ipsum dolor sit amet consectetur adipisicing elit.
                 Quaerat hic iusto omnis praesentium, unde recusandae veniam harum pariatur perspiciatis laboriosam.
               </p>
               <a href="#" class="btn-text">Learn more &rarr;</a> 
             </div>
             <div class="col-1-of-2">
                <div class="composition">

                  <img srcset="img/nat-1.jpg 300w, img/nat-1-large.jpg 1000w"
                    sizes ="(max-width:900px) 20vw, (max-width:600px) 30vw, 300px"
                    alt="Photo1"
                    class="composition__photo composition__photo--p1"
                    src="img/nat-1-large.jpg">
                  
                  <img srcset="img/nat-2.jpg 300w, img/nat-2-large.jpg 1000w"
                    sizes ="(max-width:900px) 20vw, (max-width:600px) 30vw, 300px"
                    alt="Photo2"
                    class="composition__photo composition__photo--p2"
                    src="img/nat-2-large.jpg">
                  
                  <img srcset="img/nat-3.jpg 300w, img/nat-3-large.jpg 1000w"
                    sizes ="(max-width:900px) 20vw, (max-width:600px) 30vw, 300px"
                    alt="Photo3"
                    class="composition__photo composition__photo--p3"
                    src="img/nat-3-large.jpg">
               </div>
             </div>
           </div>
         </section>

         <section class="section-features">
           <div class="row">
             <div class="col-1-of-4">
                <div class="feature-box u-margin-bottom-small">
                  <i class="feature-box__icon icon-basic-world"></i>
                  <h3 class="heading-tertiary">
                    explore the world
                  </h3>
                  <p class="feature-box__text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.Quaerat hic iusto omnis praesentium, unde recusandae veniam harum pariatur.
                  </p>
                </div>
             </div>

             <div class="col-1-of-4">
               <div class="feature-box u-margin-bottom-small">
                 <i class="feature-box__icon icon-basic-compass"></i>
                 <h3 class="heading-tertiary">
                   meet nature
                 </h3>
                 <p class="feature-box__text">
                   Lorem ipsum dolor sit amet consectetur adipisicing elit.Quaerat hic iusto omnis praesentium, unde recusandae veniam harum pariatur.
                 </p>
               </div>
             </div>

             <div class="col-1-of-4">
               <div class="feature-box u-margin-bottom-small">
                 <i class="feature-box__icon icon-basic-map"></i>
                 <h3 class="heading-tertiary">
                    find your way
                 </h3>
                 <p class="feature-box__text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.Quaerat hic iusto omnis praesentium, unde recusandae veniam harum pariatur.
                 </p>
               </div>
             </div>

             <div class="col-1-of-4">
               <div class="feature-box u-margin-bottom-small">
                 <i class="feature-box__icon icon-basic-heart"></i>
                 <h3 class="heading-tertiary">
                   live a healthy life
                 </h3>
                 <p class="feature-box__text">
                   Lorem ipsum dolor sit amet consectetur adipisicing elit.Quaerat hic iusto omnis praesentium, unde recusandae veniam harum pariatur.
                 </p>
               </div>
             </div>
           </div>
         </section>
         <section class="section-tours" id="section-tours">
            <div class="u-center-text u-margin-bottom-big">
              <h2 class="heading-secondary">
                 most popular tours
              </h2>
            </div>
            
            <div class="row">
              <div class="col-1-of-3">
                <div class="card">
                  <div class="card__side card__side--front">
                    <div class="card__picture card__picture-1">
                       &nbsp;
                    </div>
                    <h4 class="card__heading">
                      <span class="card__heading--span card__heading--span--1"> The sea explorer</span>
                    </h4>
                    <div class="card__details">
                       <ul>
                         <li>3 day Tour</li>
                         <li>Upto 30 people</li>
                         <li>2 tour guides</li>
                         <li>Sleep in cozy Hotels</li>
                         <li>Difficulty-Easy</li>
                       </ul>
                    </div>
                    
                  </div>
                  <div class="card__side card__side--back card__side--back-1">
                      <div class="card__cta">
                         <div class="card__price-box">
                           <p class="card__price-only">only</p>
                           <p class="card__price-pricing">Rs1817/-</p>
                         </div>
                          <a href="#popup" class="btn btn--white ">Book now</a>
                      </div>
                  </div>
                </div>
              </div>
              <div class="col-1-of-3">
                <div class="card">
                  <div class="card__side card__side--front">
                     <div class="card__picture card__picture-2">
                       &nbsp;
                     </div>
                      <h4 class="card__heading">
                        <span class="card__heading--span card__heading--span--2"> The forest hiker</span>
                      </h4>
                      <div class="card__details">
                       <ul>
                         <li>7 day Tour</li>
                         <li>Upto 40 people</li>
                         <li>6 tour guides</li>
                         <li>Sleep in provided Tents</li>
                         <li>Difficulty-Medium</li>
                       </ul>
                     </div> 
                  </div>
                  <div class="card__side card__side--back card__side--back-2">
                      <div class="card__cta">
                         <div class="card__price-box">
                           <p class="card__price-only">only</p>
                           <p class="card__price-pricing">Rs3217/-</p>
                         </div>
                          <a href="#popup" class="btn btn--white ">Book now</a>
                      </div>
                  </div>
               </div>
              </div>
              <div class="col-1-of-3">
                <div class="card">
                 <div class="card__side card__side--front">
                    <div class="card__picture card__picture-3">
                      &nbsp;
                    </div>
                    <h4 class="card__heading">
                      <span class="card__heading--span card__heading--span--3"> The snow piercer</span>
                    </h4>
                    <div class="card__details">
                     <ul>
                       <li>5 day Tour</li>
                       <li>Upto 15 people</li>
                       <li>3 tour guides</li>
                       <li>Sleep in provided Tents</li>
                       <li>Difficulty-Hard</li>
                     </ul>
                    </div> 
                 </div>
                 <div class="card__side card__side--back card__side--back-3">
                     <div class="card__cta">
                        <div class="card__price-box">
                          <p class="card__price-only">only</p>
                          <p class="card__price-pricing">Rs6817/-</p>
                        </div>
                        <a href="#popup" class="btn btn--white ">Book now</a>
                     </div>
                 </div>
                </div>
              </div>
            </div>
            <div class="u-center-text u-margin-top-big">
             <a href="#" class="btn btn--green">Discover all tours</a>
            </div>
         </section> 
          
          <section class="section-stories">
              <div class="bg-video">
                 <video class="bg-video__content" autoplay muted loop>
                   <source src="img/video.mp4" type="video/mp4">
                   <source src="img/video.webm" type="video/webm">
                   Your browser is not suppoerted!
                 </video>
              </div>
              <div class="u-center-text u-margin-bottom-big">
                 <h2 class="heading-secondary">
                    we make people genuinely happy
                 </h2>
              </div>
               
              <div class="row">
                <div class="story">
                  <figure class="story__shape">
                    <img src="img/nat-8.jpg" alt="photo" class="story__img">
                    <figcaption class="story__caption">marry smith</figcaption>
                  </figure>
                  <div class="story__text">
                    <h3 class="heading-tertiary u-margin-bottom-small">
                      i had the best week over with my family
                    </h3>
                    <p>
                     Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit, omnis sed consectetur harum optio impedit quo quis soluta sint. Molestias impedit tempore sapiente amet! Modi at totam deleniti repudiandae harum.
                    </p>
                  </div>
                </div>
                <div class="story2 ">
                  <figure class="story2__shape">
                    <img src="img/nat-9.jpg" alt="photo" class="story2__img">
                    <figcaption class="story2__caption">John wick</figcaption>
                  </figure>
                 <div class="story2__text">
                   <h3 class="heading-tertiary u-margin-bottom-small">
                     &quot;wow my life is completely better now&quot; 
                   </h3>
                   <p>
                     Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur autem, alias assumenda maxime veritatis mollitia in consectetur iure esse eius, laboriosam libero excepturi ea, ex error illo ad porro dicta.
                   </p>
                 </div>
                </div>
              </div>
              <div class="u-center-text u-margin-top-big">
                <a href="#" class="btn-text">find all stories&rarr;</a>
              </div>
          </section>

          <section class="section-booking">
            <div class="row">
              <div class="book">
                <div class="book__form">
                  <form action="#" class="form">

                    <div class="u-margin-bottom-med">
                      <h2 class="heading-secondary">
                        start booking now
                      </h2>
                    </div>

                    <div class="form__group">
                      <input type="text" class="form__input" placeholder="Full name" id="name" required>
                      <label for="name" class="form__label">Full name</label>
                    </div>

                    <div class="form__group">
                      <input type="email" class="form__input" placeholder="Email Adress" id="email" required>
                      <label for="email" class="form__label">Email Adress</label>
                    </div>

                    <div class="form__group u-margin-bottom-med">
                      <div class="form__radio">
                        <input type="radio" class="form__radio-input" id="small" required name="size">
                        <label for="small" class="form__radio-label">
                          <span class="form__radio-button"></span>
                          Small tour group
                        </label>
                      </div>

                      <div class="form__radio">
                        <input type="radio" class="form__radio-input" id="large" required name="size">
                        <label for="large" class="form__radio-label">
                          <span class="form__radio-button"></span>
                          Large tour group
                        </label>
                      </div>
                    </div>

                    <div class="form__group">
                       <button class="btn btn--green ">Next Step &rarr;</button>
                    </div>
                  </form>
                </div>
              </div>
            </div>
          </section>
       </main>

       <footer class="footer">
         <div class="footer__logo-box">

          <picture class="footer__logo">
            <source srcset="img/logo-green-small-1x.png 1x, img/logo-green-small-2x.png 2x" media="(max-width: 37.5em)">
          </picture>
           <img srcset="img/logo-green-small-1x.png 1x, img/logo-green-1x.png 2x" alt="full logo" class="footer__logo">
         </div>
         <div class="row">
           <div class="col-1-of-2">
             <div class="footer__navigation">
                <ul class="footer__list">
                  <li class="footer__items "><a href="#" class="footer__links">Company</a></li>
                  <li class="footer__items "><a href="#" class="footer__links">Contact Us</a></li>
                  <li class="footer__items "><a href="#" class="footer__links">Careers</a></li>
                  <li class="footer__items "><a href="#" class="footer__links">Privacy Policy</a></li>
                  <li class="footer__items "><a href="#" class="footer__links">Terms</a></li>
                </ul>  
             </div>
           </div>
           <div class="col-1-of-2">
             <p class="footer__copyright">
               Built by <a href="#" class="footer__links">Satya Swaroop</a> for my portfolio <a href="#" class="footer__links">This &quot;Natours Project&quot;</a> Copyright &copy; by Satya Swaroop . You can use this website for your own and commercial use , but don't claim it that you designed this. Credit to the author &quot;Satya Swaroop&quot; is highly appericiated.
             </p>
           </div>
         </div>
       </footer>
        <div class="popup" id="popup">
          <div class="popup__content">
            <div class="popup__left">
               <img src="img/nat-8.jpg" alt="Tour" class="popup__image">
               <img src="img/nat-9.jpg" alt="Tour" class="popup__image">
            </div>
            <div class="popup__right">
              <a href="#section-tours" class="popup__close">&times;</a>
              <h2 class="heading-secondary u-margin-bottom-small">Start booking now</h2>
              <h3 class="heading-tertiary u-margin-bottom-small">Important &ndash; Please read this terms before booking</h3>
              <p class="popup__text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum ullam doloribus, adipisci corporis optio quod impedit voluptate blanditiis provident assumenda dolorem reprehenderit alias nulla est, veniam tempora obcaecati debitis voluptatem.
              </p>
              <a href="#" class="btn btn--green">Book Now</a>
            </div>
          </div>
        </div>
       <!--
        <section class="grid-box">
         
         
         <div class="row">
           <div class="col-1-of-3">
             col-1-of-3
           </div>
           <div class="col-2-of-3">
             col-2-of-3
           </div>
         </div>
        
         <div class="row">
           <div class="col-1-of-4">
             col-1-of-4
           </div>
           <div class="col-1-of-4">
             col-1-of-4
           </div>
           <div class="col-1-of-4">
             col-1-of-4
           </div>
           <div class="col-1-of-4">
             col-1-of-4
           </div>
         </div>
         <div class="row">
           <div class="col-1-of-4">
             col-1-of-4
           </div>
           <div class="col-1-of-4">
             col-1-of-4
           </div>
           <div class="col-2-of-4">
             col-2-of-4
           </div>
         </div>
        
         <div class="row">
           <div class="col-1-of-4">
             col-1-of-4
           </div>
           <div class="col-3-of-4">
             col-3-of-4
           </div>
         </div>
       </section>
       -->
    </body>
</html>
