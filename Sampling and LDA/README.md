# Sampling and LDA

## MH Sampling

## Gibbs Sampling

LDA Topic Model is a very good example and application for Gibbs Sampling. There is a good video on Youtube(https://www.youtube.com/watch?v=u7l5hhmdc0M), that gives me very explicit intuition on how Gibbs Sampling works on LDA. 

### Collapsed Gibbs Sampling
An important operation -1 -- Pretend we don't know the topic assignment of this word/ topic assignment of this document. 


### What role does Dirichlet distribution play 

I don't know if others have the same confusion as me, but when I 
Should Dirichlet distribution be used to generate the random topic assignment of each word? Or should . The answer is NO -- and the only sign that Dirichlet distribution ever exit is the parameter alpha and beta in the . Or we can say the setting of Dirichlet distribution as a prior (conjugate prior more specifically) determined the closed form function. 

Then what does Dirichlet distribution really work on in the LDA model. It's the time to talk about it's property as a "Generative Model".


(To be update -- 12/11/2019)
