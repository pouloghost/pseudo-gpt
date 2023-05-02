# Domain Problem Advicer
Provide well-known methods for a domain problem.

# Pseudo Code - general
General advices for solving your problem.
```
problem = ${problem here}
void adviceForDomain(domain) {
	if({con#1:{domain} is small enough to be improved with well-known methods}) {
		{sta#3:list well-known methods and material to improve ${domain}};
	} else {
		subDomains = {sta#4:break domain to subdomains, so that each subdomain can be improved with well-known methods};
		for (sub in subDomains) {
			adviceForDomain(sub);
		}
	}
}
possibleDomains = {sta#1:list domains to improve to solve ${problem}, each domain starts with d-[index]:. you must give at least 5 domains. you must give at most 10 domains.};
domains = {sta#2:ask which domain I would like to improve. you have to wait for my reply. I will give index of domain.};
for(domain in domains) {
	adviceForDomain(domain);
}
```

# Pseudo Code - learning material
Recommend learning materials for solving your problem.
```
problem = ${problem here}
void adviceForDomain(domain) {
	if({con#1:{domain} is small enough to be learned with well-known materials or books}) {
		{sta#3:list well-known books and materials to learn ${domain}};
	} else {
		subDomains = {sta#4:break ${domain} to sub learning areas, so that each sub learning areas can be improved with well-known materials};
		for (sub in subDomains) {
			adviceForDomain(sub);
		}
	}
}
possibleDomains = {sta#1:list learning areas to improve to solve ${problem}, each learning areas starts with d-[index]:. you must give at least 5 learning areas. you must give at most 10 learning areas. each learning areas must focus on improving personal abilities.};
domains = {sta#2:ask which learning areas I would like to improve. you have to wait for my reply. I will give index of learning areas.};
for(domain in domains) {
	adviceForDomain(domain);
}
```