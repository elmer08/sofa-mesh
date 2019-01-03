<<<<<<< HEAD
# The Bug

Inconsistent package name generation between the import:

* import golang_org_x_net_context "golang.org/x/net/context"
* import google_golang_org_grpc "google.golang.org/grpc"

and the dummy vars:

* var _ context.Context
* var _ grpc.ClientConn
=======
# The Bug

Inconsistent package name generation between the import:

* import golang_org_x_net_context "golang.org/x/net/context"
* import google_golang_org_grpc "google.golang.org/grpc"

and the dummy vars:

* var _ context.Context
* var _ grpc.ClientConn
>>>>>>> 1.1.0-snapshot.4
