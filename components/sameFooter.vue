<template>
    <footer>
        <div class="footer-wrapper">
            <div class="footer-info">
                <div class="artist">
                    <p><a href="https://jordanfurr.com/" class="links">Katrina Stalcup</a></p>
                </div>
                <div class="artist">
                    <p><a href="https://jordanfurr.com/" class="links">Jordan Furr</a></p>
                </div>
            </div>
        </div>
    </footer>
</template>

<style>
.footer-wrapper{ 
    background-color: black;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 30vh;
}
.footer-info{
    display: flex;
    width: 50%;
    margin: 1rem;
    padding: 2rem 2rem;
}
.artist{
    flex: 1;
    text-align: center;
}
.artist:first-child{
    margin-right: 20px;
}
</style>