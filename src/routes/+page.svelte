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

            <div class="flex justify-center items-center pt-3 h-auto buttons text-2xl titlebar gap-10 mr-5">
                <a class="button titleButton visited:text-gray-300" href="#leaks">
                    Leaks
                </a>
                <a class="button titleButton visited:text-gray-300" href="#autons">
                    Autons
                </a>
                <a class="button titleButton visited:text-gray-300" href="#roster">
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
            <div class=" text-xl text-(--black) text-center font-[Arial_Nova] overflow-hidden h-7 bg-mauve-700">
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

        <div class="h-32"></div>






    </div>
</div>