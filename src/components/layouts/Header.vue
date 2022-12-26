<script setup>
import '/src/assets/layouts/header.css'
</script>

<template>
    <header class="header">
        <div class="header__logo">
            <img src="/src/assets/logo_48.svg" alt="logo" width="22">
            <span class="logo__title">Ghazwul</span>
        </div>
        <ul class="header__nav">
            <li class="nav__item active"><a href="#">Home</a></li>
            <li class="nav__item"><a href="#">Projects</a></li>
            <li class="nav__item"><a href="#">About</a></li>
            <li class="nav__item"><a href="#">Contact</a></li>
        </ul>
        <ul class="header__icons">
            <li class="icon__item"><a href="#"><font-awesome-icon icon="fa-brands fa-dribbble" /></a></li>
            <li class="icon__item"><a href="#"><font-awesome-icon icon="fa-brands fa-linkedin" /></a></li>
            <li class="icon__item"><a href="#"><font-awesome-icon icon="fa-brands fa-instagram" /></a></li>
        </ul>
    </header>
</template>