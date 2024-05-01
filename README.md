# Highlight-Cell-in-MSExcel
This formula and codes will highlight the row and column of selected cell.

# Instructions for Use
1. Highlight/select the range of cells these codes will be applied. 
2. In `Home` select `Conditional Formatting` > `New Rule` > `Use a formula to determine which cells to format`, paste the formula in [ColumnFormula](ColumnFormula) in the space in `Edit the Rule Description`. Select `Format` > `Fill`, then select the color you want to use in highlighting the columns. When done seleck `Ok` > `Ok`.
3. Just like in `1`, Highlight/select the range of cells these codes will be applied.
4. In `Home` select `Conditional Formatting` > `New Rule` > `Use a formula to determine which cells to format`, paste the formula in [RowFormula](RowFormula) in the space in `Edit the Rule Description`. Select `Format` > `Fill`, then select the color you want to use in highlighting the rows. When done seleck `Ok` > `Ok`.
5. Right click on `Tab` of the active worksheet and select `View Code`, then paste the code in [MacroCode-Highlight.vba](MacroCode-Highlight.vba). Then close it by clicking ❌.
6. Well Done! 👍

>[!IMPORTANT]
>The file must be save as excel file with `.xlm` extension.

## License
This project is licensed under the [MIT License](LICENSE).
