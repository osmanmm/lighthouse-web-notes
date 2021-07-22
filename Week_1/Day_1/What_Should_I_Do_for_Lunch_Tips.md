### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.
 ``` javascript
 function whatToDoForLunch(hungry, availableTime) {
 	if (hungry === false){
  		console.log("get back to work");
  	} else{
  		if (availableTime > 30 ){
    			 console.log("remind ourselves that we're in a bootcamp");
    		}else if (availableTime >= 20 && availableTime <= 30 ){
      			 console.log("try a place nearby");
    		}else if( availableTime < 20 ){
    			 console.log("pick something up and eat");
          	}
  	  	}
  }
  ```
