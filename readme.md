## Fixed file: `src/core/cell.js`

1) evalSuffixExpr: Check that `formulaMap[formula]` exists. Otherwise, it
   will crash on unknown formulas.
2) cellRender: If formula is not rendered, return source as text.
