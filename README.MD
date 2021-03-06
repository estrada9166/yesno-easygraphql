# YesNo example with EasyGraphQL

This is an example using [YesNo](https://github.com/FormidableLabs/yesno) and [EasyGraphQL](https://github.com/EasyGraphQL)
to mock your GraphQL requests.

+ [easygraphql-mock](https://github.com/EasyGraphQL/easygraphql-mock): Mock all the schema.
+ [easygraphql-tester](https://github.com/EasyGraphQL/easygraphql-tester): Using the method `.mock(query)` it returns the mock of the query.

## How to run
You can run it yourselves after cloning the repo.

```shell
$ npm install
$ npm run easygraphql-server
```

Then in a separate window
```shell
$ npm test
```

## easygraphql-server
Running this, you will have a mocked server of your GraphQL schema. It is using under the hood
[easygraphql-now](https://github.com/EasyGraphQL/easygraphql-now)

### The MIT License

Copyright (c) 2018 EasyGraphQL

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.