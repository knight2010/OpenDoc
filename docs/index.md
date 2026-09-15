# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

```python linenums="1" hl_lines="2 4"
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n - 1)
```

<div class="termynal" data-termynal>
    <span data-ty="input" data-ty-prompt="$ ">pip install mkdocs-material</span>
    <span data-ty="result">Successfully installed!</span>
    <span data-ty="input" data-ty-prompt="> ">print("Hello")</span>
    <span data-ty="result">Hello</span>
</div>

<div class="termy">

```console
$ uv pip install pandas matplotlib 
---> 100%
$ uv pip install --upgrade mkdocs-material pymdown-extensions
$ uv pip install mkdocs mkdocs-drawio
---> 100%
Successfully installed mkdocs 
```

</div>

<div class="termy">
```console
// You get a --help for free
$ typer main.py run --help

Usage: typer [PATH_OR_MODULE] run [OPTIONS] NAME

Run the provided Typer app.

╭─ Arguments ───────────────────────────────────────╮
│ *    name      TEXT  [default: None] [required]   |
╰───────────────────────────────────────────────────╯
╭─ Options ─────────────────────────────────────────╮
│ --help          Show this message and exit.       │
╰───────────────────────────────────────────────────╯

// Now pass the NAME argument
$ typer main.py run Camila

Hello Camila

// It works! 🎉
```
</div>

++option+shift+key++

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

++ctrl+alt+delete++

--8<-- "main.py"

- [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
- [ ] Vestibulum convallis sit amet nisi a tincidunt
    * [x] In hac habitasse platea dictumst
    * [x] In scelerisque nibh non dolor mollis congue sed et metus
    * [ ] Praesent sed risus massa
- [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque

$$f(x)$$

<iframe src="./Manim.pdf" width="100%" height="800px" style="border: 1px solid #ccc; overflow: auto;">
</iframe>


<div class="progress progress-100plus">
    <div class="progress-bar" style="width:100.00%">
        <p class="progress-label">100%</p>
    </div>
</div>

!!! warning "注意"
    请不要随意修改配置文件。
    https://facelessuser.github.io/pymdown-extensions/extensions/blocks/plugins/html/

!!! info inline end
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    ![](AutoMathMagic.drawio){ data-toolbar-zoom="false" }

!!! tip "提示标题"
    <div class="termynal" data-termynal>
    <span data-ty="input" data-ty-prompt="$ ">pip install mkdocs-material</span>
    <span data-ty="result">Successfully installed!</span>
    <span data-ty="input" data-ty-prompt="> ">print("Hello")</span>
    <span data-ty="result">Hello</span>
    </div>

![](AutoMathMagic.drawio){ data-toolbar-zoom="false" }


!!! Warning
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    ``` mermaid
    graph LR
    A[Start] --> B{Error?};
    B -->|Yes| C[Hmm...];
    C --> D[Debug];
    D --> B;
    B ---->|No| E[Yay!];
    ```


<iframe src="https://irreplacel.github.io/MkDocs/zh-Hant/%E5%A6%82%E4%BD%95%E5%88%9B%E5%BB%BA%E4%B8%80%E4%B8%AAMkDocs%E7%BD%91%E7%AB%99%E5%B9%B6%E8%87%AA%E5%8A%A8%E5%8C%96%E9%83%A8%E7%BD%B2%E5%88%B0GitHub%E4%B8%8A/" width="100%" height="800px" style="border: 1px solid #ccc; overflow: auto;">
</iframe>