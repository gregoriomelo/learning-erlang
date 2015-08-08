# Learning some erlang

## Erlang by example

### Chapter 2 - Basic Erlang

#### Assignment

```
> A=10.
> {B,C,D}={1,2,3}.
> {E,E,foo}={5,5,foo}.
> [H|T] = [1,2,3].
> H.
1
> T.
[2,3]
```

#### Functions

```
-module(demo).
-export([double/1]).

% Doubling numbers

double(X) ->
  times(X, 2).

times(X, N) ->
  X * N.
```

Loading functions:

`c(demo).`
