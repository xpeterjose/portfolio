<template>
  <div>
    <Navbar />

    <Hero />

    <AboutMe />

    <Skills />
    
    <Resume />

    <RecentWorks />

    <ContactMe />

    <Footer />
  </div>
</template>

<script>
import Navbar from '~/components/Navbar'
import Hero from '~/components/Hero'
import AboutMe from '~/components/AboutMe'
import Skills from '~/components/Skills'
import Resume from '~/components/Resume'
import RecentWorks from '~/components/RecentWorks'
import ContactMe from '~/components/ContactMe'
import Footer from '~/components/Footer'

export default {
  name: 'IndexPage',
  components: {
    Navbar,
    Hero,
    AboutMe,
    Skills,
    Resume,
    RecentWorks,
    ContactMe,
    Footer
  },
}
</script>
