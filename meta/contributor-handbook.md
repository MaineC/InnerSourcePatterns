# Contributor Handbook

This document lays out a basic guideline of how to write and contribute a new pattern.

## Maturity Levels

We have defined three maturity levels for patterns: The higher a pattern's maturity level, the more strictly it was validated and the better is its writing.

### In a Nutshell

| \# | Name | Description | Time to merge |
| ---- | ---- | ---- | ---- |
| 1 | Initial | Contains an initial pattern idea or what we call a donut (a pattern with missing sections). | A few days / weeks |
| 2 | Structured | Contains a complete pattern that it is not properly validated yet (e.g. because it only synthesizes an idea or the experiences from one instead of three organizations). | A few days / weeks |
| 3 | Validated | The pattern is validated (e.g. because three or more instances exists and are synthesized by the pattern) and its writing is of high quality. | A few months |

For the first pattern you contribute, you should aim for maturity levels `1: Initial` or `2: Structured`. 

If you want to help promoting a pattern one maturity level up, we suggest to first create an issue to discuss the matter and see if someone else is working on that already. After that, you can create a pull request with the necessary changes.

To achieve a given maturity level a pattern has to satisfy the requirements for that given maturity level and lower levels. The following sections lay out the requirements per maturity level in detail.


### Requirements: Level 1 - Initial

Patterns (or other documents) of level 1 are stored in the directory `/1-initial`.

- Validation requirements:
	- N/A
	
- Content requirements:
	- The document is readible & comprehensible for other parties (not just for the author(s))
	- The author(s) contribute the contents according to the [license](../LICENSE.txt) & are allowed to do so
	- Thoughts and contents by third parties are quoted / referenced explicitly

	
### Requirements: Level 2 - Structured

Patterns of level 2 are stored in the directory `/2-structured`.

- Validation requirements:
	- Is validated by at least one known instance 
		- Alternatively: key elements of the pattern have been validated in separate contexts and, in consequence, it is justified to believe the full solution will function
	
- Content requirements:
	- Complies with the [patterns format](pattern-template.md)
	- Complies with *basic style guide*(#) - *Oops! We have not yet developed this*
	
	
### Requirements: Level 3 - Validated

Patterns of level 3 are stored in the directory `/3-validated`.

- Validation requirements:
	- Is validated by at least three known instances
	- Considers all known instances to the best of working group members' knowledge
	- Community agreement (via lazy consensus of trusted committers) on correctness of contents
	
- Content requirements:
	- Uses & has no conflicts with working group terminology (defined by glossary / implicit usage) - *Oops! We have not yet developed this.*
	- Fits & has no conflicts with existing patterns (of this maturity level or higher)
	- Thorough review by at least two trusted committers

