<template>
  <section id="h4c-results" class="container py-5">
    <div class="row justify-content-center">
      <div id="h4c-results-image" class="col-12 col-md-6">
        <img class="img-fluid" src="~/assets/images/slide-1.jpg" >
      </div>
      <div
        id="h4c-results-content"
        class="col-12 col-md-6 align-self-center text-center"
      >
        <div id="h4c-results-title" class="h4c--header">
          <p id="h4c-results-title" class="h4c--title">
            2019 HACK RESULTS
          </p>
        </div>
        <div id="h4c-results-description">
          <p id="h4c-results-description" class="lead">
            We had an incredibly successful hackathon with a
            spectacular turnout and some truly brilliant ideas.
            Multiple projects were successfully adopted by local
            businesses and are being implemented now.
          </p>
        </div>
        <div id="h4c-challenge-button">
          <router-link
            class="btn btn-sm btn--h4c btn--h4c-outline"
            to="/challenges-2019"
          >
            VIEW 2019 CHALLENGES
          </router-link>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
    name: "HackResults2019"
}
</script>
