<template>
    <div>
        <TopNav navHeader="Welcome" imgSrc="deekslake_1.jpg"></TopNav>
        <div class="flex flex-col items-center">
            <div class="flex flex-col m-6 p-6 w-2/3 flex content-center rounded-lg items-center">
                <p class="p-6 text-lg font-semibold bg-gray-400 rounded-lg">Greetings wanderer!  You must be tired from surfing through the web.  
                    <br>Feel free to stay a while and rest your weary mind before moving on.</p>
            </div>
        </div>
    </div>
</template>

<script>
import TopNav from "../components/TopNav";
export default {
    name: 'Welcome',

    components: {
        TopNav
    }

}
</script>

<style scoped>

</style>