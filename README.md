# 1.-Different-ways-are-there-to-call-a-function-in-R

a.	call(name, ...) 
where, 
name:  is a a non-empty character string naming the function to be called
… stands for arguments to be part of the call

call returns an unevaluated function call, that is, an unevaluated expression which consists of the named function applied to the given. Although the call is unevaluated, the arguments ... are evaluated.

b.	do.call 	
do.call constructs and executes a function call from a name or a function and a list of arguments to be passed to it.

c.	Recall 	
Recall is used as a placeholder for the name of the function in which it is called. It allows the definition of recursive functions which still work after being renamed	
