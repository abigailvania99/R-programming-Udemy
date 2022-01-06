# Homework: Law of Large Number
## R Programming A-Z™: R For Data Science With Real Exercises!

```
N <- 100
counter <- 0
for(i in rnorm(N)){
  if(i > -1 & i < 1){
    counter <- counter + 1
  }
}

answer <- counter / N
answer
```
Hasilnya adalah 0.71 artinya 71%, tetapi hasil tersebut bisa saja berubah. Hal tersebut terjadi karena rnorm mengambil angka sembarang dari suatu distribusi normal
