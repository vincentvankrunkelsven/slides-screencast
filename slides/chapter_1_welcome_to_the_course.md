---
title: Welcome to the course
key: 92d179019a6d5934563c11dcf7fa6370
video_link: https://videos.datacamp.com/transcoded/1796_intro-stats-eda/v1/hls-ch0_0.master.m3u8

--- type:TitleSlide key:1a47dcefb2
## Welcome to the course


*** =lower_third
name: Vincent Vankrunkelsven
title: Instructor at DataCamp

*** =script
Welcome to this course about ,...


--- type:TwoColumns key:e6bd461cb6
## Two Columns, nice

*** =part1
One {{1}}

*** =part2
Three {{2}}

*** =script



--- type:TwoRowsTwoColumns key:c21d39a4ca
## Some interesting stuff

*** =part1
- This is {{1}}
- a bulleted {{1}}
- list {{2}}

*** =part2
This **is** some text with some _effects_ in it. ~~Nice~~. {{2}}

*** =part3
![](http://s3.amazonaws.com/assets.datacamp.com/production/course_3555/datasets/test_screenshot.png) {{3}}

*** =part4
$$\sum\_{i = 0}^{N}{\frac{i}{N}}$$ {{4}}

*** =script



--- type:FullSlide key:6a3aecb4aa
## Two rows

*** =part1

| id  |  gender | race  |  ... | socst |
|-----|---------|-------|------|-------|
| 70  | male    | white |  ... | 57    |
| 121 | female  | white |  ... | 61    |
| 86  | male    | white |  ... | 31    |
| ... | ...     | ...   |  ... | ...   |
| 137 | female  | white |  ... | 61    | {{1}}


*** =script



--- type:TwoColumns key:c2cc45f581
## Some code

*** =part1
```{r}
> summary(data)
## ...
> head(data)
# ...
``` {{1}}
```{r}
> ggplot(data, 
         aes=(x=time, y=credits))
   + geom_point()
# ...

``` {{2}}

```{r}
# Some calculations with dplyr
```{{3}}

*** =part2
- Explore your data {{1}}
- Visualize your data {{2}}
- Munge your data {{3}}

*** =script


