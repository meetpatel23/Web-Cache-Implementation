# Web-Cache-Implementation
Implementation of a a proxy server and Analysis as well as comparison of different caching algorithms like LFU (Least Frequently Used) and LRU (Least Recently Used)

-> Two different folders 'LFU' and 'LRU' contain two whole different programs.
<br>
-> Folder 'LFU' contains 'LFU_main.py' which uses Least Frequently Used algorithm for web caching.
<br>
-> Similarly, Folder 'LRU' contains 'LRU_main.py' which uses Least Recently Used algorithm for web caching.
<br>
-> 'cache.pkl' stores cached web pages' metadata.
<br>
-> Both the algorithms were run independently on randomly generated data (same data for both programs)
<br>
-> Analysis was done for LFU and LRU algorithms by plotting graph of cache size vs number of misses.
<br>
-> 'Results' folder contain two graphs obtained by randomly generated data for both algorithms. Seeing both the graphs, we reached to the conclusion that both LFU and LRU algorithms perform almost the same in terms of number of hits/misses. No inference can be derived as to one algorithm dominating the other one. There is no substatial evidence to prove remarkable difference between these two algorithms. 
<br>
