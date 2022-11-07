<template>
  <section class="hero is-medium">
    <div class="hero-body">
      <div class="container is-fullhd">
        <p class="intro is-size-4 has-text-centered">My Qualification</p>
        <p
          class="awesome-journey is-size-1 has-text-weight-bold has-text-centered"
        >
          Awesome Journey
        </p>
        <p class="resume-title has-text-weight-bold is-size-3 mt-5">
          Education
        </p>

        <div class="resume-wrap transition is-flex mt-4">
          <div
            class="icon is-flex is-align-items-center is-justify-content-center"
          >
            <b-icon
              icon="school-outline"
              size="is-medium"
              type="is-primary"
            ></b-icon>
          </div>
          <div class="text ml-3">
            <span class="date">2016-2018</span>
            <h4>Bachelor in Computer Engineering</h4>
            <span class="position">Rizal Technological University</span>
            <p>
              Lorem ipsum, or lipsum as it is sometimes known, is dummy text
              used in laying out print, graphic or web designs. The passage is
              attributed to an unknown typesetter in the 15th century who is
              thought to have.
            </p>
          </div>
        </div>

        <div class="resume-wrap transition is-flex mt-4">
          <div
            class="icon is-flex is-align-items-center is-justify-content-center"
          >
            <b-icon
              icon="school-outline"
              size="is-medium"
              type="is-primary"
            ></b-icon>
          </div>
          <div class="text ml-3">
            <span class="date">2014-2016</span>
            <h4>Diploma in Computer Engineering</h4>
            <span class="position">Rizal Technological University</span>
            <p>
              Lorem ipsum, or lipsum as it is sometimes known, is dummy text
              used in laying out print, graphic or web designs. The passage is
              attributed to an unknown typesetter in the 15th century who is
              thought to have.
            </p>
          </div>
        </div>

        <p class="resume-title has-text-weight-bold is-size-3 mt-5">
          Experience
        </p>

        <div class="resume-wrap transition is-flex mt-4">
          <div
            class="icon is-flex is-align-items-center is-justify-content-center"
          >
            <b-icon
              icon="school-outline"
              size="is-medium"
              type="is-primary"
            ></b-icon>
          </div>
          <div class="text ml-3">
            <span class="date">June 2018 - June 2020</span>
            <h4>Leandev Inc</h4>
            <span class="position">Front-end Developer</span>
            <p>
              Lorem ipsum, or lipsum as it is sometimes known, is dummy text
              used in laying out print, graphic or web designs. The passage is
              attributed to an unknown typesetter in the 15th century who is
              thought to have.
            </p>
          </div>
        </div>

        <div class="resume-wrap transition is-flex mt-4">
          <div
            class="icon is-flex is-align-items-center is-justify-content-center"
          >
            <b-icon
              icon="school-outline"
              size="is-medium"
              type="is-primary"
            ></b-icon>
          </div>
          <div class="text ml-3">
            <span class="date">June 2020 - March 2021</span>
            <h4>Kairos Cargo Group Inc</h4>
            <span class="position">Front-end Developer</span>
            <p>
              Lorem ipsum, or lipsum as it is sometimes known, is dummy text
              used in laying out print, graphic or web designs. The passage is
              attributed to an unknown typesetter in the 15th century who is
              thought to have.
            </p>
          </div>
        </div>

        <div class="resume-wrap transition is-flex mt-4">
          <div
            class="icon is-flex is-align-items-center is-justify-content-center"
          >
            <b-icon
              icon="school-outline"
              size="is-medium"
              type="is-primary"
            ></b-icon>
          </div>
          <div class="text ml-3">
            <span class="date">March 2021 - Oct 2021</span>
            <h4>BasicBrix</h4>
            <span class="position">Front-end Developer</span>
            <p>
              Lorem ipsum, or lipsum as it is sometimes known, is dummy text
              used in laying out print, graphic or web designs. The passage is
              attributed to an unknown typesetter in the 15th century who is
              thought to have.
            </p>
          </div>
        </div>

        <div class="resume-wrap transition is-flex mt-4">
          <div
            class="icon is-flex is-align-items-center is-justify-content-center"
          >
            <b-icon
              icon="school-outline"
              size="is-medium"
              type="is-primary"
            ></b-icon>
          </div>
          <div class="text ml-3">
            <span class="date">Oct 2021 - Present</span>
            <h4>Traxion</h4>
            <span class="position">Mobile Developer</span>
            <p>
              Lorem ipsum, or lipsum as it is sometimes known, is dummy text
              used in laying out print, graphic or web designs. The passage is
              attributed to an unknown typesetter in the 15th century who is
              thought to have.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ResumeComponent',
}
</script>

<style scoped>
.intro {
  color: #43a7ff;
}
.awesome-journey {
  color: #0b224b;
  font-weight: 800 !important;
}
.resume-title {
  color: #0b224b;
}
.has-text-primary {
  color: #fff !important;
}

.resume-wrap {
  width: 100%;
  margin-bottom: 30px;
  background-color: #f1f4fb;
  padding: 40px 30px;
  border-radius: 10px;
}
.resume-wrap .icon {
  width: 50px;
  height: 50px;
  background: #43a7ff;
  border-radius: 50%;
}
.resume-wrap .date {
  font-weight: 700;
  font-size: 16px;
  color: #222222;
}
.resume-wrap h4 {
  font-size: 20px;
  font-weight: 700;
}
.resume-wrap .position {
  display: inline-block;
  margin-bottom: 10px;
}
.resume-wrap:hover {
  background: #43a7ff;
  color: #ffffff;
}
.resume-wrap:hover .date {
  color: #ffffff;
}
.resume-wrap:hover .icon {
  background: #ffffff;
}

.resume-wrap:hover .has-text-primary {
  color: #0b224b !important;
}
.mdi-36px.mdi-set, .mdi-36px.mdi:before {
    font-size: 26px !important;
}
.transition {
  transition: all 0.3s ease 0s;
}
</style>
