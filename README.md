### Hi there 👋


I am a research assistant at the Universitätsklinik Innsbruck and have been a freelance statistician since 2006.

This Github page is a pure playground for me and the libraries presented are purely experimental.

If someone (hello Thomas :wink:) does not want to be prevented from installing the libraries, then please do so in this order. 


First step: install the following programs and leave all default settings.



1. GitHub
First create an account at https://github.com/
then install Git..
 https://git-scm.com/downloads 
2. R for Windows  https://cran.rstudio.com/
 R-base:  https://cran.rstudio.com/bin/windows/base/
3. RTools  https://cran.rstudio.com/bin/windows/Rtools/
4. RStudio Desktop
https://posit.co/download/rstudio-desktop/
5. Optionally install PSPP https://www.heise.de/download/product/pspp/download alternativer Link https://www.gnu.org/software/pspp/get.html
6. run the code below

```

if(!require(devtools)) install.packages("devtools")
if(!require(tidyverse)) install.packages("tidyverse")

if(!require(htmlTable)) install.packages("htmlTable")
if(!require(Hmisc)) install.packages("Hmisc")
if(!require(car)) install.packages("car")
if(!require(psych)) install.packages("psych")
if(!require(hwriter)) install.packages("hwriter")
if(!require(vcd)) install.packages("vcd")
# install.packages("installr")

# used by stp25-packages
install.packages(
  c('Formula', 'stringr','lazyeval',
    'lavaan', 'performance',
    'kableExtra', 'flextable', 'broom.mixed',
    'cowplot', 'effects',  'e1071',
    'WebPower', 'pwr',
    'parameters','bookdown', 'effectsize',
    'PlackettLuce',
    'epiR', 'multcomp', 'lmerTest', 'report', 'coin',
    'survival','survminer', 'qcc', 'lattice', 'latticeExtra','HH',
    'see', 'equatiomatic','komaletter',
    'meta',
    'caret', 'pscl', 'modelsummary','DescTools','labelled',
    'consort',
    'rockchalk'
    )
)

# statistical tables
devtools::install_github("stp4/stp25settings")
devtools::install_github("stp4/stp25tools")
devtools::install_github("stp4/stp25stat2")
devtools::install_github("stp4/stp25output2")

# Optional
devtools::install_github("stp4/stp25plot")
devtools::install_github("stp4/stp25data")
devtools::install_github("stp4/stp25Project")
devtools::install_github("stp4/stp25metcomp")
devtools::install_github("stp4/stp25kano")
devtools::install_github("stp4/stp25samplesize")
 
 
 # Optional markdown -> pdf Output
  install.packages("knitr")
  install.packages("rticles")
  install.packages("komaletter")
  remotes::install_github("datalorax/equatiomatic")


  install.packages("tinytex") 
  tinytex::install_tinytex()
  # tinytex::reinstall_tinytex()

 
# The libraries are optimised for a Windos system and I have only tested them there.
# On Linux or Mac, the paths in the source code must be adapted.

