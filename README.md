See this Wikipedia entry: http://en.wikipedia.org/wiki/Matrix_chain_multiplication

    $ java MatrixChain 5 6 7 3 2 9 2

```
A1: 5x6
A2: 6x7
A3: 7x3
A4: 3x2
A5: 2x9
A6: 9x2
(A1,(A2,(A3,(A4,(A5,A6)))))=234
((A1,(A2,(A3,A4))),(A5,A6))=242
(A1,((A2,(A3,A4)),(A5,A6)))=246
(A1,(A2,((A3,A4),(A5,A6))))=250
(A1,((A2,A3),(A4,(A5,A6))))=270
((A1,((A2,A3),A4)),(A5,A6))=278
(A1,(((A2,A3),A4),(A5,A6)))=282
(A1,(A2,(A3,((A4,A5),A6))))=294
((A1,(A2,A3)),(A4,(A5,A6)))=294
(((A1,(A2,A3)),A4),(A5,A6))=302
(A1,((A2,A3),((A4,A5),A6)))=330
((A1,(A2,A3)),((A4,A5),A6))=354
(((A1,(A2,(A3,A4))),A5),A6)=366
((A1,A2),(A3,(A4,(A5,A6))))=370
(((A1,A2),(A3,A4)),(A5,A6))=378
((A1,A2),((A3,A4),(A5,A6)))=386
(((A1,A2),A3),(A4,(A5,A6)))=393
((((A1,A2),A3),A4),(A5,A6))=401
(A1,(((A2,(A3,A4)),A5),A6))=402
(((A1,((A2,A3),A4)),A5),A6)=402
((((A1,(A2,A3)),A4),A5),A6)=426
((A1,A2),(A3,((A4,A5),A6)))=430
(A1,(A2,(((A3,A4),A5),A6)))=438
(A1,((((A2,A3),A4),A5),A6))=438
(((A1,A2),A3),((A4,A5),A6))=453
(((A1,(A2,A3)),(A4,A5)),A6)=495
((((A1,A2),(A3,A4)),A5),A6)=502
(A1,(((A2,A3),(A4,A5)),A6))=510
(A1,(A2,((A3,(A4,A5)),A6)))=513
(((((A1,A2),A3),A4),A5),A6)=525
((A1,A2),(((A3,A4),A5),A6))=574
((A1,((A2,(A3,A4)),A5)),A6)=594
((((A1,A2),A3),(A4,A5)),A6)=594
((A1,(((A2,A3),A4),A5)),A6)=630
((A1,A2),((A3,(A4,A5)),A6))=649
((A1,((A2,A3),(A4,A5))),A6)=702
(A1,((A2,((A3,A4),A5)),A6))=714
(((A1,A2),((A3,A4),A5)),A6)=783
(A1,((A2,(A3,(A4,A5))),A6))=789
(((A1,A2),(A3,(A4,A5))),A6)=858
((A1,(A2,((A3,A4),A5))),A6)=906
((A1,(A2,(A3,(A4,A5)))),A6)=981
```
