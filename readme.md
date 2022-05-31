# assignment 0: Markdown
## you have to write markdown
### some math equation
<p align="center">First equation: Y=X&beta;+&epsilon;<sub>y</sub> ,&forall;X<br>
Second equation: X=Z&gamma;+&epsilon;<sub>x</sub> <br>

$$f_1(\omega) =  \frac{\sigma^2}{2\pi},\omega\in[-\pi,\pi]$$
</p>

1. First item\
    a. first sub-item\
    A) first sub-sub-item\
    b. second sub-item
2. Second item
3. Third item\
    a. second sub item
4. Fourth Item

* First Item
* Second Item
    * first sub-item
        * first sub-sub-item
    * second sub-item

![picture](https://scontent-ecv1-1.xx.fbcdn.net/v/t1.18169-9/395832_307220585995588_301406571_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=19026a&_nc_eui2=AeHWWlTQvs-bea0UPhbealH--R-0OmFK6y75H7Q6YUrrLnhWRXjDO5eOwau6DS8dpORxgVfe4C7UJEmVFAxS2tdA&_nc_ohc=p1I0gziW8CsAX9E5fyr&_nc_ht=scontent-ecv1-1.xx&oh=00_AT_fSlWiNm5eVqjXhMQnI2KDlsigFfF3zk93Af1mvqvU1g&oe=62B9DC7C)

```
library(tidyverse)
library(mdsr)
SAT_2010 %>% ggplot(aes(write,..density..)) + geom_histogram() +
geom_density() + theme_minimal() + labs(title = "SAT Writing Scores")
```
# Table with alignment
<p>You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.</p>

|**Syntax**        | **Description**   |**Test Text**|
| ------------- |:-------------:| -----: |
| Header      | Title | Here's this  |
| Paragraph      | Text      |   And more |
# Instructions

6.S191 software labs are designed to be completed at your own pace. At the end of each
of the labs, there will be instructions on how you can submit your notebook for grade.
Additionally, if you would like to submit your lab as part of the 6.S191 lab competitions,
instructions regarding what information must be submitted is also provided at the end of
each lab.

## License
All code in this repository is copyright 2022 [MIT 6.S191 Introduction to Deep Learning.](http://introtodeeplearning.com/) All
Rights Reserved.\

Licensed under the MIT License. You may not use this file except in compliance with the
License. Use and/or modification of this code outside of 6.S191 must reference:
>© MIT 6.S191: Introduction to Deep Learning\
>http://introtodeeplearning.com