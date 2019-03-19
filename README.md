# my-apollo-fetcher

在支付宝小程序中使用apollo client所需要的fetcher （https://github.com/kdong007/wx-apollo-fetcher）
是wx-apollo-fetcher的fork

# 安装
```
npm install my-apollo-fetcher --save
```
或者
```
yarn add my-apollo-fetcher
```

# 使用

```js
import { createHttpLink } from "apollo-link-http"; // 或者 apollo-link-batch-http
import myApolloFetcher from "my-apollo-fetcher";

const link = createHttpLink({ 
    uri: "xxxxx",
    fetch: myApolloFetcher,
});

```


