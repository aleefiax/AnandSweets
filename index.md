<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home</title>
  <link href="https://cdn.rawgit.com/michalsnik/aos/2.1.1/dist/aos.css" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Cedarville+Cursive&display=swap" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles/styles.css">
</head>

<body>

  <div class="menu-wrap">
    <input type="checkbox" class="toggler">
    <div class="hamburger"><div></div></div>
    <div class="menu"><div>
      <div>
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="menu.html">Menu</a></li>
          <li><a href="events.html">Events</a></li>
          <li><a href="reachUs.html">How to reach us</a></li>
          <li><a href="staff.html">Staff</a></li>
        </ul>
      </div>
    </div>
  </div>
    </div>
    
  <div class="container">
    <div class="header">

      <video class="mainImage" autoplay loop muted>
        <source src="video/sampplevid.mp4" type="video/mp4">
      </video>

      <section>
        <img data-aos="flip-left"
        data-aos-easing="ease-out-cubic"
        data-aos-duration="2000" class="logoClass" src="images/logo.jpg" alt="">
        <!-- <h1 class="extraText">Traditional Indian taste</h1> -->
      </section>
    </div>

    <div class="information">
      <ul class="links">
        <!-- facebook button doesnt work. they rest do. werid -_- -->
        <li><a href="http://facebook.com/" target="_blank"><img src="Images/001-facebook.svg" alt="" height="30px" ></a></li>
        <li><a href="http://instagram.com/" target="_blank"><img src="Images/002-instagram.svg" alt="" height="30px" ></a></li>
        <li><a href="http://twitter.com/" target="_blank"><img src="Images/003-twitter.svg" alt="" height="30px" ></a></li>
      </ul>
      <div class="scroll">scroll down for more</div>
    </div>

    <main class="mainContent">
      <div class = "content-item" >
        <div class="image-1 writing-1">
          <div data-aos="fade-up" class="blurredTextImage ">
            <h1>Lorem, ipsum.</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus quos iste animi hic, culpa porro
              cumque, quibusdam eaque voluptates consequatur mollitia cum nam officiis quisquam labore rerum assumenda
              harum quam ratione at repellendus sint pariatur natus? Aspernatur ut ab fugit alias! Earum similique
              perspiciatis, temporibus, est repellendus rem sunt voluptates debitis iure, reiciendis magnam error
              quisquam aut. Natus tempore quae sit magni amet impedit hic maxime quos, minima accusamus eos aperiam?
              Exercitationem perspiciatis explicabo quas dignissimos, nesciunt qui itaque quisquam aspernatur pariatur
              deserunt incidunt asperiores? Ipsa dicta mollitia tenetur dolorum maxime impedit repudiandae, accusamus
              aspernatur cumque beatae libero provident rerum.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus quos iste animi hic, culpa porro
              cumque, quibusdam eaque voluptates consequatur mollitia cum nam officiis quisquam labore rerum assumenda
              harum quam ratione at repellendus sint pariatur natus? Aspernatur ut ab fugit alias! Earum similique
              perspiciatis, temporibus, est repellendus rem sunt voluptates debitis iure, reiciendis magnam error
              quisquam aut. Natus tempore quae sit magni amet impedit hic maxime quos, minima accusamus eos aperiam?
              Exercitationem perspiciatis explicabo quas dignissimos, nesciunt qui itaque quisquam aspernatur pariatur
              deserunt incidunt asperiores? Ipsa dicta mollitia tenetur dolorum maxime impedit repudiandae, accusamus
              aspernatur cumque beatae libero provident rerum.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus quos iste animi hic, culpa porro
              cumque, quibusdam eaque voluptates consequatur mollitia cum nam officiis quisquam labore rerum assumenda
              harum quam ratione at repellendus sint pariatur natus? Aspernatur ut ab fugit alias! Earum similique
              perspiciatis, temporibus, est repellendus rem sunt voluptates debitis iure, reiciendis magnam error
              quisquam aut. Natus tempore quae sit magni amet impedit hic maxime quos, minima accusamus eos aperiam?
              Exercitationem perspiciatis explicabo quas dignissimos, nesciunt qui itaque quisquam aspernatur pariatur
              deserunt incidunt asperiores? Ipsa dicta mollitia tenetur dolorum maxime impedit repudiandae, accusamus
              aspernatur cumque beatae libero provident rerum.</p>
          </div>
        </div>
      </div>
    </main>

    <div class="main2">
        <div class="inner-main2-child main2-image1">
          <div id="map"></div>
        </div>
        <div class="inner-main2-child main2-image2">
          <h1>How to reach us!</h1>
        </div>
    </div>

    <!-- <img src="../Images/menu-bg.jpeg"> -->

    <div class="restMenu">
      <!-- TODO: figure out why menu items dont animate now. They dont because above layer is still there, but still! figure it out sis. -->
      <div  class="menuItemOverlay">
        <div class="menuItem">
          <div class="menu-item-child">
              <div class="pages page-1">
                <div class="page-content">
                  <h1>Main</h1>
                  <div class="menu-item-card__container">
                    <!-- ROW 1 -->
                    <div class="row">
                      <div class="menu-item-card">
                        <div style="background-image:url('https://i.ndtvimg.com/i/2017-10/thali_620x350_71507031336.jpg');" class="menu-item-card__image"></div>
                        <h5>Indian Thali</h5>
                        <h5>$10.5</h5>
                      </div>
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://healthynibblesandbits.com/wp-content/uploads/2019/07/Paneer-Tikka-Masala-FF3.jpg');"
                          class="menu-item-card__image"></div>
                        <h5>Paneer Tikka</h5>
                        <h5>$10.5</h5>
                      </div>
                    </div>
                    <!-- ROW 2 -->
                    <div class="row">
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/chicken-tikka-long-1581347468.jpg?crop=1.00xw:0.716xh;0,0.151xh&resize=480:*');"
                          class="menu-item-card__image"></div>
                        <h5>Chiken Tikka</h5>
                        <h5>$10.5</h5>
                      </div>
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://static.toiimg.com/thumb/53205522.cms?imgsize=302803&width=800&height=800');"
                          class="menu-item-card__image"></div>
                        <h5>Butter Chicken</h5>
                        <h5>$10.5</h5>
                      </div>
                    </div>
                    <!-- ROW 3 -->
                    <div class="row">
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/chicken-tikka-long-1581347468.jpg?crop=1.00xw:0.716xh;0,0.151xh&resize=480:*');"
                          class="menu-item-card__image"></div>
                        <h5>Chiken Tikka</h5>
                        <h5>$10.5</h5>
                      </div>
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://static.toiimg.com/thumb/53205522.cms?imgsize=302803&width=800&height=800');"
                          class="menu-item-card__image"></div>
                        <h5>Butter Chicken</h5>
                        <h5>$10.5</h5>
                      </div>
                    </div>
                    <!-- ROW 4 -->
                    <div class="row">
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/chicken-tikka-long-1581347468.jpg?crop=1.00xw:0.716xh;0,0.151xh&resize=480:*');"
                          class="menu-item-card__image"></div>
                        <h5>Chiken Tikka</h5>
                        <h5>$10.5</h5>
                      </div>
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://static.toiimg.com/thumb/53205522.cms?imgsize=302803&width=800&height=800');"
                          class="menu-item-card__image"></div>
                        <h5>Butter Chicken</h5>
                        <h5>$10.5</h5>
                      </div>
                    </div>
                    <!-- ROW 5 -->
                    <div class="row">
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/chicken-tikka-long-1581347468.jpg?crop=1.00xw:0.716xh;0,0.151xh&resize=480:*');"
                          class="menu-item-card__image"></div>
                        <h5>Chiken Tikka</h5>
                        <h5>$10.5</h5>
                      </div>
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://static.toiimg.com/thumb/53205522.cms?imgsize=302803&width=800&height=800');"
                          class="menu-item-card__image"></div>
                        <h5>Butter Chicken</h5>
                        <h5>$10.5</h5>
                      </div>
                    </div>
                    <!-- ROW 6 -->
                    <div class="row">
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/chicken-tikka-long-1581347468.jpg?crop=1.00xw:0.716xh;0,0.151xh&resize=480:*');"
                          class="menu-item-card__image"></div>
                        <h5>Chiken Tikka</h5>
                        <h5>$10.5</h5>
                      </div>
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://static.toiimg.com/thumb/53205522.cms?imgsize=302803&width=800&height=800');"
                          class="menu-item-card__image"></div>
                        <h5>Butter Chicken</h5>
                        <h5>$10.5</h5>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="pages page-2">
                <div class="page-content">
                  <h1>Sweets</h1>
                    <div class="menu-item-card__container">
                      <!-- ROW 1 -->
                    <div class="row">
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/chicken-tikka-long-1581347468.jpg?crop=1.00xw:0.716xh;0,0.151xh&resize=480:*');"
                          class="menu-item-card__image"></div>
                        <h5>Chiken Tikka</h5>
                        <h5>$10.5</h5>
                      </div>
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://static.toiimg.com/thumb/53205522.cms?imgsize=302803&width=800&height=800');"
                          class="menu-item-card__image"></div>
                        <h5>Butter Chicken</h5>
                        <h5>$10.5</h5>
                      </div>
                    </div>
                    <!-- ROW 2 -->
                    <div class="row">
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/chicken-tikka-long-1581347468.jpg?crop=1.00xw:0.716xh;0,0.151xh&resize=480:*');"
                          class="menu-item-card__image"></div>
                        <h5>Chiken Tikka</h5>
                        <h5>$10.5</h5>
                      </div>
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://static.toiimg.com/thumb/53205522.cms?imgsize=302803&width=800&height=800');"
                          class="menu-item-card__image"></div>
                        <h5>Butter Chicken</h5>
                        <h5>$10.5</h5>
                      </div>
                    </div>
                    <!-- ROW 3 -->
                    <div class="row">
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/chicken-tikka-long-1581347468.jpg?crop=1.00xw:0.716xh;0,0.151xh&resize=480:*');"
                          class="menu-item-card__image"></div>
                        <h5>Chiken Tikka</h5>
                        <h5>$10.5</h5>
                      </div>
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://static.toiimg.com/thumb/53205522.cms?imgsize=302803&width=800&height=800');"
                          class="menu-item-card__image"></div>
                        <h5>Butter Chicken</h5>
                        <h5>$10.5</h5>
                      </div>
                    </div>
                    <!-- ROW 4 -->
                    <div class="row">
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/chicken-tikka-long-1581347468.jpg?crop=1.00xw:0.716xh;0,0.151xh&resize=480:*');"
                          class="menu-item-card__image"></div>
                        <h5>Chiken Tikka</h5>
                        <h5>$10.5</h5>
                      </div>
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://static.toiimg.com/thumb/53205522.cms?imgsize=302803&width=800&height=800');"
                          class="menu-item-card__image"></div>
                        <h5>Butter Chicken</h5>
                        <h5>$10.5</h5>
                      </div>
                    </div>
                    <!-- ROW 5 -->
                    <div class="row">
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/chicken-tikka-long-1581347468.jpg?crop=1.00xw:0.716xh;0,0.151xh&resize=480:*');"
                          class="menu-item-card__image"></div>
                        <h5>Chiken Tikka</h5>
                        <h5>$10.5</h5>
                      </div>
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://static.toiimg.com/thumb/53205522.cms?imgsize=302803&width=800&height=800');"
                          class="menu-item-card__image"></div>
                        <h5>Butter Chicken</h5>
                        <h5>$10.5</h5>
                      </div>
                    </div>
                    <!-- ROW 6 -->
                    <div class="row">
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/chicken-tikka-long-1581347468.jpg?crop=1.00xw:0.716xh;0,0.151xh&resize=480:*');"
                          class="menu-item-card__image"></div>
                        <h5>Chiken Tikka</h5>
                        <h5>$10.5</h5>
                      </div>
                      <div class="menu-item-card">
                        <div
                          style="background-image:url('https://static.toiimg.com/thumb/53205522.cms?imgsize=302803&width=800&height=800');"
                          class="menu-item-card__image"></div>
                        <h5>Butter Chicken</h5>
                        <h5>$10.5</h5>
                      </div>
                    </div>

                    </div>
                </div>
              </div>
          </div>
        </div>
      </div>
    </div>

    <footer class = "footer" >
      HAHAHAA sucker
     </footer>

</div>

</body>
<script
      src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap&libraries=&v=weekly"
      async
    ></script>
<script src="https://cdn.rawgit.com/michalsnik/aos/2.1.1/dist/aos.js"></script>
<script>
    // Initialize and add the map
function initMap() {
  // The location of Uluru
  const uluru = { lat: -25.344, lng: 131.036 };
  // The map, centered at Uluru
  const map = new google.maps.Map(document.getElementById("map"), {
    zoom: 4,
    center: uluru,
  });
  // The marker, positioned at Uluru.
  const marker = new google.maps.Marker({
    position: uluru,
    map: map,
  });
}

document.querySelectorAll('.restMenu > .menuItemOverlay .menu-item-child')[0].addEventListener('mouseenter', (e) => {
e.target.style.opacity = '1';
});

document.querySelectorAll('.restMenu > .menuItemOverlay .menu-item-child')[0].addEventListener('mouseleave', (e) => {
e.target.style.opacity = '0';
});

</script>
<script>
  AOS.init();
</script>
</html>
