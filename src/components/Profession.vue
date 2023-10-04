<script setup>
const portfolio = [

]
</script>
<template>
    <section>
        <div class="about-me">
            <div class="about-heading">
                <h1>About me</h1>
            </div>
        </div>
        <div class="self-summary">
            <div class="self-image">
                <img src="./images/chris-bg.jpg" alt="christopher gathuthi image">
            </div>
            <div class="main-area">
                <div class="cta-wrapper">
                    <p>I am web developer with almost three years of experience in developing websites and web applications.
                        I
                        build web applications that aim at streamlining business operations and creating value for business
                    </p>
                </div>
                <div class="stats">
                    <div class="box">
                        <h2>02+</h2>
                        <span>Years experience</span>
                    </div>
                    <div class="box">
                        <h2>20+</h2>
                        <span>completed projects</span>
                    </div>
                    <div class="box">
                        <h2>10+</h2>
                        <span>Clients serviced</span>
                    </div>
                </div>
                <div class="resume">
                    <a href="#" role="button" download>Download Resume</a>
                </div>
            </div>

        </div>

    </section>
    <section>
        <div class="skills">
            <div class="skills-heading">
                <h1>Skills</h1>
            </div>
        </div>
        <div class="skills-wrapper">
            <div class="tools-wrapper">
                <div class="tool-item">
                    <img src="./images/python.png" alt="django project icon" width="64" height="64">
                    <span>Python</span>
                </div>
                <div class="tool-item">
                    <img src="./images/JavaScript.png" alt="django project icon" width="64" height="64">
                    <span>JavaScript</span>
                </div>
                <div class="tool-item">
                    <img src="./images/go.png" alt="django project icon" width="64" height="64">
                    <span>Go</span>
                </div>
                <div class="tool-item">
                    <img src="./images/django.png" alt="django project icon" width="64" height="64">
                    <span>Django</span>
                </div>
                <div class="tool-item">
                    <img src="./images/vue.png" alt="django project icon" width="64" height="64">
                    <span>Vue</span>
                </div>
                <div class="tool-item">
                    <img src="./images/postgres.png" alt="django project icon" width="64" height="64">
                    <span>Postgres</span>
                </div>
                <div class="tool-item">
                    <img src="./images/docker.png" alt="django project icon" width="64" height="64">
                    <span>Docker</span>
                </div>
                <div class="tool-item">
                    <img src="./images/git.png" alt="django project icon" width="64" height="64">
                    <span>Git</span>
                </div>
                <div class="tool-item">
                    <img src="./images/linux.png" alt="django project icon" width="64" height="64">
                    <span>bash</span>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="portfolio">
            <div class="porfolio-heading">
                <h1>Porfolio</h1>
            </div>
        </div>

        <div class="portfolio-wrapper">
            <div class="project-wrapper">
                <div class="thumbnail">
                    <img src="https://jalesafoundation.org/static/img/logo-1_5_rz.7ec3a5e66bbb.png"
                        alt="jalesa foundation logo">

                </div>
                <div class="name">
                    <h3>Jalesa Foundation</h3>
                </div>
                <div class="info">
                    <a href="https://jalesafoundation.org">Read more</a>
                </div>
            </div>

            <div class="project-wrapper">
                <div class="thumbnail">
                    <img src="./images/rystoport.png" alt="rystoport logo">
                </div>
                <div class="name">
                    <h3>Rystoport</h3>
                </div>
                <div class="info">
                    <a href="https://rystoport.com">Read more</a>
                </div>
            </div>
            <div class="project-wrapper">
                <div class="thumbnail">
                    <img src="https://fastechinternet.co.ke/assets/logo-730f1e60.png" alt="fastech solution">
                </div>
                <div class="name">
                    <h3>Fastech solution</h3>
                </div>
                <div class="info">
                    <a href="https://fastechinternet.com">Read more</a>
                </div>
            </div>
        </div>


    </section>
    <section>
        <div class="articles">
            <div class="articles-heading">
                <h1>Articles</h1>
            </div>
            <div class="articles-wrapper">
                <div class="articles-item">
                    <img src="./images/django-orm.png" alt="" loading="lazy">
                    <h1><a href="https://medium.com/@soverignchriss/querying-related-objects-in-django-web-framework-3aece5bd927d"
                            target="_blank">Traversing model relationships</a>
                    </h1>
                </div>
                <div class="articles-item">
                    <img src="./images/optimazation-banner.png" alt="" loading="lazy">
                    <h1>
                        <a href="https://medium.com/@soverignchriss/understanding-select-related-and-prefetch-related-methods-in-django-orm-db36003d5fbf"
                            target="_blank">select_related vs prefetch_related</a>
                    </h1>
                </div>
                <div class="articles-item">
                    <img src="./images/htmx.webp" alt="" loading="lazy">
                    <h1>
                        <a href="https://medium.com/@soverignchriss/asynchronous-form-field-validation-with-htmx-and-django-eb721165b5e8"
                            target="_blank">Django with htmx</a>
                    </h1>
                </div>
            </div>
        </div>
        <v-divider></v-divider>
    </section>
</template>