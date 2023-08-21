<template>
  <header>
    <div class="logo-section">
      splitter
    </div>
  </header>

  <main>
    <section class="calculator">
      <article class="calculator__input-article">
        <h1 class="calculator__title">Bill</h1>
        <input data-icon="money" type="text">
      </article>

      <article class="calculator__select-tip">
        <h1 class="calculator__title">Select Tip %</h1>
        <div class="calculator__tips">
          <button class="tip-element">5%</button>
          <button class="tip-element">10%</button>
          <button class="tip-element">15%</button>
          <button class="tip-element">25%</button>
          <button class="tip-element">50%</button>
          <button class="tip-element">Custom</button>
        </div>
      </article>

      <h1 class="calculator__title">Number of People</h1>
      <input data-icon="people" type="text">
    </section>

    <section class="results">

      <div class="results__container">
        <div class="results__text-container">
          <p class="results__text">
            Tip Amount
          </p>
          <p class="results__per-person">
            / person
          </p>
        </div>
        <p class="results__amount">4.27</p>
      </div>

      <div class="results__container">
        <div class="results__text-container">
          <p class="results__text">
            Total
          </p>
          <p class="result__per-person">
            / person
          </p>
        </div>
        <p class="result__amount">4.27</p>
      </div>

      <button class="reset-button">Reset</button>

    </section>
  </main>
</template>
