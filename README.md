Hi! 👋

You've opened the IDE Sandbox. 🎉

The Sandbox is an environment that you can access on "readme" and "code-along" lessons in Learn. It's a great place to experiment with code when you're not working on a "lab" (labs open the IDE In Browser).

The work you do in the Sandbox will be saved from lesson to lesson, and is automatically saved on your behalf to a repository in your GitHub account called `learn-co-sandbox`.

Please DO NOT touch this repository in GitHub, as it will affect your Sandbox experience, and potentially cause your work to be out of sync.

To learn more about the Sandbox, please visit http://help.learn.co/ide-in-browser#sandbox.
function sayHelloToIsabel() {
console.log("Hello, Isabel!")
}
function sayHelloToSofia() {
  console.log("Hello, Sofia")
  }
  function sayHelloToBrandan() {
    console.log("Hello, Brendan!")
    }
    sayHelloToIsabel()
    sayHelloToSofia()
    sayHelloToBrendan()
    
  }
}
}

var x = 1;
 
function myFunction(){
  y = 2;
  console.log(x);
}

function outerFunction() {
  var innerVariable = "I'm sort of a secret.";
 
  return function innerScope() {
    var inaccessible = "Nothing can touch me.";
 
    return innerVariable;
  }
}

var myScope = outerFunction();

myScope;

innerScope();

