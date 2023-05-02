# Simple Batching
Simply batching similar QA using for-loop and if-else branch.
# Pseudo Code
```
jobs = ["程序员", "设计师"];
count = 1;
for(job in jobs) {
	if({con#1:ai可以在${job}上完全替代人类}){
		{sta#1:说明可以替代的理由};
	} else if({con#2:ai可以在${job}上部分替代人类}){
		{sta#2:说明不可以替代的领域, 限制字数${count} * 10};
	} else {
		{sta#3:说明不可以替代的理由};
	}
	count++;
}
```