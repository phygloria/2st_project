<script setup>

</script>

<template>
    <div id="categoryMenu">
        <div @click="" class="menuBtn">
            <h4>추천메뉴!</h4>
        </div>

        <div @click="" class="menuBtn">
            <h4>추천메뉴!</h4>
        </div>
    </div>
</template>


<style scoped>

    @font-face {
    font-family: 'BMJUA';
    src: url('https://fastly.jsdelivr.net/gh/projectnoonnu/noonfonts_one@1.0/BMJUA.woff') format('woff');
    font-weight: 900;
    font-style: normal;
    }

    .categoryMenu{
        display: flex;

    }



    .menuBtn{
        display: flex;
        font-family: 'BMJUA';
        font-size: 1.15em;
        cursor: pointer;
        color: white;
        background-color: #783E19;
        width: 100px;
        height: 50px;
        border-radius: 10px;
        
        /* justify-content: center; 좌우 가운대 */
        justify-content: center; 
        /* align-items: center; 상하 가운대 */
        align-items: center;

    }

</style>