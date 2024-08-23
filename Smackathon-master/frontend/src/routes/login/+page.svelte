<script>
    let signUp = false;
</script>

  
  
  <body class="w-screen h-screen bg-slate-50 flex flex-row">
    <div class="flex flex-col w-1/3 m-auto justify-evenly gap-5 items-center">
        <div class="absolute z-0 left-2/4">
            <img src="src\routes\lander\img\woman guard.jpg" alt="" class="opacity-40 w-94">
        </div> 
    <div class="w-full flex flex-row justify-evenly text-white text-xl gap-3 mt-5 z-10">
        <button on:click={signUp==false} class="bg-pink-400 hover:bg-pink-800 w-72 h-8 rounded-lg uppercase text-xl font-medium">Log In</button>
        <button on:click={signUp==true} class="bg-pink-400 hover:bg-pink-800 h-8 w-72 rounded-lg uppercase font-medium">Sign Up</button>
    </div>
    
    {#if signUp}
        <form class="w-96 flex flex-col gap-2 min-h-96 m-0 md:m-auto rounded-lg p-10 z-10">
            <h1 class="text-center text-4xl font-sans font-semibold text-purple-800">LOG IN</h1>
            <div class="flex flex-col gap-1">
                <p class="text-sm ">Email:</p>
                <input class="border-2 rounded-xl border-pink-600 px-2 text-sm h-8 ">
                <p class="tex-sm">Password:</p>
                <input type="password" class="border-2 rounded-xl border-pink-600 px-2 h-8">
                <input type="submit" value="Submit" class="w-60 h-10 bg-pink-500 rounded-xl text-white font-bold mx-auto mt-8 hover:bg-pink-600">
            </div>
        </form>
    {:else}

    <form class="w-96 flex flex-col gap-2 min-h-96 m-0 md:m-auto rounded-lg p-10 z-10">
        <h1 class="text-center text-4xl font-sans font-semibold text-purple-800 mb-4">SIGN IN</h1>
        <div class="flex flex-col gap-1">
            <p class="text-sm ">Name:</p>
            <input class="border-2 rounded-xl border-pink-600 px-2 text-sm h-8">
            <p class="text-sm ">Email:</p>
            <input class="border-2 rounded-xl border-pink-600 px-2 text-sm h-8">
            <p class="text-sm ">Password:</p>
            <input class="border-2 rounded-xl border-pink-600 px-2 text-sm h-8">
            <p class="tex-sm">Confirm Password:</p>
            <input type="password" class="border-2 rounded-xl border-pink-600 px-2 h-8">
            <p class="tex-sm">Date of birth:</p>
            <input type="date" class="border-2 rounded-xl border-pink-600 px-2 h-8">

            <input type="submit" value="Submit" class="w-60 h-10 bg-pink-500 rounded-xl text-white font-bold mx-auto mt-8 hover:bg-pink-600 ">
        </div>
    </form>
    {/if}
</div>
</body>


