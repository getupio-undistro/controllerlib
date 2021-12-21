Controllerlib is an Undistro component responsible for patching Kubernetes
objects from the <sigs.k8s.io/controller-runtime/pkg/client> package. This is
more frequently done when updating CRD instances during reconciliation, in such
a way to standardize the manner by which controllers mutate their target custom
type.
