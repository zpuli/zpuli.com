<script setup>
</script>

<template>
  <main class="wrapperx">
      <h1><b>Z</b>enware <b>P</b>arallel <b>U</b>tility <b>L</b>inked <b>I</b>oT</h1>
      <small>
        Think Smart; Place Internet of Things Everywhere.
      </small>
  </main>
</template>

<style>
.wrapperx{
  display: flex;
  flex-direction: column;
  justify-content: center;
}

b {
  font-size: 1.3em;
  text-align: center;
  line-height: 1;
  color: #c6e2ff;
  animation: neon .08s ease-in-out infinite alternate;
}

@keyframes neon {
  from {
    text-shadow:
    0 0 6px rgba(202,228,225,0.92),
    0 0 30px rgba(202,228,225,0.34),
    0 0 12px rgba(30,132,242,0.52),
    0 0 21px rgba(30,132,242,0.92),
    0 0 34px rgba(30,132,242,0.78),
    0 0 54px rgba(30,132,242,0.92);
  }
  to {
    text-shadow:
    0 0 6px rgba(202,228,225,0.98),
    0 0 30px rgba(202,228,225,0.42),
    0 0 12px rgba(30,132,242,0.58),
    0 0 22px rgba(30,132,242,0.84),
    0 0 38px rgba(30,132,242,0.88),
    0 0 60px rgba(30,132,242,1);
  }
}
</style>
