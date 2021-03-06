----------------------------------------------------------------------------
# Programming

## General

### Words
* [Word](https://en.wikipedia.org/wiki/Word_(computer_architecture))

### ExpMod
* [David Neto's code page](http://www.cs.utoronto.ca/~neto/code/fastexp.scm): Scheme and Ideal Turing
* [Bitwise operators (Python)](https://wiki.python.org/moin/BitwiseOperators)

### Floating point
* [Gustavo's IEEE-754 Brain Teaser](https://www.goinggo.net/2013/08/gustavos-ieee-754-brain-teaser.html) by William Kennedy
* [IEEE Standard 754 Floating Point Numbers](http://steve.hollasch.net/cgindex/coding/ieeefloat.html) by Steve Hollasch
* [Comparing Floating Point Numbers, 2012 Edition](https://randomascii.wordpress.com/2012/02/25/comparing-floating-point-numbers-2012-edition/) by randomASCII
* [Example: Converting to Float](http://class.ece.iastate.edu/arun/CprE281_F05/ieee754/ie5.html)
* [What Every Programmer Should Know About Floating-Point Arithmetic or Why don’t my numbers add up?](http://floating-point-gui.de/)
* [What Every Computer Scientist Should Know About Floating-Point Arithmetic](http://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html)

### Duck Typing
* [General](https://en.wikipedia.org/wiki/Duck_typing)

### Multiplication
* [Efficient Arithmetic on Koblitz Curves](http://computacion.cs.cinvestav.mx/~armfaz/res/soli2000.pdf) by Solinas

### Functions
* [Variadic function](https://en.wikipedia.org/wiki/Variadic_function)

### Algorithms
* [The Yacas Book of Algorithms](http://yacas.sourceforge.net/Algo.book.pdf) by the Yacas team

### Data representation
* [Hexadecimal Floating-Point Constants](http://www.exploringbinary.com/hexadecimal-floating-point-constants/) by Rick Regan 
* [A Tutorial on Data Representation: Integers, Floating-point Numbers, and Characters](https://www3.ntu.edu.sg/home/ehchua/programming/java/datarepresentation.html)

## Padding
* [Structure Member Alignment, Padding and Data Packing](http://www.geeksforgeeks.org/structure-member-alignment-padding-and-data-packing/)

## Bits
* [Multiplication of Binary Integers](http://www4.wittenberg.edu/academics/mathcomp/shelburne/comp255/notes/binarymultiplication)
* [Binary Arithmetic](https://www.swarthmore.edu/NatSci/echeeve1/Ref/BinaryMath/BinaryMath.html)
* [Multiplication in binary](http://www.xilinx.com/univ/teaching_materials/dsp_primer/sample/lecture_notes/FPGAArithmetic_mult.pdf)
* [Binary Multiply - Repeated Shift and Add](https://courses.cs.vt.edu/~cs1104/BuildingBlocks/multiply.040.html)
* [Lecture 8: Binary Multiplication & Division](https://www.cs.utah.edu/~rajeev/cs3810/slides/3810-08.pdf)
* [Bit field](https://en.wikipedia.org/wiki/Bit_field)
* [Masking](https://en.wikipedia.org/wiki/Mask_(computing))
* [Least significant bit](https://en.wikipedia.org/wiki/Least_significant_bit)
* [Ancient Egyptian multiplication](https://en.wikipedia.org/wiki/Ancient_Egyptian_multiplication)
* [Binary Arithmetic](http://courseweb.stthomas.edu/tpsturm/private/notes/qm300/ARITH.html)
* [Biased Notation](http://www.cs.uwm.edu/classes/cs315/Bacon/Lecture/HTML/ch04s14.html)
* [Binary Subtraction](https://courses.cs.vt.edu/~cs1104/BuildingBlocks/arithmetic.040.html)
* [Bit Twiddling Hacks](http://graphics.stanford.edu/~seander/bithacks.html) by By Sean Eron Anderson
* [Binary Arithmetic](http://www.sciencedirect.com/science/article/pii/S0065245808606105?np=y&npKey=6d6b4e76e7539ace948e93c0cdce662ad3cb10a25a870feadfddd0ce6cd5624e) by George W. Reitwiesner

### Constant Time
* [Golang](https://golang.org/src/crypto/subtle/constant_time.go)
* [Selection algorithm](https://en.wikipedia.org/wiki/Selection_algorithm)
* [Time Bounds for Selection](http://people.csail.mit.edu/rivest/pubs/BFPRT73.pdf) by Manuel Blum, Robert W. Floyd, Vaughan Pratt, Ronald L. Rivest, and Robert E. Tarjan.

## ANSI
* [ANSI C](https://en.wikipedia.org/wiki/ANSI_C)

## Golang

### General
* [The Go Blog](https://blog.golang.org/)
* [Open My Mind](http://openmymind.net/) by Karl Seguin.
* [Go Playground](https://play.golang.org/)
* [Useful resources](https://github.com/golang/go/wiki#getting-started-with-go)
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet)

### Naming
* [What's in a name?](https://talks.golang.org/2014/names.slide#1) by Andrew Gerrand
* [Name](https://golang.org/doc/effective_go.html#names) by Effective Go
* [Package names](https://blog.golang.org/package-names)
* [Some questions](http://stackoverflow.com/questions/38616687/which-way-to-name-a-function-in-go-camelcase-or-semi-camelcase)

### Books
* [An Introduction to Go Programming](https://www.golang-book.com/books/intro)

### Data Structures
* [Go Data Structures](http://research.swtch.com/godata)

### Strings
* [Access to the unicode and convert to string](http://stackoverflow.com/questions/19231506/go-golang-access-string-as-character-value)
* [Count](https://golang.org/src/strings/strings.go?s=1960:1989#L67)

### Types
* [Understanding Type in Go](https://www.goinggo.net/2013/07/understanding-type-in-go.html)
* [Understanding Golang Type System](https://thenewstack.io/understanding-golang-type-system/) by shiju varghese
* [Type identity](https://golang.org/ref/spec#Type_identity)

### Params
* [Optional Parameters?](http://stackoverflow.com/questions/2032149/optional-parameters)
* [Trigger error with number of params](http://stackoverflow.com/questions/37270743/is-it-possible-to-trigger-compile-time-error-with-custom-library-in-golang)
* [Self-referential functions and the design of options](https://commandcenter.blogspot.com.au/2014/01/self-referential-functions-and-design.html) by Rob Pike

### Convert
* [Rune to Int](http://stackoverflow.com/questions/21322173/convert-rune-to-int)
* [strconv](https://golang.org/pkg/strconv/)
* [Don't abuse math.Max / math.Min](http://mrekucci.blogspot.com/2015/07/dont-abuse-mathmax-mathmin.html)

### Arrays and slices
* [Controlling Array Growth in Golang](http://openmymind.net/Controlling-Array-Growth-In-Golang/) by Karl Seguin
* [Arrays, Slices and Maps](https://www.golang-book.com/books/intro/6)
* [Arrays, slices (and strings): The mechanics of 'append'](https://blog.golang.org/slices)
* [Go Slices: usage and internals](https://blog.golang.org/go-slices-usage-and-internals)
* [SliceTricks](https://github.com/golang/go/wiki/SliceTricks)
* [Multi-dimesional arrays](https://www.tutorialspoint.com/go/go_multi_dimensional_arrays.htm)

### ForLoop
* [Control structures - Go for loop, break, continue, range](http://golangtutorials.blogspot.com/2011/06/control-structures-go-for-loop-break.html)

### Go Check
* [GoCheck](https://github.com/go-check/check)
* [Language Specification](https://golang.org/ref/spec#Conversions)
* [Checkers](https://github.com/go-check/check/blob/v1/checkers.go)

### Type Assertions
* [Language Specification](https://golang.org/ref/spec#Type_assertions)

### Shift
* [Constant literal](http://stackoverflow.com/questions/38806491/why-doesnt-left-bit-shifting-by-64-overflow-in-golang)
* [Go << and >> operators](http://stackoverflow.com/questions/5801008/go-and-operators)
* [What does the >>= operator do in golang?](http://stackoverflow.com/questions/32933333/what-does-the-operator-do-in-golang)
* [What does a >> mean in Go language?](http://stackoverflow.com/questions/9797431/what-does-a-mean-in-go-language)
* [Invalid operation: shift of type float64](http://stackoverflow.com/questions/24865339/invalid-operation-shift-of-type-float64)

### Conversions
* [A Guide to Types and Casting in Golang](http://blog.stoneriverelearning.com/a-guide-to-types-and-casting-in-golang/) by Gerard Millares
* [GoLang interface{} - 2 type conversions, type assertions, type switches](http://golang-basic.blogspot.com/2014/06/golang-interface-2-type-conversions.html) by Swati Soni
* [From reader to string](http://stackoverflow.com/questions/9644139/from-io-reader-to-string-in-go)

### Constants
* [iota: Elegant Constants in Golang](https://splice.com/blog/iota-elegant-constants-golang/)
* [constants](https://blog.golang.org/constants)
* [why arrays are not constants](https://groups.google.com/forum/#!topic/golang-nuts/5aynucvg96I)

### Errors
* [Illegal octal digit error](http://www.perlmonks.org/?node_id=768999)
* [Error handling and Go](https://blog.golang.org/error-handling-and-go) by Andrew Gerrand

### Reflection
* [The Laws of Reflection](https://blog.golang.org/laws-of-reflection)

### Types
* [How to find a type of a object in Golang?](http://stackoverflow.com/questions/20170275/how-to-find-a-type-of-a-object-in-golang)

### Interfaces
* [Go Data Structures: Interfaces](http://research.swtch.com/interfaces)
* [Demystifying Golang's io.Reader and io.Writer Interfaces](https://nathanleclaire.com/blog/2014/07/19/demystifying-golangs-io-dot-reader-and-io-dot-writer-interfaces/) by Nathan LeClaire.
* [Go Data Structures: Interfaces](https://research.swtch.com/interfaces) by Russ Cox

### Struct
* [struct Type is not an expression](http://stackoverflow.com/questions/27455170/error-struct-type-is-not-an-expression)

### Useful commands
* [Command vet](https://golang.org/cmd/vet/)
* [errcheck](https://github.com/kisielk/errcheck)

### Operations
* [Difference](http://stackoverflow.com/questions/28432398/difference-between-some-operators-golang)

### Compiling
* [Conditional compilation in Golang](http://blog.ralch.com/tutorial/golang-conditional-compilation/) by Svetlin Ralchev

### Structs
* [How to initialize members in Go struct](http://stackoverflow.com/questions/4498998/how-to-initialize-members-in-go-struct)
* [Struct's Zero value in golang](http://stackoverflow.com/questions/28625794/structs-zero-value-in-golang)

### Assembly
* [Advanced Vector Extensions](https://en.wikipedia.org/wiki/Advanced_Vector_Extensions)
* [Generating code](https://blog.golang.org/generate)
* [A Quick Guide to Go's Assembler](https://golang.org/doc/asm)
* [How to Use the Plan 9 C Compiler](http://doc.cat-v.org/plan_9/4th_edition/papers/comp)
* [A Manual for the Plan 9 assembler](https://9p.io/sys/doc/asm.html)

### Mistakes
* [50 Shades of Go: Traps, Gotchas, and Common Mistakes for New Golang Devs](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) by Kyle Quest
* [When in Go, do as Gophers do](https://talks.golang.org/2014/readability.slide#1)
* [CodeReviewComments](https://github.com/golang/go/wiki/CodeReviewComments#Variable_Names)
* [Things I Wish Someone Had Told Me About Golang](http://openmymind.net/Things-I-Wish-Someone-Had-Told-Me-About-Go/)
* [Everyday hassles in Go](http://crufter.com/@crufter/everyday-hassles-in-go) by crufter

### Talks
* [General](https://talks.golang.org/)
* [5 things I love (or why you should learn Go)](https://www.youtube.com/watch?v=fsTOOPB1TBY) by Andrew Gerrand
* [How go was made (or why you should learn Go)](https://www.youtube.com/watch?v=0ht89TxZZnk) by Andrew Gerrand
* [Closing day keynote](https://www.youtube.com/watch?v=dKGmK_Z1Zl0) by Andrew Gerrand
* [Stupid Gopher Tricks](https://www.youtube.com/watch?v=UECh7X07m6E) by Andrew Gerrand
* [The path to Go 1](https://www.youtube.com/watch?v=bj9T2c2Xk_s) by Rob Pike and Andrew Gerrand
* [Go Concurrency Patterns](https://www.youtube.com/watch?v=f6kdp27TYZs) by Rob Pike. [Slides](https://talks.golang.org/2012/concurrency.slide#2)
* [Advanced Go Concurrency Patterns](https://www.youtube.com/watch?v=QDDwwePbDtw) by Sameer Ajmani
* [Organizing Go Code](https://talks.golang.org/2014/organizeio.slide#1) Slides, by David Crawshaw
* [10 things you (probably) don't know about Go](https://talks.golang.org/2012/10things.slide#1)

### Tools
* [The cover story](https://blog.golang.org/cover) by Rob Pike

## C

### Inline
* [An Inline Function is As Fast As a Macro](https://gcc.gnu.org/onlinedocs/gcc/Inline.html)
* [C Programming/Pointers and arrays](https://en.wikibooks.org/wiki/C_Programming/Pointers_and_arrays)
* [Bitwise Operators in C Programming](https://www.programiz.com/c-programming/bitwise-operators)

### ForLoops
* [Skip](http://stackoverflow.com/questions/22211209/are-there-reasons-to-skip-the-initialization-of-the-for-loop)
* [Syntax](http://stackoverflow.com/questions/276512/what-is-the-full-for-loop-syntax-in-c-and-others-in-case-they-are-compatible)

### Print in formats
* [printf](http://www.cplusplus.com/reference/cstdio/printf/)
* [unsigned long hex representation](http://stackoverflow.com/questions/19478509/unsigned-long-hex-representation)
* [unsigned int](http://stackoverflow.com/questions/15736497/how-to-print-an-unsigned-char-in-c)

### Pointerss
* [Pointers](http://augustcouncil.com/~tgibson/tutorial/ptr.html)
* [Don't Get Bitten by Pointer vs Non-Pointer Method Receivers in Golang](https://nathanleclaire.com/blog/2014/08/09/dont-get-bitten-by-pointer-vs-non-pointer-method-receivers-in-golang/) by Nathan Leclaire

### Constants
* [References and Constants](http://www.augustcouncil.com/~tgibson/tutorial/constref.html)

### Conversion
* [deprecated conversion from string constant to 'char*'](https://en.wikibooks.org/wiki/GCC_Debugging/g%2B%2B/Warnings/deprecated_conversion_from_string_constant)

----------------------------------------------------------------------------

# Design

## Css
* [You don't need javascript](https://github.com/you-dont-need/You-Dont-Need-Javascript)

## Vim
* [Xterm256 color names for console Vim](http://vim.wikia.com/wiki/Xterm256_color_names_for_console_Vim)
* [Use Vim](https://medium.com/usevim/) by Alex R. Young
* [Being sorta useful in vim](https://kivikakk.ee/2014/04/19/being-sorta-useful-in-vim.html#normal)

----------------------------------------------------------------------------
# Useful
* [ADR tools](https://github.com/npryce/adr-tools)
* Topological math: [Topological phase transitions and topological phases of matter](https://www.nobelprize.org/nobel_prizes/physics/laureates/2016/advanced-physicsprize2016.pdf)
* [dirEnv](https://github.com/direnv/direnv)
* [lint](https://github.com/golang/lint)

# Tools
* [Principle](http://principleformac.com/)
* [Proto.io](https://proto.io/)

----------------------------------------------------------------------------
# Code for Tor Browser High Security Mode
In high security mode, Tor only allows PNG images to be available.

If your website must support non-PNG images like SVG, you can set up a fallback image
like so [(Ref.)](https://css-tricks.com/a-complete-guide-to-svg-fallbacks/):

1. With HTML:
```
<object data="your.svg" type="image/svg+xml"> <img src="yourfallback.jpg" /> </object>
```
2. With CSS, which naturally throws away rules that the browser doesn't understand:
```
.image-with-fallback {
    background-image: url(fallback.png);
        background-image: url(your.svg), none;
}{}
```
[Why is SVG a problem? Pg 16 in this iSEC report](https://github.com/iSECPartners/publications/blob/052caf9c9c683ec0bed55782714df4d35c38f107/reports/Tor%20Browser%20Bundle/Tor%20Browser%20Bundle%20-%20iSEC%20Deliverable%201.3.pdf).
