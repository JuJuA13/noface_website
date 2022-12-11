<template>
    <section>
        <footer class="footer py-10 px-60  bg-base-200 text-base-content">
            <div class="grid grid-rows-1 grid-flow-col border-t-2  border-gray-200 py-5 gap-5">
                <a class="fill-current">
                    <img alt="profil" src="@/images/Hayao.jpg" class="avatar w-24 rounded-full" />
                </a>
                <div class="px-8 text-gray-600"> 
                    <p class="leading-relaxed text-justify ">
                    Hayao Miyazaki est un animateur, réalisateur, producteur, scénariste, écrivain et mangaka japonais. 
                    Cofondateur du Studio Ghibli avec Isao Takahata, il obtient une renommée internationale grâce à son 
                    talent de conteur et ses films d'animation japonais. Il est considéré comme l'un des cinéastes les 
                    plus accomplis de l'histoire de l'animation. 
                    </p>
                </div>
            </div> 
        </footer>
        <div class="bg-gray-100">
            <div class="container mx-auto py-4 px-5 flex flex-wrap flex-col sm:flex-row">
                <p class="text-gray-500 text-sm text-center sm:text-left">© 2022 Thibaut Ayoubi
                </p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'BioItem'
}
</script>