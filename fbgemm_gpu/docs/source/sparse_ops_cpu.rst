Sparse Data Operators
======================

CUDA Operators
--------------

.. doxygenfunction:: permute_2D_sparse_data_cuda

.. doxygenfunction:: permute_1D_sparse_data_cuda

.. doxygenfunction:: expand_into_jagged_permute_cuda

.. doxygenfunction:: block_bucketize_sparse_features_cuda

.. doxygenfunction:: bucketize_sparse_features_cuda

.. doxygenfunction:: asynchronous_exclusive_cumsum_gpu

.. doxygenfunction:: asynchronous_inclusive_cumsum_gpu

.. doxygenfunction:: asynchronous_complete_cumsum_gpu

.. doxygenfunction:: offsets_range_cuda

.. doxygenfunction:: reorder_batched_ad_lengths_gpu

.. doxygenfunction:: reorder_batched_ad_indices_gpu

.. doxygenfunction:: batched_unary_embeddings_forward_cuda

.. doxygenfunction:: batched_unary_embeddings_backward_cuda

.. doxygenfunction:: jagged_1d_to_dense_gpu

.. doxygenfunction:: jagged_2d_to_dense_gpu

.. doxygenfunction:: stacked_jagged_1d_to_dense_gpu

.. doxygenfunction:: stacked_jagged_2d_to_dense_forward_cuda

.. doxygenfunction:: stacked_jagged_2d_to_dense_backward_cuda

.. doxygenfunction:: histogram_binning_calibration_cuda

CPU Operators
-------------

.. doxygenfunction:: permute_1D_sparse_data_cpu

.. doxygenfunction:: permute_2D_sparse_data_cpu

.. doxygenfunction:: expand_into_jagged_permute_cpu

.. doxygenfunction:: block_bucketize_sparse_features_cpu

.. doxygenfunction:: bucketize_sparse_features_cpu

.. doxygenfunction:: asynchronous_exclusive_cumsum_cpu

.. doxygenfunction:: asynchronous_inclusive_cumsum_cpu

.. doxygenfunction:: asynchronous_complete_cumsum

.. doxygenfunction:: offsets_range_cpu

.. doxygenfunction:: reorder_batched_ad_lengths_cpu

.. doxygenfunction:: reorder_batched_ad_indices_cpu

.. doxygenfunction:: jagged_1d_to_dense_cpu

.. doxygenfunction:: histogram_binning_calibration_cpu

.. doxygenfunction:: histogram_binning_calibration_by_feature

.. doxygenfunction:: generic_histogram_binning_calibration_by_feature

.. doxygenfunction:: segment_sum_csr

.. doxygenfunction:: lengths_range

.. doxygenfunction:: permute_sparse_features

.. doxygenfunction:: Bfloat16QuantizedToFloat

.. doxygenfunction:: FloatToBfloat16Quantized

.. doxygenfunction:: permute102_baddbmm_permute102

.. doxygenfunction:: permute_sequence_embeddings

.. doxygenfunction:: pack_segments

.. doxygenfunction:: index_select_dim0

