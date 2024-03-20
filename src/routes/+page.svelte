<svelte:head>
  <title>Ксения Кузьминова</title>
</svelte:head>
<div class="conteiner">
  <div class="info">
    <div class="animate-background">
      <div class="info-conteiner">
        <div class="info-text">
          <h1>
            <p class="animate-text-1">Lorem ipsum dolor sit amet con</p>
            <p class="text-2">Lorem fjdofdoffofdfgo</p>
          </h1>
        </div>
        <h2 class="subtitle">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rem dolorem
          necessitatibus veniam perspiciatis tenetur amet fuga praesentium
          tempora maxime, enim ab magnam dicta commodi voluptas fugiat suscipit
          laboriosam nam quae.
        </h2>
        <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
        <div
          style="color:black"
          class="scroll-button-animate-scroll"
          tabindex="0"
        >
          <a href="/about">Click Here</a>
          <div class="arrow">---</div>
        </div>
      </div>
    </div>
  </div>
</div>
<div class="background-div"></div>

<style>
  .info {
    text-align: center;
    position: relative;
  }
  .info-conteiner {
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-self: center;
    text-align: left;
    align-items: start;
  }
  .conteiner {
    max-width: 1400px;
    margin: 190px 0 0 2.5rem;
  }
  .info h1 {
    font-size: 4rem;
    margin: 0;
  }
  .info h1 p {
    position: relative;
    font: inherit;
    margin: 0;
    text-align: left;
    line-height: 130%;
    width: fit-content;
    font-weight: 800;
    letter-spacing: -0.03em;
  }
  .info h2 {
    max-width: 65ch;
    font-weight: 200;
    margin-top: 0.5rem;
  }
  .background-div {
    background-color: #ecebe8;
    width: 100%;
    height: 56vh;
    margin: -205px auto;
  }
  .info .info-text {
    position: relative;
  }
  .scroll-button-animate-scroll {
    display: flex;
    border: none;
    outline: none;
    cursor: pointer;
  }
  .scroll-button-animate-scroll .arrow {
    margin-left: 0.5rem;
  }
</style>
