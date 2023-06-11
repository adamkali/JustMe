<script lang="ts">
    import me from './me.png'
    import DiCode from 'svelte-icons/di/DiCode.svelte'
    import FaLongArrowAltRight from 'svelte-icons/fa/FaLongArrowAltRight.svelte'
    import FaCircle from 'svelte-icons/fa/FaCircle.svelte'
</script>

<main class="">
    <div class=" h-full flex flex-col rounded">
        <div class="flex flex-col items-center justify-center h-full my-4 mx-64 rounded-xl bg-black">
            <div class="w-full h-10 rounded-xl top-0 left-0 mx-4 flex flex-row items-center justify-left bg-slate-700">
                <div class="rounded-full h-4 mx-4 text-green-400"><FaCircle /></div>
                <div class="rounded-full h-4 mr-4 text-yellow-400"><FaCircle /></div>
                <div class="rounded-full h-4 mr-4 text-red-600"><FaCircle /></div>
            </div>
            <div class="flex flex-col h-full text-left overflow-y-auto p-4">
                <div class="flex flex-row p-2 text-2xl justify-start align-middle">
                    <span class="font-bold h-16 text-blue-600">adam</span>
                    <span class="font-bold h-16 text-purple-400">@</span>
                    <span class="font-bold h-16 text-blue-600 mr-2">kalinowski: ~</span>
                    <span class="font-bold h-16 text-cyan-300 mr-2">cat</span>
                    <span class="font-bold h-16 ">about.me</span>
                </div>
                <div class="flex flex-row mx-48 mb-4 text-2xl text-justify">
                    <span>
                        Hello there! I am a software engineer with a passion for building things. 
                        I have a strong background in web development, 
                        but I am always looking to learn new things. 
                        I work at eFileMadeEasy as a Full Stack Developer using C#, React and Python.
                        I also develop software in Go and Rust in my free time and I use svelte for my personal projects.
                        Like this website!
                    </span>
                </div>
                <div class="flex flex-row p-2 text-2xl justify-start align-middle">
                    <span class="font-bold h-16 text-blue-600">adam</span>
                    <span class="font-bold h-16 text-purple-400">@</span>
                    <span class="font-bold h-16 text-blue-600 mr-2">kalinowski: ~</span>
                    <span class="font-bold h-16 text-cyan-300 mr-2">cat</span>
                    <span class="font-bold h-16 ">MiraculousKingdom.gg</span>
                </div>
                <div class="flex flex-row mx-48 mb-4 text-2xl text-justify">
                    <span>
                        Right now I am working on a big project called
                        <a class="underline" href="https://github.com/adamkali/MiraculousKingdom">Miraculous Kingdom</a>.
                        It is a TTRPG written in Rust and Svelte. Right now it is in the early stages of development,
                        but on the 20th of June I am going to start advertising it and trying to get people to play a beta version.
                        I am streamind the development of it on twitch, so if you want to see how it is going, you can check it out here [to do]. If you want to contribute I am always happy to have more help, click the link and see the issues for more information.And thank you!
                    </span>
                </div>
                <div class="flex flex-row p-2 text-2xl justify-start align-middle">
                    <span class="font-bold h-16 text-blue-600">adam</span>
                    <span class="font-bold h-16 text-purple-400">@</span>
                    <span class="font-bold h-16 text-blue-600 mr-2">kalinowski: ~</span>
                    <span class="font-bold h-16 text-cyan-300 mr-2">cat</span>
                    <span class="font-bold h-16 ">./config/setup.dev</span>
                </div>
                <div class="flex flex-row mx-48 mb-4 text-2xl text-justify">
                    <span>
                        I use <span class="font-bold text-green-300">Neovim</span> as code editor. and really like it.
                        so if you want to see my config, you can check it out 
                        <a href="https://github.com/adamkali/LuaNeovimConfig/blob/main/README.md" class="text-blue-600 underline">here</a>.
                         There is docker and docker-compose, so I can run everything in containers. 
                        I also use wezterm as terminal emulator. You can find my 
                        <a href="https://github.com/adamkali/WeztermConfig" class="text-blue-600 underline">wezterm config here</a>.
                        Other than that there is not much to my setup.
                        All I want is a minimalistic setup that works.
                        And it does 😎
                        If you cant tell, I really like minimalism.
                    </span>
                </div>
                <div class="flex flex-row p-2 text-2xl justify-start align-middle">
                    <span class="font-bold h-16 text-blue-600">adam</span>
                    <span class="font-bold h-16 text-purple-400">@</span>
                    <span class="font-bold h-16 text-blue-600 mr-2">kalinowski: ~</span>
                    <span class="font-bold h-16 text-cyan-300 mr-2">cat</span>
                    <span class="font-bold h-16 ">./local/social/domains</span>
                </div>
                <div class="flex flex-row mx-48 mb-4 text-2xl text-justify">
                    <ul>
                        <li>
                            <a href="https://mastodon.social/@kaliwowski" class="text-blue-600 underline">Mastodon</a>
                        </li>
                        <li>
                            <a href="https://github.com/adamkali" class="text-blue-600 underline">Github</a>
                        </li>
                        <li>
                            <a href="https://www.linkedin.com/in/adam-kalinowski-a8209a1b1/" class="text-blue-600 underline">LinkedIn</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</main>

<style>
</style>
