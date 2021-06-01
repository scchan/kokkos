

# Subpackage name must match what appears in kokkos/cmake/Dependencies.cmake
#
KOKKOS_SUBPACKAGE(Example)

KOKKOS_ADD_EXAMPLE_DIRECTORIES(query_device)
KOKKOS_ADD_EXAMPLE_DIRECTORIES(tutorial)
KOKKOS_ADD_EXAMPLE_DIRECTORIES(virtual_functions)
KOKKOS_ADD_EXAMPLE_DIRECTORIES(virtual-functions)

KOKKOS_SUBPACKAGE_POSTPROCESS()

