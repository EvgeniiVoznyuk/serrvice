<template>
  <div class="main__form form">
    <h1 class="form__title title">
      Залишити заявку
    </h1>
    <div class="form__block">
      <div class="form__content">
        <p class="form__text">
          Бажаєте залишити заявку на ремонт?
          Введіть свої дані, ми зателефонууємо Вам найближчим часом.
        </p>
        <div class="form__card form-card">
          <div class="form-card__input-group">
            <label for="name" class="form-card__label">Ім'я</label>
            <input
              id="name"
              type="text"
              class="form-card__input"
              autocomplete="off"
            >
          </div>
          <div class="form-card__input-group">
            <label for="phone" class="form-card__label">Телефон</label>
            <input
              id="phone"
              type="text"
              class="form-card__input"
              autocomplete="off"
            >
          </div>
          <button class="form-card__btn btn">Відправити</button>
        </div>
      </div>
      <div class="form__footer"></div>
    </div>
  </div>
</template>
