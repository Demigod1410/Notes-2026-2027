# 1. Explain the Two Types of Python Modes in Which a Python Script Can Be Executed

## 1. Introduction

Python programs can be executed in two main modes:

1. Interactive Mode
2. Script Mode

Both modes use the Python interpreter to execute code, but they differ in how the programmer enters, executes, and saves the code. The official Python documentation describes both ways of using the interpreter. [Source: Python Documentation](https://docs.python.org/3/tutorial/interpreter.html).

## 2. Interactive Mode

### Definition

Interactive mode is a method of executing Python code in which the programmer enters statements directly into the Python interpreter and receives immediate results.

It is also called REPL (Read–Eval–Print Loop) because the interpreter repeatedly reads the input, evaluates it, displays the result, and waits for the next command.

### Diagram

\#chatgpt-mermaid-\_r_33a\_{font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";font-size:16px;fill:rgb(237, 237, 237);}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#chatgpt-mermaid-\_r_33a\_ .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#chatgpt-mermaid-\_r_33a\_ .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#chatgpt-mermaid-\_r_33a\_ .error-icon{fill:rgb(48, 48, 48);}#chatgpt-mermaid-\_r_33a\_ .error-text{fill:rgb(237, 237, 237);stroke:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33a\_ .edge-thickness-normal{stroke-width:1px;}#chatgpt-mermaid-\_r_33a\_ .edge-thickness-thick{stroke-width:3.5px;}#chatgpt-mermaid-\_r_33a\_ .edge-pattern-solid{stroke-dasharray:0;}#chatgpt-mermaid-\_r_33a\_ .edge-thickness-invisible{stroke-width:0;fill:none;}#chatgpt-mermaid-\_r_33a\_ .edge-pattern-dashed{stroke-dasharray:3;}#chatgpt-mermaid-\_r_33a\_ .edge-pattern-dotted{stroke-dasharray:2;}#chatgpt-mermaid-\_r_33a\_ .marker{fill:rgb(175, 175, 175);stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_33a\_ .marker.cross{stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_33a\_ svg{font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";font-size:16px;}#chatgpt-mermaid-\_r_33a\_ p{margin:0;}#chatgpt-mermaid-\_r_33a\_ .label{font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33a\_ .cluster-label text{fill:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33a\_ .cluster-label span{color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33a\_ .cluster-label span p{background-color:transparent;}#chatgpt-mermaid-\_r_33a\_ .label text,#chatgpt-mermaid-\_r_33a\_ span{fill:rgb(237, 237, 237);color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33a\_ .node rect,#chatgpt-mermaid-\_r_33a\_ .node circle,#chatgpt-mermaid-\_r_33a\_ .node ellipse,#chatgpt-mermaid-\_r_33a\_ .node polygon,#chatgpt-mermaid-\_r_33a\_ .node path{fill:rgb(17, 40, 19);stroke:rgb(58, 132, 63);stroke-width:1px;}#chatgpt-mermaid-\_r_33a\_ .rough-node .label text,#chatgpt-mermaid-\_r_33a\_ .node .label text,#chatgpt-mermaid-\_r_33a\_ .image-shape .label,#chatgpt-mermaid-\_r_33a\_ .icon-shape .label{text-anchor:middle;}#chatgpt-mermaid-\_r_33a\_ .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#chatgpt-mermaid-\_r_33a\_ .rough-node .label,#chatgpt-mermaid-\_r_33a\_ .node .label,#chatgpt-mermaid-\_r_33a\_ .image-shape .label,#chatgpt-mermaid-\_r_33a\_ .icon-shape .label{text-align:center;}#chatgpt-mermaid-\_r_33a\_ .node.clickable{cursor:pointer;}#chatgpt-mermaid-\_r_33a\_ .root .anchor path{fill:rgb(175, 175, 175)!important;stroke-width:0;stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_33a\_ .arrowheadPath{fill:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_33a\_ .edgePath .path{stroke:rgb(175, 175, 175);stroke-width:1px;}#chatgpt-mermaid-\_r_33a\_ .flowchart-link{stroke:rgb(175, 175, 175);fill:none;}#chatgpt-mermaid-\_r_33a\_ .edgeLabel{background-color:rgb(0, 0, 0);text-align:center;}#chatgpt-mermaid-\_r_33a\_ .edgeLabel p{background-color:rgb(0, 0, 0);}#chatgpt-mermaid-\_r_33a\_ .edgeLabel rect{opacity:0.5;background-color:rgb(0, 0, 0);fill:rgb(0, 0, 0);}#chatgpt-mermaid-\_r_33a\_ .labelBkg{background-color:rgba(0, 0, 0, 0.5);}#chatgpt-mermaid-\_r_33a\_ .cluster rect{fill:rgb(48, 48, 48);stroke:rgba(255, 255, 255, 0.15);stroke-width:1px;}#chatgpt-mermaid-\_r_33a\_ .cluster text{fill:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33a\_ .cluster span{color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33a\_ div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";font-size:12px;background:rgb(48, 48, 48);border:1px solid rgba(255, 255, 255, 0.15);border-radius:2px;pointer-events:none;z-index:100;}#chatgpt-mermaid-\_r_33a\_ .flowchartTitleText{text-anchor:middle;font-size:18px;fill:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33a\_ rect.text{fill:none;stroke-width:0;}#chatgpt-mermaid-\_r_33a\_ .icon-shape,#chatgpt-mermaid-\_r_33a\_ .image-shape{background-color:rgb(0, 0, 0);text-align:center;}#chatgpt-mermaid-\_r_33a\_ .icon-shape p,#chatgpt-mermaid-\_r_33a\_ .image-shape p{background-color:rgb(0, 0, 0);padding:2px;}#chatgpt-mermaid-\_r_33a\_ .icon-shape .label rect,#chatgpt-mermaid-\_r_33a\_ .image-shape .label rect{opacity:0.5;background-color:rgb(0, 0, 0);fill:rgb(0, 0, 0);}#chatgpt-mermaid-\_r_33a\_ .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#chatgpt-mermaid-\_r_33a\_ .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#chatgpt-mermaid-\_r_33a\_ .node .neo-node{stroke:rgb(58, 132, 63);}#chatgpt-mermaid-\_r_33a\_ [data-look="neo"].node rect,#chatgpt-mermaid-\_r_33a\_ [data-look="neo"].cluster rect,#chatgpt-mermaid-\_r_33a\_ [data-look="neo"].node polygon{stroke:url(#chatgpt-mermaid-\_r_33a\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_33a\_ [data-look="neo"].swimlane.cluster rect{filter:none;}#chatgpt-mermaid-\_r_33a\_ [data-look="neo"].node path{stroke:url(#chatgpt-mermaid-\_r_33a\_-gradient);stroke-width:1px;}#chatgpt-mermaid-\_r_33a\_ [data-look="neo"].node .outer-path{filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_33a\_ [data-look="neo"].node .neo-line path{stroke:rgb(58, 132, 63);filter:none;}#chatgpt-mermaid-\_r_33a\_ [data-look="neo"].node circle{stroke:url(#chatgpt-mermaid-\_r_33a\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_33a\_ [data-look="neo"].node circle .state-start{fill:#000000;}#chatgpt-mermaid-\_r_33a\_ [data-look="neo"].icon-shape .icon{fill:url(#chatgpt-mermaid-\_r_33a\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_33a\_ [data-look="neo"].icon-shape .icon-neo path{stroke:url(#chatgpt-mermaid-\_r_33a\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_33a\_ .node text{font-size:14px;font-weight:600;letter-spacing:normal;fill:rgb(140, 223, 173);}#chatgpt-mermaid-\_r_33a\_ .edgeLabels text{font-size:13px;font-weight:600;letter-spacing:-0.08px;fill:rgb(140, 223, 173);}#chatgpt-mermaid-\_r_33a\_ .node tspan[font-weight="normal"],#chatgpt-mermaid-\_r_33a\_ .edgeLabels tspan[font-weight="normal"]{font-weight:600;}#chatgpt-mermaid-\_r_33a\_ .edgeLabel .label rect{opacity:1;rx:13px;ry:13px;fill:rgb(2, 28, 12);stroke:rgb(26, 75, 45);stroke-width:1px;}#chatgpt-mermaid-\_r_33a\_ .node rect,#chatgpt-mermaid-\_r_33a\_ .node circle,#chatgpt-mermaid-\_r_33a\_ .node ellipse,#chatgpt-mermaid-\_r_33a\_ .node polygon,#chatgpt-mermaid-\_r_33a\_ .node path{fill:rgb(0, 55, 22);stroke:rgba(255, 255, 255, 0.1);stroke-width:1px;}#chatgpt-mermaid-\_r_33a\_ .node rect{rx:16px;ry:16px;}#chatgpt-mermaid-\_r_33a\_ .node.mermaid-decision .label-container{fill:rgb(2, 28, 12);stroke:rgb(26, 75, 45);stroke-dasharray:2px,2px;}#chatgpt-mermaid-\_r_33a\_ .edgePaths .flowchart-link{stroke:rgb(175, 175, 175);stroke-width:1px;stroke-linecap:round;stroke-linejoin:round;}#chatgpt-mermaid-\_r_33a\_ .marker{fill:rgb(175, 175, 175);stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_33a\_ :root{--mermaid-font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";}Start Python InterpreterEnter Python StatementInterpreter Executes StatementDisplay ResultEnter Another Statement?Exit InterpreterYesNo

Explanation: The programmer enters a statement, Python executes it, and the result is displayed immediately. The process continues until the programmer exits the interpreter.

### Example

Open a terminal or command prompt and type `python` or `python3`, depending on your system.

```
>>> 10 + 2030>>> print("Hello, Python!")Hello, Python!>>> 5 * 420
```

Here, `>>>` represents the standard interactive prompt.

### Characteristics

- Executes commands as they are entered and completed.
- Displays the result of expressions automatically.
- Allows immediate testing of Python statements.
- Maintains variables and other session state during the session.
- Does not automatically save the session as a reusable `.py` program.

### Advantages

- Easy for beginners to learn.
- Provides immediate feedback.
- Useful for testing calculations and expressions.
- Helps experiment with functions, variables, and data types.

### Disadvantages

- Not convenient for large programs.
- Code must be saved separately if it needs to be reused.
- Managing many statements can become difficult.

### Applications

- Learning Python syntax.
- Testing small code snippets.
- Performing calculations.
- Experimenting with built-in functions and libraries.

## 3. Script Mode

### Definition

Script mode is a method of executing Python code by writing the program in a file, saving it with the `.py` extension, and running that file using the Python interpreter.

It is commonly used to develop complete programs, assignments, and applications. [Source: Python Documentation — Using the Python Interpreter](https://docs.python.org/3/tutorial/interpreter.html).

### Diagram

\#chatgpt-mermaid-\_r_33u\_{font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";font-size:16px;fill:rgb(237, 237, 237);}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#chatgpt-mermaid-\_r_33u\_ .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#chatgpt-mermaid-\_r_33u\_ .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#chatgpt-mermaid-\_r_33u\_ .error-icon{fill:rgb(48, 48, 48);}#chatgpt-mermaid-\_r_33u\_ .error-text{fill:rgb(237, 237, 237);stroke:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33u\_ .edge-thickness-normal{stroke-width:1px;}#chatgpt-mermaid-\_r_33u\_ .edge-thickness-thick{stroke-width:3.5px;}#chatgpt-mermaid-\_r_33u\_ .edge-pattern-solid{stroke-dasharray:0;}#chatgpt-mermaid-\_r_33u\_ .edge-thickness-invisible{stroke-width:0;fill:none;}#chatgpt-mermaid-\_r_33u\_ .edge-pattern-dashed{stroke-dasharray:3;}#chatgpt-mermaid-\_r_33u\_ .edge-pattern-dotted{stroke-dasharray:2;}#chatgpt-mermaid-\_r_33u\_ .marker{fill:rgb(175, 175, 175);stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_33u\_ .marker.cross{stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_33u\_ svg{font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";font-size:16px;}#chatgpt-mermaid-\_r_33u\_ p{margin:0;}#chatgpt-mermaid-\_r_33u\_ .label{font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33u\_ .cluster-label text{fill:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33u\_ .cluster-label span{color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33u\_ .cluster-label span p{background-color:transparent;}#chatgpt-mermaid-\_r_33u\_ .label text,#chatgpt-mermaid-\_r_33u\_ span{fill:rgb(237, 237, 237);color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33u\_ .node rect,#chatgpt-mermaid-\_r_33u\_ .node circle,#chatgpt-mermaid-\_r_33u\_ .node ellipse,#chatgpt-mermaid-\_r_33u\_ .node polygon,#chatgpt-mermaid-\_r_33u\_ .node path{fill:rgb(17, 40, 19);stroke:rgb(58, 132, 63);stroke-width:1px;}#chatgpt-mermaid-\_r_33u\_ .rough-node .label text,#chatgpt-mermaid-\_r_33u\_ .node .label text,#chatgpt-mermaid-\_r_33u\_ .image-shape .label,#chatgpt-mermaid-\_r_33u\_ .icon-shape .label{text-anchor:middle;}#chatgpt-mermaid-\_r_33u\_ .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#chatgpt-mermaid-\_r_33u\_ .rough-node .label,#chatgpt-mermaid-\_r_33u\_ .node .label,#chatgpt-mermaid-\_r_33u\_ .image-shape .label,#chatgpt-mermaid-\_r_33u\_ .icon-shape .label{text-align:center;}#chatgpt-mermaid-\_r_33u\_ .node.clickable{cursor:pointer;}#chatgpt-mermaid-\_r_33u\_ .root .anchor path{fill:rgb(175, 175, 175)!important;stroke-width:0;stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_33u\_ .arrowheadPath{fill:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_33u\_ .edgePath .path{stroke:rgb(175, 175, 175);stroke-width:1px;}#chatgpt-mermaid-\_r_33u\_ .flowchart-link{stroke:rgb(175, 175, 175);fill:none;}#chatgpt-mermaid-\_r_33u\_ .edgeLabel{background-color:rgb(0, 0, 0);text-align:center;}#chatgpt-mermaid-\_r_33u\_ .edgeLabel p{background-color:rgb(0, 0, 0);}#chatgpt-mermaid-\_r_33u\_ .edgeLabel rect{opacity:0.5;background-color:rgb(0, 0, 0);fill:rgb(0, 0, 0);}#chatgpt-mermaid-\_r_33u\_ .labelBkg{background-color:rgba(0, 0, 0, 0.5);}#chatgpt-mermaid-\_r_33u\_ .cluster rect{fill:rgb(48, 48, 48);stroke:rgba(255, 255, 255, 0.15);stroke-width:1px;}#chatgpt-mermaid-\_r_33u\_ .cluster text{fill:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33u\_ .cluster span{color:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33u\_ div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";font-size:12px;background:rgb(48, 48, 48);border:1px solid rgba(255, 255, 255, 0.15);border-radius:2px;pointer-events:none;z-index:100;}#chatgpt-mermaid-\_r_33u\_ .flowchartTitleText{text-anchor:middle;font-size:18px;fill:rgb(237, 237, 237);}#chatgpt-mermaid-\_r_33u\_ rect.text{fill:none;stroke-width:0;}#chatgpt-mermaid-\_r_33u\_ .icon-shape,#chatgpt-mermaid-\_r_33u\_ .image-shape{background-color:rgb(0, 0, 0);text-align:center;}#chatgpt-mermaid-\_r_33u\_ .icon-shape p,#chatgpt-mermaid-\_r_33u\_ .image-shape p{background-color:rgb(0, 0, 0);padding:2px;}#chatgpt-mermaid-\_r_33u\_ .icon-shape .label rect,#chatgpt-mermaid-\_r_33u\_ .image-shape .label rect{opacity:0.5;background-color:rgb(0, 0, 0);fill:rgb(0, 0, 0);}#chatgpt-mermaid-\_r_33u\_ .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#chatgpt-mermaid-\_r_33u\_ .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#chatgpt-mermaid-\_r_33u\_ .node .neo-node{stroke:rgb(58, 132, 63);}#chatgpt-mermaid-\_r_33u\_ [data-look="neo"].node rect,#chatgpt-mermaid-\_r_33u\_ [data-look="neo"].cluster rect,#chatgpt-mermaid-\_r_33u\_ [data-look="neo"].node polygon{stroke:url(#chatgpt-mermaid-\_r_33u\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_33u\_ [data-look="neo"].swimlane.cluster rect{filter:none;}#chatgpt-mermaid-\_r_33u\_ [data-look="neo"].node path{stroke:url(#chatgpt-mermaid-\_r_33u\_-gradient);stroke-width:1px;}#chatgpt-mermaid-\_r_33u\_ [data-look="neo"].node .outer-path{filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_33u\_ [data-look="neo"].node .neo-line path{stroke:rgb(58, 132, 63);filter:none;}#chatgpt-mermaid-\_r_33u\_ [data-look="neo"].node circle{stroke:url(#chatgpt-mermaid-\_r_33u\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_33u\_ [data-look="neo"].node circle .state-start{fill:#000000;}#chatgpt-mermaid-\_r_33u\_ [data-look="neo"].icon-shape .icon{fill:url(#chatgpt-mermaid-\_r_33u\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_33u\_ [data-look="neo"].icon-shape .icon-neo path{stroke:url(#chatgpt-mermaid-\_r_33u\_-gradient);filter:drop-shadow( 1px 2px 2px rgba(185,185,185,1));}#chatgpt-mermaid-\_r_33u\_ .node text{font-size:14px;font-weight:600;letter-spacing:normal;fill:rgb(140, 223, 173);}#chatgpt-mermaid-\_r_33u\_ .edgeLabels text{font-size:13px;font-weight:600;letter-spacing:-0.08px;fill:rgb(140, 223, 173);}#chatgpt-mermaid-\_r_33u\_ .node tspan[font-weight="normal"],#chatgpt-mermaid-\_r_33u\_ .edgeLabels tspan[font-weight="normal"]{font-weight:600;}#chatgpt-mermaid-\_r_33u\_ .edgeLabel .label rect{opacity:1;rx:13px;ry:13px;fill:rgb(2, 28, 12);stroke:rgb(26, 75, 45);stroke-width:1px;}#chatgpt-mermaid-\_r_33u\_ .node rect,#chatgpt-mermaid-\_r_33u\_ .node circle,#chatgpt-mermaid-\_r_33u\_ .node ellipse,#chatgpt-mermaid-\_r_33u\_ .node polygon,#chatgpt-mermaid-\_r_33u\_ .node path{fill:rgb(0, 55, 22);stroke:rgba(255, 255, 255, 0.1);stroke-width:1px;}#chatgpt-mermaid-\_r_33u\_ .node rect{rx:16px;ry:16px;}#chatgpt-mermaid-\_r_33u\_ .node.mermaid-decision .label-container{fill:rgb(2, 28, 12);stroke:rgb(26, 75, 45);stroke-dasharray:2px,2px;}#chatgpt-mermaid-\_r_33u\_ .edgePaths .flowchart-link{stroke:rgb(175, 175, 175);stroke-width:1px;stroke-linecap:round;stroke-linejoin:round;}#chatgpt-mermaid-\_r_33u\_ .marker{fill:rgb(175, 175, 175);stroke:rgb(175, 175, 175);}#chatgpt-mermaid-\_r_33u\_ :root{--mermaid-font-family:-apple-system-body,ui-sans-serif,-apple-system,system-ui,"Segoe UI","Helvetica","Apple Color Emoji","Arial",sans-serif,"Segoe UI Emoji","Segoe UI Symbol";}Write Python ProgramSave as program.pyRun File Using PythonInterpreterExecute Program StatementsDisplay Output

Explanation: The programmer writes the code in a file, saves it, and runs the file. Python executes the program, and any requested output is displayed.

### Example

Step 1: Create a file named `hello.py`.

Write the following code:

```
name = "Student"age = 20print("Hello,", name)print("Your age is", age)
```

Step 2: Save the file.

Save the program as `hello.py`.

Step 3: Execute the program.

Open a terminal in the directory containing the file and enter:

```
python hello.py
```

Depending on your operating system and installation, you may need to use `python3 hello.py` or `py hello.py`.

Step 4: Observe the output.

```
Hello, Student
Your age is 20
```

### Step-by-Step Execution

| Step | Statement                   | Explanation                                           |
| ---- | --------------------------- | ----------------------------------------------------- |
| 1    | `name = "Student"`          | Stores the string `"Student"` in the variable `name`. |
| 2    | `age = 20`                  | Stores the integer `20` in the variable `age`.        |
| 3    | `print("Hello,", name)`     | Displays the greeting and name.                       |
| 4    | `print("Your age is", age)` | Displays the age.                                     |

### Characteristics

- The program is written in a file, usually ending in `.py`.
- Multiple statements can be organized into a complete program.
- Code can be saved, edited, shared, and reused.
- Programs can be executed repeatedly.
- Suitable for larger applications and programming assignments.

### Advantages

- Easy to save and maintain code.
- Suitable for large programs.
- Supports functions, classes, and modules.
- Makes code reuse and debugging easier.
- Useful for developing applications and automation scripts.

### Disadvantages

- Requires writing and saving a file before execution.
- Testing a simple expression may take more steps than interactive mode.
- Errors may require modifying the file and running the program again.

### Applications

- University programming assignments.
- Application development.
- Automation and data processing.
- Programs containing multiple functions and classes.

## 4. Difference Between Interactive Mode and Script Mode

| Basis           | Interactive Mode                                                | Script Mode                                     |
| --------------- | --------------------------------------------------------------- | ----------------------------------------------- |
| Definition      | Executes code entered directly into the interpreter.            | Executes code saved in a Python file.           |
| Input           | Entered at the Python prompt.                                   | Written in a `.py` file.                        |
| Execution       | Commands execute interactively.                                 | The saved file is executed by the interpreter.  |
| Output          | Expression results are displayed automatically.                 | Use `print()` to display results when required. |
| Saving          | Session input is not automatically saved as a reusable program. | Source code is saved in a file.                 |
| Best suited for | Learning and quick experiments.                                 | Complete programs and applications.             |
| Reusability     | Commands may need to be saved separately.                       | The saved program can be run repeatedly.        |
| Example         | `>>> 5 + 3`                                                     | `python program.py`                             |

Important difference: In interactive mode, entering `5 + 3` displays `8` automatically. In a Python script, writing `5 + 3` alone does not normally display the result. To display it, write `print(5 + 3)`.

## 5. Important Points to Remember for Examinations

1. Python has two common execution modes: Interactive Mode and Script Mode.
2. Interactive mode is also known as REPL — Read, Eval, Print, Loop.
3. The `>>>` symbol is the standard interactive prompt.
4. Script mode uses a file with the `.py` extension.
5. The command `python program.py` is commonly used to execute a Python script.
6. Interactive mode is useful for quick testing, while script mode is suitable for complete programs.
7. Both modes use the Python interpreter to execute Python code.

## 6. Conclusion

Python provides two common ways to execute programs. Interactive mode allows programmers to enter commands and see results immediately, making it useful for learning and testing. Script mode allows programmers to save code in `.py` files and execute complete programs, making it suitable for assignments and application development.

## 7. References

1. Python Software Foundation — Using the Python Interpreter [https://docs.python.org/3/tutorial/interpreter.html](https://docs.python.org/3/tutorial/interpreter.html) Explains interactive mode, interpreter prompts, and executing Python scripts.
2. Python Software Foundation — Command-Line and Environment [https://docs.python.org/3/using/cmdline.html](https://docs.python.org/3/using/cmdline.html) Explains how to invoke Python and execute scripts from the command line.