grunt.initConfig({
    pure_grids: {
        dest : "build/public/css/main-grid.css",
        options: {
            units: 12, // 12-column grid
            mediaQueries: {
                sm: 'screen and (min-width: 35.5em)', // 568px
                md: 'screen and (min-width: 48em)',   // 768px
                lg: 'screen and (min-width: 64em)',   // 1024px
                xl: 'screen and (min-width: 80em)',   // 1280px
                xxl: 'screen and (min-width: 120em)',  // 1920px
                xxxl: 'screen and (min-width: 160em)',  // 2560px                                    
                x4k: 'screen and (min-width: 240em)'  // 3840px                                    
            }
        }
    }
});