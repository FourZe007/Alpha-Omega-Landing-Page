<template>
  <nav id="NavBar" class="navbar navbar-expand-lg fixed-top navbar-light" aria-label="Main navigation">
    <div class="container">
      <a class="navbar-brand logo-text" href="#">Alpha Omega Edu</a>
      <button class="navbar-toggler p-0 border-0" type="button" id="navbarSideCollapse" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="navbar-collapse offcanvas-collapse" id="navbarsExampleDefault">
        <ul class="navbar-nav ms-auto navbar-nav-scroll">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#header">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#learning">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#gallery-carousel">Gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <header id="header" class="header small">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-xl-5">
          <div class="text-container">
            <h1 class="h1-large">Find The Best Teacher for You</h1>
            <p class="p-large"><span>Ignite Your Academic Journey</span> with match the perfect learning ally, accelerate
              your progress, and experience the transformative power of a personalized learning experience.</p>
            <a class="btn-solid-lg" href="#learning">Offered Teaching</a>
          </div>
        </div>
        <div class="col-lg-6 col-xl-7">
          <div class="image-container">
            <img class="img-fluid" src="./assets/banner.png" alt="alternative" />
          </div>
        </div>
      </div>
    </div>
  </header>
  <div id="learning" class="cards-1 bg-gray">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h2>Explore Our Learning</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12">


          <div class="card">
            <div class="fas card-icon">
              <div class="image-container">
                <img class="img-fluid" src="./assets/school-1-removed.png" alt="alternative" />
              </div>
              <!-- <span class="fas fa-headphones-alt"></span> -->
            </div>
            <div class="card-body">
              <h5 class="card-title">Elementary Teaching</h5>
              <p><span>Spark Curiosity, Build Confidence, Lay a Strong Foundation</span> through engaging activities and
                personalized
                support, we unlock each child's unique potential and set them on a path to success in their elementary
                years
                and beyond.</p>
              <a class="read-more no-line" href="#about">Learn more <span class="fas fa-long-arrow-alt-right"></span></a>
            </div>
          </div>

          <div class="card">
            <div class="fas card-icon red">
              <div class="image-container">
                <img class="img-fluid" src="./assets/school-2-removed.png" alt="alternative" />
              </div>
              <!-- <span class="far fa-clipboard"></span> -->
            </div>
            <div class="card-body">
              <h5 class="card-title">Junior High Teaching</h5>
              <p><span>Master Subjects, Build Confidence, Embrace Challenges</span> with personalized plans, targeted
                support, and a focus
                on critical thinking, we empower junior high students to navigate their crucial learning years with
                success and
                confidence.</p>
              <a class="read-more no-line" href="#about">Learn more <span class="fas fa-long-arrow-alt-right"></span></a>
            </div>
          </div>

          <div class="card">
            <div class="fas card-icon green">
              <div class="image-container">
                <img class="img-fluid" src="./assets/school-3-removed.png" alt="alternative" />
              </div>
              <!-- <span class="far fa-comments"></span> -->
            </div>
            <div class="card-body">
              <h5 class="card-title">Senior High Teaching</h5>
              <p><span>Confidently Navigate Senior High, Prepare for College Success</span> through personalized plans,
                expert guidance,
                and skill-building support, we help students master subjects, conquer challenges, and unlock their
                full potential.</p>
              <a class="read-more no-line" href="#about">Learn more <span class="fas fa-long-arrow-alt-right"></span></a>
            </div>
          </div>

        </div>
      </div>
    </div>
  </div>
  <div id="about" class="basic-1">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-xl-7">
          <div class="image-container">
            <img class="img-fluid" src="./assets/learn.png" alt="alternative" />
          </div>
        </div>
        <div class="col-lg-6 col-xl-5">
          <div class="text-container">
            <div class="section-title">WHAT WE DO</div>
            <h2>The right teacher can boost your learning</h2>
            <p><span>Empowering Success Through Personalized Learning</span>, we go beyond textbook teaching. Our
              personalized approach
              equips you with the right tools and support to overcome challenges, build confidence, and achieve your
              academic goals.</p>
            <!-- <a class="btn-solid-reg" href="#contact">Get Consultation</a> -->
            <a class="btn-outline-reg" href="#details">Details</a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="basic-2">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-xl-5">
          <div class="text-container">
            <div class="section-title">ABOUT US</div>
            <h2>We have more than 8 years experience in teaching</h2>
            <p><span>Passionate Educators, Proven Results</span> with over 8 years of experience guiding students to
              success,
              we understand the art of personalized learning and are dedicated to unlocking your full potential.</p>
            <a class="btn-outline-reg" href="#details">Details</a>
          </div>
        </div>
        <div class="col-lg-6 col-xl-7">
          <div class="image-container">
            <img class="img-fluid" src="./assets/custom-about-dots-2-removed.png" alt="alternative" />
          </div>
        </div>
      </div>
    </div>
  </div>
  <div id="details" class="accordion-1">
    <div class="container">
      <div class="row">
        <div class="col-xl-12">
          <h2 class="h2-heading">Our Learning Features</h2>
          <p class="p-heading"><span>Ready to Learn Differently?</span> Explore our innovative approach to personalized
            tutoring.</p>
        </div>
      </div>
      <div class="row">
        <div class="col-xl-5">
          <div class="accordion" id="accordion">


            <div class="accordion-item">
              <div class="accordion-icon">
                <span class="fas fa-tv"></span>
              </div>
              <div class="accordion-header" id="headingOne">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne"
                  aria-expanded="true" aria-controls="collapseOne">
                  Daily Learning Materials
                </button>
              </div>
              <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne"
                data-bs-parent="#accordion">
                <div class="accordion-body"><span>Stay Motivated, Stay Ahead</span> for daily materials keep you on track,
                  fuel your curiosity,
                  and help you achieve your goals faster. Explore a curated learning path with consistent support and
                  guidance.</div>
              </div>
            </div>


            <div class="accordion-item">
              <div class="accordion-icon blue">
                <span class="fas fa-microphone"></span>
              </div>
              <div class="accordion-header" id="headingTwo">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo"
                  aria-expanded="false" aria-controls="collapseTwo">
                  Prepare for Daily Exams
                </button>
              </div>
              <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo"
                data-bs-parent="#accordion">
                <div class="accordion-body"><span>Go Beyond Memorization, Build True Understanding</span> to develop
                  critical thinking skills
                  and a strong foundation in each subject, leading to confident performance on any exam.</div>
              </div>
            </div>


            <div class="accordion-item">
              <div class="accordion-icon purple">
                <span class="fas fa-video"></span>
              </div>
              <div class="accordion-header" id="headingThree">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree"
                  aria-expanded="false" aria-controls="collapseThree">
                  Prepare For All Things About National Exams
                </button>
              </div>
              <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree"
                data-bs-parent="#accordion">
                <div class="accordion-body"><span>Master Every Aspect, Conquer Anxiety, Achieve Peak Performance</span>
                  from comprehensive
                  subject coverage to personalized strategies and expert support, unlock your full potential and dominate
                  your
                  national exams with confidence.</div>
              </div>
            </div>



            <div class="accordion-item">
              <div class="accordion-icon orange">
                <span class="fas fa-tools"></span>
              </div>
              <div class="accordion-header" id="headingFour">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFour"
                  aria-expanded="false" aria-controls="collapseFour">
                  Evaluate and Adjust Your Learning
                </button>
              </div>
              <div id="collapseFour" class="accordion-collapse collapse" aria-labelledby="headingFour"
                data-bs-parent="#accordion">
                <div class="accordion-body"><span>Gain Valuable Insights, Adapt Your Strategies, Achieve Continuous
                    Progress</span>
                  through regular evaluation, personalized feedback, and expert guidance, we help you refine your
                  learning,
                  maximize your potential, and confidently journey towards success.</div>
              </div>
            </div>

          </div>
        </div>
        <div class="col-xl-7">
          <div class="image-container">
            <img class="img-fluid" src="assets/images/dashboard-2-removed.png" alt="alternative" />
          </div>
        </div>
      </div>
    </div>
  </div>
  <div id="gallery-carousel" class="slider-1">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h4>Trusted by over <span class="blue">500</span> parents in Surabaya, Indonesia</h4>
          <hr class="section-divider" />

          <div class="slider-container">
            <div class="swiper-container image-slider">
              <div class="swiper-wrapper">
                <div class="swiper-slide">
                  <a class="slider-brand logo-text" href="#">Alpha Omega Edu</a>
                </div>
                <div class="swiper-slide">
                  <a class="slider-brand logo-text" href="#">Alpha Omega Edu</a>
                </div>
                <div class="swiper-slide">
                  <a class="slider-brand logo-text" href="#">Alpha Omega Edu</a>
                </div>
                <div class="swiper-slide">
                  <a class="slider-brand logo-text" href="#">Alpha Omega Edu</a>
                </div>
                <div class="swiper-slide">
                  <a class="slider-brand logo-text" href="#">Alpha Omega Edu</a>
                </div>
                <div class="swiper-slide">
                  <a class="slider-brand logo-text" href="#">Alpha Omega Edu</a>
                </div>
              </div>
            </div>
          </div>

        </div>
      </div>
    </div>
  </div>
  <div class="basic-3">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="text-container">
            <h2>Find the right teacher for you</h2>
            <p class="p-large">The people who are crazy enough to believe they can change the world are the ones who do
            </p>
            <p class="p-large">- Steve Jobs, Former CEO of Apple</p>
            <p class="p-medium">Reach Our Social Media below for more informations</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div id="contact" class="footer bg-gray">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h5>Follow our Social Media to find out more and keep up to date about us</h5>
          <div class="social-container">
            <span class="fa-stack">
              <!-- <a href="#your-link"> -->
              <a @click="handleLinkClick">
                <!-- <a> -->
                <i class="fas fa-circle fa-stack-2x"></i>
                <i class="fab fa-line fa-stack-1x"></i>
              </a>
            </span>
            <span class="fa-stack">
              <a href="https://wa.me/+628973733773">
                <i class="fas fa-circle fa-stack-2x"></i>
                <i class="fab fa-whatsapp fa-stack-1x"></i>
              </a>
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="copyright bg-gray">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-md-12 col-sm-12">
          <ul class="list-unstyled li-space-lg p-small">
            <li><a href="#">Article Details</a></li>
            <li><a href="#">Terms & Conditions</a></li>
            <li><a href="#">Privacy Policy</a></li>
          </ul>
        </div>
        <div class="col-lg-3 col-md-12 col-sm-12">
          <p class="p-small statement">Copyright © <a href="#">Alpha Omega Edu</a></p>
        </div>
        <div class="col-lg-3 col-md-12 col-sm-12">
          <p class="p-small statement">Distributed by <a href="#header" target="_blank">Meteor Tech</a></p>
        </div>
      </div>
    </div>
  </div>
  <button id="myBtn">
    <img src="assets/images/up-arrow.png" alt="alternative" />
  </button>
</template>

<script>
export default {
  methods: {
    handleLinkClick() {
      alert("The link is not available yet.");
    },
  },
};
</script>
 
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>