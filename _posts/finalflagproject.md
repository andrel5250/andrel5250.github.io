---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of UK by Andre Lopez

## Describe your program

-   What country did you design for? _then delete this instruction_
-   What grade do you expect? _then delete this instruction_

<!--- Delete this comment and add your writing -->

## Current output

-   Insert an image that your program currently produces. _then delete this instruction_

* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.

-   What questions, strategies, help from peers or teacher, or thinking got you to this point? _then delete this instruction_

<!--- Delete this comment and add your writing -->


## Explain your code.


-  I used put-image alot to put two images together. redstripe a,b,c, and d were the different red stripes and the same thing went for the white stripes. The only problem with the code that i have is that if you change the size than the flag will not change
   

* * *

```
(define uk  (put-image redstripe_1 300 150 (put-image redstripe_2 300 150 (put-image whitestripe_1 300 150 (put-image redstripe_3 480 250 (put-image redstripe_4 120 50 (put-image redstripe_5 525 50 (put-image redstripe_6 100 237 (put-image whitestripe_4 300 150 (put-image whitestripe_3 300 150 (put-image whitestripe_2 300 100  bluebackground)))))))))))

```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 



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


