# xcall
Call X-Callback-URLs From the Command Line. Outputs the `x-success` and `x-error` responses to `stdout`/`stderr`.

## Download

[Click here to download the latest version](https://github.com/martinfinke/xcall/releases/download/v1.0.1/xcall.app.zip).

## Usage

```bash
xcall.app/Contents/MacOS/xcall -url "myapp://x-callback-url/my-action?foo=bar" -activateApp YES
```

The `url` parameter is required. The optional `activateApp` parameter controls whether the target app is brought to the foreground. If omitted, it is `NO`.

## License

Copyright (c) 2017 Martin Finke

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

## Links

xcall is used in Rob Walton's wonderful [ulysses-python-client](https://github.com/robwalton/ulysses-python-client)!