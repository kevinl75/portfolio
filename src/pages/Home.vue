<script>
import IconNavigator from '../components/IconNavigator.vue'

export default {
  components:{
    IconNavigator
  }
}
</script>

<template>
    <header class="mt-5 mb-20">
      <p class="text-2xl">Code <span class="text-red-600">and</span> Culture<span class="text-red-600">.</span></p>
    </header>
    <body>
      <p class="text-2xl">Hello! I'm Kevin<span class="text-3xl text-red-600">.</span></p>
      <p class="text-lg mt-3">I'm a Data Engineer, and this is the place where you can find my portfolio, my contact and I hope soon few blog articles<span class="text-xl text-red-600">!</span></p>
      <IconNavigator />
      <p class="text-xl mt-8">Few things about me<span class="text-red-600">...</span></p>
      <p class="text-lg mt-3">
        I'm living in Paris and currently working @ Payfit. Data Engineer for 4 years now, I mainly worked in AWS ecosystem. I'm interested in any technologies permitting me to manage the data lifecycle. I have significant experience with tools like Airflow, Redshift. I'm highly using Python and SQL in my day-to-day work.<br/>
        I'm currently trying to learn stuff around DBT and Terraform. I hope this website will allow me to share cool insights about Data Engineering, tech and other things that interested me<span class="text-red-600">.</span> 
      </p>
    </body>
</template>
