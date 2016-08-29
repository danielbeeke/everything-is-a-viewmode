<em class="active">Clean css</em>
<br>
<br>
<h2>CSS modifiers</h2>

<pre><code class="sass">.node.slide {
    height: 30vh;
}

// The modifier
.front {
    .node.slide {
        height: 70vh;
    }
    
    // Another modifier
    @include breakpoint(max-width $tablet) {
        height: 60vh;
    }
}

</code></pre>