#### 771. Jewels and Stones
该题是计算石头中有多少个是珠宝，根据官方提供的两种答案，有两种标记算法，一种是用map标记，一种是用数组标记，这一题由于类型限制在了26个字母，所以应该
想到用可以数组标记，因为字母个数限定了为26个，数组下标通过 smallLetter[c - 'a'] 和 bigLetter[c = 'A']来索引该字母是否被标记，数据标记减少了map的插入和查找，所以更快。