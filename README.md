# Merge Sort

[Patika dev'e gitmek için](https://www.patika.dev/tr)
[Benim hesabıma gitmek için](https://app.patika.dev/makoveli)
[Ödev sayfası için](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje)

---

**[16,21,11,8,12,22]** -> 

1.  Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```
- [16,21,11,8,12,22] 				>> [16,21,11] , [8,12,22]
- [16,21,11] , [8,12,22] 			>> [16]	 [21,11] , [8]	[12,22] 
- [16]	 [21,11] , [8]	[12,22] 	>> [16]	[21] [11] , [8] [12] [22]
- [16]	[21] [11] , [8] [12] [22]   >> [11,16,21] , [8,12,22]
- [11,16,21] , [8,12,22] 			>> [8,11,12,16,21,22]
```

2. Big-O gösterimini yazınız.

```
- O(nlogn)
```
