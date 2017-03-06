# IEX Market Data Tools

IEX Market Data Tools contain applications for working with [near real-time
market data][API] from [IEX][].

  [API]: https://iextrading.com/developer/
  [IEX]: https://iextrading.com

IEX Market Data Tools require Node.

## IEX TAQ

IEX TAQ is an application that displays the best bids and offers (BBOs) and
trades based on near real-time market data from IEX.

### Usage

Run IEX TAQ:

```
iex-taq <symbol> [<symbol> ...]
```

The application displays the market events on the standard output formatted as
[TAQ][].

  [TAQ]: https://github.com/paritytrading/parity/blob/master/libraries/file/doc/TAQ.md

## License

Copyright 2017 Jussi Virtanen.

Released under the Apache License, Version 2.0. See `LICENSE.txt` for details.
