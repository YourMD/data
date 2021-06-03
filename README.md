# Simple data processing coding assignment for a Software Engineer position at Your.MD

# The task

Create a REST micro-service that takes as input a string 
parameter and returns a list of matched phrases from a dictionary list.
The test dictionary is located here:

https://github.com/YourMD/data/blob/master/phrases.zip?raw=true

## Example input and output (logical):

Input: ```I have a sore throat and headache.```

Output: ```[ "sore throat", "headache" ]```

Note that this input should not match other phrases from the phrases list that have the word `sore` in them

## Interface

The micro-service should listen on port 8080, and should accept the input as a querystring parameter called `text`

## Requirements

* Use appropriate production-capable frameworks (E.g. Spring Boot/Micronaut/Vert.x/Quarkus/KTor/you-name-it for Java/Groovy/Kotlin, others as appropriate for Node.js or Python)
* Use appropriate dependency-management and build tools (E.g. Gradle for Java/Groovy, others as appropriate for Node.js or Python)
* The project's structure and organization should follow best practices
* Don't reimplement the wheel, reuse
* Prefer immutable design if possible
* Performance matters. Consider your chosen algorthm, its throughput, scalability, memory-usage
* If the framework you use is single-threaded by default, you may want to provide a multi-threaded version also
* Test your code, and your API. No need to test every permutation, but demonstrate you know the types of things to test for.
* Even though this is a simplified requirement as appropriate to being an exercise, your code should be production capable
* Show your working, if you've used any interesting libraries or approaches during development let us know and explain why in the readme. 
