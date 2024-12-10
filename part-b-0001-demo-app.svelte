<script lang="ts">

    let myName: string = "Mustafa Büyükdereli"

    let info: string = "I want to use Svelte in my Web3 projects!"

    let counter: number = 0

    function counterUp() {
        counter++
    }

</script>

<h1 class="my-name">{myName}</h1>

<h2 class="why-svelte">{info}</h2>

<div class="container">

    <button onclick={counterUp}>Counter ++</button>
    
    <p>{counter}</p>

</div>


<style>

    .my-name {
        color: blue;
        text-align: center;
    }

    .why-svelte {
        color: green;
        text-align: center;
    }

    .container {
        display: flex;
        justify-content: space-around;
        width: 300px;
        margin: 30px auto;
    }

    button {
        background-color: purple;
        color: white;
        font-size: 25px;
        padding: 10px;
        border: none;
        border-radius: 10px;
    }

    p {
        font-size: 20px;
    }

</style>
