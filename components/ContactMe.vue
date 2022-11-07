<template>
  <section class="hero is-medium">
    <div class="hero-body">
      <div class="container is-fullhd">
        <p class="intro is-size-4 has-text-centered">Contact Me</p>
        <p
          class="my-expertise is-size-1 has-text-weight-bold has-text-centered"
        >
          Get in Touch
        </p>

        <div class="columns mt-5 form">
          <div class="column is-9">
            <div class="columns">
              <div class="column">
                <b-input placeholder="Name" expanded></b-input>
              </div>
              <div class="column">
                <b-input placeholder="Email" expanded></b-input>
              </div>
            </div>
            <b-input class="mb-5" placeholder="Subject" expanded></b-input>
            <b-input type="textarea" placeholder="Message" expanded></b-input>
            <b-button class="mt-5" type="is-primary" rounded
              >Send Message</b-button
            >
          </div>
          <div class="column">
            <div class="is-flex is-align-items-center">
              <div
                class="icon is-flex is-align-items-center is-justify-content-center"
              >
                <b-icon
                  icon="phone"
                  size="is-medium"
                  type="is-primary"
                ></b-icon>
              </div>

              <div class="ml-4">
                <p class="title is-size-4">Call Me</p>
                <p class="subtitle is-size-5s">09561788123</p>
              </div>
            </div>

            <div class="is-flex is-align-items-center mt-6">
              <div
                class="icon is-flex is-align-items-center is-justify-content-center"
              >
                <b-icon
                  icon="email-outline"
                  size="is-medium"
                  type="is-primary"
                ></b-icon>
              </div>

              <div class="ml-4">
                <p class="title is-size-4">Email</p>
                <p class="subtitle is-size-5s">peterjose286@gmail.com</p>
              </div>
            </div>

            <div class="is-flex is-align-items-center mt-6">
              <div
                class="icon is-flex is-align-items-center is-justify-content-center"
              >
                <b-icon
                  icon="map-marker"
                  size="is-medium"
                  type="is-primary"
                ></b-icon>
              </div>

              <div class="ml-4">
                <p class="title is-size-4">Location</p>
                <p class="subtitle is-size-5s">Parañaque City</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.intro {
  color: #43a7ff;
}
.my-expertise {
  color: #0b224b;
  font-weight: 800 !important;
}
.form >>> .input:focus,
.form >>> .textarea:focus {
  border-color: #43a7ff !important;
  box-shadow: none !important;
}
.button.is-primary,
.button.is-primary:focus:not(:active),
.button.is-primary.is-focused:not(:active) {
  background-color: #43a7ff;
  box-shadow: none;
}
.icon {
  width: 50px;
  height: 50px;
  background: #43a7ff;
  border-radius: 50%;
}
.has-text-primary {
  color: #fff !important;
}
.icon .mdi-36px.mdi-set,
.mdi-36px.mdi:before {
  font-size: 26px !important;
}
</style>
