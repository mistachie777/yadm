options(repos=structure(c(CRAN="http://cran.rstudio.com/")))
# Lines added by the Vim-R-plugin command :RpluginConfig (2014-Oct-14 16:27):
if(interactive()){
    options(colorout.verbose = 1,
            nvimcom.verbose = 1,
            help_type = "text",
            editor='nvim',
            width = 200,
            menu.graphics = FALSE,
            save.defaults = list(compress = FALSE),
            prompt = " ",
            radian.prompt = " ",
            radian.color_scheme = "colorful")


    library(nvimcom)
    library(pacman)

    #library(unixtools)
    #set.tempdir("~/Rtmp")

     #syntax highlighting
    library(colorout)
    if (!Sys.getenv('TERM') %in% c('', 'linux'))
        setOutputColors256(
        normal = 145,
        number = 12,
        negnum = 9,
        string = 10,
        const = 13,
        stderror = 120,
        error = c(1, 0, 1),
        warn = 5,
        verbose=FALSE
    )
}

.bc = function() {
    print('Sourcing http://bioconductor.org/biocLite.R')
    source("http://bioconductor.org/biocLite.R")
}
