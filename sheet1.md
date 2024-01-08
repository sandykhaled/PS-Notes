**summuation rule** 

```
∑5
5! => 5+4+3+2+1 = 15 
n(n+1)/2
```
2- faster code
```
ios_base::sync_with_stdio(false);
    cin.tie(nullptr);
```
**
ios_base::sync_with_stdio(false);

By default, C++ cin and cout are synchronized with the C standard I/O functions (scanf and printf). This means that operations on cin and cout can be slower compared to their C counterparts.
Disabling synchronization (sync_with_stdio(false)) allows for potentially faster input and output operations in C++.
cin.tie(nullptr);

By default, cin is tied to cout, meaning that when cin is used, cout is flushed, and vice versa. This can introduce unnecessary flushing of the output buffer, affecting performance.
cin.tie(nullptr) unties cin from cout, preventing automatic flushing. This can lead to improved performance when there's no need for synchronized input and output**
