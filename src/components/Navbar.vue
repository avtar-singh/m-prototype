<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-md-center" id="navbarNav">
        <ul class="navbar-nav">
        <li class="nav-item active">
            <a class="nav-link" href="#">Home / Yard <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">Culture</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">Parenthood</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">Life Style</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">Popularity</a>
        </li>
        </ul>
    </div>
    </nav>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>
.nav-item{
  width: 200px;
}

nav{
    font-size: 1.3em;
}

.nav-link{
    text-decoration: none !important;
    text-transform: uppercase;
}

</style>

