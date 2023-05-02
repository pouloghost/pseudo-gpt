# Cluster and Summary
A two step map-reduce process for extract summary for seperate items such as exam questions.

p.s. Also a demonstration of array declaration.

# Pseudo Code
```
questions = [${your items here, as a string list}];
clusters = {sta#1:根据内容的相似程度将${questions}中的内容进行分类，至少分2类，最多分3组};
summaries = [];
for (cluster in clusters) {
	summaries.add({sta#2:用一句话总结${cluster}的内容});
}
{sta#3:把${summaries}中的内容有机的组合到一起，并输出};
```