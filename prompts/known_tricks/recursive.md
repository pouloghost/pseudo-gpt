# Decomposing Problem Recursively
Guide GPT-4 decomposing complex problem into simpler problems until each one is simple enough to be solved.

p.s. Also a demonstration of function declaration.

# Pseudo Code - base
Automative problem solving without human help.
```
result solve(question) {
	if({con#1:${question} is solvable with high confident}) {
		return {sta#1:answer to ${question}};
	} else {
		questions = {sta#2:break ${question} into sub questions};
		answers = [];
		for(q in questions) {
			answers.add(solve(q));
		}
		return {sta#3:combine ${answers} to solve ${question}};
	}
}

solve(${problem here})
```
# Pseudo Code - interactive
Solving problem with human help whenever needed. Can be seen as a POC of ChatGPT plugin.
```
result solve(question) {
	if({con#1:need more information to solve ${question}}) {
		{sta#4:ask for more information need for solve ${question}, starts with 'help:', continue when replied};
	}
	if({con#1:${question} is solvable with high confident}) {
		return {sta#1:answer to ${question}};
	} else {
		questions = {sta#2:break ${question} into sub questions};
		answers = [];
		for(q in questions) {
			answers.add(solve(q));
		}
		return {sta#3:combine ${answers} to solve ${question}};
	}
}

solve(${problem here})
```