npx protoc --plugin=protoc-gen-ts_proto=".\\node_modules\\.bin\\protoc-gen-ts_proto.cmd" --ts_proto_out=./ --ts_proto_opt=nestJs=true ./ proto/auth.proto
