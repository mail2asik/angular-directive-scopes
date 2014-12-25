Angularjs Directives Scopes

The significance feature of Angularjs is Directives. Angularjs slogan is HTML enhanced for web apps. Means, developer can introduce new HTML element (eg: <datatable>) or new attribute ( goTo="") whenever needed and write a script for their behaviour. We should know about the scope of directives. So that we can write Directives efficiently.

I assume that you have some prior knowledge regarding directives. This post explains the type of scope can be used for directives.

1. scope: false (Default)
   
   This is default behaviour. you can get the parent scope inside directive and this scope will be act as two-way data binding. Means, if you change the scope inside directive, then it will be changed in parent.
   
   Example:

2. scope: true (Inherit scope)
	
   you can get the parent scope inside directive and this scope will be act as one-way data binding. Means, if you change the scope inside directive, then it will not be changed in parent.
   
   Example:

3. scope:{} (Isolated scope)

   You can pass particulr scopes inside directive through attributes and you may decide whether the scope will be act as two-way data binding (=) or one-way data binding (@).
   
   Example: (two-way data binding)
   
   Example: (one-way data binding)