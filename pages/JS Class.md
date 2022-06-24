---
publish: true
tags: ref/js
---
````javascript
class Forest {
  constructor(number) {
    this.trees = []
    

  }
  plant(number){
    for (var x = 0; x < number; x++) {
      var tree = new Tree();
      this.trees.push(tree);

    }
  }
  grow() {

    for (const trees of this.trees) {


      trees.grow()
    }
    print("all the trees grew.")
    print(forest)
  }

  draw() {
    for (const trees of this.trees) {
      trees.draw()
    }

  }
}
````
