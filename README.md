compiled
========

Docker image for compiling [D][dlang] code.

Usage
-----

```d
/** hello.d */
import std.stdio;

void main()
{
    writeln("Hello world!");
}
```

```bash
docker run --rm -v $PWD:/app miklosmartin/compiled hello.d
```

[dlang]: http://dlang.org
