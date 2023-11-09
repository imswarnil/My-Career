---
layout: page
title: Thanks
permalink: /guide/
width: small
---

<div class="uk-container uk-container-medium uk-flex uk-flex-middle uk-flex-wrap">
                <!-- Left side: Title, Heading, and Search -->
                <div class="uk-width-1-2@s uk-margin-top@m">
                    <h1 class="uk-heading-primary uk-margin-remove-top">Welcome To Bangalore Job Seekers Guide</h1>
                    <p class="uk-text-lead">Follow Swarnil's path to succeed in Bangalore with job search, relocation guidance, and valuable articles and videos tailored for Bangalore job seekers.</p>
                        <div class="hero-search">
                            <!-- Html Elements for Search -->
                            <div class="uk-position-relative">
                                <form class="uk-search uk-search-default uk-width-1-1" name="search-hero" onsubmit="return false;">
                                    <span class="uk-search-icon-flip uk-search-icon uk-icon" data-uk-search-icon=""><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="search-icon"><circle fill="none" stroke="#000" stroke-width="1.1" cx="9" cy="9" r="7"></circle><path fill="none" stroke="#000" stroke-width="1.1" d="M14,14 L18,18 L14,14 Z"></path></svg></span>
                                    <input id="search-hero" class="uk-search-input uk-box-shadow-large" type="search" placeholder="Search for answers" autocomplete="off">
                                </form>
                                <ul id="search-hero-results" class="uk-position-absolute uk-width-1-1 uk-list"></ul>
                            </div>
                            <script>
                               SimpleJekyllSearch({
                                    searchInput: document.getElementById('search-hero'),
                                    resultsContainer: document.getElementById('search-hero-results'),
                                    noResultsText: '<li class="no-results">No results found</li>',
                                    searchResultTemplate: '<li><a href="{url}">{title}</a><span>{subtitle}</span></li>',
                                    json: "/search.json"
                                });
                                searchResults("search-hero");
                            </script>
                        </div>
                </div>
                <!-- Right side: Image or SVG -->
                <div class="uk-width-1-2@s uk-text-center@s uk-margin-top@m">
                    
                        <p class="hero-image uk-text-center"><img src="https://job.imswarnil.com//uploads/knowledge.svg" alt="Hero"></p>
                </div>
            </div>