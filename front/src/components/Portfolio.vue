<template>
  <section class="section section-portfolio">
    <div class="section-portfolio-title">作品集</div>
    <hr />
    <div class="section-portfolio-content">
      <a
        class="section-portfolio-content-item"
        href="https://github.com/HawkingHuang/Raspberry-Pi-Sensor-Demo"
        >Raspberry-Pi-Sensor-Demo</a
      >
      <a
        class="section-portfolio-content-item"
        href="https://github.com/HawkingHuang/All-Pass"
        >All-Pass</a
      >
      <a
        class="section-portfolio-content-item"
        href="https://github.com/HawkingHuang/Word-Correcting"
        >Word-Correcting</a
      >
      <a
        class="section-portfolio-content-item"
        href="https://github.com/HawkingHuang/RWD-Omnifood"
        >RWD-Omnifood</a
      >
      <a
        class="section-portfolio-content-item"
        href="https://github.com/HawkingHuang/Pig-Game"
        >Pig-Game</a
      >
      <a
        class="section-portfolio-content-item"
        href="https://github.com/HawkingHuang/Guess-My-Number-Game"
        >Guess-My-Number-Game</a
      >
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.section-portfolio {
  max-width: 150rem;
  margin: 2rem auto 10rem auto;
}

.section-portfolio-title {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.section-portfolio-content {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  margin: 2rem 0;
  gap: 2rem;
}

.section-portfolio-content-item {
  border: 1px solid gray;
  border-radius: 5px;
  padding: 1rem 1rem;
  text-decoration: none;
  font-size: 2rem;
  text-align: center;
}
</style>
