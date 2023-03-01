<script>

</script>

<template>
    <h1>
        Kevin Kelbach
    </h1>
    <nav>
        <ul>
            <li>
            <a >About Me</a>
            </li>
            <li>
            <a >My Work</a>
            </li>
            <li>
            <a >Contact Me</a>
            </li>
            <li>
            <a >Extra</a>
            </li>
        </ul>
    </nav>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

nav {
    font-size: 1.3rem;
}

nav ul li {
    display: inline;
    padding: 0.6rem;
    position: relative;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>