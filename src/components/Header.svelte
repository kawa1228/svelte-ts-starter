<header class:visible="{visible || open}">
    <nav>
        <Icon name="/svg/svelte-logo.svg#icon" size={30}/>
        <ul class="primary">
            <li>
                <a href="/" use:link>Home</a>
            </li>
            <li>
                <a href="/lucky" use:link>Lucky</a>
            </li>
        </ul>
    </nav>
</header>

<script lang="typescript">
    import {link} from 'svelte-spa-router';
	import Icon from "../components/Icon.svelte";

	let open = false;
    let visible = true;

</script>

<style lang="scss">
    nav {
        display: flex;
        justify-content: space-between;

        ul {
            display: flex;
        }
    }
</style>
