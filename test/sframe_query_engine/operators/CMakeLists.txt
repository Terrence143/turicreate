project(Turi)

make_boost_test(sarray_source.cxx REQUIRES unity_shared_for_testing)
make_boost_test(sframe_source.cxx REQUIRES unity_shared_for_testing)
make_boost_test(project.cxx REQUIRES unity_shared_for_testing)
make_boost_test(transform.cxx REQUIRES unity_shared_for_testing)
make_boost_test(append.cxx REQUIRES unity_shared_for_testing)
make_boost_test(binary_transform.cxx REQUIRES unity_shared_for_testing)
make_boost_test(logical_filter.cxx REQUIRES unity_shared_for_testing)
make_boost_test(union.cxx REQUIRES unity_shared_for_testing)
make_boost_test(ternary_operator.cxx REQUIRES unity_shared_for_testing)

# The lambda test requires a pickled function without turicreate dependency
# make_boost_test(lambda_transform.cxx REQUIRES unity_shared_for_testing)
