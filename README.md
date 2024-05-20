# RAPIDS.AI : cuDF.pandas
In this repository I have used RAPIDS cuDF, which is a GPU DataFrame library that accelerates the data processing tool pandas with zero code changes.

cuDF is a Python GPU DataFrame library (built on the Apache Arrow columnar memory format) for loading, joining, aggregating, filtering, and otherwise manipulating tabular data using a DataFrame style API in the style of pandas. cuDF now provides a pandas accelerator mode (`cudf.pandas`), allowing you to bring accelerated computing to your pandas workflows without requiring any code change.

To verify that Pandas slowness on T4 GPUs is due to its lack of GPU optimization, we can use this library to leverage the parallel processing capabilities of GPUs, which can significantly improve the performance of data manipulation and analysis tasks.
By comparing the performance of Pandas and cuDF on the same dataset and hardware, we can empirically demonstrate the benefits of using cuDF for GPU-accelerated data processing. This will provide concrete evidence that Pandas' slowness on T4 GPUs is indeed due to its lack of GPU optimization.

## EXECUTION FLOW
![image](https://github.com/iiakshat/rapids-cudf-pandas/assets/92530735/f6376fc6-2b6d-4ee1-9fea-f12e5f0e70d5)

## RAPIDS Documentation and Resources

[DOCS](https://docs.rapids.ai/) serves to unify the documentation for RAPIDS. Whether you’re new to RAPIDS, looking to contribute, or are a part of the RAPIDS team, the docs will help guide you.

Visit [RAPIDS.ai](https://RAPIDS.ai) for more information on the overall project.
