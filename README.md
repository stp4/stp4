### Hi there 👋


I am a research assistant at the Universitätsklinik Innsbruck and have been a freelance statistician since 2006.

This Github page is a pure playground for me and the libraries presented are purely experimental.

If someone (hello Viki :wink:) does not want to be prevented from installing the libraries, then please do so in this order. 

````r

-    Iinstall the latest version from
[GitHub](https://github.com/stp4) as follow:

if(!require(devtools)) install.packages("devtools")
if(!require(tidyverse)) install.packages("tidyverse")
if(!require(fs)) install.packages("fs")
if(!require(gridExtra)) install.packages("gridExtra")
if(!require(checkmate)) install.packages("checkmate")
if(!require(viridis)) install.packages("viridis")
 
if(!require(htmlTable)) install.packages("htmlTable")
if(!require(Hmisc)) install.packages("Hmisc")
if(!require(car)) install.packages("car")
if(!require(haven)) install.packages("haven")


# statistical tables
devtools::install_github("stp4/stp25settings")
devtools::install_github("stp4/stp25tools")
devtools::install_github("stp4/stp25stat2")

devtools::install_github("stp4/stp25output2")

# Optional
devtools::install_github("stp4/stp25plot")
devtools::install_github("stp4/stp25data")


install.packages(
c(
'Hmisc', 'car', 'knitr', 'Formula', 'stringr', 'tinytex',
'R2HTML', 'kableExtra', 'flextable', 'broom.mixed',
'cowplot', 'effects', 'lazyeval', 'vcd', 'e1071',
'hwriter','pander','WebPower', 'pwr', 'psych',
'ggpubr', 'parameters','bookdown', 'effectsize',
'dtrackr' , 'consort', 'ggplotify', 'patchwork', 'GGally', 'PlackettLuce',
'epiR', 'multcomp','betareg', 'equatiomatic', 'lmerTest', 'report', 'coin',
'survival','survminer', 'qcc', 'heplots', 'lattice', 'latticeExtra','HH',
'rockchalk','see','equatiomatic','komaletter')
)

```



 
The libraries are optimised for a Windos system and I have only tested them there. On Linux or Mac, the paths in the source code must be adapted.

<!--
**stp4/stp4** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
