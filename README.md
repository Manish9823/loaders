<style>
    .spinner{
        height:40px;
        width:40px;
        border:4px solid #00ccff;
        border-radius:100px;
        border-top-color:transparent;
        animation: move;
        animation-duration: 1s;
        animation-iteration-count: infinite;
    }
    @keyframes move{
        from{
            transform:rotate(0deg);
        }
        to {
            transform:rotate(360deg);
        }
    }

</style>
<div>
    <div class="spinner"></div>
</div>
