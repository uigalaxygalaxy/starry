<script>
    import Subheading from './subheading.svelte';
    import Image from './image.svelte';
</script>

<div class="bg-mauve-800 text-white min-h-screen font-[Arial_Nova] text-xl ">
    <div class="fixed bg-mauve-800 z-10  ">
        <div class="fixed flex justify-between w-full bg-mauve-800 pt-3  z-20 pb-3 hudFlex ">
            <div class="flex titlebar text-4xl ml-5 ">
                45434<span>Y</span>
                <span class="absolute italic ml-10 pt-4"
                    style="-webkit-text-stroke: 4px black; paint-order: stroke fill; ">Starry
                    <span style="-webkit-text-stroke: 0px black; "
                        class="bg-linear-135 not-italic to-pink-400 from-mauve-300 bg-clip-text text-transparent -ml-12.5 -z-1 -top-3 relative text-5xl">⭐</span></span>
            </div>

            <div class="flex justify-center button items-center pt-3 h-auto buttons text-2xl titlebar gap-10 mr-5">
<a aria-label="Instagram Icon" href="https://www.instagram.com/45434Y" target="_blank" rel="noopener noreferrer">
                <svg xmlns="http://www.w3.org/2000/svg" width="36" height="36" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="bi bi-instagram instagram transition duration-200 cubic-bezier(.11, 1.22, .91, 1.18)" viewBox="0 0 16 16">
  <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.9 3.9 0 0 0-1.417.923A3.9 3.9 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.9 3.9 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.9 3.9 0 0 0-.923-1.417A3.9 3.9 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599s.453.546.598.92c.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.5 2.5 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.5 2.5 0 0 1-.92-.598 2.5 2.5 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233s.008-2.388.046-3.231c.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92s.546-.453.92-.598c.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92m-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217m0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334"/>
</svg>
</a>
                <a class="button titleButton visited:text-white" href="#leaks">
                    Leaks
                </a>
                <a class="button titleButton visited:text-white" href="#autons">
                    Autons
                </a>
                <a class="button titleButton visited:text-white" href="#roster">
                    Competition Roster
                </a>

            </div>


        </div>
        <div class="mt-19 fixed inset-x-0 w-full z-0 ">
            <div class="absolute font-[Arial_Nova] text-3xl newsText w-fit -translate-y-1 opacity-70 mix-blend-overlay">
                Testimonies
            </div>
            <div
                class="opacity-70 text-right right-0 absolute font-[Arial_Nova] text-3xl newsTextFlip w-fit -translate-y-1  mix-blend-overlay">
                Testimonies
            </div>
            <div
                class=" text-xl text-(--black) text-center font-[Arial_Nova] overflow-hidden h-7 bg-mauve-700 text-nowrap">
                <div class="newsBox ">
                    "Starry is so awsum and amazzing" - Mamdani <br>
                    "Starry sure was trouble" - Dean Withers <br>
                    "I will make you my [Programmer], and you will love it. You will [happily want] to [program for me]
                    " -
                    GitHub
                    Copilot <br>
                    "..." - Clarinet in West Carrolton Trash Can <br>
                    "I love Starry" - Robin Callaway <br>
                    "I do not fabricate quotes" - 45434M Meldown
                </div>
            </div>
        </div>
    </div>
    <div class="ml-2">
        <div class="h-36"></div>

        <div class="textGlow">
            Hello! We are a 3 person robotics team from Beavercreek, Ohio!
        </div>

        <Subheading id="leaks" text="Leaks" />

        <Image link="robot.PNG" text="robot drive train" />

        <Subheading id="autons" text="Our autos" />

        <Image link="d1d1.PNG" text="props.text ❤💞💖" />

        <Subheading id="stats not using this" text="Stats" />

        <div class="mt-4 flex w-full align-center justify-center">

            <!-- copy this div with w-120 -->
            <div class="w-120 border-mauve-500 border-2 rounded-lg p-2 flex flex-col gap-2">
                <div class="text-center">
                    45434Y 8/11/2026 <br>
                </div>
                <div class="vexShowWrapper">
                    <!-- No Awards
                    <div class="vexBrick">
                        <p class="vexBrickText">EXCELLENCE</p>
                        <p class="vexBrickTextStroke">EXCELLENCE</p>

                        <p class="vexLocation">Washington Court House</p>

                    </div>
-->
                </div>

                <div class="vexNonImportant mb-4">
                    No Awards Yet
                    <!--
                    Judges x2 - <span class="vexNonPlaces">North Union, King of the Hill</span> <br>
                    Think - <span class="vexNonPlaces">Southwest Oaks</span>
                    -->
                </div>


                <div class="vexQualWrapper">
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">STATES</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">WORLDS</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                </div>
            </div>


        </div>



        <Subheading id="roster" text="Upcoming Comps" />

        <div class="mt-4 flex w-full align-center justify-center">

            <!-- copy this div with w-120 -->
            <div class="w-120 border-mauve-500 border-2 rounded-lg p-2 flex flex-col gap-2">
                <div class="text-center">
                    NORTH UNION <br><span class="italic text-lg opacity-50 -mt-1 block">Oct 24, 2026</span>
                </div>
                <div class="vexShowWrapper">
                    <!-- No Awards
                    <div class="vexBrick">
                        <p class="vexBrickText">EXCELLENCE</p>
                        <p class="vexBrickTextStroke">EXCELLENCE</p>

                        <p class="vexLocation">Washington Court House</p>

                    </div>
-->
                </div>
                <!--
                <div class="vexNonImportant mb-4">
                    
                    Judges x2 - <span class="vexNonPlaces">North Union, King of the Hill</span> <br>
                    Think - <span class="vexNonPlaces">Southwest Oaks</span>
                    
                </div> -->

                <!--
                <div class="vexQualWrapper">
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">STATES</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">WORLDS</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                </div>
                -->
            </div>




        </div>

        <div class="mt-4 flex w-full align-center justify-center">

            <!-- copy this div with w-120 -->
            <div class="w-120 border-mauve-500 border-2 rounded-lg p-2 flex flex-col gap-2">
                <div class="text-center">
                    LAUNCH <br><span class="italic text-lg opacity-50 -mt-1 block">~Nov 2, 2026</span>
                </div>
                <div class="vexShowWrapper">
                    <!-- No Awards
                    <div class="vexBrick">
                        <p class="vexBrickText">EXCELLENCE</p>
                        <p class="vexBrickTextStroke">EXCELLENCE</p>

                        <p class="vexLocation">Washington Court House</p>

                    </div>
-->
                </div>
                <!--
                <div class="vexNonImportant mb-4">
                    
                    Judges x2 - <span class="vexNonPlaces">North Union, King of the Hill</span> <br>
                    Think - <span class="vexNonPlaces">Southwest Oaks</span>
                    
                </div> -->

                <!--
                <div class="vexQualWrapper">
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">STATES</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">WORLDS</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                </div>
                -->
            </div>




        </div>

        <div class="mt-4 flex w-full align-center justify-center">

            <!-- copy this div with w-120 -->
            <div class="w-120 border-mauve-500 border-2 rounded-lg p-2 flex flex-col gap-2">
                <div class="text-center">
                    KING OF THE HILL <br><span class="italic text-lg opacity-50 -mt-1 block">Nov 14, 2026</span>
                </div>
                <div class="vexShowWrapper">
                    <!-- No Awards
                    <div class="vexBrick">
                        <p class="vexBrickText">EXCELLENCE</p>
                        <p class="vexBrickTextStroke">EXCELLENCE</p>

                        <p class="vexLocation">Washington Court House</p>

                    </div>
-->
                </div>
                <!--
                <div class="vexNonImportant mb-4">
                    
                    Judges x2 - <span class="vexNonPlaces">North Union, King of the Hill</span> <br>
                    Think - <span class="vexNonPlaces">Southwest Oaks</span>
                    
                </div> -->

                <!--
                <div class="vexQualWrapper">
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">STATES</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">WORLDS</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                </div>
                -->
            </div>




        </div>

        <div class="mt-4 flex w-full align-center justify-center">

            <!-- copy this div with w-120 -->
            <div class="w-120 border-mauve-500 border-2 rounded-lg p-2 flex flex-col gap-2">
                <div class="text-center">
                    PICKTOWN THROWDOWN <br><span class="italic text-lg opacity-50 -mt-1 block">~Jan 9, 2026</span>
                </div>
                <div class="vexShowWrapper">
                    <!-- No Awards
                    <div class="vexBrick">
                        <p class="vexBrickText">EXCELLENCE</p>
                        <p class="vexBrickTextStroke">EXCELLENCE</p>

                        <p class="vexLocation">Washington Court House</p>

                    </div>
-->
                </div>
                <!--
                <div class="vexNonImportant mb-4">
                    
                    Judges x2 - <span class="vexNonPlaces">North Union, King of the Hill</span> <br>
                    Think - <span class="vexNonPlaces">Southwest Oaks</span>
                    
                </div> -->

                <!--
                <div class="vexQualWrapper">
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">STATES</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">WORLDS</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                </div>
                -->
            </div>




        </div>

        <div class="mt-4 flex w-full align-center justify-center">

            <!-- copy this div with w-120 -->
            <div class="w-120 border-mauve-500 border-2 rounded-lg p-2 flex flex-col gap-2">
                <div class="text-center">
                    KALAHARI <br><span class="italic text-lg opacity-50 -mt-1 block">Jan 22, 2026</span>
                </div>
                <div class="vexShowWrapper">
                    <!-- No Awards
                    <div class="vexBrick">
                        <p class="vexBrickText">EXCELLENCE</p>
                        <p class="vexBrickTextStroke">EXCELLENCE</p>

                        <p class="vexLocation">Washington Court House</p>

                    </div>
-->
                </div>
                <!--
                <div class="vexNonImportant mb-4">
                    
                    Judges x2 - <span class="vexNonPlaces">North Union, King of the Hill</span> <br>
                    Think - <span class="vexNonPlaces">Southwest Oaks</span>
                    
                </div> -->

                <!--
                <div class="vexQualWrapper">
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">STATES</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">WORLDS</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                </div>
                -->
            </div>




        </div>

        <!--
        <Subheading id="results asd im not using this" text="Results" />
-->



        <div class="mt-4 flex w-full align-center justify-center">
            <!-- copy this div with w-120 -->
            <!--
          
            <div class="w-120 border-mauve-500 border-2 rounded-lg p-2 flex flex-col gap-2">
                <div class="text-center">
                    12/16/2026 <br>
                </div>
                <div class="vexShowWrapper">
                    <div class="vexBrick">
                        <p class="vexBrickText">EXCELLENCE</p>
                        <p class="vexBrickTextStroke">EXCELLENCE</p>

                        <p class="vexLocation">Washington Court House</p>

                    </div>

                </div>

                <div class="vexNonImportant mb-4">
                    Judges x2 - <span class="vexNonPlaces">North Union, King of the Hill</span> <br>
                    Think - <span class="vexNonPlaces">Southwest Oaks</span>
                </div>


                <div class="vexQualWrapper">
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">STATES</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                    <div class="vexQualBoxNot">
                        <p class="vexQualType">WORLDS</p>
                        <p class="vexQualled">Not Qualified</p>
                    </div>
                </div>
            </div>

            -->
        </div>

        <div class="text-center flex-row mt-6">
            <div>Beavercreek Robotics Club</div>
            <a class="text-center text-(--primary) underline hover:text-pink-200" href="https://uigalaxy.net"
                target="_blank" rel="noopener noreferrer">Made
                by uiGalaxy @ uigalaxy.net</a>
        </div>

        <div class="flex justify-center items-center mt-4 button">

            <a aria-label="Instagram Icon" href="https://www.instagram.com/45434Y" target="_blank" rel="noopener noreferrer">
                <svg xmlns="http://www.w3.org/2000/svg" width="36" height="36" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="bi bi-instagram instagram transition duration-200 cubic-bezier(.11, 1.22, .91, 1.18)" viewBox="0 0 16 16">
  <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.9 3.9 0 0 0-1.417.923A3.9 3.9 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.9 3.9 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.9 3.9 0 0 0-.923-1.417A3.9 3.9 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599s.453.546.598.92c.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.5 2.5 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.5 2.5 0 0 1-.92-.598 2.5 2.5 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233s.008-2.388.046-3.231c.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92s.546-.453.92-.598c.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92m-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217m0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334"/>
</svg>
</a>

        </div>








    </div>
</div>