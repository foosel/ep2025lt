# Let's bind a harcover book!

## Where are the slides?

- Live presentation: https://foosel.github.io/ep2025lt/
- PDF Export: https://raw.githubusercontent.com/foosel/ep2025lt/main/slides.pdf

## Building the slides

Requirements: 

- Python3
- `pip install mkslides`
- NodeJS
- [Taskfile](https://taskfile.dev)

### Development server w/ live reload

``` bash
task serve
```

### Build

``` bash
task build
```

### Update the PDF export

``` bash
task export
```

## Shortcuts

- `S`: Pop-out window w/ speaker view