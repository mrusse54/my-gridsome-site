<template>
  <Layout>
 <About />
     <Courses />
     <Project />
      <Resume />
     <Contact />
  </Layout>
</template>

<script>

import About from '@/components/About.vue'
import Courses from '@/components/Courses.vue'
import Project from '@/components/Project.vue'
import Resume from '@/components/Resume.vue'
import Contact from '@/components/Contact.vue'

export default {
  metaInfo: {
    title: "About",
  },
  components: {
  About,
  Courses,
   Resume,
  Project,
  Contact
  },
  
  data: () => ({
      years: [
        {
          color: 'blue',
          colorText: 'white',
          year: '1960',
          school: 'Blank',
          bio: 'IDK WHAT I DID THERE',
        },
        {
          color: 'blue',
          colorText: 'white',
          year: '1960',
          school: 'Blank',
          bio: 'IDK WHAT I DID THERE',
        },
        {
          color: 'blue',
          colorText: 'white',
          year: '1960',
          school: 'Blank',
          bio: 'IDK WHAT I DID THERE',
        },
        {
          color: 'blue',
          colorText: 'white',
          year: '1960',
          school: 'Blank',
          bio: 'IDK WHAT I DID THERE',
        },
        {
          color: 'blue',
          colorText: 'white',
          year: '1960',
          school: 'Blank',
          bio: 'IDK WHAT I DID THERE',
        },
      ],
    }),
};
</script>

<style >

#portrait{
  margin-right: -700px;
}


</style>
