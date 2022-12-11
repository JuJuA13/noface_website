<template>
    <section class="text-gray-600 body-font py-10">
        <h1 class="mb-4 text-4xl text-center font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl py-5"><span class="text-red-500">Sans Visage</span>, un personnage mystérieux</h1>

        <!--<h1 class="title-font text-center sm:text-4xl text-3xl mb-4 font-medium text-gray-900">Sans Visage, un personnage mystérieux</h1>-->
        <div class="container p-5 mx-auto">
            <div class="flex items-center lg:w-3/5 mx-auto pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
                <img class="inline" src="@/images/SV.png"/>
                <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0 px-9">
                    <!--<h2 class="text-gray-900 text-lg title-font font-medium mb-2">Shooting Stars</h2>-->
                    <p class="leading-relaxed text-justify text-base">Sans visage est sans doute un des personnages les plus intriguants 
                        du <span class="italic">Voyage de Chihiro</span>. Il apparaît sous la forme d'un esprit masqué, ce qui lui vaut ce nom. 
                        Ce personage est très complexe et on sait peu de choses sur lui malgré son nombre d'apparitions dans le 
                        film où on le découvre sous différentes formes.</p>
                </div>
            </div>
            <div class="flex items-center lg:w-3/5 mx-auto pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
                <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0 ">
                    <p class="leading-relaxed text-justify text-base"> Ce personnage mystique aurait la capacité de réagir aux émotions et 
                        d’ingérer d'autres individus afin d’acquérir leur apparence et leur voix. Il utilise d'ailleurs cette capacité
                        pour exprimer son appétit après avoir avalé un employé du bain, après quoi il engloutira tout ce qu'il trouve sur son passage.
                    </p>
                </div>
                <img class="inline h-48 w-96 px-9" src="@/images/SV_colere.png"/>
            </div>
            <div class="flex items-center lg:w-3/5 mx-auto pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
                <img class="inline" src="@/images/Sans-Visage_3.png" controls width="300%"/>
                <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0 px-9">
                    <!--<h2 class="text-gray-900 text-lg title-font font-medium mb-2">Shooting Stars</h2>-->
                    <p class="leading-relaxed text-justify text-base">
                        Il porte un masque de nô, un style de théâtre traditionnel japonais. Ce masque symbolise la dissimulation de soi 
                        et la confusion des identités. En effet, c'est ce masque qui le prive de visage et qui le rend si mystérieux et intriguant 
                        auprès du public. A l'inverse des autres personnages du film, Sans Visage du 
                        folklore japonais. Il est directement issu de l'imagination d'Hayao Myiazaki, le réalisateur du film.
                    </p>
                </div>
            </div>

            <div class="flex container lg:w-3/5 mx-auto pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
                <video class="flex flex-col mx-auto justify-center my-5" controls width="60%" autoplay="false" muted="false">
                    <source src="@/images/video1.mp4">
                </video>
            </div>
        </div>
        <div>
            <h2 class="mb-4 text-3xl text-center font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white">Qui est <span class="text-red-500 dark:text-blue-500">Sans Visage</span> ?</h2>
            <p class="text-lg text-center font-normal text-gray-600 lg:text-xl dark:text-gray-400">Le personnage ne semble pas influencer le cours de l'histoire, alors qui est-il et à quoi sert-il ?</p>
        </div>
        
        <div class="container p-5 mx-auto py-5">
            <div class="flex items-center lg:w-3/5 mx-auto pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
                <img class="inline" src="@/images/chihiro.png" controls width="250%"/>
                <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0 px-9">
                    <!--<h2 class="text-gray-900 text-lg title-font font-medium mb-2">Shooting Stars</h2>-->
                    <p class="leading-relaxed text-justify text-base">
                        On pourrait voir en ce personnage un simple spectateur ou témoin des aventures de Chihiro  
                        cependant, pour lui chihiro est la seule personne qui interagit avec lui et c'est peut-être la 
                        raison pour laquelle il décide de la suivre dans son voyage et de l'aider comme dans la scène du bain.
                    </p>
                </div>
            </div>
            <div class="flex items-center lg:w-3/5 mx-auto pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
                <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0 ">
                    <p class="leading-relaxed text-justify text-base"> 
                        Chihiro est la seule qui refuse son or, ce qui le frustre et lui fait perdre la raison. 
                        Il s'attaque alors au bain puis part à l'expédition chez Zeniba avec Chihiro, chez qui il trouvera à la fin la paix. 
                    </p>
                </div>
                <img class="inline h-48 w-96 px-9" src="@/images/or2.gif"/>
            </div>
            <div class="flex items-center text-justify lg:w-3/5 mx-auto pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
                Sans visage semble être l'alter ego de Miyazaki. Dans une conférence le producteur aurait affirmé cette  théorie. 
                En effet, Sans Visage représenterait Miyazaki qui assiste au film. Il n’est qu’un nom et un masque, 
                et à part ça, on ne sait pas vraiment ce qu’il pense ou ce qu’il veut faire. 
                Sa seule motivation est de suivre Chihiro dans son voyage, à l'image du public. 
                Miyazaki l'a simplement appelé le sans visage parce que son expression ne change jamais, c’est tout. 
            </div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'AccueilItem'
}
</script>