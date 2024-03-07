---
layout: page
width: expand
hero:
  title: Welcome To Job & Career Project
  subtitle: Follow Swarnil's path to succeed in Bangalore with job search, relocation
    guidance, and valuable articles and videos tailored for Bangalore job seekers.
  image: "/uploads/knowledge.svg"
  search: true
---
{% include ad.html type="top-leaderboard" %}

<div class="uk-container uk-container-medium uk-flex uk-flex-middle uk-flex-wrap">
    <!-- Left side: Embedded YouTube Video -->
    <div class="uk-width-1-2@s uk-text-center@s uk-margin-top@m">
        <p class="hero-image uk-text-center">
            <div class="video-container">
                <iframe width="auto" height="315" src="https://www.youtube.com/embed/uV3eTXpEBOg" frameborder="0" allowfullscreen></iframe>
            </div>
        </p>
        <!-- JSON-LD for Video -->
        <script type="application/ld+json">
            {
                "@context": "http://schema.org",
                "@type": "VideoObject",
                "name": "Your Video Title",
                "description": "Description of your video",
                "thumbnailUrl": "URL to video thumbnail",
                "uploadDate": "2023-11-06T08:00:00Z",
                "duration": "PT5M", // Replace with video duration
                "publisher": {
                    "@type": "Organization",
                    "name": "Your Organization Name"
                }
            }
        </script>
    </div>
    <!-- Right side: Title, Heading, and Buttons -->
    <div class="uk-width-1-2@s uk-margin-top@m" style="padding-left: 20px;">
        <h1 class="uk-heading-small uk-margin-remove-top">Welcome To Bangalore Job Seekers Guide</h1>
        <p class="uk-text-lead">Follow Swarnil's path to succeed in Bangalore with job search, relocation guidance, and valuable articles and videos tailored for Bangalore job seekers.</p>
        <div class="hero-buttons uk-flex uk-flex-wrap">
            <a class="uk-button uk-button-primary" href="https://www.youtube.com/watch?v=uV3eTXpEBOg" data-uk-lightbox>
                <span data-uk-icon="icon: play; ratio: 1"></span> Watch Video
            </a>
            <a class="uk-button uk-button-border-primary uk-margin-left" href="/link-to-article">Read Article</a>
        </div>
    </div>
</div>


{% include boxes.html columns="3" title="Browse Topics" subtitle="Chose an option that you need help with or search above" %}

{% include ad.html %}

{% include featured.html tag="featured" title="Popular Articles" subtitle="Selected featured articles to get you started fast in Jekyll" %}

{% include videos.html columns="2" title="Video Tutorials" subtitle="Watch screencasts to get you started fast with Jekyll" %}

{% include faqs.html multiple="true" title="Frequently asked questions" category="presale" subtitle="Find quicke answers to frequent pre-sale questions asked by customers" %}

{% include team.html authors="evan, john, sara, alex, tom, daniel" title="We are here to help" subtitle="Our team is just an email away ready to answer your questions" %}

{% include cta.html title="Didn't find an answer?" button_text="Contact Us" button_url="/contact/" subtitle="Get in touch with us for details on setup and additional custom services pricing" %}
