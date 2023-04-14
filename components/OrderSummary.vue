<template>
  <div class="OrderSummary">
    <div class="OrderSummary-heroContainer">
      <img class="OrderSummary-hero" src="@/assets/images/illustration-hero.svg" alt="Woman happy listening to music">
    </div>
    
    <div class="OrderSummary-content">
      <div class="OrderSummary-title">
        <h1>Order Summary</h1>
      </div>
      <div class="OrderSummary-description">
        <p>You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!</p>
      </div>
      <div class="OrderSummary-planContainer">
        <div class="OrderSummary-planIcon">
          <img src="@/assets/images/icon-music.svg" alt="Music icon">
        </div>
        <div>
          <p class="OrderSummary-plan">Annual Plan</p>
          <p class="OrderSummary-price">$59.99/year</p>
        </div>
        <div class="OrderSummary-change">
          <a href="#">Change</a>
        </div>
      </div>
      <div class="OrderSummary-buttonContainer">
        <button class="OrderSummary-button">Proceed to Payment</button>
      </div>
      <div class="OrderSummary-cancel">
        <a href="#">Cancel Order</a>
      </div>
    </div>
  </div>
</template>