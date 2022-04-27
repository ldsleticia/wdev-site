<template>
  <main>
    <div class="text-top">
      Vídeos novos toda <strong>quinta</strong> às <strong>20h</strong>
    </div>
    <a href="google.com.br" target="blank">
      <img
        src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg"
        alt="inscreva-se"
        id="subscribe"
      />
    </a>
    <div class="text-botton">google.com.br</div>
  </main>
</template>

<style scoped>
main {
  background-color: var(--color-background-home);
  justify-content: center;
  align-items: center;
}

.text-top {
  color: var(--color-text-light);
  font-size: 22px;
  margin-bottom: 20px;
}

#subscribe {
  width: 340px;
}

.text-botton {
  color: var(--color-text-light);
  font-size: 18px;
  margin-top: 20px;
}

@media (min-width: 700px) {
  #subscribe {
    width: 370px;
  }
}
</style>
