<template>
  <main>
    <article class="card">
      <div class="card__image-container">
        <img
          src="../images/image-product-mobile.jpg"
          alt="alt"
          width="686"
          height="480"
          class="card__image"
          srcset="
            ../images/image-product-300.jpg 300w,
            ../images/image-product-450.jpg 450w,
            ../images/image-product-600.jpg 600w
          "
          sizes="(max-width: 45rem) 600w, (max-width: 60rem) 450w, 300w"
        />
      </div>
      <section class="card__content">
        <header class="card__header">
          <div class="card__tag-container">
            <span class="card__tag">perfume</span>
          </div>
          <h1 class="card__title">Gabrielle Essence Eau De Parfum</h1>
        </header>
        <p class="card__description">
          A floral, solar and voluptuous interpretation composed by Olivier
          Polge, Perfumer-Creator for the House of CHANEL.
        </p>
        <div class="card__price">
          <div class="card__promotional-price">$149.99</div>
          <div class="card__base-price"><s>$169.99</s></div>
        </div>
        <div class="card__actions">
          <div class="card__button">
            <img
              src="../images/icon-cart.svg"
              alt="cart"
              height="14.39"
              width="16"
            />
            <span>Add to Cart</span>
          </div>
        </div>
      </section>
    </article>
  </main>
</template>

<script>
import "./assets/styles/main.scss";
export default {
  name: "App",
  components: {},
};
</script>
