---
---

<header>
<h1>Lorem ipsum dolor sit amet</h1>
</header>

## Section 1

### Vivamus ac auctor eros
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur ut neque sit amet neque facilisis condimentum. Suspendisse posuere risus at mi lacinia, ac cursus turpis dignissim. Vivamus non dictum felis. Ut tincidunt augue id ullamcorper vestibulum.

### In erat ligula

In auctor tellus eu metus pellentesque, quis facilisis nibh placerat. Commodo in lorem eget, vulputate bibendum ante. Etiam vestibulum quis diam a dapibus. Integer fermentum nec purus sed dictum. Donec fermentum et sapien eget suscipit. Fusce consequat est a ex molestie ultrices.

<img src="http://placehold.it/800x600">

## Section 2

Donec dictum hendrerit rutrum: 

> Proin ultrices hendrerit vestibulum. Curabitur non placerat metus. Donec suscipit ligula et aliquam semper. Fusce sed imperdiet augue. Suspendisse potenti. Cras vestibulum, metus et vulputate ornare, ante libero gravida felis, a bibendum magna felis ut tortor.

<img src="http://placehold.it/800x600">

## Section 3

Sed molestie augue libero, eget suscipit velit euismod ullamcorper.

`fibonacci.js`:

```javascript
var Fib = {
    [Symbol.iterator]() {
        var n1 = 1, n2 = 1;

        return {
            // make the iterator an iterable
            [Symbol.iterator]() { return this; },

            next() {
                var current = n2;
                n2 = n1;
                n1 = n1 + current;
                return { value: current, done: false };
            },

            return(v) {
                console.log(
                    "Fibonacci sequence abandoned."
                );
                return { value: v, done: true };
            }
        };
    }
};

for (var v of Fib) {
    console.log( v );

    if (v > 50) break;
}
// 1 1 2 3 5 8 13 21 34 55
// Fibonacci sequence abandoned.
```

## Section 4

### Pellentesque lobortis volutpat maximus 

Etiam condimentum:

- orci non consequat elementum
- tortor tellus viverra neque
- id dignissim nibh nisl id magna
- suspendisse aliquet dolor vehicula velit imperdiet

Suspendisse pretium molestie metus a consectetur. Sed nec interdum magna. Suspendisse efficitur, mi eget finibus mollis, orci tortor dignissim nisi, non vestibulum velit tellus ut odio. Praesent vitae sapien varius, mollis nunc vel, interdum nunc.

<img src="http://placehold.it/800x600">