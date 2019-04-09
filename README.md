# FibPair
# generic types

exercises in using classes that are parameterized with
generic types

## in [`Pair` example](https://github.com/stuyvesant-cs/solutionsHolmes/tree/master/2019-04-05_PairOfGenerics)

For each item in this section, find exemplifying code in the `Pair` example.
>For easy reference in the future, you can take advantage of
GitHub's "Copy permalink" command: click on a line number,
then click on the resulting ellipsis. Use the permalink as the URL
in [GitHub-Flavored Markdown](https://help.github.com/en/articles/basic-writing-and-formatting-syntax#links).


* (an example of this task) the declaration of a `main` method:
```
public static void main(String[] args)
```
in [UserSavedByCompiler](https://github.com/stuyvesant-cs/solutionsHolmes/blob/21b641c9dda3c43d3e71de138c24c29f11687d88/2019-04-05_PairOfGenerics/UserSavedByCompiler.java#L11)


* declaration of a Pair
```
Pair<String> mm;
```
in [UserOfPair](https://github.com/stuyvesant-cs/solutionsHolmes/blob/650c94c91da1ad1b815e13c35c5816c2419446e5/2019-04-05_PairOfGenerics/UserOfPair.java#L15)

* Use of a Pair as a promised output (with a specific type)
```
public static Pair<String> minmax( String[] a) {
```
in [UserOfPair](https://github.com/stuyvesant-cs/solutionsHolmes/blob/650c94c91da1ad1b815e13c35c5816c2419446e5/2019-04-05_PairOfGenerics/UserOfPair.java#L30)

* Initialization of a Pair
```
return new Pair<String>(min, max);
```
in [UserOfPair](https://github.com/stuyvesant-cs/solutionsHolmes/blob/650c94c91da1ad1b815e13c35c5816c2419446e5/2019-04-05_PairOfGenerics/UserOfPair.java#L46)

* types can be substituted using the <T>
```
private T first;
```
in [Pair](https://github.com/stuyvesant-cs/solutionsHolmes/blob/650c94c91da1ad1b815e13c35c5816c2419446e5/2019-04-05_PairOfGenerics/Pair.java#L10)
