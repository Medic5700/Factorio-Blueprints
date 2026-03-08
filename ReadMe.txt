A collection of my Factorio Blueprints

Discription Code
    EX: [E2DsPnT0U01V00.00], [E#D#P#T#U##V##.##]

    E   -   Edition:
        0 = Factorio Early Access V0.__
        1 = Factorio V1.0
        2 = Factorio V2.0
    D   -   DLC
        s - Space Age (Note: Space Age DLC may be indicated in blueprints that don't need it because the blueprint was designed with Space Age enabled, and were not tested without Space Age)
    P   -   Planet Optimization
        a - Aquilo
        f - Fulgora
        g - Gleba
        n - Nauvis
        s - Space Platforms
        v - Vulcanus
    T   -   Estimated Technology Level
        0 = Bootstrap, no advanced technology
        1 = Pre-Space, have steel
        2 = Post-Space
        3 = Pre-Infinite Research
        4 = Post-Infinite Research
    U   -   Appoximate size of blueprint in terms of roboport diamiters. 
            Should be an intager, not a float.
    V   -   Blueprint Version Number. 
            Of form VXX.YY, where X is the major revision number, and Y is the minor revision number.
    '-' -   Not Applicable
    '_' -   Unknown

Generating Blueprint Images
    # Use a Discord bot from the Factorio Discord Server
    # Note can't use default command '/bp file ' because the surrounding boarder template doesn't scale to the blueprint size. IE: iff using massive blueprint, the boarder reaches max size, and therefor scales down the image for the blueprint to fit in the boarder, making the image pixalated and blury.
    Factorio Discord Server -> 'Help' group channel -> '# bot-stuff'
        use '/blueprint custom file: show-background:true show-alt-mode:true show-grid-numbers:true' to upload a 'blueprint text file' to the bot
        Note: 'file' must go before options, otherwise options seem to be ignored
	Note: '/bp file' shows a fancy boarder with more information about the blueprint (materials needed, name of blueprint, etc), BUT the zoomlevel can't be adjusted at all

Factorio Blueprint (Stylized) Visualizer
    #TODO to evaluate
    https://piebro.github.io/factorio-blueprint-visualizer/
