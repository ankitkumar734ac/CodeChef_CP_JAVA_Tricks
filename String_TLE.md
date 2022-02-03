# String TLE

<h2 align="center">String Concatenations using one character at a time</h2>

- [ ] The below code will take O(n^2) time

```
String s = "" 
for(int i=0;i<n;i++) 
{ 
        s += "1"; 
} 
```

- [ ] The below code will take O(n) time.

```
char arr[] = new char[n]; 
for(int i=0;i<n;i++){ 
        arr[i] = '1'; 
} 
String str = String.valueOf(arr) ;
```
<h2 align="center"></h2>
