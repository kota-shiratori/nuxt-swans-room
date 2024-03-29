<template>
    <header class="header">
        <div class="header__inner">
            <h1 class="header__logo">
                <NuxtLink to="/" class="header__logo--link">
                    <img class="lazyload" src="~/assets/wsc.png" loading="lazy" alt="Swan's LOGO">
                </NuxtLink>
            </h1>
            <nav class="header__nav">
                <ul class="header__nav--list">
                    <li class="header__nav--item">
                        <NuxtLink to="/" class="header__nav--link">
                            Works
                        </NuxtLink>
                    </li>
                    <li class="header__nav--item">
                        <NuxtLink to="/about" class="header__nav--link">
                            About
                        </NuxtLink>
                    </li>
                    <li class="header__nav--item">
                        <NuxtLink to="/contact" class="header__nav--link">
                            Contact
                        </NuxtLink>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style>
.header {
    z-index: 9999;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 30px;
    padding-left: 20px;
}

.header__inner {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: justify;
    -ms-flex-pack: justify;
    justify-content: space-between;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    max-width: 980px;
    margin: 0 auto;
}

.header__logo--link img {
    border-radius: 50%;
    width: 50px;
    height: 50px;
}

.header__nav {
    position: absolute;
    top: 45px;
    right: 70px;
}

.header__nav--list {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    gap: 1em;
}

.header__nav--link {
    font-size: 0.75rem;
    color: #333;
}

@media screen and (min-width: 300px) {
    .header__nav--link {
        font-size: 1rem;
    }
}

@media screen and (min-width: 768px) {
    .header {
        padding-left: 30px;
    }

    .header__logo--link img {
        width: 80px;
        height: 80px;
    }

    .header__nav {
        top: 50px;
        right: 100px;
    }

    .header__nav--list {
        gap: 2em;
    }

    .header__nav--link {
        font-size: 1.25rem;
    }
}

@media screen and (min-width: 1200px) {
    .header__nav {
        position: static;
    }

    .header__nav--list {
        gap: 2.5em;
    }
}
</style>