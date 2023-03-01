<script setup>
defineProps({
  title: {
    type: String,
    required: true
  },
  tech: {
    type: String,
    required: true
  },
  link: {
    type: String,
    required: true
  },
  github: {
    type: String,
    required: true
  },
  about: {
    type: String,
    required: true
  },
  image: {
    type: Image,
    required: true
  }
})
</script>

<template>
    <div class="card" style="width: 18rem;">
    <img class="card-img-top" src={{image}} alt={{title}}>
    <div class="card-body">
        <h5 class="card-title">{{ title }}</h5>
        <h6>{{ tech }}</h6>
        <a href={{link}} class="btn btn-primary">Deployed App</a>
        <a href={{github}} class="btn btn-primary">Github</a>
        <p class="card-text">{{ about }}</p>
    </div>
    </div>
</template>

<style>
.card {
    background-color: var(--color-background-mute);
}
</style>