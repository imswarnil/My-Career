---
layout: page
hero:
  title: Welcome To Job & Career Project
  subtitle: Follow Swarnil's path to succeed in Bangalore with job search, relocation
    guidance, and valuable articles and videos tailored for Bangalore job seekers.
  image: "/uploads/knowledge.svg"
  search: true
---
{% include ad.html type="top-leaderboard" %}

<div class="container is-medium is-flex is-align-items-center is-flex-wrap-wrap">
    <!-- Left side: Embedded YouTube Video -->
    <div class="column is-half has-text-centered mt-5">
        <div class="video-container">
            <iframe width="auto" height="315" src="https://www.youtube.com/embed/uV3eTXpEBOg" frameborder="0" allowfullscreen></iframe>
        </div>
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
    <div class="column is-half mt-5" style="padding-left: 20px;">
        <h1 class="title is-3">Welcome To Bangalore Job Seekers Guide</h1>
        <p class="subtitle is-5">Follow Swarnil's path to succeed in Bangalore with job search, relocation guidance, and valuable articles and videos tailored for Bangalore job seekers.</p>
        <div class="buttons">
            <a class="button is-primary" href="https://www.youtube.com/watch?v=uV3eTXpEBOg">
                <span class="icon">
                    <i class="fas fa-play"></i>
                </span>
                <span>Watch Video</span>
            </a>
            <a class="button is-outlined is-primary ml-3" href="/link-to-article">Read Article</a>
        </div>
    </div>
</div>

<style>
.video-container {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    overflow: hidden;
    max-width: 100%;
    background: #000;
    margin-bottom: 1rem;
}

.video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
</style>


{% include boxes.html columns="3" title="Browse Topics" subtitle="Chose an option that you need help with or search above" %}

{% include ad.html %}

{% include featured.html tag="featured" title="Popular Articles" subtitle="Selected featured articles to get you started fast in Jekyll" %}

{% include videos.html columns="2" title="Video Tutorials" subtitle="Watch screencasts to get you started fast with Jekyll" %}

{% include faqs.html multiple="true" title="Frequently asked questions" category="presale" subtitle="Find quicke answers to frequent pre-sale questions asked by customers" %}

{% include team.html authors="evan, john, sara, alex, tom, daniel" title="We are here to help" subtitle="Our team is just an email away ready to answer your questions" %}

{% include cta.html title="Didn't find an answer?" button_text="Contact Us" button_url="/contact/" subtitle="Get in touch with us for details on setup and additional custom services pricing" %}
