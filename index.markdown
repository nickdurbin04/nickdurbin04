---
layout: default
---

<!-- Hero Section -->
<section class="hero">
    <div class="hero-content">
        <img src="{{ site.baseurl }}/img/profile.png" alt="Profile Picture" class="profile-pic">
        <h1>Welcome to Nick Durbin's Portfolio</h1>
        <p>Exploring cutting-edge AI, coding, and technology research.</p>
        <a href="{{ '/contact' | relative_url }}" target="_blank" class="btn-primary">View Contacts</a>
    </div>
</section>

<!-- Content Grid -->
<section class="content-grid">

    <!-- Technical Blogs Section -->
    <div class="content-block" id="blogs">
        <div class="text-content">
            <h2>Technical Blogs</h2>
            <p>Follow my thoughts on AI, machine learning, and coding at Dev.to.</p>
            <a href="https://dev.to/nickdurbin04" class="btn-primary">Read Blogs</a>
        </div>
    </div>

    <!-- GitHub Projects Section -->
    <div class="content-block reverse" id="projects">
        <div class="text-content">
            <h2>GitHub Projects</h2>
            <p>Check out my GitHub repositories, including CodeCoreLM—a code-core language model I'm developing.</p>
            <a href="{{ site.baseurl }}/projects" class="btn-primary">View Projects</a>
        </div>
        <div class="image-content">
            <img src="{{ site.baseurl }}/img/github.png" alt="GitHub Projects">
        </div>
    </div>

    <!-- ArXiv Papers Section -->
    <div class="content-block" id="papers">
        <div class="text-content">
            <h2>ArXiv Papers I've Read</h2>
            <p>Explore the key research papers I've studied, including groundbreaking work in AI and machine learning.</p>
            <a href="{{ site.baseurl }}/papers" class="btn-primary">View Papers</a>
        </div>
    </div>

</section>

