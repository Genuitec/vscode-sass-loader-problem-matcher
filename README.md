# VSCode sass-loader problem matcher

## Description
This is used by Angular IDE by [CodeMix](https://www.genuitec.com/products/codemix/) to provide enhanced automated reporting of errors from “ng watch” and similar build pipeline tools directly into the workspace.

![Demo](images/demo-problem-matcher.gif)

## Example
```
// tasks.json entry
{
    "type": "npm",
    "script": "watch",
    "problemMatcher": [
        "$sass-loader"
    ]
}
```

If you plan to use this extension for Angular CLI development, why don't take a look at [Angular CLI Task Provider](https://marketplace.visualstudio.com/items?itemName=Genuitec.angular-cli-task-provider).


## License
MIT