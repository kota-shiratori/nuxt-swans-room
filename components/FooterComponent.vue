<template>
    <footer class="footer">
        <div class="footer__inner">
            <p class="footer__copyright">© 2022 Swan's Room</p>
        </div>
    </footer>
</template>

<style>
.footer {
    background-color: #000;
    height: 10vh;
    width: 100%;
}

.footer__inner {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    height: 100%;
}

.footer__copyright {
    color: #fff;
    font-size: 1rem;
}
</style>