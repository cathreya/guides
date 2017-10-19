# std::vector

The ```std::vector``` is a sequence container that supports random access of data like an array. However, vectors can dynamically resize themselves when more data needs to be inserted. Thus they allow very efficient data access and relatively efficient adding or removing of elements from the end.

**Creating a vector object**

```C++
#include <iostream>
#include <vector>
int main{
  std::vector<int> vec_name1;        //Creates an empty vector of integers called vec_name1
  std::vector<int> vec_name2(5,1);   //Creates a vector called vec_name2 and initializes it to have 5 integers having values 1
}
```
**Accesing an element from the vector**
```C++
  std::cout<<"The value in the 2nd index is : "<<vec_name2[2]<<endl;
```
**Iterating through all the elements of the vector**
```C++
  for(int i=0; i<vec_name2.size(); i++){                                   // vec_name2.size() returns the number of elements in the vector.
    std::cout<<"The value at the "<<i<<"th index is : "<<vec_name2[i]<<endl;
  }
```