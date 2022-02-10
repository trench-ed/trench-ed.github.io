<img src="/assets/img/logo.png" width="200px" height="200px">

[Trench-ED](https://trench-ed.trenchproject.com/) is the education arm of the [Trench Project](https://www.trenchproject.com/), dedicated to thinking beyond air temperature to understand how organisms experience climate change.

### *TrEnCh*: Tools for TRanslating ENvironmental CHange into organismal responses

The material on the website is written to be easily accessible to advanced high schoolers, beginning undergraduates, and beyond. If you are an educator, we invite you to integrate TrEnCh-Ed into your classroom or homework activities in any way that works for you. Alignments between our content and Next Generation Science Standards is available in the teacher’s guide. 

Trench-ED consists of:
* overviews of climate change, physiology, elevational and latitudinal gradients and historical data
* data visualizations
* worksheets and answer keys for each visualization
* glossary of terms and teacher resources

Our data visualizations: 
* [Introduction to Graphs](https://huckley.shinyapps.io/Introduction-to-Graphs/) ([Repo](https://github.com/trenchproject/Introduction-to-Graphs))
* [Temperature Metabolism](https://insectphenology.ml/Climate-Change-Metabolism/) ([Repo](https://github.com/trenchproject/Climate-Change-Metabolism))
* [Energy Budgets](https://huckley.shinyapps.io/RShiny_ButterflyAdvanced/) ([Repo](https://github.com/trenchproject/RShiny_ButterflyAdvanced))
* [Robomussels](https://huckley.shinyapps.io/ClimateBiology/) ([Repo](https://github.com/trenchproject/RShiny_robomussels))
* [Butterfly Museum Specimens](https://huckley.shinyapps.io/butterflies/) ([Repo](https://github.com/trenchproject/butterflies))
* [Wildflower Phenology](https://huckley.shinyapps.io/PlantPhenology/) ([Repo](https://github.com/trenchproject/RShiny_PlantPhenology))
* [RMBL Phenology](https://huckley.shinyapps.io/RShiny_RMBL-phenology/) ([Repo](https://github.com/trenchproject/RShiny_RMBL-phenology))
* [Grasshopper Resurvey](https://huckley.shinyapps.io/grasshoppers/) ([Repo](https://github.com/HuckleyLab/RShinyGrasshopper))
* [Range Shifts](https://huckley.shinyapps.io/RShiny_RangeShifts/) ([Repo](https://github.com/trenchproject/RShiny_RangeShifts))

## For contributors
To create a new RShiny visualization, use this method:
* First, create a new repository in the trenchproject repository. Copy the basic contents of one of our other RShiny visualizations to get the basics and format set up.
* Create data visualization.
* On the google drive (in the Projects > Trench-ED > Visualizations folder), find the worksheet template. Use this template to create worksheets for your visualization.
* Once ready, publish through shinyapps.io. Use the lab login to host it on our shinyapps huckley account.
* Either by cloning this repository or by editing the page through the github website, add your visualization to the list of visualizations on [this](https://github.com/trench-ed/trench-ed.github.io/blob/master/_posts/2020-01-07-RShiny.md) page. By commiting these changes, the website will be updated.
* Finally, add links to your visualization and your repository to our list of visualizations on this README above.
* Done :)

Almost all of the data and pagees are hosted on shinyapps.io. For especially large files, we host on AWS. You can find more details on the AWS server [here](https://github.com/trenchproject/R-Docker-Server).
