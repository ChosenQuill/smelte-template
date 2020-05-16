<script>   
    import { Button } from 'smelte';
</script>

<svelte:head>
  <title>About</title>
</svelte:head>

<h1>About this site</h1>

<p class="my-4">This is the 'about' page. There's not much here except these buttons.</p>

<Button on:click="{()=>alert("Hi")}">
    Hey there!
</Button>

<Button on:click="{()=>alert("I'm doing great!")}" color="blue">
    How are you?
</Button>