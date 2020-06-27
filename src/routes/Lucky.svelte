<h1 id="lucky">You're in!</h1>

<h2>The count is {$count}</h2>

<button on:click={count.increment}>+</button>
<button on:click={count.decrement}>-</button>
<button on:click={count.reset}>reset</button>

<script lang="typescript">
    import { count } from '../store/count';
</script>
