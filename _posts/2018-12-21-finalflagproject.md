---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of UK by Andre Lopez

## Describe your program

-   I designed this for the flag of the United Kingdom. I believe this project should get a four because it matched the exact same widths and lengths for the uk flag and it is completly done




## Current output



* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.

<!--- All the different definitions confused me but after ALOT of thinking I finally got them right. Also i needed help with getting the specific colors but i also found that out myself-->


## Explain your code.


-  I used put-image alot to put two images together. redstripe a,b,c, and d were the different red stripes and the same thing went for the white stripes. The only problem with the code that i have is that if you change the size than the flag will not change
   

* * *

```
(define uk  (put-image redstripe_1 300 150 (put-image redstripe_2 300 150 (put-image whitestripe_1 300 150 (put-image redstripe_3 480 250 (put-image redstripe_4 120 50 (put-image redstripe_5 525 50 (put-image redstripe_6 100 237 (put-image whitestripe_4 300 150 (put-image whitestripe_3 300 150 (put-image whitestripe_2 300 100  bluebackground)))))))))))

```

* * *

-   Everything in this section  of the code is just using put-image. What put-image does is put two images together on an overlay once you input a shape size and coordinates. This is the part of my program where I made sure that all teh stripes on the flag were aligned and in their right place.

 



## Program code

```(define size 300)
(define width 600)
(define height 300)
(define stripeheight (* height 2))
(define stripewidth (* height 0.22))
(define bluebackground (rectangle width height "solid" "navy"))
(define whitestripe_1 (rectangle stripeheight 100 "solid" "white"))
(define whitestripe_2 (rectangle 100 stripeheight "solid" "white"))
(define redstripe_1 (rectangle stripeheight stripewidth "solid" "crimson"))
(define redstripe_2 (rectangle stripewidth stripeheight "solid" "crimson"))
(define whitestripe_3 (rotate 27 (rectangle 700 60 "solid" "white")))
(define whitestripe_4 (rotate -27 (rectangle 700 60 "solid" "white")))
(define redstripe_3 (rotate -63 (rectangle 20 300 "solid" "crimson")))
(define redstripe_4 (rotate -63 (rectangle 20 300 "solid" "crimson")))
(define redstripe_5 (rotate 63 (rectangle 20 300 "solid" "crimson")))
(define redstripe_6 (rotate 63 (rectangle 20 300 "solid" "crimson")))

(define uk  (put-image redstripe_1 300 150 (put-image redstripe_2 300 150 (put-image whitestripe_1 300 150 (put-image redstripe_3 480 250 (put-image redstripe_4 120 50 (put-image redstripe_5 525 50 (put-image redstripe_6 100 237 (put-image whitestripe_4 300 150 (put-image whitestripe_3 300 150 (put-image whitestripe_2 300 100  bluebackground)))))))))))
```


