Q1 Linear regression

(a) Yes. If the players have the same ELO rating, then the expected score for white is 0.56 (the intercept).
    Since this is bigger than 0.5, there is an advantage to playing with the white pieces.

(b) No. The p-value is 0.0782, which is bigger than alpha=0.05.

(c) Yes. R^2 is only 3.4%, so almost all variation in score appears to be due to chance.
    Of course there may be other factors influencing the score, that have not been included in the model.

(d) Expected score = 0.5586+1000*0.0005368 = 1.0954.
    This doesn't make any sense, since the maximum possible score is 1.
    

Q2 Logistic Regression

(a) If the value of ink increases, then (according to the model) the probability that the digit is a 1 decreases.

(b) This makes sense, since writing a 1 tends to consume less ink then writing a 0.

(c) z = 10.98 - 0.47*25 = -0.77
    P(t=0|ink=25) = 1/(1+exp(-0.77))=0.6835.

(d) if ink >= 23.362 then predict 0, otherwise predict 1.

Q3 SVMs

(a) 2 (row 4 and 5)

(b) 4-x1+x2=0

(c) y=4-8+5=1. Since y is positive, we predict class +1.

(d) 1/sqrt(2) = 0.707