<script>
import { fullImages } from "../index.ts";

function setter(src, hidden) {
    largeImage.src = src;
    largeImage.hidden = hidden;
    return
}

let largeImage;
let imageElement;

const enlarge = {
    "src":"",
    "hidden":true
}

</script>

<main class="flex flex-wrap">
    {#each fullImages as image}
        <img src="images/{image}" alt="" class="size m-1" >
    {/each}

    <!-- <div>
        <img src="images/{imageElement.src}" alt="" hidden={true} bind:this={largeImage}>
    </div> -->
</main>