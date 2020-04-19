# 💎🌌 Calakmul

A decentralized network running your favorite apps, databases, and servers.
It uses ruby as language to deploy apps, that are shared through a network of nodes connected using Gossip protocol. 
Each node has its own execution environment and can talk with others, sharing objects in realtime.

Powered by `mruby`, `libp2p` and `rust`

## Run

Open a decentralized repl shell

```shell
cargo run
```

Open a second node connecting to the first

```shell
cargo run "/ip4/127.0.0.1/tcp/49276"
```

## Use

Declare an array on the first node

```shell
a = [1,2,3]
```

On the second node or any node connected to the network you can inspect the object

```shell
a.inspect
```

## License

Copyright 2020 Luis Silva

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.