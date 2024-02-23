<template>
  <div class="home-container">
    <div class="home-container1">
      <img
        alt="Logo"
        src="https://storage.googleapis.com/business-downloads/logobf.png"
        loading="lazy"
        class="home-image"
      />
    </div>
    <div class="home-container2">
      <div class="home-container3">
        <h1 class="home-text">
          <span>O melhor jeito de pedir delivery é com Batatais Food</span>
          <br />
        </h1>
        <a
          href="https://api.whatsapp.com/send?phone=5516994105060&amp;text=Quero%20fazer%20parte%20do%20Batatais%20Food"
          target="_blank"
          rel="noreferrer noopener"
          class="home-link"
        >
          Faça parte
        </a>
        <a
          href="https://onelink.to/majw5z"
          target="_blank"
          rel="noreferrer noopener"
          class="home-link1"
        >
          Baixe o app
        </a>
      </div>
      <div class="home-container4">
        <img
          alt="image"
          src="https://storage.googleapis.com/business-downloads/bfmobile.png"
          class="home-image1"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {},
  metaInfo: {
    title: 'Bland Interesting Crocodile',
    meta: [
      {
        property: 'og:title',
        content: 'Bland Interesting Crocodile',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-image: radial-gradient(circle at center top, rgb(189, 195, 199) 0.00%,rgb(204, 0, 0) 46.00%,rgb(204, 0, 0) 100.00%);
}
.home-container1 {
  width: 100%;
  height: auto;
  display: flex;
  align-items: flex-start;
}
.home-image {
  width: 291px;
  height: 109px;
  object-fit: cover;
}
.home-container2 {
  width: 100%;
  height: 888px;
  display: flex;
  padding: 16px;
  position: relative;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-container3 {
  width: 100%;
  height: 469px;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-text {
  color: #ffffff;
  text-align: center;
  margin-bottom: 16px;
}
.home-link {
  width: 70%;
  height: auto;
  padding: 8px;
  text-align: center;
  border-radius: var(--dl-radius-radius-radius8);
  margin-bottom: 8px;
  background-color: rgb(255, 255, 255);
}
.home-link1 {
  color: rgb(255, 255, 255);
  width: 70%;
  height: auto;
  padding: 8px;
  text-align: center;
  border-color: #ffffff;
  border-width: 1px;
  border-radius: var(--dl-radius-radius-radius8);
}
.home-container4 {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-image1 {
  width: 100%;
  height: 461px;
  object-fit: cover;
}
@media(max-width: 479px) {
  .home-container {
    background-image: radial-gradient(circle at right bottom, rgb(189, 195, 199) 0.00%,rgb(204, 0, 0) 46.00%,rgb(204, 0, 0) 100.00%);
  }
  .home-container2 {
    flex-direction: column;
  }
}
</style>
