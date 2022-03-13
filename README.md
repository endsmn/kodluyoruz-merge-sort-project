# Kodluyoruz Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort

1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```
                [16,21,11,8,12,22]
               /                  \
          [16,21,11]           [8,12,22]
         /          \         /         \
     [16,21]       [11]    [8,12]      [22]
      /   \          |      /  \        |
    [16] [21]      [11]   [8] [12]     [22]
      \   /          |      \  /        |
     [16,21]       [11]    [8,12]      [22]
         \          /         \         /
          [11,16,21]           [8,12,22]
               \                  /
                [8,11,12,16,21,22]
```

 2- Big-O gösterimini yazınız.

 ```
 O(nlogn)
 ```

# Contributing

Pull requestler kabul edilir. Büyük değişiklikler için, lütfen önce neyi değiştirmek istediğinizi tartışmak için bir konu açınız.

# License

[MIT](https://choosealicense.com/licenses/mit/)