# deeprl-project

## Deadlines

4/11: fixed Tx/Rx
4/17: one page description due at beginning of class
5/8: 5-8 page report


## 4/4/17:

look at apsk, bpsk, qpsk, 16-quam
do we want to whether we want to paramaterize output of transmitter as cartesian or polar?

fixed Tx, learn Rx:
⋅⋅⋅input x,y of complex, softmax output + eps greedy / boltzman exploration


tasks:
1. reward shaping for transmitter (need to restrict power and maximize distance between points. former must be stronger than latter to prevent outer points from flying away)

1st: Tx -> Rx and Rx gives reward back to Tx. Rx provides k-nn guess for each datasample back to Tx
2nd: Tx on both sides, Rx on both sides. 
3rd: OpenAI style

![Alt text](https://c1.staticflickr.com/3/2929/33290540844_2afbbcd75d_b.jpg )



## Reports
### CS294-121: 
[https://www.sharelatex.com/project/58eedf885eecccdc7a8817a8](https://www.sharelatex.com/project/58eedf885eecccdc7a8817a8)
### CS294-133:
[https://www.sharelatex.com/project/58bf4907d9f1e6e906db8ad5](https://www.sharelatex.com/project/58bf4907d9f1e6e906db8ad5)
