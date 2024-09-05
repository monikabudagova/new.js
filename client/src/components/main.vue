<template>
    <main>
        <article>
            <img src='../assets/img/cabbage.png' alt="">
            <p>Капуста давно и прочно вошла в рацион нашего питания и принадлежит к числу важнейших овощных растений. Она также является неотъемлемой частью таких традиционных блюд, как: борщ, щи, солянка, тушеная капуста, голубцы, капустная запеканка и конечно квашеная капуста.</p>
            <p>Капуста не только популярный, но и полезный продукт: она богата витаминами А, В1, Р, К, В6, U. Капуста является лидером среди овощей по содержанию витамина С, причем он сохраняется в капусте как при длительном хранении в сыром виде, так и при термической обработке. В ней также много минералов - сера, кальций, калий и фосфор, клетчатки и воды.</p>
        </article>
        <div class="image-container">
            <button ><img class="like" src="../assets/img/like.png"></button>
        </div>
        <div class="knopka">
            <button><p>Поделиться</p></button>
        </div>
    </main>
</template>

<style scoped>
    .knopka{
            width: 150px;
            padding: 10px 20px;
            background-color: #B54B62;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    .like{
        height: auto;
        max-width: 50px;

    }
    .image-container {
        text-align: right; 
        margin: 20px; 
    }
    main {
        border-radius: 60px 60px 0px 0px;
        background-color: #FEA896;
        padding: 20px;
        height: 100%;
    }

    article {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        grid-template-rows: repeat(2, 1fr);
        grid-column-gap: 0px;
        grid-row-gap: 0px;
        gap: 20px;
        color: #B54B62;
        font-family: Roboto;
        font-size: 24px;
        font-weight: 400;
        line-height: 28.13px;
        text-align: left;
    }

    .img {
        grid-area: 1 / 1 / 2 / 2;
    }

    p:first-child {
        grid-area: 1 / 2 / 2 / 3;
    }

    p:last-child {
        grid-area: 2 / 1 / 3 / 3;
        text-indent: 40px;
    }

    img {

        width: 480px;
        height: 320px;
        border-radius: 40px;
    }
</style>
