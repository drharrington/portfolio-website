<script>
  const exps = [
    {
      title: "Association for Computing Machinery",
      duration: "Jul 2022 - Present",
    },
    {
      title: "LBX Immersive LLC Intern",
      duration: "Feb 2021 - May 2021",
    },
  ];
</script>
  
<section class="container__exps" id="Experiences">
  <p class="header--big">Experiences</p>
  {#each exps as { title, duration }}
    <div class="container__exp">
      <p class="header__title">{title}</p>
      <p class="header__duration">{duration}</p>
    </div>
  {/each}
</section>
  
<style>
  .container__exps {
    margin-top: 10rem;
    display: flex;
    justify-content: center;
    flex-direction: column;
  }
  .header--big {
    font-size: 2.5rem;
    font-weight: 780;
  }
  .container__exp {
    background-color: #0F3F8C;
    border-radius: 2rem;
    margin: 1rem;
  }
  .header__title {
    font-size: 1.5rem;
    font-weight: 600;
  }
</style>