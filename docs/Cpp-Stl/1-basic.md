

## pairs and vectors
```cpp
int main(){
    pair<int,string>p;
    p=make_pair(1,"abc");
    // other syntax p = {1,"abc"};
    pair<int,string> p1=p; // will copy p to p1 
    p1.first=2; // changing p1 will not change p
    // to change pass by refrence 
    //  pair<int,string> &p1=p;
    cout<<p.first<<" "<<p.second<<endl;
}
```

- used to maintain relations

```cpp
int a[]={1,2,3};
int b[]={4,5,6};

pair<int,int>p_array[3];
p_array[0]={1,2};
p_array[1]={3,4};
p_array[2]={5,6};
for(int i=0;i<3;i++){
    cout<<p_array[i].first<<" "<<p_array[i].second<<endl;
}
```

---

> vector are of dynamic size