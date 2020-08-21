<template>
    <header class="nuxt-site-header">
        <div class="uk-container uk-container-expand uk-background-muted">
            <div class="uk-navbar">
                <div class="uk-navbar-left">
                    <a class="uk-navbar-item uk-logo" href="#">Logo</a>
                </div>
                <nav class="uk-navbar-center">
                    <ul class="uk-navbar-nav ">
                        <li class="uk-active"><a href="#">Home</a></li>
                        <li><a href="#">About</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </nav>
                <div class="uk-navbar-right">
                    <div class="uk-navbar-item">
                        <ul class="uk-grid-small uk-grid" uk-grid="">
                            <li class="uk-first-column">
                                <a
                                    class="uk-icon-button uk-icon"
                                    href="#"
                                    uk-icon="icon: user"
                                    ></a>
                            </li>
                            <li>
                                <a
                                    class="uk-icon-button uk-icon"
                                    href="#"
                                    uk-icon="icon: settings"
                                    ></svg
                                ></a>
                            </li>
                            <li>
                                <a
                                    class="uk-icon-button uk-icon"
                                    href="#"
                                    uk-icon="icon: search"
                                    ></svg
                                ></a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
    export default {}
</script>

<style></style>
