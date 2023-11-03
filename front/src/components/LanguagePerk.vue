<template>
  <section class="section section-language-perk">
    <div class="language-perk-title">語言能力</div>
    <hr />
    <div class="language-perk-content">
      <a class="language-perk-content-item" href="">中文：流利</a>
      <a class="language-perk-content-item" href="">英語：中等</a>
      <a class="language-perk-content-item" href="">台語：中等</a>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.section-language-perk {
  max-width: 150rem;
  margin: 2rem auto 0 auto;
}

.language-perk-title {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.language-perk-content {
  margin: 2rem 0;
  display: flex;
  gap: 1rem;
  font-size: 1.4rem;
}

.language-perk-content-item {
  text-decoration: none;
  padding: 0.4rem 0.4rem;
  border: 1px solid #adb5bd;
  border-radius: 5px;
}
</style>
