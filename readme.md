# Coder Academy - Portfolio

## Overview
This is a portfolio website for displaying the services that coder academy provides. This is in development phase and we will keep on adding those features in this readme that we add on the website.

## Components

### Header
Header has logo and name of the company along with the navigation bar. Here is the code for the header we have: 
```html
<header>
        <div class="logo-name">
            <a href="./index.html">
                <img src="./images/logo.png" alt="logo">
            </a>
            <p class="name">
                <span class="coder-text">Coder</span> 
                <span class="academy-text">Academy</span>
            </p>
        </div>
        <nav class="nav-items">
            <a href="./pages/about.html">About</a>
            <a href="./pages/services.html">Services</a>
            <a href="./pages/contact.html">Contact</a>
        </nav>
    </header>
```
### Footer
Footer has social media links, contact number and address. Here is the code that we have:

```html
<footer>
        <div class="social-media">
            <a href="">
                <i class="fa-brands fa-github"></i>
            </a>
            <a href="">
                <i class="fa-brands fa-linkedin"></i>
            </a>
            <a href="">
                <i class="fa-brands fa-instagram"></i>
            </a>
        </div>
        <div class="info">
            <p>Contact: 0404040404</p>
            <p>Address: 1 Street St, Suburb</p>
        </div>
    </footer>
```

### Home
Home page, for now, just displays some loren ipsum text. Here is the code that we have used:

``` html
<main>
        <section>
            <div class="jumbotron">
                <img src="./images/jumbotron.jpg" />
            </div>
            <div class="details">
                <p>
                    Coder Academy is Lorem ipsum dolor sit amet, consectetur
                    adipisicing elit. Harum corporis saepe exercitationem
                    suscipit quibusdam debitis sed ducimus doloribus, ut non
                    eveniet obcaecati maiores minima animi est odio quod
                    necessitatibus dolorum! Lorem ipsum dolor sit amet
                    consectetur adipisicing elit. Fuga molestias autem,
                    suscipit, ut magni alias totam nemo deserunt odit eaque
                    pariatur iusto? Placeat esse provident at consequatur
                    vitae nostrum in? Lorem ipsum dolor, sit amet
                    consectetur adipisicing elit. Provident in, maiores
                    distinctio possimus libero dolorem exercitationem,
                    repellat vel tempore soluta fugit nulla quod aperiam
                    corporis explicabo voluptatem ullam quos quam.
                </p>
            </div>
        </section>
    </main>
```