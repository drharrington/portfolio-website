<script>
  const projects = [
    {
      title: "Portfolio Website",
      description: "Developed this website",
      url: "https://github.com/drharrington/portfolio-website",
    },
    {
      title: "Placeholder",
      description: "Did this thing",
      url: "https://github.com/drharrington/portfolio-website",
    },
  ];
</script>
  
<section class="container__projects" id="Projects">
  <p class="header--big">Projects</p>
  {#each projects as { title, description, url }}
    <div class="container__project">
      <a href={url} target="_blank">
        <p class="header__title">{title}</p>
      </a>
      <p>{description}</p>
    </div>
  {/each}
</section>
  
<style>
  .container__projects {
    margin-top: 10rem;
    display: flex;
    justify-content: center;
    flex-direction: column;
  }
  .header--big {
    font-size: 2.5rem;
    font-weight: 780;
  }
  .container__project {
    margin: 1rem;
  }
  .header__title {
    color: white;
    font-size: 1.5rem;
    font-weight: 600;
    transition: 400ms all;
  }
  .header__title:hover {
    color: #2c91c6;
  }
</style>