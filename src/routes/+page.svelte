<script>
    const links = [
        {
            name: "YouTube",
            url: "https://www.youtube.com/smoljames",
            icon: "fa-brands fa-youtube",
        },
        {
            name: "Learn to code · Roadmap",
            url: "https://github.com/jamezmca/learn-to-code",
            icon: "fa-solid fa-signs-post",
        },
        {
            name: "Discord",
            url: "https://discord.gg/BYr6gujs4k",
            icon: "fa-brands fa-discord",
        },
        {
            name: "Newsletter",
            url: "https://smoljames.beehiiv.com/subscribe",
            icon: "fa-regular fa-newspaper",
        },
        {
            name: "Twitter",
            url: "https://twitter.com/_Smoljames",
            icon: "fa-brands fa-twitter",
        },
        {
            name: "LinkedIn",
            url: "https://www.linkedin.com/in/jamezmcarthur/",
            icon: "fa-brands fa-linkedin",
        },
        {
            name: "GitHub",
            url: "https://github.com/jamezmca",
            icon: "fa-brands fa-github",
        },
        {
            name: "Study Notes",
            url: "https://github.com/jamezmca/learn-to-code/tree/main/course%20notes",
            icon: "fa-solid fa-book",
        },
        // {
        //     name: "Spiccy Site",
        //     url: "https://github.com/jamezmca/learn-to-code/tree/main/course%20notes",
        //     icon: "fa-solid fa-book",
        // },
    ];
</script>

<main
    class="flex flex-col gap-6 items-center justify-center w-full px-4 flex-1 relative py-10 sm:py-14 md:py-20"
>
    <img
        class="w-full max-w-[90px] sm:max-w-[100px] mx-auto"
        src="smoljames_logo_2.png"
        alt="logo"
    />
    <p
        class="text-base sm:text-lg md:text-xl font-medium text-green-300 bg-slate-950 rounded-xl border-2 border-solid border-[#080E34] px-2 py-1"
    >
    ✦ Smoljames ✦
    </p>

    <ul class="flex flex-col gap-4 md:gap-5 w-full">
        {#each links as link}
            <a
                href={link.url}
                target="_blank"
                class="px-4 py-2 sm:px-6 sm:py-3 md:px-8 md:py-3 rounded-lg text-center w-full mx-auto max-w-[540px] relative group flex items-center justify-center relative bg-[#080E34] border-[2px] border-solid border-[#020617] specialShadow text-green-300"
            >
                <!-- <div
                    class={"absolute inset-0 blueBorder duration-500 rounded-md "}
                />

                <div
                    class={"absolute -inset-2 blur-xl blueBorder duration-500 rounded-md opacity-20 "}
                />
                <div
                    class="bg-slate-900 hover:bg-transparent hover:text-white px-4 text-base sm:text-lg py-3 z-1 duration-200 relative rounded-md flex items-center gap-4"
                >
                    <p class="text-base sm:text-lg ">smoljames</p>
                </div> -->
                <p>{link.name}</p>
                <i
                    class={link.icon +
                        " text-lg sm:text-xl absolute left-2 sm:left-3 md:left-4 top-1/2 -translate-y-1/2"}
                />
            </a>
        {/each}
    </ul>
    <a href="mailto:jamesismathematicool@gmail.com" class="-mt-2 sm:-mt-1"
        ><i
            class="fa-regular fa-envelope text-2xl md:text-3xl text-green-300 hover:text-white duration-200"
        ></i></a
    >
</main>

<svelte:head>
    <script type="text/javascript">
        (function (c, l, a, r, i, t, y) {
            c[a] =
                c[a] ||
                function () {
                    (c[a].q = c[a].q || []).push(arguments);
                };
            t = l.createElement(r);
            t.async = 1;
            t.src = "https://www.clarity.ms/tag/" + i;
            y = l.getElementsByTagName(r)[0];
            y.parentNode.insertBefore(t, y);
        })(window, document, "clarity", "script", "htf56frmd5");
    </script>
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <!-- Google tag (gtag.js) -->
    <script
        async
        src="https://www.googletagmanager.com/gtag/js?id=G-ZJGT8ESSY1"
    ></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag() {
            dataLayer.push(arguments);
        }
        gtag("js", new Date());

        gtag("config", "G-ZJGT8ESSY1");
    </script>
    <title>Smoljames</title>
    <!-- <meta name="robots" content="noindex nofollow" /> -->
    <meta
        name="description"
        content="I self-taught programming and landed a developer job FOR FREE, and you can too! With Smoljames, you can learn to code with the highest quality learning resources (totally free), and land a developer job ASAP."
    />
    <meta name="viewport" content="width=device-width" />
</svelte:head>
