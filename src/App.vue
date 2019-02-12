<template>
<div class="main-wrapper">
  <body id="page-top">
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top" id="sideNav">
      <a class="navbar-brand js-scroll-trigger" href="#page-top">
        <span class="d-block d-lg-none">Aprilia Hartami</span>
        <span class="d-none d-lg-block">
          <img
            class="img-fluid img-profile rounded-circle mx-auto mb-2"
            src="./assets/april.png"
            alt
          >
        </span>
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link js-scroll-trigger" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link js-scroll-trigger" href="#experience">Experience</a>
          </li>
          <li class="nav-item">
            <a class="nav-link js-scroll-trigger" href="#education">Education</a>
          </li>
          <li class="nav-item">
            <a class="nav-link js-scroll-trigger" href="#skills">Skills</a>
          </li>
          <li class="nav-item">
            <a class="nav-link js-scroll-trigger" href="#interests">Interests</a>
          </li>
          <li class="nav-item">
            <a class="nav-link js-scroll-trigger" href="#awards">Awards</a>
          </li>
        </ul>
      </div>
    </nav>

    <div class="container-fluid p-0">
      <section class="resume-section p-3 p-lg-5 d-flex d-column" id="about">
        <div class="my-auto">
          <h1 class="mb-0">
            {{ name }}
            <span class="text-primary">{{ surname }}</span>
          </h1>
          <div class="subheading mb-5">
            {{ address }}
            <a href="mailto:name@email.com">{{ email }}</a>
          </div>
          <p class="mb-5">{{ aboutMe }}</p>
          <ul class="list-inline list-social-icons mb-0">
            <li class="list-inline-item">
              <a href="https://www.xing.com/profile/Aprilia_Hartami">
                <span class="fa-stack fa-lg">
                  <i class="fa fa-circle fa-stack-2x"></i>
                  <i class="fa fa-xing fa-stack-1x fa-inverse"></i>
                </span>
              </a>
            </li>
            <li class="list-inline-item">
              <a href="https://www.linkedin.com/in/ahartami/">
                <span class="fa-stack fa-lg">
                  <i class="fa fa-circle fa-stack-2x"></i>
                  <i class="fa fa-linkedin fa-stack-1x fa-inverse"></i>
                </span>
              </a>
            </li>
            <li class="list-inline-item">
              <a href="https://github.com/hartami">
                <span class="fa-stack fa-lg">
                  <i class="fa fa-circle fa-stack-2x"></i>
                  <i class="fa fa-github fa-stack-1x fa-inverse"></i>
                </span>
              </a>
            </li>
          </ul>
        </div>
      </section>

      <hr class="m-0">

      <section class="resume-section p-3 p-lg-5 d-flex flex-column" id="experience">
        <div class="my-auto">
          <h2 class="mb-5">Experience</h2>

          <div class="resume-item d-flex flex-column flex-md-row mb-5">
            <div class="resume-content mr-auto">
              <h3 class="mb-0">Junior Front-end Developer</h3>
              <div class="subheading mb-3">KATAJIWA</div>
              <p>Design and implement UI/UX with HTML5, CSS, React, and other supporting technologies.</p>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">November 2018 - present</span>
            </div>
          </div>

          <div class="resume-item d-flex flex-column flex-md-row mb-5">
            <div class="resume-content mr-auto">
              <h3 class="mb-0">Intern as Software Developer</h3>
              <div class="subheading mb-3">ITEE - University of Oulu</div>
              <p>Enhanced besouro (an Eclipse plugin) with some additional metrics</p>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">October 2016 - August 2017</span>
            </div>
          </div>

          <div class="resume-item d-flex flex-column flex-md-row mb-5">
            <div class="resume-content mr-auto">
              <h3 class="mb-0">Analyst</h3>
              <div class="subheading mb-3">Bukalapak.com</div>
              <p>Performed requirement engineering, business research, UI/UX design, data science, and software testing.</p>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">November 2013 - November 2014</span>
            </div>
          </div>

          <div class="resume-item d-flex flex-column flex-md-row mb-5">
            <div class="resume-content mr-auto">
              <h3 class="mb-0">IT Consultant</h3>
              <div class="subheading mb-3">PUSILKOM UI</div>
              <p>Designed digital solution systems and IT master plans for several Indonesian ministries and national agencies.</p>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">October 2011 - September 2013</span>
            </div>
          </div>

          <div class="resume-item d-flex flex-column flex-md-row">
            <div class="resume-content mr-auto">
              <h3 class="mb-0">Intern as junior SAP Consultant</h3>
              <div class="subheading mb-3">Accenture Indonesia</div>
              <p>Handled data migration and verification for SAP FICO module from previous system to new SAP system of an Energy company.</p>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">February 2011 - May 2011</span>
            </div>
          </div>
        </div>
      </section>

      <hr class="m-0">

      <section class="resume-section p-3 p-lg-5 d-flex flex-column" id="education">
        <div class="my-auto">
          <h2 class="mb-5">Education</h2>

          <div class="resume-item d-flex flex-column flex-md-row mb-5">
            <div class="resume-content mr-auto">
              <h3 class="mb-0">University of Oulu</h3>
              <div class="subheading mb-3">Master of Science</div>
              <div>Software Engineering</div>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">August 2016 - June 2018</span>
            </div>
          </div>

          <div class="resume-item d-flex flex-column flex-md-row mb-5">
            <div class="resume-content mr-auto">
              <h3 class="mb-0">Technische Universität Kaiserslautern</h3>
              <div class="subheading mb-3">Master of Science</div>
              <div>Software Engineering</div>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">October 2015 - May 2018</span>
            </div>
          </div>

          <div class="resume-item d-flex flex-column flex-md-row">
            <div class="resume-content mr-auto">
              <h3 class="mb-0">Universitas Indonesia</h3>
              <div class="subheading mb-3">Bachelor of Computer Science</div>
              <div>Software Engineering</div>
            </div>
            <div class="resume-date text-md-right">
              <span class="text-primary">August 2007 - August 2011</span>
            </div>
          </div>
        </div>
      </section>

      <hr class="m-0">

      <section class="resume-section p-3 p-lg-5 d-flex flex-column" id="skills">
        <div class="my-auto">
          <h2 class="mb-5">Skills</h2>
          <div class="subheading mb-3">Tecnical Skills and Knowledge</div>
          <ul class="fa-ul mb-0">
            <li>
              <i class="fa-li fa fa-check"></i>
              Java: Android
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              Javascript: React, Vue, Node (basic), Express (basic)
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              HTML5 and CSS
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              PHP: Laravel (basic)
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              Data Analysis: Google Analytics, Tableau Public, IBM Watson (basic)
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              Prototyping: Balsamiq, Axure RP, and Sketch
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              Management: Scrum
            </li>
          </ul>
          <p></p>
          <p></p>

          <div class="subheading mb-3">Languages</div>
          <ul class="fa-ul mb-0">
            <li>
              <i class="fa-li fa fa-check"></i>
              Java (native)
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              Bahasa Indonesia (native)
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              English (fluent)
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              Germany (intermediate - B1)
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              Spanish (basic)
            </li>
            <li>
              <i class="fa-li fa fa-check"></i>
              Finnish (basic)
            </li>
          </ul>
        </div>
      </section>

      <hr class="m-0">

      <section class="resume-section p-3 p-lg-5 d-flex flex-column" id="interests">
        <div class="my-auto">
          <h2 class="mb-5">Interests</h2>
          <p>Apart from being a web developer, I enjoy various hobbies, which mostly are related to art and social works. I love painting and cooking. During the warmer months here in Euroe, I enjoy traveling and bycycling.</p>
          <p
            class="mb-0"
          >I am also interested to many activities which support sustainanbility and entrepreneurship. I am getting excited easily for new ideas. There are always many interesting things that come to my minds. To calm my minds, I do regularly meditation and yoga.</p>
        </div>
      </section>

      <hr class="m-0">

      <section class="resume-section p-3 p-lg-5 d-flex flex-column" id="awards">
        <div class="my-auto">
          <h2 class="mb-5">Awards &amp; Certifications</h2>
          <ul class="fa-ul mb-0">
            <li>
              <i class="fa-li fa fa-trophy text-warning"></i>
              Erasmus Mundus Scholarship for Software Engineering Master's Programme (EMSE)
            </li>
            <li>
              <i class="fa-li fa fa-trophy text-warning"></i>
              Deutsch als Fremdsprache - Technical Universität Kaiserslautern
            </li>
            <li>
              <i class="fa-li fa fa-trophy text-warning"></i>
              Director Award - CESL University of Arizona
            </li>
            <li>
              <i class="fa-li fa fa-trophy text-warning"></i>
              Introduction to SAP by using GBI Dataset - SAP University Alliance
            </li>
          </ul>
        </div>
      </section>
    </div>
  </body>
</div>
</template>

<script>
export default {
  data() {
    return {
      title: "My Personal Web",
      name: "APRILIA",
      surname: "HARTAMI",
      address: "Kaiserslautern Germany",
      email: "apriliahartami@gmail.com",
      aboutMe:
        "I am passionate about web and mobile development. I always want to deliver valuable applications which improve human lives, support business development, and create technology innovation."
    };
  },
  mounted() {
    const $ = this.jquery;
    this.$nextTick(() => {
      // customized jQuery code
      $('a.js-scroll-trigger[href*="#"]:not([href="#"])').click(function() {
        if (
          location.pathname.replace(/^\//, "") ===
            this.pathname.replace(/^\//, "") &&
          location.hostname === this.hostname
        ) {
          var target = $(this.hash);
          target = target.length
            ? target
            : $("[name=" + this.hash.slice(1) + "]");
          if (target.length) {
            $("html, body").animate(
              {
                scrollTop: target.offset().top
              },
              1000,
              "easeInOutExpo"
            );
            return false;
          }
        }
      });
      // Closes responsive menu when a scroll trigger link is clicked
      $(".js-scroll-trigger").click(function() {
        $(".navbar-collapse").collapse("hide");
      });
      // Activate scrollspy to add active class to navbar items on scroll
      $("body").scrollspy({
        target: "#sideNav"
      });
    });
  }
};
</script>

<style>
@import "./assets/App.css";
</style>
