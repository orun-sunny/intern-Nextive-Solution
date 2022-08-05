<template>
  <v-footer dark padless>
    <v-card
      flat
      tile
      class="black white--text py-5 px-5 text-center"
      width="100%"
    >
      <section
        class="ftco-section contact-section ftco-no-pb"
        id="contact-section"
      >
        <div class="container">
          <div class="row justify-content-center py-5 mt-5">
            <div class="col-md-12 heading-section text-center ftco-animate">
              <h2 class="mt-8 white--text">Contact Me</h2>
            </div>
          </div>

          <!-- <div class="row justify-content-center mb-4 pb-3">
            <div class="col-md-7 heading-section text-center ftco-animate">
              <h2 class="mb-4">Contact Me</h2>
            </div>
          </div> -->
          <div class="row mx-auto my-15 ml-15 second">
            <div class="col-md-4 text-center d-flex mx-auto ftco-animate">
              <v-card
                :loading="loading"
                class="mx-auto my-15"
                max-width="374"
                color="#385F73"
                dark
              >
                <v-card-text>
                  <v-row align="center" class="mx-0">
                    <v-rating size="14"></v-rating>
                  </v-row>

                  <a>
                    <v-icon large color="white darken-2"> mdi-dialpad </v-icon>
                    <div class="desc">
                      <p class="white--text">Contact Number</p>
                      <p class="white--text">01942257725</p>
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
                class="mx-auto my-15"
                max-width="374"
                color="#385F73"
                dark
              >
                <v-card-text>
                  <v-row align="center" class="mx-0">
                    <v-rating size="14"></v-rating>
                  </v-row>

                  <a>
                    <v-icon large color="white darken-2 p-2">
                      mdi-email
                    </v-icon>
                    <div class="desc mt-8">
                      <p class="white--text">Email</p>
                      <p class="white--text">sunny.mukut@gmail.com</p>
                    </div>
                  </a>
                </v-card-text>

                <v-divider class="mx-4"></v-divider>

                <v-card-title></v-card-title>
              </v-card>
            </div>
            <div class="col-md-4 text-center d-flex mx-auto ftco-animate">
              <v-card
                :elevation="hover ? 16 : 2"
                class="mx-auto my-15 { 'on-hover': hover }"
                max-width="374"
                color="#385F73"
                dark
              >
                <v-card-text>
                  <v-row align="center" class="mx-0">
                    <v-rating size="14"></v-rating>
                  </v-row>

                  <a>
                    <v-icon large color="white darken-2">
                      mdi-message-text
                    </v-icon>
                    <div class="desc">
                      <p class="white--text">Website</p>
                      <p class="white--text">Orun-sunny</p>
                    </div>
                  </a>
                </v-card-text>

                <v-divider class="mx-4"></v-divider>

                <v-card-title></v-card-title>
              </v-card>
            </div>
          </div>

          <!-- <v-row>
            <v-col cols="6">
              <div class="col-md-6 order-md-last d-flex">
                <form
                  method="POST"
                  action="https://formspree.io/f/mnqlzbwg"
                  class="bg-light p-4 p-md-5 contact-form"
                >
                  <div class="form-group">
                    <input
                      type="text"
                      class="form-control"
                      name="name"
                      placeholder="Your Name"
                      required
                    />
                  </div>
                  <div class="form-group">
                    <input
                      type="email"
                      class="form-control"
                      name="email"
                      placeholder="Your Email"
                      required
                    />
                  </div>
                  <div class="form-group">
                    <textarea
                      id=""
                      cols="30"
                      rows="7"
                      class="form-control"
                      name="message"
                      placeholder="Message"
                      required
                    ></textarea>
                  </div>

                  <div class="form-group">
                    <input
                      type="submit"
                      value="Send Message"
                      class="btn btn-primary py-3 px-5"
                    />
                    <input
                      type="hidden"
                      name="_next"
                      value="//https://github.com/orun-sunny"
                    />
                  </div>
                </form>
              </div>
            </v-col>

            <v-col cols="6">
              <v-img src="1.png" contain max-height="500"></v-img>
            </v-col>
          </v-row> -->

          <!-- <div class="col-md-6 d-flex">
              <div
                class="img"
                style="background-image: url(assets/about.jpeg)"
              ></div>
            </div> -->
        </div>
      </section>

      <!-- try here -->
      <v-row>
        <v-col cols="6">
          <v-img src="1.png" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <div class="col-md-6 border-md-last d-flex">
            <form
              method="POST"
              action="https://formspree.io/f/mnqlzbwg"
              class="bg-light p-4 p-md-5 contact-form bgColor1"
            >
              <div class="form-group m-1px border">
                <input
                  border="1px solid"
                  type="text"
                  class="form-control"
                  name="name"
                  placeholder="Your Name"
                  required
                />
              </div>
              <div class="form-group border">
                <input
                  type="email"
                  class="form-control"
                  name="email"
                  placeholder="Your Email"
                  required
                />
              </div>
              <div class="form-group border">
                <textarea
                  id=""
                  cols="30"
                  rows="7"
                  class="form-control"
                  name="message"
                  placeholder="Message"
                  required
                ></textarea>
              </div>

              <div class="form-group">
                <input
                  type="submit"
                  value="Send Message"
                  class="btn rounded-lg rounded-tl-0 black--text py-3 px-5"
                />
                <input
                  type="hidden"
                  name="_next"
                  value="https://github.com/orun-sunny"
                />
              </div>
            </form>
          </div>
        </v-col>
      </v-row>

      <v-row>
        <v-col cols="12" sm="4">
          <v-card-text class="white--text pt-2">
            <v-btn icon>
              <!-- <v-icon color="#A7121D">sunny</v-icon> -->
            </v-btn>
          </v-card-text>
        </v-col>

        <v-col cols="12" sm="4">
          <footer class="ftco-footer ftco-section">
            <div class="container">
              <div class="row mb-5">
                <div class="col-md">
                  <div class="ftco-footer-widget mb-4">
                    <h2 class="ftco-heading-2">About</h2>
                    <p class="white--text">
                      I like working with new tools and technologies
                    </p>
                    <p class="mt-4"><u>Social Links</u></p>
                  </div>
                </div>
                <div class="col-md">
                  <div class="ftco-footer-widget mb-4 ml-md-4">
                    <h2 class="ftco-heading-2">Links</h2>
                    <ul class="list-unstyled">
                      <li><v-icon href="#home-section">home</v-icon>Home</li>
                      <li><v-icon href="#about-section"></v-icon>About</li>
                      <li><v-icon href="#project-section"></v-icon>Project</li>
                      <li>
                        <!-- <a href="#project-section"
                          ><span class="icon-long-arrow-right mr-2"></span
                          >Projects</a -->
                        <v-icon href="#project-section"></v-icon>Contact
                      </li>
                    </ul>
                  </div>
                </div>

                <div class="col-md">
                  <div class="ftco-footer-widget mb-4">
                    <h2 class="ftco-heading-2">Have a Question?</h2>
                    <div class="block-23 mb-3">
                      <ul>
                        <li>
                          <a
                            ><span class="icon icon-phone"></span
                            ><span class="text">01942257725</span></a
                          >
                        </li>
                        <li>
                          <a href="mailto:sunny.mukut@gmail.com"
                            ><span class="icon icon-envelope"></span
                            ><span class="text">sunny.mukut@gmail.com</span></a
                          >
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-md-12 text-center">
                  <i class="icon-heart color-danger" aria-hidden="true"></i>
                  <i class="icon-heart color-danger" aria-hidden="true"></i>
                  <p class="mt-5">Copyright 2022&copy;</p>
                  <v-card-text class="pt-4">
                    <v-btn class="white--text" icon>
                      <v-icon color="#A7121D">mdi-heart</v-icon>
                    </v-btn>
                    Created by Orun
                  </v-card-text>
                </div>
                <v-col cols="12" sm="4"> </v-col>
              </div>
            </div>
          </footer>
        </v-col>
      </v-row>
    </v-card>
  </v-footer>
</template>

<script>
export default {};
document.write(new Date().getFullYear());
</script>

<style>
.container {
  background-color: black;
}

.bgColor1 {
  text-decoration: none;
  background-color: #e3f2fd;

  /* background-color: #1e1e1e; */
  padding: 4rem 4rem;
  padding-top: 50px;

  text-align: left;
}

.border {
  background-color: beige;
}
</style>
