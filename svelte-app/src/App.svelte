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

<section id="top-bar">
    <h1 id="bill-sprinters">
        <img src="bs-logo2.svg" alt=""/>            
    </h1>
</section>
<section id="image-bar">

</section>
