

page_type: reference
<style> table img { max-width: 100%; } </style>


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.contrib.graph_editor.get_tensors

``` python
tf.contrib.graph_editor.get_tensors(graph)
```



Defined in [`tensorflow/contrib/graph_editor/util.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.7/tensorflow/contrib/graph_editor/util.py).

See the guide: [Graph Editor (contrib) > Module: util](../../../../../api_guides/python/contrib.graph_editor#Module_util)

get all the tensors which are input or output of an op in the graph.

#### Args:

* <b>`graph`</b>: a `tf.Graph`.

#### Returns:

A list of `tf.Tensor`.

#### Raises:

* <b>`TypeError`</b>: if graph is not a `tf.Graph`.