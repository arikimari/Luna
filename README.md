# Luna
(**L**ogic **U**sing **NA**nd gates)

Logic description/programming language. Only two keywords, **\#** and **|**. 
 
NAND is a universal gate. This means that one can build any logic circuit using only NAND gates.
Luna uses this fact. There is a base object which is a 2-input NAND gate. User can use this base object to create more objects. User can then use those objects to build even more complex objects.

Luna consists two parts. Logic compiler **Lunac** and logic simulator **Lunas**.

## Lunac

Luna compiler. Takes Luna source file (\*.ls) and compiles it to Luna object file (\*.lo).

### Syntax

Type
```
lunac
```
to get available arguments.

## Lunas

Luna simulator. Used to run/simulate Luna object file. Reads input file and outputs results to output file.

### Syntax

Type
```
lunas
```
to get available arguments.


Example syntax


## Build

### Linux
Makefile included. Run command

```
make
```

You need to have GNU cpp installed. Should create lunac and lunas executables.

### Others

Luna is written using standart C-libraries. Porting to other OS shoudn't be hard.

