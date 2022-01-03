<script>
// @ts-ignore
import { sampleimages } from "../index.ts";
</script>

<main>
    <h1 class="text-xl">Nathan's Photography</h1>
    <br>
    <div class="flex flex-wrap">
        {#each sampleimages as image}
            <img src="images/{image}" alt="" class="grid m-1 size">
        {/each}
    </div>
</main>