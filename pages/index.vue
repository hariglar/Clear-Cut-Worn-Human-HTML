<template>
  <div class="home-container">
    <div class="home-hero">
      <div class="home-container1">
        <h1 class="home-text">محتوى رائع</h1>
        <span class="home-text1">
          <br />
          <span>مرحبا بك في هذا العالم الجميل</span>
        </span>
        <button class="home-button button">Get Started</button>
      </div>
      <form name="contact" method="POST" class="home-form">
        <input
          type="number"
          id="phonenumber"
          name="phone"
          required
          placeholder="ادخل اسمك"
          data-netlify="true"
          class="home-textinput input"
        />
        <button type="submit" class="home-button1 button">Button</button>
      </form>
      <img
        alt="image"
        src="/playground_assets/sdsfd56965-700h.webp"
        class="home-image"
      />
      <img
        alt="image"
        src="/playground_assets/batterycamerfdgf56-1200w.webp"
        class="home-image1"
      />
      <img
        alt="image"
        src="/playground_assets/night-vision-1200w.webp"
        class="home-image2"
      />
      <div class="home-testimonial">
        <div class="home-container2">
          <h1 class="home-text4">
            <span>What they’re saying</span>
            <br />
            <span></span>
          </h1>
          <span class="home-text7">
            <span>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non
              volutpat turpis. Mauris luctus rutrum mi ut rhoncus. Integer in
              dignissim tortor.
            </span>
          </span>
          <div class="home-container3"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  head: {
    title: 'okdok',
    meta: [
      {
        property: 'og:title',
        content: 'okdok',
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
}
.home-hero {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  min-height: 80vh;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-container1 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-text {
  font-size: 3rem;
  font-family: Tahoma;
}
.home-text1 {
  margin-top: var(--dl-space-space-twounits);
  text-align: center;
  font-family: Tahoma;
  padding-left: var(--dl-space-space-threeunits);
  margin-bottom: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-threeunits);
}
.home-button {
  transition: 0.3s;
  font-family: Tahoma;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
}
.home-button:hover {
  transform: scale(1.02);
}
.home-form {
  width: 416px;
  height: 365px;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-textinput {
  font-family: Tahoma;
}
.home-button1 {
  left: 165px;
  bottom: 97px;
  position: absolute;
  align-self: center;
  text-align: center;
  font-family: Tahoma;
  padding-right: var(--dl-space-space-unit);
}
.home-image {
  width: auto;
  height: 619px;
  object-fit: cover;
}
.home-image1 {
  width: auto;
  height: auto;
  margin-top: var(--dl-space-space-twounits);
}
.home-image2 {
  width: auto;
  height: auto;
}
.home-testimonial {
  width: 100%;
  display: flex;
  justify-content: center;
  background-color: 232323;
}
.home-container2 {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-text4 {
  color: var(--dl-color-gray-white);
  font-family: Tahoma;
}
.home-text7 {
  color: var(--dl-color-gray-white);
  font-size: 0.75rem;
  max-width: 600px;
  margin-top: var(--dl-space-space-unit);
  text-align: center;
  font-family: Tahoma;
  margin-bottom: var(--dl-space-space-twounits);
}
.home-container3 {
  width: 100%;
  display: grid;
  grid-gap: var(--dl-space-space-twounits);
  grid-template-columns: 1fr 1fr 1fr;
}
@media(max-width: 991px) {
  .home-hero {
    flex-direction: column;
  }
  .home-container1 {
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-text {
    text-align: center;
  }
  .home-text1 {
    text-align: center;
  }
  .home-image1 {
    width: 80%;
  }
  .home-image2 {
    width: 80%;
  }
  .home-text4 {
    text-align: center;
  }
  .home-text7 {
    text-align: center;
  }
  .home-container3 {
    grid-template-columns: 1fr;
  }
}
@media(max-width: 767px) {
  .home-hero {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-text1 {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-container2 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
}
@media(max-width: 479px) {
  .home-hero {
    position: relative;
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-container1 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-button {
    margin-top: var(--dl-space-space-unit);
    margin-left: 0px;
  }
  .home-image {
    width: 479px;
    height: 484px;
  }
  .home-image1 {
    width: 479px;
    margin: 0px;
  }
  .home-image2 {
    width: 479px;
    margin: 0px;
  }
  .home-container2 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
}
</style>
