<!-- eslint-disable vue/no-parsing-error -->
<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="1.png" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <v-btn class="mt-6" title color="#FF8F00" dark> about me </v-btn>
          <h1 class="white--text">Full-Stack Web Developer</h1>
          <ul class="about-info white--text font-weight-bold mt-4 px-md-0 px-2">
            <li class="d-flex"><span>Name:</span><span>Md.Orun Sunny</span></li>
            <li class="d-flex">
              <span>Email:</span><span style="">sunny.mukut@gmail.com</span>
            </li>
            <li class="d-flex">
              <span>Phone:</span><span>+880-1942257725</span>
            </li>
            <li class="d-flex">
              <span>Country:</span> <span>Bangladesh</span>
            </li>
            <li class="d-flex"><span>City:</span><span>Dhaka</span></li>
          </ul>

          <v-btn class="mt-6" title color="#FF8F00" dark>
            <div class="text" title color="#FF8F00">
              <p title color="#FF8F00">
                <a
                  title
                  color="#FF8F00"
                  href="https://drive.google.com/file/d/1VhxwpzhQskiJ-9F_KkhzrFy5Or632Kre/view?usp=sharing"
                  target="_blank"
                  class="py-3"
                  >Download CV</a
                >
              </p>
            </div>
          </v-btn>
        </v-col>

        <v-col cols="12" class="padd">
          <div class="first" id="project">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <h2 class="heading white--text ml-3 mt-4">Education</h2>
                  >
                  <div class="resume-wrap d-flex ftco-animate">
                    <div
                      class="icon d-flex align-items-center justify-content-center"
                    >
                      <span class="flaticon-graduation-cap"></span>
                    </div>
                    <div class="text pl-3 white--text">
                      <h2>University of Asia Pacific</h2>
                      <span class="position">Bachelor of Science</span>
                      <p><strong>Computer Science & Engineering</strong></p>
                      <p>Dhaka -Bangladesh</p>
                      <span class="date">2018-2021</span>
                    </div>
                  </div>
                  <v-btn color="#FF8F00" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>

                <div class="child bgColor2">
                  <div class="text pl-3">
                    <h2>Chuadanga Govt. College,Chuadanga</h2>
                    <span class="position">Higher Secondary Certificate</span>
                    <p><strong>Science </strong></p>
                    <p>Chuadanga -Bangladesh</p>
                    <span class="date">2013-2015</span>
                  </div>
                  <v-btn color="" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <div class="text pl-3 white--text">
                    <h2 class="heading white--text mt-4">SSC</h2>
                    <br />
                    <h2>V.J Govt high School</h2>
                    <span class="position">Science</span>
                    <br />
                    <span class="position">Basic Science</span>

                    <p>Chuadanga -Bangladesh</p>
                    <span class="date">2007-2013</span>
                  </div>
                  <v-btn color="#FF8F00" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
              </v-col>

              <!-- Uporer part ses -->

              <v-col cols="12" class="mt-10">
                <div class="child">
                  <h1 class="orange--text mt-3">Experience</h1>
                  <h2 class="cyan--text mt-3">Brain-cache</h2>
                  <div>
                    <li class="white--text mt-3">Web-dev</li>
                    <li class="white--text mt-3">Dec 2018 - 2019</li>
                  </div>
                </div>
                <div class="child">
                  <h1 class="orange--text mt-3">achievements</h1>
                  <h2 class="cyan--text mt-3">1st runner up</h2>
                  <div>
                    <li class="white--text mt-3">NCPC</li>
                    <li class="white--text mt-3">Dec 2019</li>
                  </div>
                </div>

                <div class="child">
                  <h1 class="orange--text mt-3">Leadership & Activities</h1>

                  <h2 class="cyan--text mt-3">Software & Hardware Club</h2>
                  <div>
                    <li class="white--text mt-3">President</li>
                    <li class="white--text mt-3">Dec 2018 - 2020</li>
                  </div>
                </div>

                <!-- <div class="child2 mButton padding bgColor1">
                        <h1 class="red--text text--darken-4">60+</h1>
                        <p class="grey--text">Clients</p>
                      </div> -->
              </v-col>
            </v-row>
          </div>
        </v-col>

        <!-- projects -->

        <section
          class="ftco-section justify-content-center"
          id="project-section"
        >
          <div class="container-fluid px-md-5">
            <div class="row justify-content-center py-5 mt-5">
              <div class="col-md-12 heading-section text-center ftco-animate">
                <h2 class="mt-16 white--text">Projects</h2>
              </div>
            </div>
            <div class="row mx-auto my-15 ml-15 second">
              <div class="col-md-4 text-center d-flex mx-auto ftco-animate">
                <v-card
                  :loading="loading"
                  class="mx-auto my-15"
                  max-width="374"
                  color="#385F73"
                  dark
                >
                  <v-card-title>BD-CarZ</v-card-title>

                  <v-card-text>
                    <v-row align="center" class="mx-0">
                      <v-rating
                        :value="4.5"
                        color="amber"
                        dense
                        half-increments
                        readonly
                        size="14"
                      ></v-rating>
                    </v-row>

                    <a
                      href="https://github.com/orun-sunny/BD-CarZ-Client"
                      target="_blank"
                      class="services-1 shadow"
                    >
                      <span class="icon">
                        <i class="flaticon-camp"></i>
                      </span>
                      <div class="desc">
                        <h3 class="mb-4 white--text">BD-CarZ</h3>
                        <p class="white--text">
                          <strong>React • Bootstrap • MongoDB </strong>
                        </p>
                        <p class="white--text">
                          A website those are want to buy car, they can add to
                          cart,and easy job.It will make life easier <br />
                          Used React along with HTML ,CSS to make the
                          application. MongoDB for the database.
                        </p>
                      </div>
                    </a>
                  </v-card-text>

                  <v-divider class="mx-4"></v-divider>

                  <v-card-title></v-card-title>
                </v-card>
              </div>

              <div class="col-md-4 text-center d-flex mx-auto ftco-animate">
                <v-card
                  :loading="loading"
                  class="mx-auto my-12"
                  max-width="374"
                  color="#385F73"
                  dark
                >
                  <v-card-title>Online healthcare</v-card-title>

                  <v-card-text>
                    <v-row align="center" class="mx-0">
                      <v-rating
                        :value="4.5"
                        color="amber"
                        dense
                        half-increments
                        readonly
                        size="14"
                      ></v-rating>
                    </v-row>

                    <a
                      href="https://github.com/orun-sunny/health-care"
                      target="_blank"
                      class="services-1 shadow"
                    >
                      <span class="icon">
                        <i class="icon-stethoscope"></i>
                      </span>
                      <div class="desc">
                        <h3 class="mb-4 white--text">Online Health Care</h3>
                        <p class="white--text">
                          <strong>React • Bootstrap</strong>
                        </p>
                        <p class="white--text">
                          private/protected routes are use with firebase
                          Authentication,Here you can make an Appointment
                          interactivity.
                        </p>
                      </div>
                    </a>
                  </v-card-text>

                  <v-divider class="mx-4"></v-divider>
                </v-card>
              </div>
              <div class="col-md-4 text-center d-flex mx-auto ftco-animate">
                <v-card
                  :loading="loading"
                  class="mx-auto my-12"
                  max-width="374"
                  color="#385F73"
                  dark
                >
                  <v-card-title>Copa America Frontend</v-card-title>

                  <v-card-text>
                    <v-row align="center" class="mx-0">
                      <v-rating
                        :value="4.5"
                        color="amber"
                        dense
                        half-increments
                        readonly
                        size="14"
                      ></v-rating>
                    </v-row>

                    <a
                      href="https://github.com/orun-sunny/copa-america"
                      target="_blank"
                      class="services-1 shadow"
                    >
                      <span class="icon">
                        <i class="icon-terminal"></i>
                      </span>
                      <div class="desc">
                        <h3 class="mb-4 white--text">Copa America Frontend</h3>
                        <p class="white--text">
                          <strong>HTML • CSS •Bootstrap </strong>
                        </p>
                        <p class="white--text">
                          A Front page is a compilation of materials that
                          exemplifies your beliefs, skills,
                          qualifications,education, training and experiences. It
                          provides me skills, Confidence.
                        </p>
                      </div>
                    </a>
                  </v-card-text>

                  <v-divider class="mx-4"></v-divider>
                </v-card>
              </div>
            </div>

            <div class="row ml-16 mr-16 second">
              <div class="col-md-4 text-center d-flex mx-auto ftco-animate">
                <v-card
                  :loading="loading"
                  class="mx-auto my-12"
                  max-width="374"
                  color="#385F73"
                  dark
                >
                  <v-card-title>Tourism</v-card-title>

                  <v-card-text>
                    <v-row align="center" class="mx-0">
                      <v-rating
                        :value="4.5"
                        color="amber"
                        dense
                        half-increments
                        readonly
                        size="14"
                      ></v-rating>
                    </v-row>

                    <a
                      href="https://github.com/orun-sunny/tourism-web-client"
                      target="_blank"
                      class="services-1 shadow"
                    >
                      <span class="icon">
                        <i class="icon-paper-plane"></i>
                      </span>
                      <div class="desc">
                        <h3 class="mb-4 white--text">Tourism</h3>
                        <p class="white--text">
                          <strong>React •NodeJS • MongoDB</strong>
                        </p>
                        <p class="white--text">
                          It has an admin dashboard and functionality like
                          adding or deleting packages. Anyone Can order a
                          package and Handel own order from booking page.
                          Authentication Added.
                        </p>
                      </div>
                    </a>
                  </v-card-text>

                  <v-divider class="mx-4"></v-divider>
                </v-card>
              </div>
              <div class="col-md-4 text-center d-flex ftco-animate">
                <v-card
                  :loading="loading"
                  class="mx-auto my-12"
                  max-width="374"
                  color="#385F73"
                  dark
                >
                  <v-card-title>Gym-Frontend</v-card-title>

                  <v-card-text>
                    <v-row align="center" class="mx-0">
                      <v-rating
                        :value="4.5"
                        color="amber"
                        dense
                        half-increments
                        readonly
                        size="14"
                      ></v-rating>
                    </v-row>

                    <a
                      href="https://github.com/orun-sunny/Gym-frontend "
                      target="_blank"
                      class="services-1 shadow"
                    >
                      <span class="icon">
                        <i class="flaticon-circuit-board"></i>
                      </span>

                      <div class="desc">
                        <h3 class="mb-4 white--text">Gym-Frontend</h3>
                        <p class="white--text">
                          <strong>Html •ReactJS </strong>
                        </p>
                        <p class="white--text">
                          Fronted responsive Page developed with Bootstrap,
                          HTML, CSS and deployed GitHub.
                        </p>
                      </div>
                    </a>
                  </v-card-text>

                  <v-divider class="mx-4"></v-divider>
                </v-card>
              </div>
              <div class="col-md-4 text-center d-flex ftco-animate">
                <v-card
                  :loading="loading"
                  class="mx-auto my-12"
                  max-width="374"
                  color="#385F73"
                  dark
                >
                  <v-card-title>Gym-Frontend</v-card-title>

                  <v-card-text>
                    <v-row align="center" class="mx-0">
                      <v-rating
                        :value="4.5"
                        color="amber"
                        dense
                        half-increments
                        readonly
                        size="14"
                      ></v-rating>
                    </v-row>

                    <a
                      href="https://github.com/orun-sunny/onlinemedical"
                      target="_blank"
                      class="services-1 shadow"
                    >
                      <span class="icon">
                        <i class="flaticon-bomberman"></i>
                      </span>

                      <div class="desc">
                        <h3 class="mb-4 white--text">online Counseling</h3>
                        <p class="white--text">
                          <strong>Python • Django •sqlite3 </strong>
                        </p>
                        <p class="white--text">
                          A web based application that allows user to take
                          medical service own.<br />Used Python along with
                          Django to make the application. sqlite3 for the
                          database. <br />(Team Project -3rd year)
                        </p>
                      </div>
                    </a>
                  </v-card-text>

                  <v-divider class="mx-4"></v-divider>
                </v-card>
              </div>
            </div>
          </div>

          <!-- </div> -->
        </section>

        <!-- I will try -->

        <v-col cols="12">
          <div class="second">
            <div class="secondchild1" id="contact">
              <v-row>
                <v-col cols="12">
                  <div class="row justify-content-center">
                    <div class="col-md-8 ftco-animate text-center">
                      <h2 class="orange--text">
                        I'm <span>Available</span> for Hire
                      </h2>
                      <!-- <p class="mb-0">I am looking for opportunities in<br>Software Development • Software Engineering • Web Development</p> -->

                      <!-- <a href="resume/.pdf" target="_blank" class="btn btn-primary py-3 px-5">Hire me</a> -->
                      <v-btn>
                        <a
                          id="fiverr"
                          href="https://www.fiverr.com/orun_sunny?up_rollout=true"
                          target="_blank"
                          >Fiverr</a
                        >
                      </v-btn>
                    </div>
                  </div>
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#111111" dark flat> </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";

export default {
  name: "Home",
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
  components: {
    NavBar,
    Footer,
  },
};
</script>
<style scoped>
.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -250px;
}
.topTolbar {
  margin-top: 200px;
  text-align: center;
}
.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 8rem 8rem;
}
.secondchild1 {
  text-decoration: none;
  display: inline-block;
  background-color: #1e1e1e;
  padding: 8rem 8rem;
  padding-top: 50px;
  vertical-align: middle;
  text-align: left;
  margin-top: 200px;
  /* margin-bottom: 50px; */
}
.child {
  text-decoration: none;
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1 {
  background-color: #1e1e1e;
}
.bgColor2 {
  background-color: #ff8f00;
}

.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0;
}

.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
#project-section {
  align-items: center;
}
</style>
