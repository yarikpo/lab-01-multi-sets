# lab-01-multi-sets

## Download and run

Download git repository by:

```sh
git clone https://github.com/yarikpo/email-spammer.git
```

Compile ```main.cpp``` by:

```sh
g++ main.cpp -o main
```

Run the program:

On Linux: ```./main```

On Windows: ```.\main.exe```

## How to use

 *	create **name** ( example: ```create A``` )
 *	add **name** {objects} ( example: ```add A {1,2,3}``` )
 *	delete **name** {objects} ( example: ```del A {1,2}``` )
 *	nigation: ! **name** -> returns set
 *	union: **name_1** | **name_2** -> returns set
 *	intersection: **name_1** & **name_2** -> returns set
 *	compliment: **name_1** \ **name_2** -> return set
 *	! -> & -> | -> \
 *	```show```: -> writes all sets in console
 *	do: **command** -> writes result of expression in console ( example: ```do (A\B\C)|(B\A\C)|(C\A\B)|(A&B&C)``` )
 *	```exit``` or ```.exit```: -> exits the program
