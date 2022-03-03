<template>
  <main>

    <section class="ivi-grid-section ivi-grid-section__is-intro ivi-grid-section__no-max-width">
      <div class="ivi-grid-section__column">
        <img width="66.66666%" alt="logo ivi complete" src="@/assets/logo_complete.svg">
      </div>
      <img id="bg-intro" src="@/assets/intro.jpg" alt="background">
    </section>


    <section class="ivi-grid-section ivi-grid-section__is-intro" id="intro">
      <div class="ivi-grid-section__column">
        <h1>interface for the visually&nbsp;impaired</h1>
        <h2>putting controls, at your fingertips</h2>
      </div>
      <img id="bg-intro_2" src="@/assets/intro_2.jpg" alt="background">
    </section>

    <section class="ivi-grid-section">
      <div class="ivi-grid-section__column">
        <h3 style="text-align: center">Ivi is an external interface for visually impared. Why? Interface whith out physical profile are dificult or event imposible to use for the visualy impared. It is in the form of an shell for OTS smartphones.</h3>
      </div>
    </section>

    <section class="ivi-grid-section">
      <div class="ivi-grid-section__column">
        <section class="ivi-grid-section">
          <div class="ivi-grid-section__column ivi-grid-section__column__1-3">
            <h3>Problem</h3>
          </div>

          <div class="ivi-grid-section__column">
            <p>How do you operate a smartphone when you can’t see its&nbsp;controls?</p>
          </div>
        </section>

        <img id="bg-problem" src="@/assets/probleme.jpg" alt="background">
      </div>
    </section>


    <section class="ivi-grid-section">

      <div class="ivi-grid-section__column">
        <section class="ivi-grid-section">
          <div class="ivi-grid-section__column ivi-grid-section__column__1-3">
            <h3>Solution</h3>
          </div>
          <div class="ivi-grid-section__column">
            <p>A tactile interface that:</p>
            <ul>
              <li>puts controls where your fingers touch a device to hold it and;</li>
              <li>generates an audible or haptic tag telling you what control a finger commands.</li>
            </ul>
          </div>
        </section>

        <img id="bg-solution" src="@/assets/solution.jpg" alt="background">
      </div>
    </section>


    <section class="ivi-grid-section">

      <div class="ivi-grid-section__column" >

        <h2 style="text-align: center">Product</h2>

        <section class="ivi-grid-section">
          <div class="ivi-grid-section__column ivi-grid-section__column__1-3"></div>
          <div class="ivi-grid-section__column">
            <p>A casing for OTS smartphones:</p>
            <ul>
              <li>with edges configured as touch pads;</li>
              <li>a processor to dynamically map controls to where your fingers touch the edges;</li>
              <li>and to generate audible or haptic tags telling you what pressing a finger does.</li>
            </ul>
          </div>
        </section>

        <img id="bg-product" src="@/assets/product.jpg" alt="background">
      </div>


    </section>

    <section id="resources" >

    </section>

  </main>
</template>

<script setup lang="ts">

</script>

<style>
#bg-intro {
  display: block;
  position: absolute;
  z-index: -10;
  bottom: 0;
  left: 0;
  width: 100%;
  object-position: center;
  height: 100%;
  object-fit: cover;
}

#bg-intro_2 {
  display: block;
  position: absolute;
  z-index: -10;
  bottom: 0;
  left: 0;
  width: 100%;
  object-position: bottom right;
  height: 100%;
  object-fit: cover;
}

#bg-problem {
  display: block;
  position: relative;
  z-index: -10;
  margin-top: -50px;
  width: 100%;
  height: auto;
}

#bg-solution {
  display: block;
  position: relative;
  z-index: -10;
  margin-top: -50px;
  width: 100%;
  height: auto;
}

#bg-product {
  display: block;
  position: relative;
  z-index: -10;
  width: 100%;
  height: auto;
}

</style>