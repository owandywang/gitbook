# 滑动窗口

### 滑动窗口模版

```text
int left = 0, right = 0;
while (right < s.size()) {
    // 增大窗口
    window.add(s[right]);
    right++;
    
    while (window needs shrink) {
        // 减小窗口
        window.remove(s[left]);
        left++;
    }
}
```

### LC3.无重复字符的最长子串

### LC76.最小覆盖子串

### LC567.字符串的排列

### LC438.找到字符串中所有字母异位词

### 其他

unordered\_map

