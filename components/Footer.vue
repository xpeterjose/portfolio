<template>
  <section class="hero is-small">
    <div class="hero-body">
      <div class="container is-fullhd">
        <div class="has-text-centered">
          <img src="~/assets/img/peter.png" width="50" />
          <p class="title is-5 has-text-weight-semibold mt-5">Follow Me</p>

          <div class="is-flex is-justify-content-center">
            <a href="https://www.facebook.com/peter.jose28/" target="_blank">
              <b-icon
                icon="facebook"
                size="is-medium"
                type="is-primary"
              ></b-icon>
            </a>

            <a
              href="https://www.linkedin.com/in/peter-jose-aa4701194/"
              target="_blank"
            >
              <b-icon
                icon="linkedin"
                size="is-medium"
                type="is-primary"
                class="mx-6"
              ></b-icon>
            </a>
            <a href="https://www.instagram.com/xpedrooo_/" target="_blank">
              <b-icon
                icon="instagram"
                size="is-medium"
                type="is-primary"
              ></b-icon>
            </a>
          </div>

          <p class="is-6 mt-5">Copyright ©All rights reserved</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'FooterComponent',
}
</script>
<style scoped>
.hero {
  background: #0b224b;
}
.intro {
  color: #43a7ff;
}
.my-expertise {
  color: #0b224b;
  font-weight: 800 !important;
}
p {
  color: #fff;
}
.has-text-primary {
  color: #fff !important;
}
</style>
