# learningJs

Notas pessoais para o estudo e constante aprendizado sobre JavaScript. Para acessar os documentos vá até o Wiki.

## Exercício 2

**Write a function prettyPrint() that accepts an object as an argument and prints out a "pretty" string version of the object.**

	prettyPrint({name: "Rusty", species: "dog", breed: "mutt"});
	
	//the above code should print the following 3 lines:
	//name: Rusty
	//species: dog
	//breed: mutt

Solução

	function prettyPrint(obj) {
		for (var prop in obj){
		console.log(prop + ":" + " " + obj[prop]);	
		}
	}

