<template>
    <div id="promo">
        <h2>Promo</h2>
        <div class="cards">
            <div class="card">
                <div>
                    <h3>Design</h3>
                </div>
            </div>
            <div class="card">
                <div>
                    <h3>Responsive</h3>
                </div>
            </div>
            <div class="card">
                <div>
                    <h3>Ideas</h3>
                </div>
            </div>
            <div class="card">
                <div>
                    <h3>Creative</h3>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
    #promo {
        background: #82defe;
        padding: 5%;
    }

    #promo h2 {
        text-align: center;
    }

    .cards {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
        grid-auto-rows: auto;
        grid-gap: 1rem;
    }

    .cards .card {
        border-radius: 4px;
        border-radius: 8px;
        padding: 11.5rem 0;
        background: #23272f;
        box-shadow: 5px 13px 20px 4px
        
    }

    .cards .card h3 {
        text-align: center;
        color: #fff;
    }
</style>

<script>
export default {
    name:"Promo"
}
</script>