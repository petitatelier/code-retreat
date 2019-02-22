# Week 3
## Learning trail · Olivier
[TODO]

## Learning trail · Yves
### 2019-02-18
- Creating template to draw force graph layout with SVG elements as slot
- Researches on the lit-element children/slots
	- [Lit-Element Templates](https://lit-element.polymer-project.org/guide/templates)
  - Trying to resolve issue with `<slot>` and `<svg>` 
  - Discussion with Justin Fagiani that recommend to use `<foreignObject>` (but that is to integrate HTML element only, therefore the `<circle>` is not working) 
    Not working for my use case because <slot> is not an HTML component and it seems that
    LitElement doesn't replace the slot that is in a SVG element.
### 2019-02-19
- Updating directed-force-graph component to support nodes elements in SVG and HTML containers
- Adds `nodes` and `links` slots

### 2019-02-20
- The mathematical recall
  - [Limits, derivative, slope](https://en.wikipedia.org/wiki/Derivative)
  - [Differential equation](https://en.wikipedia.org/wiki/Differential_equation)
   - [Equation diff](https://www.methodemaths.fr/equadiff/)
  - [Verlet integration](https://en.wikipedia.org/wiki/Verlet_integration)
- Justin Fagiani talk show, https://shoptalkshow.com/episodes/348/
- [Conf. slides](https://github.com/olange/webcomponents-primer/wiki/Slides-%C2%B7-Exemples-de-WebComponents)
    - Discussion avec Olivier concernant les slides => webcomponents + firebase + sync slides

### 2019-02-21
- Finishing the Force Directed Graph component
  - Update demo to show how to add a new node and link
  - Styling and better colors, description
  - WIP: documentation and publishing to repo
- Discussion about business of PAGL with Olivier
- [Modifying a force directed graph](https://gist.github.com/mbostock/1095795)

### 2019-02-22
- Fix simulation forces to have nice demos 
- Make attribute public to control the force directed graph
- Fixing issue with D3.js and the d3-force simulation when adding new node or link

