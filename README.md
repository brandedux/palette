# Palette
Simply download it and import it from your CSS library.

<img src="palette-example.png" />

## Getting started
Download or clone the code.<br /> 
```git clone https://github.com/brandedux/palette.git```

**Import Palette:**<br /> 
Import palette.scss into your app.scss or primary file.<br /> 
```@import './palette';```

**Example Class:**<br />
Include the palette class in your markup.<br />
```class="palette"```

Nest color, grayscale and alpha channel classes within the palette class.<br /> 
```class="bg-red txt-black alpha-50"```

Nested classes should be used like:<br />
```<div class="palette">```<br />
```  <p class="bg-red txt-black alpha-50">Warning!</p>```<br />
```</div>```<br />

#### 1. Prefixes for background and text colors
* bg = background color
* txt = text color

#### 2. Default color, tint and grayscale arrays
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
* grayscale-90
* grayscale-80
* grayscale-70
* grayscale-60
* grayscale-50
* grayscale-40
* grayscale-30
* grayscale-20
* grayscale-10 

#### 3. Alpha channel array
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
