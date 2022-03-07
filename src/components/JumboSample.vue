<template>
  <section class="ms_game ms_returnal">
        <div class="container text-light ms_game">
          <div class="row align-items-end py-5 ms_game">
            <div class="col-12 col-xl-4 ms_game">
              <div class="row">
                <div class="col-8 col-xl-7">
                  <img class="mb-4 ms_game" src="../assets/returnal-hero-banner-logo.png" alt="">
                </div>
              </div>
              <h2 class="mb-4 ms_fw600">Rompi il cerchio</h2>
              <p class="mb-4 ms_game">
                Rialzati dopo ogni sconfitta e affronta una nuova sfida con ogni rinascita in questo esplosivo thriller fantascientifico, disponibile in esclusiva su PS5.
              </p>
              <button type="button" class="btn btn-danger rounded-pill ms_game ms_returnal">Acquista ora</button>
            </div>
          </div>
        </div>
      </section>
</template>

<script>
export default {
  name: 'TitleSample',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
section.ms_game {
    background-position: center;
    background-size: cover;
}

section.ms_game.ms_returnal {
    background-image: url("../assets/jumbo-bg.png");
}
</style>
