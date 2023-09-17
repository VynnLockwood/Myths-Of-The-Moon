<template>
    <div class="w-full h-16 m-0 bg-white relative">

        <div class="logo absolute h-16 w-40 flex items-center ml-14">
            <img src="../src/images/motm-logo.png" alt="" srcset="" class="h-12 w-12">
            <p class="ml-3 text-sm">MOTM</p>
        </div>

        <div class="w-40 h-16 flex items-center absolute right-40">
            <input type="text" placeholder="Search.." class="border-solid rounded-3xl border-gray border-2 pl-4">
        </div>

        <button class="w-10 h-16 flex items-center absolute right-14">
                <img src="../src/icons/Icon/Outline/search.png" alt="search icon" class="w-5 h-5 right-0">
        </button>


        <ul class="navlist flex justify-center h-16">
            <li><a href="#" class="">Home</a></li>
            <li><a href="#" class="">Services</a></li>
            <li><a href="#" class="">Goal</a></li>
            <li><a href="#" class="">About us</a></li>
        </ul>
    </div>
</template>


<style>
    .navlist li{
        display: flex;
        align-items: center;
        height: 4rem;
        padding-right: 2rem;
    }
    .navlist li a:hover{
        color: bisque;
    }
</style>