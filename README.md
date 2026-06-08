# iam-go-contracts

Shared gRPC + event **contracts** for the IAM Go microservices: the `.proto`
sources and committed generated stubs (`gen/`). Consumed by
[iam-go-auth](https://github.com/malvinpratama/iam-go-auth),
[iam-go-user](https://github.com/malvinpratama/iam-go-user) and
[iam-go-gateway](https://github.com/malvinpratama/iam-go-gateway).

```go
import authv1 "github.com/malvinpratama/iam-go-contracts/gen/auth/v1"
```

Regenerate with `buf generate` (requires `buf`). Tagged `vMAJOR.MINOR.PATCH`;
consumers pin an exact version. Part of the [iam-go](https://github.com/malvinpratama/iam-go) platform.
