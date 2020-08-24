<template>
  <div class="wrapper">
    <parallax class="page-header header-filter" :style="headerStyle">
      <div class="md-layout">
        <div class="md-layout-item">
          <div class="image-wrapper">
            <!--<img :src="leaf4" alt="leaf4" class="leaf4" v-show="leafShow" />-->
            <!--<img :src="leaf3" alt="leaf3" class="leaf3" v-show="leafShow" />-->
            <!--<img :src="leaf2" alt="leaf2" class="leaf2" v-show="leafShow" />-->
            <!--<img :src="leaf1" alt="leaf1" class="leaf1" v-show="leafShow" />-->
            <div class="brand">
              <h1><strong style="text-shadow:2px 2px 2px rgba(0,0,0,0.6)">FBS</strong>Innova</h1>
              <h3>Learn, track, diversify!</h3>
              <!--<h3 class="md-shallow">Learn - Track - Diversify</h3>-->
            </div>
          </div>
        </div>
      </div>
    </parallax>


    <div class="main main-raised">
        <div class="section">

        <div class="container">
          <div class="md-layout">
            <div
                    class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto text-center"
            >
              <h2 class="text-center">Maximize your yield</h2>
              <h5 class="description">
               FBSInnova is a functional, modular smartphone application that helps smallholder-farmers have on-demand
                access to Farmer Business School(FBS) tools and information, plan and efficiently manage their crops and diversify their
                production for increased profitability and improved livelihoods.
              </h5>
            </div>
          </div>
          <div class="features text-center">
            <div class="md-layout">
              <div class="md-layout-item md-medium-size-33 md-small-size-100 boxed">
                <div class="info">
                  <div class="icon icon-info">
                    <img
                            :src="education_icon"
                            width="60"
                    />
                  </div>
                  <h4 class="info-title"> Get educated</h4>
                  <p>
                    Daily curated content on technical advice that enlightens the farmer on best farming practices.
                    Education on personal finances and household accounting in terms of savings and spendings.
                  </p>
                </div>
              </div>


              <div class="md-layout-item md-medium-size-33 md-small-size-100 boxed">
                <div class="info">
                  <div class="icon icon-success">
                    <img :src="money_icon" width="60"/>
                  </div>
                  <h4 class="info-title">Track your finances</h4>
                  <p>

                    The accounting feature allows farmers to track their money in and money out.
                    They are able to monitor their individual crops per plot separately and measure each crop’s finances.

                  </p>
                </div>
              </div>
              <div class="md-layout-item md-medium-size-33 md-small-size-100 boxed">
                <div class="info">
                  <div class="icon icon-danger">
                    <img :src="crop_icon" width="60"/>
                  </div>
                  <h4 class="info-title">
                    Schedule farm activities</h4>
                  <p>
                    They can schedule and track their farm activities and receive prompts
                    before due dates of scheduled activities with best farm practices serving as benchmarks.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <hr style="color:whitesmoke;width:86%;text-shadow:0px 20px 2px rgba(0,0,0,0.1);text-align:center" />

      <div class="section section-examples">


        <div class="container-fluid text-center">
          <div class="md-layout">

            <div class="md-layout-item md-xsmall-hide">
              <md-card
                      style="width:500px;margin-left:100px;padding:20px"
              >
                <carousel
                        :per-page="1"
                        loop
                        :speed="700"
                        autoplay
                        :autoplay-timeout="5000"
                        :mouse-drag="false"
                >
                  <slide>
                    <img :src="carousel1" alt="carousel1" />
                  </slide>
                  <slide>
                    <img :src="carousel2" alt="carousel2" />
                  </slide>
                  <slide>
                    <img :src="carousel3" alt="carousel3" />
                  </slide>
                </carousel>
              </md-card>
            </div>


            <!--<div class="md-layout-item md-xsmall-hidden">-->
              <!--<md-card-->
                      <!--style="width:500px;margin-left:100px;padding:20px"-->
              <!--&gt;-->
                <!--<carousel-->
                        <!--:per-page="1"-->
                        <!--loop-->
                        <!--:speed="700"-->
                        <!--autoplay-->
                        <!--:autoplay-timeout="5000"-->
                        <!--:mouse-drag="false"-->
                <!--&gt;-->
                  <!--<slide>-->
                    <!--<img :src="carousel1" alt="carousel1" />-->
                  <!--</slide>-->
                  <!--<slide>-->
                    <!--<img :src="carousel2" alt="carousel2" />-->
                  <!--</slide>-->
                  <!--<slide>-->
                    <!--<img :src="carousel3" alt="carousel3" />-->
                  <!--</slide>-->
                <!--</carousel>-->
              <!--</md-card>-->
            <!--</div>-->

              <!--HIDDEN ON PHONES-->
            <!--<div class="md-small-size-20 md-layout-item text-center">-->
              <!--<div style="width:350px;margin-left:100px;margin-top:30px">-->
                <!--<h2> Our Aim</h2>-->
                 <div class="md-layout-item text-center">
              <div style="width:65%;margin-left:20%;margin-top:30px">
                <h2> Our Aim</h2>


                We aim to solve the major challenge
                faced by smallholders farmers across Africa - Low crop yield due to lack of technical and entrepreneurial skills.
                <br />
                Our solution is to help the smallholder farmer to use digital technologies to maximize efficiency in their farms by
                helping them learn, track and diversify their crops.
                <br />
                With this tool we’re creating shared value for all the key actors along the agricultural value chain by bridging the data gaps and maximizing supply chain efficiency.

                <br />
              </div>

            </div>
          </div>
        </div>
      </div>


      <div class="section">
        <div class="container text-center">
          <div class="md-layout">
            <div
                    class="md-layout-item md-size-66 md-xsmall-size-100 ml-auto mr-auto text-center"
            >
              <h2>Our core modules</h2>
              <h4>
                FBSInnova uses three(3) primary modules to enable smallholder-farmers <br />
                 track thier finances, diversify thier crops and maximize income <br />
                by equipping them with effective entrepreneurial skills.
              </h4>
            </div>
          </div>
        </div>
      </div>



      <div class="section section-examples">
        <div class="container-fluid text-center">
          <div class="md-layout">
            <div class="md-layout-item">
                <img
                        :src="iphone_education"
                        alt="Rounded Image"
                        class="rounded img-fluid"
                        width="250"
                />
              <h3>Educational hub</h3>
            </div>




            <div class="md-layout-item">
                <img
                        :src="iphone_money"
                        alt="Rounded Image"
                        class="rounded img-fluid"
                        width="250"
                />
              <h3>Money-In Money-Out</h3>

            </div>


            <div class="md-layout-item">
              <img
                      :src="iphone_calendar"
                      alt="Rounded Image"
                      class="rounded img-fluid"
                      width="250"
              />
              <h3>Cropping calendar</h3>

            </div>
          </div>

          <!--GIRL WARD-->

          <div
                  style="margin-top:120px"
                  class="md-layout-item md-size-66 md-xsmall-size-100 ml-auto mr-auto text-center"
          >
            <h2>Our impact</h2>
          </div>


          <div class="section section-examples">
            <div class="container-fluid text-center">
              <div class="md-layout">
                <div class="md-layout-item">
                  <a href="#/profile" target="_blank">
                    <img
                            :src="img_poverty"
                            alt="Rounded Image"
                            class="img-raised rounded img-fluid"
                    />
                  </a>
                  <h4>Livelihood empowerment for farmers </h4>
                </div>


                <div class="md-layout-item">
                  <a href="#/profile" target="_blank">
                    <img
                            :src="img_zero_hunger"
                            alt="Rounded Image"
                            class="img-raised rounded img-fluid"
                    />
                  </a>
                  <h4>Ensuring sustainable food security</h4>
                </div>


                <div class="md-layout-item">
                  <a href="#/profile" target="_blank">
                    <img
                            :src="img_economic"
                            alt="Rounded Image"
                            class="img-raised rounded img-fluid"
                    />
                  </a>
                  <h4>Promote full and productive employment and decent <br />
                    work through access to finance </h4>

                </div>

                <div class="md-layout-item">
                  <a href="#/profile" target="_blank">
                    <img
                            :src="img_innovation"
                            alt="Rounded Image"
                            class="img-raised rounded img-fluid"
                    />
                  </a>
                <h4>Innovation solution to power the agricultural value chain</h4>
              </div>




              </div>
            </div>

          </div>

          <div class="md-layout">
            <div class="md-layout-item text-center">
              <md-button href="#/profile" class="md-simple md-success md-lg"
              >Read More >></md-button
              >
            </div>
          </div>


          <!--SPONSORS AND PARTNERS VIEW-->


          <div class="section">

            <div class="container">
              <div class="md-layout">
                <div
                        class="md-layout-item md-size-200 md-xsmall-size-100 mx-auto text-center"
                >
                  <h2 >Trusted by</h2>

          <div id="images" class="md-layout" style="margin-top:40px">
            <div class="md-layout">
              <div
                      class="md-layout-item md-size-20 md-xsmall-size-100"
                      :class="{ 'text-center': responsive }"
              >
                <img
                        :src="img_giz"
                        alt="Rounded Image"
                        class="rounded"
                        :class="{ 'responsive-image': responsive }"
                />
              </div>

              <div
              class="md-layout-item md-size-20 md-xsmall-size-100 ml-auto"
              :class="{ 'text-center': responsive }"
              >
              <img
              :src="img_agro"
              alt="Raised Image"
              :class="{ 'responsive-image': responsive }"
              />
              </div>

              <div
                      class="md-layout-item md-size-20 md-xsmall-size-100 ml-auto"
                      :class="{ 'text-center': responsive }"
              >
                <img
                        :src="img_mofa"
                        alt="Circle Image"
                        :class="{ 'responsive-image': responsive }"
                />
              </div>

              <div
                      class="md-layout-item md-size-20 md-xsmall-size-100 ml-auto"
                      :class="{ 'text-center': responsive }"
              >
                <img
                        :src="img_cocobod"
                        alt="Thumbnail Image"
                        :class="{ 'responsive-image': responsive }"
                />
              </div>
            </div>
          </div>


        </div>


      </div>



  </div>
  </div>
  </div>
      </div>
      </div>
      </div>

</template>

<script>
import BasicElements from "./components/BasicElementsSection";
import Navigation from "./components/NavigationSection";
import SmallNavigation from "./components/SmallNavigationSection";
import Tabs from "./components/TabsSection";
import NavPills from "./components/NavPillsSection";
import Notifications from "./components/NotificationsSection";
import TypographyImages from "./components/TypographyImagesSection";
import JavascriptComponents from "./components/JavascriptComponentsSection";
import { LoginCard } from "@/components";

export default {
  components:{
    BasicElements,
    Navigation,
    SmallNavigation,
    Tabs,
    NavPills,
    Notifications,
    TypographyImages,
    JavascriptComponents,
    LoginCard
  },
  name: "index",
  bodyClass: "index-page",
  props: {
    image: {
      type: String,
      default: require("@/assets/img/vue-mk-header.jpg")
    },
    iphone_money: {
      type: String,
      default: require("@/assets/img/fbs_assets/iphone_money.png")
    },
    iphone_education: {
      type: String,
      default: require("@/assets/img/fbs_assets/iphone_education.png")
    },
    iphone_calendar: {
      type: String,
      default: require("@/assets/img/fbs_assets/iphone_calendar.png")
    },
    crop_icon: {
      type: String,
      default: require("@/assets/img/fbs_assets/fin5.png")
    },
    money_icon: {
      type: String,
      default: require("@/assets/img/fbs_assets/fin_1.png")
    },
    education_icon: {
      type: String,
      default: require("@/assets/img/fbs_assets/set2.png")
    }
  },
  data() {
    return {
      firstname: null,
      email: null,
      password: null,
      leafShow: false,
      classicModal: false,
      selectedDate: new Date("2018/03/26"),
      carousel1: require("@/assets/img/innova1.png"),
      carousel2: require("@/assets/img/innova2.png"),
      carousel3: require("@/assets/img/innova3.png"),
      img_giz: require("@/assets/img/partners/img_giz.png"),
      img_cocobod: require("@/assets/img/partners/img_cocobod.jpg"),
      img_mofa: require("@/assets/img/partners/img_mofa.png"),
      img_agro: require("@/assets/img/partners/img_agro.png"),
      img_zero_hunger: require("@/assets/img/partners/zero_hunger.jpg"),
      img_economic: require("@/assets/img/partners/economic.png"),
      img_poverty: require("@/assets/img/partners/poverty.gif"),
      img_innovation: require("@/assets/img/partners/innovation.jpg"),
      responsive: false
    };
  },
  methods: {
    leafActive() {
      if (window.innerWidth < 768) {
        this.leafShow = false;
      } else {
        this.leafShow = true;
      }
    }
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.image})`
      };
    },
    signupImage() {
      return "backgroundImage:url("+this.edu_hub+");width:600px;" +
              "position:relative;left:200px";
    }
  },
  mounted() {
    this.leafActive();
    window.addEventListener("resize", this.leafActive);
  },
  beforeDestroy() {
    window.removeEventListener("resize", this.leafActive);
  }
};
</script>
<style lang="scss">
.section-download {
  .md-button + .md-button {
    margin-left: 5px;
  }
}

@media all and (min-width: 991px) {
  .btn-container {
    display: flex;
  }
  .boxed{
    border:1px solid #e3e3e3;
    box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
    transition: all 0.3s cubic-bezier(.25,.8,.25,1);
    border-radius:10px;
    margin-left:5px;
  }

  .boxed:hover {
    box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22);
  }
}



</style>
