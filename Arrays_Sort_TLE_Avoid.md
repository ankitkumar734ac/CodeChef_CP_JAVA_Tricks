# Arrays.sort() TLE
When trying to sort an array in Java it is convenient to use Arrays.sort():
- [ ] Quicksort has on average a runtime of , but worst-case runtime is O(n2) for arrays
- [ ] It can get a TLE.
```
long[] arr = {5,3,4,2,1};
Arrays.sort(arr);
// after sorting print arr
```
<h2 align="center">Solutions</h2>

### Method 1: Use objects (wrapper class)
While long[] arr is sorted with quicksort Long[] arr_obj is sorted with mergesort which has a worst-case runtime of . In Java an array with objects is sorted with mergesort when using Arrays.sort().
```
long[] arr = {5,3,4,2,1};
int n = arr.length;
Long[] arr_obj = new Long[n];
for(int i=0; i<n; ++i){
   arr_obj[i] = new Long(arr[i]);
}
Arrays.sort(arr_obj);
```
