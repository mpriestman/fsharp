# DOT DSL

Write a Domain Specific Language similar to the Graphviz dot language.

A [Domain Specific Language
(DSL)](https://en.wikipedia.org/wiki/Domain-specific_language) is a
small language optimized for a specific domain.

For example the [DOT language](https://en.wikipedia.org/wiki/DOT_(graph_description_language)) allows
you to write a textual description of a graph which is then transformed into a picture by one of
the [Graphviz](http://graphviz.org/) tools (such as `dot`). A simple graph looks like this:

    graph {
        graph [bgcolor="yellow"]
        a [color="red"]
        b [color="blue"]
        a -- b [color="green"]
    }

Putting this in a file `example.dot` and running `dot example.dot -T png
-o example.png` creates an image `example.png` with red and blue circle
connected by a green line on a yellow background.

Create a DSL similar to the dot language.

## Running the tests

To run the tests, run the command `dotnet test` from within the exercise directory.

## Further information

For more detailed information about the F# track, including how to get help if
you're having trouble, please visit the exercism.io [F# language page](http://exercism.io/languages/fsharp/resources).

## Submitting Incomplete Solutions
It's possible to submit an incomplete solution so you can see how others have completed the exercise.
