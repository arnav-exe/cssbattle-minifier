# Code optimizer for CSSBattle.dev

This Python script performs a few functions to intelligetntly optimise your code for the online code golfing game [CSSBattle.dev](https://cssbattle.dev/)

### Optimisations:
* removes all elements that are comments
* removes last set of lines:
  * final closing curly bracket "}"
  * closing style tag "</style>"
 * removes last semicolon inside each class
 * removes all whitespaces in between valid punctuation
 * removes units for width and height (EG: width: 100px -> width: 100)
 * removes all newlines



Next steps:
deploy as a Lambda function