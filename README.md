# Arithmetic Calculator
Computes basic mathematical expressions. Incorporates PEMDAS and parentheses.

<h2>Shout out to Edsger Dijkstra</h2>
The calculator uses Edsger Dijkstra's shunting-yard algorithm(not to be confused with Dijkstra's famous shortest paths algorithm)
for converting mathematical expressions from infix notation(standard notation, like "2 + 3 / 5") 
to postfix notation, which is a different way of representing math expressions. For example, the expression "2 + 3 / 5" in infix notation would be
"3 5 / 2 +" in postfix notation. We want to convert the function from infix to postfix for easy parsing. It is much simpler to program a computer to
compute a postfix expression than to program a computer to compute an infix expression.
