# atom-language-xtpl

XTemplate support in Atom

## Installation

```bash
$ apm install atom-language-xtpl

# or

$ cd ~/.atom/packages
$ git clone https://github.com/LingyuCoder/atom-language-xtpl.git
```

## Syntax Highlight

File with `.xtpl` or `.xtemplate` will be highlight like this

![Syntax highlight](http://7q5asf.com1.z0.glb.clouddn.com/QQ20151129-1@2x.png)

## Snippets

### `xrq`:require

```
{{ require ("path") }}
```

### `xv`:variable

```
{{ variable }}
```

### `xr`:raw

```
{{%
  content
%}}
```

### `xc`:comment

```
{{! comment}}
```

### `xi`:include

```
{{ include ("path") }}
```

### `xet`:extend

```
{{ extend ("path") }}
```

### `xu`:use

```
{{ use ("path", params) }}
```

### `xs`:set

```
{{ set (dist=from) }}
```

### `xif`:if

```
{{#if (condition)}}content{{/if}}
```

### `xe`:each

```
{{#each (params)}}
  content
{{/each}}
```

### `xief`:if-else

```
{{#if (condition)}}
  content
{{else}}
  content
{{/if}}
```

### `xieef`:if-elseif-else

```
{{#if (condition)}}
  content
{{elseif (condition)}}
  content
{{else}}
  content
{{/if}}
```

### `xw`:with

```
{{#with}}
  content
{{/with}}
```

### `xbd`:block-define

```
{{#block ("name")}}
  content
{{/block}}
```

### `xb`:block

```
{{{block ("name")}}}
```

### `xm`:marco

```
{{#macro(params)}}
  content
{{/macro}}
```

## License

The MIT License (MIT)

Copyright (c) 2015 天镶

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
