<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vue Market Otomasyonu</title>
  <script src="https://cdn.jsdelivr.net/npm/vue@3/dist/vue.global.js"></script>
  <style>
    body { font-family: Arial, sans-serif; margin: 20px; }
    .product { margin-bottom: 10px; }
    .cart { margin-top: 20px; }
    button { margin-left: 10px; }
  </style>
</head>
<body>
  <div id="app">
    <h1>Market Otomasyonu</h1>

    <!-- Ürün Listesi -->
    <div>
      <h2>Ürünler</h2>
      <div v-for="product in products" :key="product.id" class="product">
        {{ product.name }} - {{ product.price }} ₺
        <button @click="addToCart(product)">Sepete Ekle</button>
      </div>
    </div>

    <!-- Sepet -->
    <div class="cart">
      <h2>Sepet</h2>
      <ul>
        <li v-for="(item, index) in cart" :key="index">
          {{ item.name }} - {{ item.price }} ₺
          <button @click="removeFromCart(index)">Kaldır</button>
        </li>
      </ul>
      <p><strong>Toplam Tutar:</strong> {{ totalPrice }} ₺</p>
    </div>
  </div>

  <script>
    const { createApp } = Vue;

    createApp({
      data() {
        return {
          products: [
            { id: 1, name: 'Elma', price: 10 },
            { id: 2, name: 'Armut', price: 12 },
            { id: 3, name: 'Muz', price: 15 },
            { id: 4, name: 'Çilek', price: 20 }
          ],
          cart: []
        };
      },
      computed: {
        totalPrice() {
          return this.cart.reduce((total, item) => total + item.price, 0);
        }
      },
      methods: {
        addToCart(product) {
          this.cart.push(product);
        },
        removeFromCart(index) {
          this.cart.splice(index, 1);
        }
      }
    }).mount('#app');
  </script>
</body>
</html>
