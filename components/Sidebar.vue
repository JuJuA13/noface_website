
<template>
    <div class="flex items-left sticky top-0 bg-white h-full max-h-screen dark:bg-gray-800 mx-1">
      <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css" rel="stylesheet"/>
      <div class="flex flex-col sm:flex-row sm:justify-around">
          <div class="w-80 h-screen">
                <div class="grid grid-cols-1 gap-4 place-items-center justify-start mx-6 mt-10">
                    <a class="block relative ">
                        <img alt="profil" src="@/images/Hayao.jpg" class="avatar w-25 rounded-full" />
                    </a>
                    <span class="text-gray-900 dark:text-black text-3xl font-bold">
                        Hayao Myiazaki
                    </span>
              </div>
              <br/>
              <div class="px-8 text-gray-600"> 
                 <p class="leading-relaxed text-left ">
                    Hayao Miyazaki est un animateur, réalisateur, producteur, scénariste, écrivain et mangaka japonais. 
                    Cofondateur du Studio Ghibli avec Isao Takahata, il obtient une renommée internationale grâce à son 
                    talent de conteur et ses films d'animation japonais. Il est considéré comme l'un des cinéastes les 
                    plus accomplis de l'histoire de l'animation. 
                 </p>
              </div>
          </div>
      </div>
    </div>
</template>

<script>
export default {
    name:"SideBar",
    css: [
        '~/css/main.css'
    ]
}
</script>