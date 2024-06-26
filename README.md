### Hi there 👋


I am a research assistant at the Universitätsklinik Innsbruck and have been a freelance statistician since 2006.

This Github page is a pure playground for me and the libraries presented are purely experimental.

If someone  does not want to be prevented from installing the libraries, then please do so in this order. 
<!-- (hello Thomas :wink:) -->

```

if(!require(devtools)) install.packages("devtools")
if(!require(tidyverse)) install.packages("tidyverse")
 
 
if(!require(htmlTable)) install.packages("htmlTable")
if(!require(Hmisc)) install.packages("Hmisc")
if(!require(car)) install.packages("car")
if(!require(psych)) install.packages("psych")


# statistical tables
devtools::install_github("stp4/stp25settings")
devtools::install_github("stp4/stp25tools")
devtools::install_github("stp4/stp25stat2")

devtools::install_github("stp4/stp25output2")

# Optional
devtools::install_github("stp4/stp25plot")
devtools::install_github("stp4/stp25data")



#  if(!require(hwriter)) install.packages("hwriter")
# devtools::install_github("stp4/stp25Project")
#  if(!require(vcd)) install.packages("vcd")
# devtools::install_github("stp4/stp25metcomp")
# devtools::install_github("stp4/stp25kano")
# devtools::install_github("stp4/stp25samplesize")


# Optional
install.packages(
  c(
 'lavaan',  'performance', 
    'kableExtra', 'flextable', 'broom.mixed',
    'cowplot', 'effects', 'vcd', 'e1071',
   # 'hwriter',
   # 'pander',
   'WebPower', 'pwr',  
    'parameters','bookdown', 'effectsize',
    'PlackettLuce',
    'epiR', 'multcomp',  'lmerTest', 'report', 'coin',
    'survival','survminer', 'qcc',   'lattice', 'latticeExtra','HH',
   'see', 'equatiomatic','komaletter')
)
```

The libraries are optimised for a Windos system and I have only tested them there. On Linux or Mac, the paths in the source code must be adapted.

