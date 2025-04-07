<script>
import Page from '../+page.svelte';
import Title from '../../lib/Title.svelte'
</script>

<Title name="About" />
<section>
    <div class="outer">
        <div class="inner flow">
            <h2>Subheading One</h2>

            <div class="columns flow">
            <p> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dignissimos aliquid saepe odio, libero, soluta repellat dicta facere possimus placeat deleniti, fugit voluptatum nihil earum consequuntur. Unde qui fuga mollitia, quis deleniti eum.</p>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis quod beatae amet, consequatur incidunt ratione sint id debitis dignissimos perferendis velit necessitatibus reprehenderit tenetur nam iure, doloribus neque veniam voluptatibus eligendi harum saepe vel maxime quaerat. Optio voluptates omnis fugit deserunt placeat?
            </p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fugit quisquam quibusdam neque maxime aut nulla magnam. Molestiae quidem fugiat ab cum saepe fuga accusantium cumque at laborum non! Unde deserunt rem saepe aut debitis nostrum ipsa sapiente quam, officiis, nesciunt recusandae dicta, iure earum minima rerum? Obcaecati minima animi molestias earum iusto!</p>
            </div>
        </div>
</section>

<section>
    <div class="outer bg-blue white">
        <div class="inner flow">
            <h2>Subheading Two</h2>

            <div class="columns flow">
            <p class="white"> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dignissimos aliquid saepe odio, libero, soluta repellat dicta facere possimus placeat deleniti, fugit voluptatum nihil earum consequuntur. Unde qui fuga mollitia, quis deleniti eum.</p>
            <p class="white">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis quod beatae amet, consequatur incidunt ratione sint id debitis dignissimos perferendis velit necessitatibus reprehenderit tenetur nam iure, doloribus neque veniam voluptatibus eligendi harum saepe vel maxime quaerat. Optio voluptates omnis fugit deserunt placeat?
            </p>
            <p class="white">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fugit quisquam quibusdam neque maxime aut nulla magnam. Molestiae quidem fugiat ab cum saepe fuga accusantium cumque at laborum non! Unde deserunt rem saepe aut debitis nostrum ipsa sapiente quam, officiis, nesciunt recusandae dicta, iure earum minima rerum? Obcaecati minima animi molestias earum iusto!</p>
            </div>
        </div>
</section>

<section>
    <div class="outer">
        <div class="inner flow wide-text">
            <h2>Subheading Three</h2>
            <img class="float-right" src="https://picsum.photos/400/300" alt="">
            <p> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dignissimos aliquid saepe odio, libero, soluta repellat dicta facere possimus placeat deleniti, fugit voluptatum nihil earum consequuntur. Unde qui fuga mollitia, quis deleniti eum.</p>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis quod beatae amet, consequatur incidunt ratione sint id debitis dignissimos perferendis velit necessitatibus reprehenderit tenetur nam iure, doloribus neque veniam voluptatibus eligendi harum saepe vel maxime quaerat. Optio voluptates omnis fugit deserunt placeat?
            </p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. sit amet consectetur, adipisicing elit. Fugit quisquam quibusdam neque maxime aut nulla magnam. Molestiae quidem fugiat ab cum saepe fuga accusantium cumque at laborum non! Unde deserunt rem saepe aut debitis nostrum ipsa sapiente quam, officiis, nesciunt recusandae dicta, iure earum minima rerum? Obcaecati minima animi molestias earum iust sit amet consectetur, adipisicing elit. Fugit quisquam quibusdam neque maxime aut nulla magnam. Molestiae quidem fugiat ab cum saepe fuga accusantium cumque at laborum non! Unde deserunt rem saepe aut debitis nostrum ipsa sapiente quam, officiis, nesciunt recusandae dicta, iure earum minima rerum? Obcaecati minima animi molestias earum iust Fugit quisquam quibusdam neque maxime aut nulla magnam. Molestiae quidem fugiat ab cum saepe fuga accusantium cumque at laborum non! Unde deserunt rem saepe aut debitis nostrum ipsa sapiente quam, officiis, nesciunt recusandae dicta, iure earum minima rerum? Obcaecati minima animi molestias earum iusto!</p>
        </div>
    </div>
</section>

<style>
.wide-text p {
    max-width: unset;
}
</style>