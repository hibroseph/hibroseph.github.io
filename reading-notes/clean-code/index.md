---
layout: post
---
## Clean Code
### Robert C. Martin

#### Chapter 10: Classes
- Classes should be small
- Classes should be even smaller than that
- We count classes not with physical lines but with responsibilities (136)
- Naming is the first tell that a class has too many responsibilities. If it is hard to 'derive a concise name for a class, then it's likely too large. The more ambiguous the class name, the more likely it has too many responsibilities'.
- Identifiying helps us recognize responsibilities in our code. Recognizing responsibilities helps us create better abstractions. 
- It's important to organize our classes into small chunks so developers need only deal with the complexity they are concerned with. In contrast to wading through code that isn't important to them.
- In an ideal world, we should add features by extending a class, not by modifying it
