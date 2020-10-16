# grid

it's a 12-column grid system based on, you guessed it, css grid.

## features
- 12 column grid based on css grid
- responsive
- offsets
- display properties
- customisable through scss variables

## how to use
import `grid.scss` into your project

## example
```
<div class="grid">
    <div class="c-12 c-md-6 c-lg-8 offset-md-3 offset-lg-2">
        <h1>Column Example</h1>
    </div>
</div>
```

```
<div class="d-none d-md-block d-lg-flex">
    Hidden on mobile, display block on tablet, display flex on tablet landscape
</div>
```

## classes
`.grid` is the wrapper element for the grid structure

`.c-bp-width` is the column element, e.g `.c-lg-6`

## but... why?
i love bootstrap, but it's too much. all i need in a project is a solid grid structure, with the occasional hide/show div depending on the breakpoint. i hacked bootstrap so much that i nearly damn created a whole new version, so i figured i'd just build my own #devlife