<template>
  <section class="hero is-medium">
    <div class="hero-body">
      <div class="container is-fullhd">
        <p class="intro is-size-4 has-text-centered">Why Choose Me</p>
        <p
          class="my-expertise is-size-1 has-text-weight-bold has-text-centered"
        >
          My Expertise Area
        </p>

        <div class="columns mt-6">
          <div class="column">
            <div class="progress-wrap">
              <h5>HTML5</h5>
              <div class="progress">
                <div class="progress-bar" style="width: 95%">
                  <span>95%</span>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <div class="progress-wrap">
              <h5>CSS3</h5>
              <div class="progress">
                <div class="progress-bar" style="width: 90%">
                  <span>90%</span>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="columns">
          <div class="column">
            <div class="progress-wrap">
              <h5>JQuery</h5>
              <div class="progress">
                <div class="progress-bar" style="width: 85%">
                  <span>85%</span>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <div class="progress-wrap">
              <h5>Vue</h5>
              <div class="progress">
                <div class="progress-bar" style="width: 95%">
                  <span>95%</span>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="columns">
          <div class="column">
            <div class="progress-wrap">
              <h5>GIT</h5>
              <div class="progress">
                <div class="progress-bar" style="width: 80%">
                  <span>80%</span>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <div class="progress-wrap">
              <h5>Bootrap</h5>
              <div class="progress">
                <div class="progress-bar" style="width: 85%">
                  <span>85%</span>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="columns">
          <div class="column">
            <div class="progress-wrap">
              <h5>C#</h5>
              <div class="progress">
                <div class="progress-bar" style="width: 75%">
                  <span>75%</span>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <div class="progress-wrap">
              <h5>Xamarin</h5>
              <div class="progress">
                <div class="progress-bar" style="width: 75%">
                  <span>75%</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SkillsComponent',
}
</script>

<style scoped>
.hero {
  background: #f1f4fb;
}
.intro {
  color: #43a7ff;
}
.my-expertise {
  color: #0b224b;
  font-weight: 800 !important;
}
.progress-wrap {
  width: 100%;
  margin-bottom: 30px;
}
.progress-wrap h5 {
  font-size: 16px;
  margin-bottom: 10px;
  font-weight: 600;
}
.progress {
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  font-size: 0.75rem;
  border-radius: 0.25rem;
  height: 6px;
  background: #cdcdcd;
  overflow: visible;
  box-shadow: none;
}
.progress-bar {
  background: #43a7ff;
  position: relative;
  font-size: 12px;
  line-height: 1.2;
  color: #000000;
  font-weight: 600;
  position: relative;
  overflow: visible;
  border-radius: 2px;
}
.progress-bar span {
  position: absolute;
  top: -38px;
  right: 0;
  font-size: 16px;
  font-weight: 600;
  color: #000000;
}
.progress-bar::after {
  position: absolute;
  top: -2px;
  right: 0;
  width: 10px;
  height: 10px;
  content: '';
  background: #43a7ff;
  border-radius: 50%;
}
</style>
