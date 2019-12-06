<template>
    <a class="home-button-wrap">
    <span class="home-button">
        <font-awesome-icon :icon="['fas', 'home']" class="home-button-icon" />     
    </span>
    </a>
</template>

<style>
.home-button-wrap{
    background: #f7f7f7;
    display: inline-block;
    border-radius: 100px;
    box-shadow: 0 0 2px rgba(0, 0, 0, 0.2) inset;
}
    .home-button{
        text-align: center;
        line-height: 70px;
        display: inline-block;
        color: rgba(3, 169, 244, 0.54);
        border-radius: 100px;
        font-size: 32px;
        width: 72px;
        height: 72px;
        margin: 12px;
        background-image: linear-gradient(#e8e8e8 0%, #d6d6d6 100%);
        border-width: 0px;
        text-shadow: 0 3px 2px rgba(0, 0, 0, 0.2);
    }

            .home-button-icon{
                box-shadow:                 
    }
</style>