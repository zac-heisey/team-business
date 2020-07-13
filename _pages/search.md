---
layout: page
title: Search
permalink: /search/
description: Search anything in the site from here.
---

<!-- Html Elements for Search -->
<div id="search-container">
<input type="text" id="search-input" placeholder="Search..." autofocus>
</div>
<div id="results-container"></div>

<!-- Script pointing to jekyll-search.js -->
<script src="{{site.baseurl}}/assets/js/jekyll-search.min.js"></script>
<script>
  window.simpleJekyllSearch = new SimpleJekyllSearch({
    searchInput: document.getElementById('search-input'),
    resultsContainer: document.getElementById('results-container'),
    json: '{{ site.baseurl }}/search.json',
    searchResultTemplate: '<li><a href="{url}">{title}</a></li>',
    noResultsText: 'No results found',
    limit: 20,
    fuzzy: false,
    exclude: ['Welcome']
  });
</script>
