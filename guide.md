---
title: Thanks
permalink: "/guide/"
layout: page
width: large
---

<div class="container is-max-desktop is-flex is-align-items-center is-flex-wrap-wrap">
    <!-- Left side: Title, Heading, and Search -->
    <div class="column is-half mt-5">
        <h1 class="title is-1 mb-3">Welcome To Bangalore Job Seekers Guide</h1>
        <p class="subtitle is-5">Follow Swarnil's path to succeed in Bangalore with job search, relocation guidance, and valuable articles and videos tailored for Bangalore job seekers.</p>
        <div class="hero-search">
            <!-- Html Elements for Search -->
            <div class="control has-icons-left">
                <form class="control is-expanded" name="search-hero" onsubmit="return false;">
                    <input id="search-hero" class="input is-large box" type="search" placeholder="Search for answers" autocomplete="off">
                    <span class="icon is-small is-left"><i class="fas fa-search"></i></span>
                </form>
                <ul id="search-hero-results" class="dropdown-content"></ul>
            </div>
            <script>
                SimpleJekyllSearch({
                    searchInput: document.getElementById('search-hero'),
                    resultsContainer: document.getElementById('search-hero-results'),
                    noResultsText: '<li class="dropdown-item">No results found</li>',
                    searchResultTemplate: '<li class="dropdown-item"><a href="{url}">{title}</a><span>{subtitle}</span></li>',
                    json: "/search.json"
                });
                searchResults("search-hero");
            </script>
        </div>
    </div>
    <!-- Right side: Image or SVG -->
    <div class="column is-half has-text-centered mt-5">
        <p class="hero-image has-text-centered"><img src="https://job.imswarnil.com//uploads/knowledge.svg" alt="Hero"></p>
    </div>
</div>
