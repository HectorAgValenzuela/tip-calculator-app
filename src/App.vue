<template>
  <header>
    <div class="logo-section">
      <img src="/src/assets/images/logo.svg" alt="Logo of the application with the word SPLITTER in uppercase">
    </div>
  </header>

  <main>
    <section class="calculator">
      <article>
        <h1 class="calculator__title">Bill</h1>
        <input class="input" data-icon="money" type="number">
      </article>

      <article>
        <h1 class="calculator__title">Select Tip %</h1>
        <div class="calculator__tips">
          <button class="tip-element">5%</button>
          <button class="tip-element">10%</button>
          <button class="tip-element">15%</button>
          <button class="tip-element">25%</button>
          <button class="tip-element">50%</button>
          <input class="input input-tip" placeholder="Custom">
        </div>
      </article>

      <article class="calculator__input-article">
        <h1 class="calculator__title">Number of People</h1>
        <input class="input" data-icon="people" type="number">
      </article>
    </section>

    <section class="results">

      <article class="results__amount-article">
        <div class="results__container">
          <div class="results__text-container">
            <p class="results__text">
              Tip Amount
            </p>
            <p class="results__per-person">
              / person
            </p>
          </div>
          <p class="results__amount">$4.27</p>
        </div>

        <div class="results__container">
          <div class="results__text-container">
            <p class="results__text">
              Total
            </p>
            <p class="results__per-person">
              / person
            </p>
          </div>
          <p class="results__amount">$32.79</p>
        </div>
        </article>

      <button class="reset-button">Reset</button>

    </section>
  </main>
</template>
