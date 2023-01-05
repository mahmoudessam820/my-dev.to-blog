<template>
  <div>
    <section id="topics" class="topics" aria-labelledby="topic-label">
      <div class="container">

        <div class="card topic-card">


          <div class="card-content">


            <h2 class="headline headline-2 section-title card-title" id="topic-label">
              Topics
            </h2>

            <p class="card-text">
              This is my interstate topic.
            </p>

            <div class="btn-group">

              <button class="btn-icon" aria-label="previous" data-slider-prev>
                <ion-icon name="arrow-back" aria-hidden="true"></ion-icon>
              </button>

              <button class="btn-icon" aria-label="next" data-slider-next>
                <ion-icon name="arrow-forward" aria-hidden="true"></ion-icon>
              </button>

            </div>

          </div>


          <div class="slider" data-slider>
            <ul class="slider-list" data-slider-container>


              <li class="slider-list">

                <a href="#" class="slider-card">


                  <figure class="slider-banner img-holder" style="--width: 507; --height: 618;">
                    <img />
                  </figure>

                  <div class="slider-content">

                  </div>

                </a>

              </li>

            </ul>
          </div>


        </div>

      </div>
    </section>
  </div>
</template>

<script type="text/javascript">
export default {
  name: "TheTopics",
};
</script>

<style scoped>

</style>