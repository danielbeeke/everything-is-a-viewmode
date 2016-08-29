<em class="active">Clean markup</em>
<br><br>
<h2>example_jacket.theme (Drupal 8)</h2>
```

/**
 * Implementation of theme_image().
 */
function example_jacket_preprocess_image(&$vars) {
  if (isset($vars['style_name'])) {
    $vars['attributes']['class'][] = 'style-' . $vars['style_name'];
  }

  unset($vars['attributes']['width']);
  unset($vars['attributes']['height']);
}


```