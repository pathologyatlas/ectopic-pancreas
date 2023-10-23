





```
r language ectopic-pancreas, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis midede ektopik pankreas TR, echo = (language == "TR")
## ectopic-pancreas - midede ektopik pankreas {#sec-ectopic-pancreas }
```


```
asis ectopic pancreas in stomach EN, echo = (language == "EN")
## ectopic-pancreas - ectopic pancreas in stomach {#sec-ectopic-pancreas }
```






```
r ectopic-pancreas screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/thumbnail_ectopic-pancreas-HE.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/ectopic-pancreas/HE.html",
  file = "./screenshots/thumbnail_ectopic-pancreas-HE.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/ectopic-pancreas/HE.html](https://images.patolojiatlasi.com/ectopic-pancreas/HE.html)





```
asis, echo = (language == "TR")

**midede ektopik pankreas**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/thumbnail_ectopic-pancreas-HE.png){width="25%"}](https://images.patolojiatlasi.com/ectopic-pancreas/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/ectopic-pancreas/HE.html)
```

```
asis, echo = (language == "EN")

**ectopic pancreas in stomach**

[![Click for Full Screen WSI](./screenshots/thumbnail_ectopic-pancreas-HE.png){width="25%"}](https://images.patolojiatlasi.com/ectopic-pancreas/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/ectopic-pancreas/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/ectopic-pancreas/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/ectopic-pancreas/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

midede ektopik pankreas

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

ectopic pancreas in stomach

:::

```









:::::

