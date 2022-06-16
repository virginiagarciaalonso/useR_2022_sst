# Retrieving and visualizing satellite sea water temperature data for marine analyses: a case study using the *rerddap* R package

Repository with the scripts and materials employed to create the poster mentioned above and a screen reader friendly slide presentation to be presented at useR! 2022.

Here you can find the final files:

-[Poster (english)](<https://github.com/virginiagarciaalonso/useR_2022_sst/blob/main/poster_en.pdf>)
-[Poster (spanish)](<>)
-[Slides (english)](<https://user-2022-sst-slides-en.netlify.app/>)
-[Slides (spanish)](<>)

The poster was created employing the `posterdown_betterport` template from the [*posterdown*](<https://github.com/brentthorne/posterdown>) package by Brent Thorne.

We strongly recommend checking [this blog](<https://rmendels.github.io/Using_rerddap.nb.html>) by Roy Mendelssohn and Scott Chamberlain on how to use *rerddap* to access data from ERDDAP servers from which we based our methodology to retrieve sea temperature data.

But, what is ERDDAP? As it is described in the  [*rerddap* repository](<https://github.com/ropensci/rerddap>), ERDDAP is a server built on top of OPenDAP, which serves some NOAA data. You can get gridded data ([griddap](<https://upwell.pfeg.noaa.gov/erddap/griddap/documentation.html>)), which lets you query from gridded datasets, or table data ([tabledap](<https://upwell.pfeg.noaa.gov/erddap/tabledap/documentation.html>)) which lets you query from tabular datasets.

In this poster we used the `jplMURSST41` gridded data set which is a Multiscale Ultrahigh Resolution (MUR) L4 analysis of a Group for High Resolution Sea Surface Temperature (GHRSST) sea surface temperature analysis produced at the JPL Physical Oceanography DAAC (PODAAC) in an optimal interpolation approach on a global 0.01 degree grid with temperature expressed in Celsius degrees (ÂºC). More information can be found at the [podaac dataset website](<https://podaac.jpl.nasa.gov/dataset/MUR-JPL-L4-GLOB-v4.1>)

In case you want to visualize other ERDDAP data sets you can check [this page](<https://coastwatch.pfeg.noaa.gov/erddap/griddap/index.html?page=1&itemsPerPage=1000>)