
# Techniques

## Yeah

  * [Behavior Driven Development (BDD)](#behavior-driven-development-bdd)
  * [Microservices](#microservices)

## Eh
  
  * [Monolith](#monolith)

---

### Behavior Driven Development (BDD)

Shifts the focus of testing from testing your code structure, to testing its behavior.
The technique does not require a BDD oriented testing framework,
but can be applied with any.

### Microservices

Breaking up your service into many smaller services brings benefits too all of those microservices.
It allows them to be more focused on their task.
It allows adoption of new technologies into each service faster.
It brings benefits in scalability over a [monolith](#monolith).
It enforces modularity.
Be careful not to take it too far, with services that do too little.

### Monolith

Starting your project with a monolith is usually preferable to [microservices](#microservices).
It is easier to deploy and develop at a small scale in a single code base.
A monolith can always migrate towards microservices at a later date.
With discipline you can even achieve the rare
[magestic monolith](https://m.signalvnoise.com/the-majestic-monolith-29166d022228).
