<template>
  <section class="section section-skills">
    <div class="skills-title">專業技能</div>
    <hr />
    <div class="skills-subsection">
      <div class="skills-subtitle-1">
        <ion-icon name="desktop-outline"></ion-icon>
        <p>程式設計</p>
      </div>
      <div class="skills-content-1">
        <a
          class="skills-content-1-item"
          href="https://developer.mozilla.org/en-US/docs/Web/HTML"
          >HTML</a
        >
        <a
          class="skills-content-1-item"
          href="https://developer.mozilla.org/en-US/docs/Web/CSS"
          >CSS</a
        >
        <a
          class="skills-content-1-item"
          href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"
          >JavaScript</a
        >
        <a
          class="skills-content-1-item"
          href="https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Vue_getting_started"
          >Vue3</a
        >
      </div>
    </div>
    <div class="skills-subsection">
      <div class="skills-subtitle-2">
        <ion-icon name="language-outline"></ion-icon>
        <p>英中筆譯</p>
      </div>
      <div class="skills-content-2">
        <a class="skills-content-2-item" href="">Translation Task Manager</a>
        <a class="skills-content-2-item" href="">Memsource</a>
        <a class="skills-content-2-item" href="">Trados</a>
        <a class="skills-content-2-item" href="">KantanStream</a>
        <a class="skills-content-2-item" href="">TOEIC Gold</a>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.section-skills {
  max-width: 150rem;
  margin: 2rem auto 0 auto;
}

.skills-title {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.skills-subsection {
  margin: 2rem 0;
}

.skills-subtitle-1 {
  font-size: 2rem;
  margin: 1rem 0;
  display: flex;
  gap: 0.5rem;
  align-items: center;
}

.skills-content-1 {
  display: flex;
  gap: 1rem;
  font-size: 1.4rem;
}

.skills-content-1-item,
.skills-content-2-item {
  text-decoration: none;
  padding: 0.4rem 0.4rem;
  border: 1px solid #adb5bd;
  border-radius: 5px;
}

.skills-subtitle-2 {
  font-size: 2rem;
  margin: 1rem 0;
  display: flex;
  gap: 0.5rem;
  align-items: center;
}

.skills-content-2 {
  display: flex;
  gap: 1rem;
  font-size: 1.4rem;
}
</style>
