<script setup>
import MyWorkSiteCard from './MyWorkSiteCard.vue'
</script>
<template>
    <div class="row">
        <div class="col-8 mx-auto my-3">
            <h2>My Work</h2>
            <p class="row">Explore more at <a href='https://github.com/Kelbach'> My Github Repo</a></p>
            <div class="col-12">
                <MyWorkSiteCard 
                    title="site.title"
                    tech="site.tech"
                    deployed="site.deployed"
                    github="site.github"
                    image="site.image"
                    about="site.about"
                />
            </div>
        </div>
    </div>
</template>