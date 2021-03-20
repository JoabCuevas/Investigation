# Investigation

##Fundamentals of the modular programming methodology

Modular programming. The best-known method of solving a problem is to break it down into smaller problems, called subproblems. In this way, instead of solving a complex and tedious task, we solve other simpler ones and from them we arrive at the solution. This technique is widely used in programming since programming is nothing more than solving problems, and is often called top-down design or divide and rule methodology; these subprograms are often called modules, hence the name modular programming. Source [Link](https://www.ecured.cu/Programaci%C3%B3n_Modular)

###Types of modular programming

*Parameters by valuer - it has this name because what the subprogram receives are nothing more than copies of the data values that the invoking program passes to it. Therefore, if in the procedure we modify any of these values, the original data will remain unchanged.

*Parameters by reference - what is passed to the procedure is the data itself. And if it modifies them, the changes will remain once the execution returns to the module that invoked the procedure. They are used to obtain values from calculations made by an applet.

##Subalgorith

A subalgorithm is called each of the parts of a more general algorithm that solves each of the particular tasks necessary for said general algorithm to achieve the objective for which it was designed, that is, to solve a problem. This concept is linked to the structured design of algorithms, in which a problem is divided into parts that are later solved by a module. Each module will match a subalgorithm. Source [Link](https://es.wikipedia.org/wiki/Subalgoritmo)

##Types of modules 

###Depending on its situation with respect to the module that invokes it

*Internal: it is in the same file as the module that invokes it.

*External: it is in a different file.

###Considering the possible return of a value

*Function: returns a value when it returns control to the module that invoked it. This value will be collected to use it in an expression.

*Procedure: it does not make an explicit return of a value at the end of the module. When control is returned to the calling module, execution continues on the statement following the one that made the call.

###Depending on when it was developed

*Program: its development has been carried out entirely in the current program.

*From library: it has been previously developed and is contained in library files.

###Depending on the number of different modules that make the call

*Subprogram: it is invoked by a single module.

*Routine or subroutine: it is invoked by various modules.

Source[Link](http://agrega.juntadeandalucia.es/repositorio/02122016/a5/es-an_2016120212_9131705/41_clasificacin_de_los_mdulos.html)






