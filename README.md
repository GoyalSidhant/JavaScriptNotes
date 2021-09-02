
Hoisting in JS 

JS codes Executes in  2 phases
-phase 1 : memory Execution -> variable -> stores undefined , function -> whole code as it is . 
-phase 2: code execution 

Execution context -> everything happens inside this ->2 components -> memory creation and code execution phase

function Definitions 
- Normal 

function getName(){

}

- Arrow 

var getName = () => {

} 

- third method

var getName = function(){

}

arrow function -> act as a variable

Window and this are created in global even for in empty file too.
at global level -> this === window (window is its name in case of browsers)

undefined ==> special place holder, until var is assigned any value
undefined and not defined r different

js is loosely/weakly typed language.

Lexical env.
function a() {
    console.log(b);
}

var b =10;
a();

scope of variable

Let and Const -> hoisted -> temporal dead zone -> difference b/w the memory and code execution phase

let it is much strict than var
const -> it is more strict than let , const has to be assigned the value at initialization only. 

type error , syntax error , reference error

shrinking the temporal dead zone to zero.

block in js -> defined by {}

{
    //grp the statements together 
}


block scope -?> resides inside the block
Shadowing in JS -> same named var in block and global space; 

illegal shadowing->var is not shadowed using let; 

Closures -> access to parents execution context 
when function return from function the remember there binding .... a closure is returned



function statement/declaration  and function expression 
anonymous function -> can be used in place where functions r used as a value;
named function expression -> 
var b = function xyc(){
    console.log("g gjk");
}

parameters and arguments

first class functions 

Callback functions 

Event loop- > one job-> conintously mointor call stack and callback queue.

microtask queue - > higher priorty 
microtask -> all the cb from promises and mutation of server 























