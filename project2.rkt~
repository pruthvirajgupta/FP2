#lang racket

(require plot)
(plot3d (contour-intervals3d (λ (x y) (+ (sqr x) (sqr y)))
                               -1.1 1.1 -1.1 1.1
                               #:label "z = x^2 + y^2"))
