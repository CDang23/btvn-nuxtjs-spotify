<template>
        <div class=" w-auto h-auto mx-4 sm:mx-[345px] pb-16 shadow-md">
                <header class="mx-24 pt-6 ">
                        <!--Nav begin-->
                        <div class="flex justify-between mb-16 ">
                                <div></div>
                                <nav class="sm:block hidden">
                                        <ul
                                                class="leading-10  border-[1px] flex justify-center font-sans text-sm gap-8 rounded-full px-6 cursor-pointer">
                                                <li class="hover:text-green-400"><nuxt-link :to="'/about'">About</nuxt-link>
                                                </li>
                                                <li class="hover:text-green-400"><nuxt-link
                                                                :to="'articles'">Articles</nuxt-link></li>
                                                <li class="hover:text-green-400"><nuxt-link
                                                                :to="'projects'">Projects</nuxt-link></li>
                                                <li class="hover:text-green-400"><nuxt-link
                                                                :to="'speaking'">Speaking</nuxt-link></li>
                                                <li class="hover:text-green-400"><nuxt-link :to="'uses'">Uses</nuxt-link></li>
                                        </ul>
                                </nav>
                                <button class="w-12 h-10 border-[1px] text-xl leading-9 flex justify-center rounded-full text-green-400">
                                        <div>
                                                <Icon name="ph:sun" width="24" height="24" />
                                        </div>
                                </button>
                        </div>
                        <!--Nav end-->

                        <!--Header content begin-->
                        <div>

                                <a href="#"><img class="h-16 w-16 rounded-full"
                                                src="https://spotlight.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Favatar.51a13c67.jpg&w=64&q=75"
                                                alt="ava"></a>
                                <div class="pt-6"></div>
                                <div class="max-w-2xl">
                                        <h1 class="text-4xl font-bold tracking-tight sm:text-5xl ">Software designer, founder,
                                                and amateur
                                                astronaut.</h1>
                                        <p class="mt-6 text-base text-zinc-600">I’m Spencer, a software designer and
                                                entrepreneur based in New York City. I’m the founder and CEO of Planetaria,
                                                where we develop
                                                technologies that empower regular people to explore space on their own terms.
                                        </p>
                                        <div class="mt-6">
                                                <ul class="flex gap-6 text-lg text-zinc-600">
                                                        <li><nuxt-link :to="'https://twitter.com'">
                                                                        <Icon name="mdi:twitter" width="24" height="24" />
                                                                </nuxt-link></li>
                                                        <li><nuxt-link :to="'https://instagram.com'">
                                                                        <Icon name="mdi:instagram" width="24" height="24" />
                                                                </nuxt-link></li>
                                                        <li><nuxt-link :to="'https://github.com'">
                                                                        <Icon name="mdi:github" width="24" height="24" />
                                                                </nuxt-link></li>
                                                        <li><nuxt-link :to="''">
                                                                        <Icon name="mdi:linkedin" width="24" height="24" />
                                                                </nuxt-link></li>
                                                </ul>
                                        </div>
                                </div>

                        </div>
                        <!--Header content End-->
                </header>
        </div>
</template>


