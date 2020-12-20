# System Programming 1091 Final hw

```diff
- 欲執行PLY請輸入：python mylex.py 
```

# 語法：
* 冪次運算： base  ^  n
```diff
calc > 2^3 
```
* 根號運算： num  **  n
```diff
calc > 4**2 
```
* for-loop： for 起始值 to 結束 ("欲執行的指令運算")
```diff
calc > i=0
calc > for 1 to 3 (i=i+2)
calc > i
6
``` 
* if-else： if ("條件判斷") "expression" else "expression" 
```diff
calc > i=0
calc > if (i<0) i=1 else i=2
calc > i
2
``` 
* 若輸入四則運算，則會把Three-Address Code一一列出
![image](https://github.com/huikaiwang/SP_2020/blob/main/img/截圖%202020-12-20%20下午4.40.37.png)

* 最後在原.py檔的資料夾內會多一份.png檔，為依據上述所建立的一棵Parsing Tree
![image](https://github.com/huikaiwang/SP_2020/blob/main/img/nx_test.png)
