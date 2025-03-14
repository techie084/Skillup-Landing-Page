<main>
  <div class="text-container">
    <h1 class="heading-text">
      Empower
      <span class="bg-colored-text">
        Your
        <img
          class="small-img"
          src="./Assets/image-1.png"
          alt="small-des-img"
        /><br />
      </span>
      Future with <span class="skew-bg">Tech.</span>
    </h1>
    <p class="sub-text">
      Learn at Your Own Pace with Hands-on <br />
      Projects and Real-World Lessons.
    </p>
    <div class="btn-container">
      <button class="btn-1">Get Started</button>
      <button class="btn-2">Browse Course</button>
    </div>
  </div>
  <div class="img-container">
    <div class="blurred-bg-1">
      <span class="rocket-emoji">🚀</span> Get 20% off on your first course
    </div>
    <img class="student-img" src="./Assets/img.png" alt="student-img" />
    <div class="rectangle-1"></div>
    <div class="rectangle-2"></div>
    <div class="blurred-bg-2">
      <div class="image-con-stack"></div>
      Over 1000+ Student plus enrolled around the country
    </div>
  </div>
</main>

<style>
  main {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto;
    text-align: left;
    gap: 5rem;
  }

  .heading-text {
    font-weight: 700;
    font-size: 50px;
  }

  .bg-colored-text {
    font-weight: 700;
    font-size: 50px;
  }

  .small-img {
    width: 142px;
    height: auto;
    margin: -4.5% -2.8%;
    position: absolute;
  }

  .skew-bg {
    width: 147px;
    position: absolute;
    margin: -4% 18.5%;
    display: flex;
    border-radius: 5px;
    background: var(--primary);
    padding: 0 6px;
    color: var(--white);
    rotate: 3deg;
  }

  .sub-text {
    width: 391px;
    margin-top: 20px;
    font-weight: 400;
    font-size: 20px;
    text-align: left;
  }

  .btn-container {
    margin-top: 1rem;
    display: flex;
    gap: 1.5rem;
  }

  .btn-1 {
    font-size: 20px;
    font-weight: 600;
    border-radius: 32px;
    cursor: pointer;
    text-align: center;
    border: none;
    width: 164px;
    height: 54px;
    padding: 12px 24px;
    color: var(--white);
    background: var(--primary);
  }

  .btn-2 {
    font-size: 20px;
    font-weight: 600;
    border-radius: 32px;
    cursor: pointer;
    text-align: center;
    border: none;
    padding: 6px 12px;
    color: var(--black);
    background: none;
    border: 1px solid var(--primary);
  }

  .blurred-bg-1 {
    position: absolute;
    padding: 0.5rem;
    font-size: 12px;
    margin: 3.5% 31%;
    border-radius: 5px;
    width: 195px;
    border-radius: 10px;
    display: flex;
    align-items: center;
    gap: 10px;
    background: var(--blurBg);
    backdrop-filter: blur(5px);
  }

  .blurred-bg-2 {
    position: absolute;
    padding: 12px;
    font-size: 12px;
    text-align: center;
    margin: -4% 5%;
    width: 135px;
    display: flex;
    align-items: center;
    background: var(--blurBg);
    backdrop-filter: blur(5px);
    border-radius: 10px;
  }

  .rocket-emoji {
    width: 30px;
    font-size: 28px;
  }

  .rectangle-1 {
    position: absolute;
    width: 450px;
    height: 30em;
    margin: -33.3% 11%;
    background: var(--secondary);
    border: 1px solid var(--secondary);
    rotate: -3deg;
    border-radius: 10px;
    z-index: -1;
  }

  .rectangle-2 {
    position: absolute;
    width: 28em;
    height: 29em;
    margin: -34.5% 9%;
    border: 1px solid var(--black);
    rotate: -3deg;
    border-radius: 10px;
    z-index: -2;
  }

  .student-img {
    width: fit-content;
    height: 603px;
    rotate: -1deg;
  }
</style>
