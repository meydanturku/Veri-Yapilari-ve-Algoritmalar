# Merge Short Projesi
---
## [16,21,11,8,12,22] -> Merge Short 
---

### 1. Yukarıdaki dizinin sort türüne göre aşamaları

```
step1 ->         [16,21,11,8,12,22]
                  /               \
step2 ->     [16,21,11]        [8,12,22]
              /     \            /   \
step3 ->  [16,21]  [11]      [8,12]  [22]
            /   \     \        /  \     \
step4 -> [16]  [21]   [11]   [8]  [12]  [22]
            \   /      /       \   /     /
step5 ->   [16,21]  [11]      [8,12]  [22]
               \     /           \     /
step6 ->      [11,16,21]        [8,12,22]
                   \                /
step7 ->          [8,11,12,16,21,22]    

```
### 2. Big-O gösterimini yazınız

` O(nlogn) `




