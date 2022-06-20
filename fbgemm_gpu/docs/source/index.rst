.. FBGEMM documentation master file, copied from fbgemm/docs
   on Wed Jun 8 17:19:01 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to FBGEMM's documentation!
=======================================

This documentation provides a comprehensive reference of the `fbgemm_gpu`
library documentation.

.. toctree::
   :maxdepth: 2
   :caption: fbgemm_gpu

   quantize_ops_gpu.rst
   quantize_ops_cpu.rst
   sparse_ops_gpu.rst
   sparse_ops_cpu.rst
   merge_pooled_embeddings_gpu.rst
   merge_pooled_embeddings_cpu.rst
   permute_pooled_embedding_ops_split_cpu.rst
   permute_pooled_embedding_ops_split_gpu.rst
   embedding_forward_quantized_host_cpu.rst
   input_combine_cpu.rst
   split_table_batched_embeddings.rst
   jagged_tensor_ops.cu.rst
   jagged_tensor_ops_cpu.rst
   cumem_utils_host.rst
   layout_transform_ops_cpu.rst
   ssd_split_table_batched_embeddings.rst

.. toctree::
   :maxdepth: 2
   :caption: codegen

   codegen.embedding_backward_split_host_template.rst
   codegen.embedding_backward_split_host_cpu_template.rst
   codegen.embedding_forward_quantized_host.rst
   codegen.embedding_bounds_check_host.rst
   codegen.embedding_bounds_check_host_cpu.rst
   codegen.embedding_backward_dense_host.rst
   codegen.embedding_backward_dense_host_cpu.rst
