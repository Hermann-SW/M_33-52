# M_33-52
After <kbd>bzip2 -d u.gp.bz2</kbd>, executimg the 171MB PARI/GP script computes integers x,y from the stored sqrt(Mod(-3,M_i)) and verifies that M_i==x^2+3*y^2 in less than two minutes for the top 20 known Mersenne primes:
```
hermann@7950x:~/M_33-52$ time ( gp -q < u.gp )
859433: 1
1257787: 1
1398269: 1
2976221: 1
3021377: 1
6972593: 1
13466917: 1
20996011: 1
24036583: 1
25964951: 1
30402457: 1
32582657: 1
37156667: 1
42643801: 1
43112609: 1
57885161: 1
74207281: 1
77232917: 1
82589933: 1
136279841: 1

real	1m14.267s
user	1m13.777s
sys	0m0.484s
hermann@7950x:~/M_33-52$ 
```
