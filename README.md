# A TS Grpc mood

## Try a first lib

https://grpc.io/

### Running first example code

* source : https://grpc.io/docs/languages/node/quickstart/

```bash
mkdir -p example/1
# Clone the repository to get the example code
git clone -b @grpc/grpc-js@1.9.0 --depth 1 --shallow-submodules https://github.com/grpc/grpc-node ./example/1/
# Navigate to the node example
cd ./example/1/examples
# Install the example's dependencies
# npm install
pnpm i
# Navigate to the dynamic codegen "hello, world" Node example:
cd helloworld/dynamic_codegen

```

## Tooling

* https://github.com/peterj/vscode-protobuf