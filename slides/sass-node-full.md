<em class="active">Clean css</em>
<br>
<br>
<h2>CSS inheritance</h2>

<pre><code class="sass">
.node.full {
  > .header-wrapper {
    width: 100%;
    height: 60vh;
    overflow: hidden;
    margin-bottom: -8vh;

    > .image-style-header {
      width: 100%;
    }
  }
}
</code></pre>