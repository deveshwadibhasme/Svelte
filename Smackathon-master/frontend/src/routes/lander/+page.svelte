<html lang="en">
  <head>
    <meta charset="utf-8" />
    <link rel="icon" href="%sveltekit.assets%/favicon.png" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Women Safety</title>
    <link
      href="https://fonts.googleapis.com/css?family=Hanken+Grotesk:100,200,300,regular,500,600,700,800,900,100italic,200italic,300italic,italic,500italic,600italic,700italic,800italic,900italic"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/css?family=Poppins:100,100italic,200,200italic,300,300italic,regular,italic,500,500italic,600,600italic,700,700italic,800,800italic,900,900italic"
      rel="stylesheet"
    />
  </head>
  <body>
    <header
      class="max-w-screen-xl mx-auto p-5 flex h-39 shadow-lg justify-between"
    >
      <div class="flex h-full">
        <img
          class="h-8"
          src="src\routes\lander\img\Custom-Icon-Design-Pretty-Office-4-Woman.ico"
          alt=""
        />
        <h5 class="font-bold text-lg">Women's Safety</h5>
      </div>
      <div class="h-full hover:cursor-pointer" title="Profile">
        <img
          class="h-8"
          src="src\routes\lander\img\icone-utilisateur-rose.png"
          alt="" title="Profile"    
        />
      </div>
    </header>
    <main class="justify-center w-full h-full flex flex-wrap md:justify-between my-10">
      <div class="flex flex-row  w-full md:w-[420px] justify-between p-4 shadow-2xl items-center gap-4">
        <div class="flex flex-col max-w-52">
          <h3 class="font-bold">Emergency Call</h3>
          <p>One-tap emergency call for immediate assistance.</p>
        </div>
        <div class="h-9 w-9 rounded-full">
            <img class="h-full overflow-hidden" src="src\routes\lander\img\call-icon.png" alt=""></div>
      </div>
      <div class="flex h-28 md:h-36 w-full md:w-[420px] justify-between p-4 shadow-2xl items-center gap-4">
        <div class="flex flex-col max-w-52">
          <h3 class="font-bold">Live Location</h3>
          <p>Track your location in real-time for added safety.</p>
        </div>
        <div class="h-9 w-9 rounded-full">
            <img class="h-full overflow-hidden" src="src\routes\lander\img\loc-icon.png" alt=""></div>
      </div>
      <div class="flex h-28 md:h-36 w-full md:w-[420px] justify-between p-4 shadow-2xl items-center gap-4">
        <div class="flex flex-col max-w-52">
          <h3 class="font-bold">Audio Recording</h3>
          <p>Discreetly record audio for evidence and security.</p>
        </div>
        <div class="h-9 w-9 rounded-full">
            <img class="h-full overflow-hidden" src="src\routes\lander\img\mic-icon.png" alt=""></div>
      </div>
      <div class="flex h-28 md:h-36 w-full md:w-[420px] justify-between p-4 shadow-2xl items-center gap-4">
        <div class="flex flex-col max-w-52">
          <h3 class="font-bold">Camera</h3>
          <p>Capture photos for documentation and evidence.</p>
        </div>
        <div class="h-10 rounded-full">
            <img class="h-full w-full overflow-hidden" src="src\routes\lander\img\camera-icon.png" alt=""></div>
      </div>
    </main>
  </body>
</html>
