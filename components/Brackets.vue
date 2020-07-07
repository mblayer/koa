<template>
  <div class="brackets">
    <h2 class="subtitle">Brackets</h2>
    <section class="containerBrackets">
      <section>
        <section class="octavos">
          <section class="match">
            <section class="partido">
              <article class="participante">Nicov</article>
              <article class="participante">Rodrigus</article>
            </section>
            <section class="partido">
              <article class="participante">Capoch</article>
              <article class="participante">Pela</article>
            </section>
          </section>
          <section class="match">
            <section class="partido">
              <article class="participante">Dogao</article>
              <article class="participante">Biry - Darknight</article>
            </section>
            <section class="partido">
              <article class="participante">Twigg</article>
              <article class="participante">Gabi - Hoang</article>
            </section>
          </section>
          <section class="match">
            <section class="partido">
              <article class="participante">Sobek</article>
              <article class="participante">Laaan</article>
            </section>
            <section class="partido">
              <article class="participante">Bact</article>
              <article class="participante">Carbo</article>
            </section>
          </section>
          <section class="match">
            <section class="partido">
              <article class="participante">Noisick</article>
              <article class="participante">Uzzi</article>
            </section>
            <section class="partido">
              <article class="participante">Heimdall</article>
              <article class="participante">Tatoh</article>
            </section>
          </section>
        </section>
      </section>
      <section class="cuartos">
        <section class="match">
          <section class="partido">
            <article class="participante">-</article>
            <article class="participante">-</article>
          </section>
          <section class="partido">
            <article class="participante">-</article>
            <article class="participante">-</article>
          </section>
        </section>
        <section class="match">
          <section class="partido">
            <article class="participante">-</article>
            <article class="participante">-</article>
          </section>
          <section class="partido">
            <article class="participante">-</article>
            <article class="participante">-</article>
          </section>
        </section>
      </section>
      <section class="semis">
        <section class="match">
          <section class="partido">
            <article class="participante">-</article>
            <article class="participante">-</article>
          </section>
          <section class="partido">
            <article class="participante">-</article>
            <article class="participante">-</article>
          </section>
        </section>
      </section>
      <section class="final">
        <section class="partido">
          <article class="participante">-</article>
          <article class="participante">-</article>
        </section>
      </section>
    </section>
  </div>
</template>
<style>
.brackets {
  margin: 3rem auto;
}
.containerBrackets {
  display: flex;
  justify-content: space-between;
}
.partido {
  margin: 1rem;
}
.participante:first-child {
  border-top-left-radius: 0.25rem;
  border-top-right-radius: 0.25rem;
}
.participante:last-child {
  border-bottom-right-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem;
}
.participante {
  box-sizing: border-box;
  color: #e5cf3e;
  border-left: 0.25rem solid #858585;
  border-top: 0.01rem solid #858585;
  border-right: 0.01rem solid #858585;
  background: #292828;
  min-width: 8rem;
  height: 3rem;
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.12);
  line-height: 3;
  font-size: 1rem;
  font-family: 'Roboto Slab';
  padding: 0 1rem;
  font-weight: 600;
  box-sizing: content-box;
}
.ganador {
  border-left: 0.25rem solid #60c645;
  color: #60c645;
}
.cuartos .partido {
  margin: 5rem 2rem;
}
.cuartos .partido:not(:first-child) {
  margin: 8rem 2rem;
}
.semis .partido {
  margin: 12rem 2rem;
}
.semis .partido:not(:first-child) {
  margin: 22rem 2rem;
}
.final .partido {
  margin: 26rem 2rem;
}

@media only screen and (max-width: 840px) {
  .containerBrackets {
    display: block;
  }
  .octavos {
    display: flex;
    flex-flow: row wrap;
    justify-content: space-around;
  }
  .cuartos,
  .semis,
  .final {
    display: none;
  }
  .octavos .match,
  .cuartos .match,
  .semis .match,
  .final .match {
    /* width: 100%; */
    border: solid 2px #e5cf3e;
    margin: 1rem;
    border-radius: 0.5rem;
  }
  .octavos .partido,
  .cuartos .partido,
  .semis .partido,
  .final .partido,
  .octavos .partido:not(:first-child),
  .cuartos .partido:not(:first-child),
  .semis .partido:not(:first-child),
  .final .partido:not(:first-child) {
    margin: 1rem;
  }
}
</style>
