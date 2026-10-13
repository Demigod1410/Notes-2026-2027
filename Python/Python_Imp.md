# 1. Explain the Two Types of Python Modes in Which a Python Program Can Be Executed

## 1. Introduction

Python programs can be executed in two main modes:

1. Interactive Mode
2. Script Mode

Both modes allow you to execute Python code, but they differ in how code is entered, executed, and saved.

Interactive mode is useful for quickly testing small pieces of code, whereas script mode is useful for writing, saving, and executing complete programs.

## 2. Interactive Mode

### Definition

Interactive mode is a way of running Python in which you enter statements directly into the Python interpreter and receive the results immediately.

It is also called the REPL (Read–Eval–Print Loop) because Python repeatedly reads your input, evaluates it, and displays the result.

### How interactive mode works

[Installation · HonKit](https://images.openai.com/static-rsc-4/7MF4F7yghrFvIlZK9b1cAQdYsiqO_QhuPNLeTBJ4Ks5NuAYqo1noQlRcvz9ckAbCclBRNyHvrjkT1iAUPp4uWncb9O1nkie8D6KbTaU5d2h-BTIx5QQPXudy9UGflhAaq66ILv7VG4JGa3OuCmrGPFK0NUVl0hAJBvkGVfGc4Bw?purpose=inline)

[cs.du.edu](https://cs.du.edu/~intropython/byte-of-python/installation.html)

\#chatgpt-mermaid-\_r_2sf\_{font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";font-size:16px;fill:rgb(237, 237, 237);}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#chatgpt-mermaid-\_r_2sf\_ .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#chatgpt-mermaid-\_r_2sf\_ .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#chatgpt-mermaid-\_r_2sf\_ .error-icon{fill:rgb(48, 48, 48);}#chatgpt-mermaid-\_r_2sf\_ .error-text{fill:rgb(237, 237, 237);stroke:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2sf\_ .edge-thickness-normal{stroke-width:1px;}#chatgpt-mermaid-\_r_2sf\_ .edge-thickness-thick{stroke-width:3.5px;}#chatgpt-mermaid-\_r_2sf\_ .edge-pattern-solid{stroke-dasharray:0;}#chatgpt-mermaid-\_r_2sf\_ .edge-thickness-invisible{stroke-width:0;fill:none;}#chatgpt-mermaid-\_r_2sf\_ .edge-pattern-dashed{stroke-dasharray:3;}#chatgpt-mermaid-\_r_2sf\_ .edge-pattern-dotted{stroke-dasharray:2;}#chatgpt-mermaid-\_r_2sf\_ .marker{fill:rgb(175, 175, 175);stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_2sf\_ .marker.cross{stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_2sf\_ svg{font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";font-size:16px;}#chatgpt-mermaid-\_r_2sf\_ p{margin:0;}#chatgpt-mermaid-\_r_2sf\_ .label{font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2sf\_ .cluster-label text{fill:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2sf\_ .cluster-label span{color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2sf\_ .cluster-label span p{background-color:transparent;}#chatgpt-mermaid-\_r_2sf\_ .label text,#chatgpt-mermaid-\_r_2sf\_ span{fill:rgb(237, 237, 237);color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2sf\_ .node rect,#chatgpt-mermaid-\_r_2sf\_ .node circle,#chatgpt-mermaid-\_r_2sf\_ .node ellipse,#chatgpt-mermaid-\_r_2sf\_ .node polygon,#chatgpt-mermaid-\_r_2sf\_ .node path{fill:rgb(17, 40, 19);stroke:rgb(58, 132, 63);stroke-width:1px;}#chatgpt-mermaid-\_r_2sf\_ .rough-node .label text,#chatgpt-mermaid-\_r_2sf\_ .node .label text,#chatgpt-mermaid-\_r_2sf\_ .image-shape .label,#chatgpt-mermaid-\_r_2sf\_ .icon-shape .label{text-anchor:middle;}#chatgpt-mermaid-\_r_2sf\_ .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#chatgpt-mermaid-\_r_2sf\_ .rough-node .label,#chatgpt-mermaid-\_r_2sf\_ .node .label,#chatgpt-mermaid-\_r_2sf\_ .image-shape .label,#chatgpt-mermaid-\_r_2sf\_ .icon-shape .label{text-align:center;}#chatgpt-mermaid-\_r_2sf\_ .node.clickable{cursor:pointer;}#chatgpt-mermaid-\_r_2sf\_ .root .anchor path{fill:rgb(175, 175, 175)!important;stroke-width:0;stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_2sf\_ .arrowheadPath{fill:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_2sf\_ .edgePath .path{stroke:rgb(175, 175, 175);stroke-width:1px;}#chatgpt-mermaid-\_r_2sf\_ .flowchart-link{stroke:rgb(175, 175, 175);fill:none;}#chatgpt-mermaid-\_r_2sf\_ .edgeLabel{background-color:rgb(0, 0, 0);text-align:center;}#chatgpt-mermaid-\_r_2sf\_ .edgeLabel p{background-color:rgb(0, 0, 0);}#chatgpt-mermaid-\_r_2sf\_ .edgeLabel rect{opacity:0.5;background-color:rgb(0, 0, 0);fill:rgb(0, 0, 0);}#chatgpt-mermaid-\_r_2sf\_ .labelBkg{background-color:rgba(0, 0, 0, 0.5);}#chatgpt-mermaid-\_r_2sf\_ .cluster rect{fill:rgb(48, 48, 48);stroke:rgba(255, 255, 255, 0.15);stroke-width:1px;}#chatgpt-mermaid-\_r_2sf\_ .cluster text{fill:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2sf\_ .cluster span{color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2sf\_ div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";font-size:12px;background:rgb(48, 48, 48);border:1px solid rgba(255, 255, 255, 0.15);border-radius:2px;pointer-events:none;z-index:100;}#chatgpt-mermaid-\_r_2sf\_ .flowchartTitleText{text-anchor:middle;font-size:18px;fill:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2sf\_ rect.text{fill:none;stroke-width:0;}#chatgpt-mermaid-\_r_2sf\_ .icon-shape,#chatgpt-mermaid-\_r_2sf\_ .image-shape{background-color:rgb(0, 0, 0);text-align:center;}#chatgpt-mermaid-\_r_2sf\_ .icon-shape p,#chatgpt-mermaid-\_r_2sf\_ .image-shape p{background-color:rgb(0, 0, 0);padding:2px;}#chatgpt-mermaid-\_r_2sf\_ .icon-shape .label rect,#chatgpt-mermaid-\_r_2sf\_ .image-shape .label rect{opacity:0.5;background-color:rgb(0, 0, 0);fill:rgb(0, 0, 0);}#chatgpt-mermaid-\_r_2sf\_ .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#chatgpt-mermaid-\_r_2sf\_ .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#chatgpt-mermaid-\_r_2sf\_ .node .neo-node{stroke:rgb(58, 132, 63);}#chatgpt-mermaid-\_r_2sf\_ [data-look="neo"].node rect,#chatgpt-mermaid-\_r_2sf\_ [data-look="neo"].cluster rect,#chatgpt-mermaid-\_r_2sf\_ [data-look="neo"].node polygon{stroke:url(#chatgpt-mermaid-\_r_2sf\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_2sf\_ [data-look="neo"].swimlane.cluster rect{filter:none;}#chatgpt-mermaid-\_r_2sf\_ [data-look="neo"].node path{stroke:url(#chatgpt-mermaid-\_r_2sf\_-gradient);stroke-width:1px;}#chatgpt-mermaid-\_r_2sf\_ [data-look="neo"].node .outer-path{filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_2sf\_ [data-look="neo"].node .neo-line path{stroke:rgb(58, 132, 63);filter:none;}#chatgpt-mermaid-\_r_2sf\_ [data-look="neo"].node circle{stroke:url(#chatgpt-mermaid-\_r_2sf\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_2sf\_ [data-look="neo"].node circle .state-start{fill:#000000;}#chatgpt-mermaid-\_r_2sf\_ [data-look="neo"].icon-shape .icon{fill:url(#chatgpt-mermaid-\_r_2sf\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_2sf\_ [data-look="neo"].icon-shape .icon-neo path{stroke:url(#chatgpt-mermaid-\_r_2sf\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_2sf\_ .node text{font-size:14px;font-weight:600;letter-spacing:normal;fill:rgb(140, 223, 173);}#chatgpt-mermaid-\_r_2sf\_ .edgeLabels text{font-size:13px;font-weight:600;letter-spacing:-0.08px;fill:rgb(140, 223, 173);}#chatgpt-mermaid-\_r_2sf\_ .node tspan[font-weight="normal"],#chatgpt-mermaid-\_r_2sf\_ .edgeLabels tspan[font-weight="normal"]{font-weight:600;}#chatgpt-mermaid-\_r_2sf\_ .edgeLabel .label rect{opacity:1;rx:13px;ry:13px;fill:rgb(2, 28, 12);stroke:rgb(26, 75, 45);stroke-width:1px;}#chatgpt-mermaid-\_r_2sf\_ .node rect,#chatgpt-mermaid-\_r_2sf\_ .node circle,#chatgpt-mermaid-\_r_2sf\_ .node ellipse,#chatgpt-mermaid-\_r_2sf\_ .node polygon,#chatgpt-mermaid-\_r_2sf\_ .node path{fill:rgb(0, 55, 22);stroke:rgba(255, 255, 255, 0.1);stroke-width:1px;}#chatgpt-mermaid-\_r_2sf\_ .node rect{rx:16px;ry:16px;}#chatgpt-mermaid-\_r_2sf\_ .node.mermaid-decision .label-container{fill:rgb(2, 28, 12);stroke:rgb(26, 75, 45);stroke-dasharray:2px,2px;}#chatgpt-mermaid-\_r_2sf\_ .edgePaths .flowchart-link{stroke:rgb(175, 175, 175);stroke-width:1px;stroke-linecap:round;stroke-linejoin:round;}#chatgpt-mermaid-\_r_2sf\_ .marker{fill:rgb(175, 175, 175);stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_2sf\_ :root{--mermaid-font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";}Open Python InterpreterEnter Python StatementPython Evaluates StatementDisplay ResultEnter Another Statement?Exit InterpreterYesNo

The diagram shows how Python accepts a statement, executes it, displays the result, and waits for further input.

### Example

Open a terminal or command prompt and type `python` (or `python3`, depending on your system). You should see a prompt similar to `>>>`.

```
>>> 10 + 2030>>> print("Hello, Python!")Hello, Python!>>> 5 * 420
```

### Characteristics of interactive mode

- Executes statements immediately after you enter them.
- Displays expression results without requiring an explicit `print()` call.
- Is useful for learning Python and testing expressions.
- Usually does not save entered statements automatically as a reusable program file.
- Maintains variables and other session state until the interpreter session ends or the state is changed.

### Advantages

- Quick and easy to use.
- Provides immediate feedback.
- Useful for debugging small expressions and testing functions.
- Helps beginners learn Python syntax.

### Disadvantages

- Not ideal for large programs.
- Code is not automatically saved as a `.py` file.
- Re-entering code can become inconvenient.
- Managing complex programs across many statements is difficult.

## 3. Script Mode

### Definition

Script mode is a method of executing Python code by writing the program in a file, saving it with the `.py` extension, and running that file using the Python interpreter.

A file containing Python source code is commonly called a Python script. The interpreter reads and executes the code in the file. [Source: Python Tutorial — Using the Python Interpreter](https://docs.python.org/3/tutorial/interpreter.html).

### How script mode works

\#chatgpt-mermaid-\_r_2to\_{font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";font-size:16px;fill:rgb(237, 237, 237);}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#chatgpt-mermaid-\_r_2to\_ .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#chatgpt-mermaid-\_r_2to\_ .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#chatgpt-mermaid-\_r_2to\_ .error-icon{fill:rgb(48, 48, 48);}#chatgpt-mermaid-\_r_2to\_ .error-text{fill:rgb(237, 237, 237);stroke:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2to\_ .edge-thickness-normal{stroke-width:1px;}#chatgpt-mermaid-\_r_2to\_ .edge-thickness-thick{stroke-width:3.5px;}#chatgpt-mermaid-\_r_2to\_ .edge-pattern-solid{stroke-dasharray:0;}#chatgpt-mermaid-\_r_2to\_ .edge-thickness-invisible{stroke-width:0;fill:none;}#chatgpt-mermaid-\_r_2to\_ .edge-pattern-dashed{stroke-dasharray:3;}#chatgpt-mermaid-\_r_2to\_ .edge-pattern-dotted{stroke-dasharray:2;}#chatgpt-mermaid-\_r_2to\_ .marker{fill:rgb(175, 175, 175);stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_2to\_ .marker.cross{stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_2to\_ svg{font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";font-size:16px;}#chatgpt-mermaid-\_r_2to\_ p{margin:0;}#chatgpt-mermaid-\_r_2to\_ .label{font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2to\_ .cluster-label text{fill:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2to\_ .cluster-label span{color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2to\_ .cluster-label span p{background-color:transparent;}#chatgpt-mermaid-\_r_2to\_ .label text,#chatgpt-mermaid-\_r_2to\_ span{fill:rgb(237, 237, 237);color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2to\_ .node rect,#chatgpt-mermaid-\_r_2to\_ .node circle,#chatgpt-mermaid-\_r_2to\_ .node ellipse,#chatgpt-mermaid-\_r_2to\_ .node polygon,#chatgpt-mermaid-\_r_2to\_ .node path{fill:rgb(17, 40, 19);stroke:rgb(58, 132, 63);stroke-width:1px;}#chatgpt-mermaid-\_r_2to\_ .rough-node .label text,#chatgpt-mermaid-\_r_2to\_ .node .label text,#chatgpt-mermaid-\_r_2to\_ .image-shape .label,#chatgpt-mermaid-\_r_2to\_ .icon-shape .label{text-anchor:middle;}#chatgpt-mermaid-\_r_2to\_ .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#chatgpt-mermaid-\_r_2to\_ .rough-node .label,#chatgpt-mermaid-\_r_2to\_ .node .label,#chatgpt-mermaid-\_r_2to\_ .image-shape .label,#chatgpt-mermaid-\_r_2to\_ .icon-shape .label{text-align:center;}#chatgpt-mermaid-\_r_2to\_ .node.clickable{cursor:pointer;}#chatgpt-mermaid-\_r_2to\_ .root .anchor path{fill:rgb(175, 175, 175)!important;stroke-width:0;stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_2to\_ .arrowheadPath{fill:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_2to\_ .edgePath .path{stroke:rgb(175, 175, 175);stroke-width:1px;}#chatgpt-mermaid-\_r_2to\_ .flowchart-link{stroke:rgb(175, 175, 175);fill:none;}#chatgpt-mermaid-\_r_2to\_ .edgeLabel{background-color:rgb(0, 0, 0);text-align:center;}#chatgpt-mermaid-\_r_2to\_ .edgeLabel p{background-color:rgb(0, 0, 0);}#chatgpt-mermaid-\_r_2to\_ .edgeLabel rect{opacity:0.5;background-color:rgb(0, 0, 0);fill:rgb(0, 0, 0);}#chatgpt-mermaid-\_r_2to\_ .labelBkg{background-color:rgba(0, 0, 0, 0.5);}#chatgpt-mermaid-\_r_2to\_ .cluster rect{fill:rgb(48, 48, 48);stroke:rgba(255, 255, 255, 0.15);stroke-width:1px;}#chatgpt-mermaid-\_r_2to\_ .cluster text{fill:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2to\_ .cluster span{color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2to\_ div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";font-size:12px;background:rgb(48, 48, 48);border:1px solid rgba(255, 255, 255, 0.15);border-radius:2px;pointer-events:none;z-index:100;}#chatgpt-mermaid-\_r_2to\_ .flowchartTitleText{text-anchor:middle;font-size:18px;fill:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_2to\_ rect.text{fill:none;stroke-width:0;}#chatgpt-mermaid-\_r_2to\_ .icon-shape,#chatgpt-mermaid-\_r_2to\_ .image-shape{background-color:rgb(0, 0, 0);text-align:center;}#chatgpt-mermaid-\_r_2to\_ .icon-shape p,#chatgpt-mermaid-\_r_2to\_ .image-shape p{background-color:rgb(0, 0, 0);padding:2px;}#chatgpt-mermaid-\_r_2to\_ .icon-shape .label rect,#chatgpt-mermaid-\_r_2to\_ .image-shape .label rect{opacity:0.5;background-color:rgb(0, 0, 0);fill:rgb(0, 0, 0);}#chatgpt-mermaid-\_r_2to\_ .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#chatgpt-mermaid-\_r_2to\_ .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#chatgpt-mermaid-\_r_2to\_ .node .neo-node{stroke:rgb(58, 132, 63);}#chatgpt-mermaid-\_r_2to\_ [data-look="neo"].node rect,#chatgpt-mermaid-\_r_2to\_ [data-look="neo"].cluster rect,#chatgpt-mermaid-\_r_2to\_ [data-look="neo"].node polygon{stroke:url(#chatgpt-mermaid-\_r_2to\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_2to\_ [data-look="neo"].swimlane.cluster rect{filter:none;}#chatgpt-mermaid-\_r_2to\_ [data-look="neo"].node path{stroke:url(#chatgpt-mermaid-\_r_2to\_-gradient);stroke-width:1px;}#chatgpt-mermaid-\_r_2to\_ [data-look="neo"].node .outer-path{filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_2to\_ [data-look="neo"].node .neo-line path{stroke:rgb(58, 132, 63);filter:none;}#chatgpt-mermaid-\_r_2to\_ [data-look="neo"].node circle{stroke:url(#chatgpt-mermaid-\_r_2to\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_2to\_ [data-look="neo"].node circle .state-start{fill:#000000;}#chatgpt-mermaid-\_r_2to\_ [data-look="neo"].icon-shape .icon{fill:url(#chatgpt-mermaid-\_r_2to\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_2to\_ [data-look="neo"].icon-shape .icon-neo path{stroke:url(#chatgpt-mermaid-\_r_2to\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_2to\_ .node text{font-size:14px;font-weight:600;letter-spacing:normal;fill:rgb(140, 223, 173);}#chatgpt-mermaid-\_r_2to\_ .edgeLabels text{font-size:13px;font-weight:600;letter-spacing:-0.08px;fill:rgb(140, 223, 173);}#chatgpt-mermaid-\_r_2to\_ .node tspan[font-weight="normal"],#chatgpt-mermaid-\_r_2to\_ .edgeLabels tspan[font-weight="normal"]{font-weight:600;}#chatgpt-mermaid-\_r_2to\_ .edgeLabel .label rect{opacity:1;rx:13px;ry:13px;fill:rgb(2, 28, 12);stroke:rgb(26, 75, 45);stroke-width:1px;}#chatgpt-mermaid-\_r_2to\_ .node rect,#chatgpt-mermaid-\_r_2to\_ .node circle,#chatgpt-mermaid-\_r_2to\_ .node ellipse,#chatgpt-mermaid-\_r_2to\_ .node polygon,#chatgpt-mermaid-\_r_2to\_ .node path{fill:rgb(0, 55, 22);stroke:rgba(255, 255, 255, 0.1);stroke-width:1px;}#chatgpt-mermaid-\_r_2to\_ .node rect{rx:16px;ry:16px;}#chatgpt-mermaid-\_r_2to\_ .node.mermaid-decision .label-container{fill:rgb(2, 28, 12);stroke:rgb(26, 75, 45);stroke-dasharray:2px,2px;}#chatgpt-mermaid-\_r_2to\_ .edgePaths .flowchart-link{stroke:rgb(175, 175, 175);stroke-width:1px;stroke-linecap:round;stroke-linejoin:round;}#chatgpt-mermaid-\_r_2to\_ .marker{fill:rgb(175, 175, 175);stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_2to\_ :root{--mermaid-font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";}Write Python CodeSave as program.pyOpen Terminal or IDERun python program.pyPython Interpreter Executesthe FileDisplay Output

The diagram shows the typical workflow: write the code, save it in a file, execute the file, and view the result.

### Example

Step 1: Write the Python program

Create a file named `hello.py` and enter the following code:

```
name = "Student"age = 20print("Hello,", name)print("Your age is", age)
```

Step 2: Save the file

Save the program as `hello.py`.

Step 3: Execute the program

Open a terminal in the directory containing the file and run:

```
python hello.py
```

Depending on your system, you may need to use `python3 hello.py` or `py hello.py` instead.

Step 4: View the output

```
Hello, Student
Your age is 20
```

### Step-by-step execution

| Step | Statement                   | Explanation                              |
| ---- | --------------------------- | ---------------------------------------- |
| 1    | `name = "Student"`          | Stores the string `"Student"` in `name`. |
| 2    | `age = 20`                  | Stores the integer `20` in `age`.        |
| 3    | `print("Hello,", name)`     | Displays the greeting and the name.      |
| 4    | `print("Your age is", age)` | Displays the age.                        |

### Characteristics of script mode

- Code is written in a file, usually with a `.py` extension.
- The program can contain multiple statements, functions, and classes.
- The source code can be saved, edited, shared, and reused.
- The program can be executed repeatedly without re-entering the code.
- It is suitable for larger programs, assignments, automation, and application development.
- Errors are reported when execution reaches the problematic code; an unhandled exception generally stops the script.

### Advantages

- Suitable for writing complete programs.
- Makes programs easy to save and maintain.
- Supports reusable functions, classes, and modules.
- Easier to organize and manage large projects.
- Useful for developing applications and automating tasks.

### Disadvantages

- Requires creating and saving a file before running the program.
- Testing a small expression can involve more steps than interactive mode.
- Errors may require editing the file and running it again.

## 4. Difference Between Interactive Mode and Script Mode

| Basis           | Interactive Mode                                                            | Script Mode                                                     |
| --------------- | --------------------------------------------------------------------------- | --------------------------------------------------------------- |
| Meaning         | Executes code entered directly into the interpreter.                        | Executes code saved in a file.                                  |
| Input           | Statements entered at the prompt.                                           | Statements written in a `.py` file.                             |
| Execution       | Usually executes each complete command immediately.                         | Executes the file when the interpreter is instructed to run it. |
| Output          | Expression results are displayed automatically; `print()` can also be used. | Output must be requested when needed, commonly with `print()`.  |
| Saving          | Input is not automatically saved as a reusable script.                      | Source code is saved in a file.                                 |
| Best suited for | Learning, experimentation, and quick testing.                               | Assignments, larger programs, and applications.                 |
| Reusability     | Requires saving or copying the commands if they are to be reused later.     | The saved program can be run repeatedly.                        |
| Example         | `>>> 5 + 3`                                                                 | `python program.py`                                             |

Important distinction: In interactive mode, Python automatically displays the result of an expression such as `5 + 3`. In a script, writing `5 + 3` by itself does not normally display the result; use `print(5 + 3)` to display it.

## 5. When Should You Use Each Mode?

Use interactive mode when:

- Learning a new Python concept.
- Checking the result of a calculation.
- Testing a function or expression.
- Experimenting with variables and data types.

Use script mode when:

- Writing university practical programs.
- Developing applications.
- Creating reusable code.
- Writing programs with multiple functions or classes.
- Building automation scripts.

## 6. Important Points to Remember for Examinations

1. Python programs can commonly be executed in interactive mode and script mode.
2. Interactive mode is also known as the REPL: Read, Eval, Print, Loop.
3. The `>>>` symbol is the standard Python interactive prompt.
4. Script mode uses a source-code file, conventionally ending in `.py`.
5. The command `python program.py` is a common way to execute a Python script.
6. Interactive mode is best for quick experiments, while script mode is better for complete, reusable programs.
7. Both modes use the Python interpreter to execute Python code.

## 7. Conclusion

Python provides two common ways to execute programs. Interactive mode lets programmers enter code and see results immediately, making it useful for learning and testing. Script mode lets programmers save code in `.py` files and execute complete programs, making it more suitable for assignments and application development.

## 8. References

1\. Python Software Foundation — Using the Python Interpreter. Explains interactive mode, the interpreter prompt, and running scripts from files. [https://docs.python.org/3/tutorial/interpreter.html](https://docs.python.org/3/tutorial/interpreter.html)

2\. Python Software Foundation — Command-Line and Environment. Explains how Python is invoked and how script files are executed. [https://docs.python.org/3/using/cmdline.html](https://docs.python.org/3/using/cmdline.html)