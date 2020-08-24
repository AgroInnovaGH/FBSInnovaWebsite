<template>
  <div class="wrapper">
    <parallax
      class="section page-header header-filter"
      :style="headerStyle"
    ></parallax>
    <div class="main main-raised">
      <div class="section profile-content">
        <div class="container">
          <div class="md-layout">
            <div class="md-layout-item md-size-50 mx-auto">
              <div class="profile">
                <div class="avatar">
                  <img
                    :src="img"
                    alt="Circle Image"
                    class="rounded-circle img-fluid"
                  />
                </div>
                <div class="name">
                  <h3 class="title">Our Impact</h3>
                </div>
              </div>
            </div>
          </div>






          <div class="section section-examples">
            <div class="container-fluid text-center" style="margin-bottom:200px">
              <div class="md-layout">
                <div class="md-layout-item">
                    <img
                            :src="img_poverty"
                            alt="Rounded Image"
                            class="img-raised rounded img-fluid"
                    />
                  <h4>Livelihood empowerment for farmers </h4>
                  <p style="margin-top:47px" class="description">
                    11% of the world’s population live in extreme poverty down from 28% in 1999 according to the UNDP. Globally, more than 800 million people are still living in less than US$ 1.25 a day and many more lack access to adequate food. Food insecurity is therefore a major fundamental issue for which Agro Innova seeks to address. Agro Innova is empowering small-holder farmers to maximize their efficiency through our tailor made technological tools which helps them manage their farms effectively and have access to guaranteed markets through cost reduction solutions and increasing profitability. At Agro Innova, we ensure that our farmers have access to technology and markets that puts them in better position to scale their businesses which helps in the poverty eradication agenda.
                  </p>
                </div>


                <!--Economic-->
              <div class="md-layout-item">
                    <img
                            :src="img_economic"
                            alt="Rounded Image"
                            class="img-raised rounded img-fluid"
                    />
                <h4>Promote full and productive employment and decent <br />
                  work through access to finance </h4>

                <p style="margin-top:47px" class="description">
                  According to the ILO, more than 204 million people were unemployed in 2015. To lower this unemployment gap, higher levels of productivity and technological innovation is needed to drive the desired economic growth and promote decent work. Agro Innova contributes to this SDG through the deployment of our suite of digital technologies (like our mobile and web-based agricultural software FBS - Innova) to help achieve full,
                  productive and decent work for all men and women in agribusinesses.
                </p>

                </div><div class="md-layout-item">
                  <img
                          :src="img_innovation"
                          alt="Rounded Image"
                          class="img-raised rounded img-fluid"
                  />
                <h4>Innovation solution to power the agricultural value chain</h4>

                  <p style="margin-top:47px" class="description">
                    As global population increases, technological progress is key to finding lasting solutions to the growing economic issues. At Agro Innova, our objective is to ensure that our farmers have equal access to industry knowledge and information in real time to help them make informed decisions, foster innovation and entrepreneurship. The agricultural value chain, just like any other industry cannot survive or thrive without the right infrastructure and constant innovations. Agro Innova therefore is focused on constantly keeping our farmers engaged through our state-of-the-art digital technologies to advance their efficiency and productivity.

                  </p>

              </div>
                <br />

                <div class="md-layout-item">
                    <img
                            :src="img_zero_hunger"
                            alt="Rounded Image"
                            class="img-raised rounded img-fluid"
                    />
                  <h4>Ensuring sustainable food security</h4>
                    <p style="margin-top:47px" class="description">
                      It is the SDGs aim to end all forms of hunger and malnutrition by 2030,
                      making sure that all people have access to sufficient and nutritious
                      food all year round through sustainable agricultural practices.
                      Our business operations are focused on helping small-holder farmers produce
                      food sustainably by providing them with timely information which helps them
                      source for production inputs through the FBSInnova mobile application which provides Good Agricultural
                      Practices. These tools and interventions empower our small-holder farmers to produce
                      food sustainably.

                    </p>

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
import { Tabs } from "@/components";
export default {
  components: {
    Tabs
  },
  bodyClass: "profile-page",
  data() {
    return {
      img_zero_hunger: require("@/assets/img/partners/zero_hunger.jpg"),
      img_economic: require("@/assets/img/partners/economic.png"),
      img_poverty: require("@/assets/img/partners/poverty.gif"),
      img_innovation: require("@/assets/img/partners/innovation.jpg"),
    };
  },
  props: {
    header: {
      type: String,
      default: require("@/assets/img/cocoa_splash.jpg")
    },
    img: {
      type: String,
      default: require("@/assets/img/innova1.png")
    }
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.header})`
      };
    }
  }
};
</script>

<style lang="scss" scoped>
.section {
  padding: 0;
}

.profile-tabs /deep/ {
  .md-card-tabs .md-list {
    justify-content: center;
  }

  [class*="tab-pane-"] {
    margin-top: 3.213rem;
    padding-bottom: 50px;

    img {
      margin-bottom: 2.142rem;
    }
  }
}

/* entire container, keeps perspective */
.flip-container {
  perspective: 1000px;
}
/* flip the pane when hovered */
.flip-container:hover .flipper, .flip-container.hover .flipper {
  transform: rotateY(180deg);
}

.flip-container, .front, .back {
  width: 320px;
  height: 480px;
}

/* flip speed goes here */
.flipper {
  transition: 0.6s;
  transform-style: preserve-3d;

  position: relative;
}

/* hide back of pane during swap */
.front, .back {
  backface-visibility: hidden;

  position: absolute;
  top: 0;
  left: 0;
}

/* front pane, placed above back */
.front {
  z-index: 2;
  /* for firefox 31 */
  transform: rotateY(0deg);
}

/* back, initially hidden pane */
.back {
  transform: rotateY(180deg);
}
</style>
