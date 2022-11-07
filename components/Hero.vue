<template>
  <section class="hero is-medium">
    <div class="hero-body">
      <div class="container is-fullhd">
        <div class="columns is-gapless is-vcentered">
          <div class="column">
            <p class="intro is-size-3">Hi There, I'm</p>
            <p class="name is-size-1 has-text-weight-bold">Peter Jose</p>
            <vue-typed-js :strings="['Front-end Developer.', 'Mobile Developer.']" :loop="true" :type-speed="100">
              <h1>I'm a <span class="typing"></span></h1>
            </vue-typed-js>

            <p class="description mt-4">Software Developer. Based in Parañaque City. <br> I Code & Design things for the web and mobile.</p>

            <div class="is-flex mt-5">
              <a class="download-cv" type="is-primary" rounded href="/PeterJose.pdf" download="">Download CV</a>
              <b-button class="ml-3" type="is-primary" rounded outlined>Contact Me</b-button>
            </div>
          </div>
          <div class="column has-text-centered is-hidden-mobile">
           <img src="~/assets/img/peterjose.jpg" width="400" height="516" />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroComponent',
}
</script>

<style scoped>
.hero {
  background: #e1e1e3;
}
.intro {
  color:#43a7ff; 
}
.name
{
  color: #0b224b;
  font-weight: 800 !important;
}
.typed-element h1 {
  font-size: 1.5rem;
  color: #0b224b;
  font-weight: 600;
}

.description {
  color: #777777;
}
.button.is-primary {
  background-color: #43a7ff;
font-weight: 500;
}
.button.is-primary.is-outlined {
  background-color: transparent;
  border-color: #43a7ff;
  color: #43a7ff;
  font-weight: 500;
}
.button.is-primary:focus:not(:active) {
   box-shadow: none;
}
.download-cv {
  background-color: #43a7ff;
  border-color: #43a7ff;
  color: #fff;
  font-weight: 500;
  border-radius: 9999px;
  padding-left: calc(1em + 0.25em);
  padding-right: calc(1em + 0.25em);
  padding-top: calc(0.5em - 0px);
  justify-content: center;
  padding-bottom: calc(0.5em - 1px);
  text-align: center;
  white-space: nowrap;
}
</style>
