<em class="active">Clean css</em>
<br>
<br>
<h2>Singularity syntax</h2>

<pre><code class="sass">
.main-menu {
  @include grid-span(
    8, // Width 
    5  // Starting column
  );
}

</code></pre>

<p>or</p>

<pre><code class="sass">
.main-menu {
  @include isolation-span(
    8,     // Width 
    5,     // Starting column
    'both' // Clearing
  );
}

</code></pre>