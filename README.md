# ESLint Config

## Let's Learn a VS Code Setting

The renderIndentGuides setting allows you to see the indentation lines in your code when it is set to true. The indentation lines allow you to visually see what lines of code are being indented and how much space they are being indented by. This is especially useful because blocks of code are nested with indention to display an organizational hierarchy. Although it has no effect when the code is compiled, it allows us as humans to read the code better. This is useful because others should be able to read your code effectively, especially when working in teams.

`"editor.renderIndentGuides": true`

For research on the renderIndentGuides setting, I used this [video](https://www.youtube.com/watch?v=heAT-Kp078U).


## Let's Learn an ESLint Rule

The no-trailing-spaces rule disallows extra whitespace at the end of a line of code. This is because extra whitespace can be flagged as diffs by source control systems. Even though extra whitespace does not cause any functional issues, it is still important not to save them. Source control systems such as Github track all changes made. Having something as small as extra whitespaces being comminted and pushed as a change in the code can be frustrating for developers. In order to avoid this, code conventions require that trailing whitespaces are removed.

For research on the no-trailing-spaces rule, I used this [link](https://eslint.org/docs/rules/no-trailing-spaces).