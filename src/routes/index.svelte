<script>
// @ts-ignore
import { images } from "../index.ts";
</script>

<main>
    <h1 class="lg">Nathan's Photography</h1>

    
        
        <details>
            <summary>
                Great Pictures right?
            </summary>
            <div class="flex flex-wrap">
                {#each images as image}
                    <img src="images/{image}" alt="" width="20%" class="grid p-1">
                {/each}
            </div>
            
        </details>

</main>