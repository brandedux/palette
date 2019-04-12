# Palette
Simply download it and import it from your CSS library.

[![Build Status](https://api.travis-ci.org/brandedux/palette.svg?branch=master)](https://travis-ci.org/brandedux/palette)

## Getting started
Download or clone the code.<br /> 
```git clone https://github.com/brandedux/palette.git```

**Import Palette:**<br /> 
Import palette.scss into your app.scss or primary file.<br /> 
```@import './palette';```

**Example Class:**<br />
Include the palette classe in your markup.<br />
```class="palette"```

Nest color, greyscale and alpha channel classes within the palette class.<br /> 
```class="bg-red txt-black alpha-50"```

So that the final nested class appears like:
```
<div class="palette">
  <p class="bg-red txt-black alpha-50">Warning!</p>
</div>
```

#### 1. Prefixes for background and text colors
* bg = background color
* txt = text color

#### 2. Default color, tint and greyscale arrays
* red
* orange
* yellow
* green
* blue
* indigo
* violet

* ultraviolet

* black
* white

* greyscale-90
* greyscale-80
* greyscale-70
* greyscale-60
* greyscale-50
* greyscale-40
* greyscale-30
* greyscale-20
* greyscale-10 

#### 3. Opacity Class Array
* alpha-90
* alpha-80
* alpha-70
* alpha-60
* alpha-50
* alpha-40
* alpha-30
* alpha-20
* alpha-10


#### Copyright and License
Copyright (c) 2019, Jeff Davis.

Palette source code is licensed under the [MIT License](LICENSE).
