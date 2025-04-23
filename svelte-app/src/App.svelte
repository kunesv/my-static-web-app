<script>
  import './styles.scss';
  import { Router, Link, Route } from 'svelte-routing';
  import About from './About.svelte';
  import Products from './products/Products.svelte';

  import { HeaderBar, NavBar, PageNotFound, Redirect } from './components';

  export let url = '';
</script>

<!-- <HeaderBar />
<div class="section columns">
  <Router {url}>
    <NavBar />
    <main class="column">
      <div>
        <Route path="/">
          <Redirect path="/products" />
        </Route>
        <Route path="/products" component={Products} />
        <Route path="/about" component={About} />
        <Route path="**" component={PageNotFound} />
      </div>
    </main>
  </Router>
</div> -->

<section id="image-bar"></section>


<section id="top-bar">
  <h1 id="bill-sprinters">
      <img src="bs-logo2.svg" alt=""/>            
  </h1>
</section>


<section id="body-text">
  <p>SPRINTERS is a family business that specializes in delivering fast and reliable solutions for your needs. Whether you need a website, a logo, a marketing campaign, or anything else, we are here to help you achieve your goals.</p>
  <p>We are a team of passionate and creative professionals who love what we do. We have the skills, the experience, and the vision to turn your ideas into reality. We work with you every step of the way, from planning to execution, to ensure your satisfaction and success.</p>
  <p>At SPRINTERS, we believe that nothing is impossible. We are always ready to take on new challenges and exceed your expectations. We are not just a service provider, we are your partner in success. Contact us today and let us show you what we can do for you.</p>
</section>

