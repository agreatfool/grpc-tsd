grpc-tsd
========

## Deprecated!!
Since gRPC has published it's official definition, see [index.d.ts](https://github.com/grpc/grpc-node/blob/v1.7.x/packages/grpc-native-core/index.d.ts). Current project is deprecated.

## Attention
Current gRPC(v1.3.7) has no official TypeScript definition. But shall have one soon, see: [#11020](https://github.com/grpc/grpc/pull/11020). This repo would be `Deprecated` as soon as official d.ts online.

## Code base
Codes mostly come from [#11020](https://github.com/grpc/grpc/pull/11020), and a bit from [mixer/etcd3](https://github.com/mixer/etcd3/blob/master/src/types/grpc.d.ts). And partly self updated.

## Aim
Maintain a grpc.d.ts file for gRPC TypeScript project.

## How to use
### Install
```bash
npm install grpc-tsd --save-dev
```

### Code
Add following codes in `tsconfig.json`：
```
"include": [
    "node_modules/grpc-tsd/src/grpc.d.ts"
],
```

## Resources
* [gRPC node source doc](http://www.grpc.io/grpc/node/index.html)
* [#11020](https://github.com/grpc/grpc/pull/11020)
* [mixer/etcd3](https://github.com/mixer/etcd3/blob/master/src/types/grpc.d.ts)
* [How to write d.ts, by Example](http://www.typescriptlang.org/docs/handbook/declaration-files/by-example.html)