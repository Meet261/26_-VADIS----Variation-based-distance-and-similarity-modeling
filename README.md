# 26_-VADIS----Variation-based-distance-and-similarity-modeling

https://mybinder.org/v2/gh/Meet261/26_-VADIS----Variation-based-distance-and-similarity-modeling/HEAD

Launch Online [![Binder](https://mybinder.org/badge_logo.svg)](https://notebooks.gesis.org/binder/v2/gh/Meet261/26_-VADIS----Variation-based-distance-and-similarity-modeling/HEAD)

| **Serial Number** | **File Name**                          | **Dependencies**                                                                                             | **Reproducibility Status** | **Issue/Obstacle**                                                                                                                                                                   |
|-------------------|----------------------------------------|--------------------------------------------------------------------------------------------------------------|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 26                | `VADIS_particles_InnerC-only.R` | `r-base=4.2`, `r-tidyverse`, `r-lme4`, `r-party`, `r-phangorn`, `r-car`, `r-devtools` | Not Reproducible           | The script fails because the `tidyverse` package cannot load due to a missing shared object (`libicui18n.so.58`). The missing library (`libicu`) is not available in the current conda channels. |


License: CC-By Attribution 4.0 International

This project uses data and resources from [VADIS -- Variation-based distance and similarity modeling](https://osf.io/3gfqn/). We acknowledge the contributions of the authors of the original project. Please refer to the [VADIS -- Variation-based distance and similarity modeling](https://osf.io/3gfqn/) for more details.
