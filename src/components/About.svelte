<script>
  export let name;
  import devlogo from "../assets/dev-logo.svg";
</script>
  
<section>
  <div class="container__about" id="About">
    <img width={180} height={123} src={devlogo} alt="" />
    <p class="header--small">Hi, I'm {name}</p>
    <p class="header--big">Welcome to my portfolio!</p>
  </div>
</section>
  
<style>
  .container__about {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 10rem;
  }
  .header--small {
    font-size: 1.5rem;
    margin: 2rem 0 0 0;
    font-weight: 600;
  }
  .header--big {
    font-size: 2rem;
    color: #2C91C6;
    font-weight: 700;
  }
</style>