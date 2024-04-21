<template>
    <footer>
        <div class="insideContainer">
            <a href="https://www.google.com/"><img src="/images/github.svg" alt="logo"/></a>
            <a href="https://www.linkedin.com/"><img src="/images/linkedin.svg" alt="logo"/></a>
            <a href="https://www.instagram.com/"><img src="/images/twitter.svg" alt="logo"/></a>
            <a href="https://www.facebook.com/"><img src="/images/facebook.svg" alt="logo"/></a>
            <hr />
            <NuxtLink to = "/blog">Blog</NuxtLink>
            <NuxtLink to = "/contact">About</NuxtLink>
            <p>©{{ new Date().getFullYear() }} Abe Hiroki</p>
        </div>
    </footer>
</template>