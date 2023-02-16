<template>
    <header class="I-header" id="header">
        <nav class="nav ba-grid">
            <div class="nav__toggle" id="nav-toggle">
                <i class='bx bxs-grid'></i>
            </div>
            <a href="#" class="nav__logo"><img src="/images/logo/nike_logo_1.png" /></a>

            <div class="nav__menu" id="nav-menu">
                <ul class="nav__list">
                    <li class="nav__item"><a href="#new_&_featured" class="nav__link active">New & Featured</a></li>
                    <li class="nav__item"><a href="#Men" class="nav__link">Men</a></li>
                    <li class="nav__item"><a href="#Women" class="nav__link">Women</a></li>
                    <li class="nav__item"><a href="#Kids" class="nav__link">Kids</a></li>
                    <li class="nav__item"><a href="#Sale" class="nav__link">Sale</a></li>
                </ul>
            </div>
            <div class="nav__shop">
                <i class='bx bx-heart'></i>
                <i class='bx bx-basket'></i>
            </div>

        </nav>

    </header>

    <main class="I-main">
        <section class="home" id="home">
            <div class="home__container bd-grid">
                <div class="home__sneaker">
                    <div class="home__shape"></div>
                    <img src="images/img_hdr/nike-air-force.png" alt="" class="home__img">
                </div>
                <div class="home__data">
                    <span class="home__new">Nike Air</span>
                    <p>Experience the New Nike Air</p>
                    <a href="#" class="button">Explore now</a>
                </div>

            </div>
        </section>

        <section class="featured section" id="featured">
            <h2 class="section-title">Featured</h2>

            <div class="featured__container bd-grid">
                <article class="sneaker">
                    <img src="images/img_hdr/pngegg.png" alt="" class="sneaker__img">
                    <span class="sneaker__name">Nike Jordan</span>
                </article>

                <article class="sneaker">
                    <img src="images/img_hdr/pngwing_2.png" alt="" class="sneaker__img1">
                    <span class="sneaker__name">Nike Free RN</span>
                </article>

                <article class="sneaker">
                    <img src="images/img_hdr/pngwing_3.png" alt="" class="sneaker__img2">
                    <span class="sneaker__name">Nike Air Force</span>
                </article>
            </div>
        </section>
    </main>
</template>

<script setup>

</script>  
 
<style scoped></style>

