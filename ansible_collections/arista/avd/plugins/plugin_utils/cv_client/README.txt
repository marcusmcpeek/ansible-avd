This package is expected to move to the pip-installable "cloudvision" package in the future.
For now we will maintain it here, as only AVD components rely on it.

./api/             gRPC client bindings for CloudVision Resource APIs using aristaproto (pip3 install aristaproto[compiler]).
./client/          Mid level abstraction of the CloudVision API, to hide some of the suboptimal APIs.
./deploy_to_cv     High level workflow abstrations to be moved to pyavd once pyavd becomes a dependency of Ansible-AVD.
Makefile           Makefile to rebuild the ./api/
mocked_classes.py  Mocked aristaproto and grpclib. Required to pass ansible sanity tests.
                   Once things move away from the ansible collection this can be removed again.
