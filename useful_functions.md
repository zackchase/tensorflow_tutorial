
# Compiling a list of useful tensorflow functions. Some of this material is copied from pages of the tensorflow documentation.


###tf.zeros(shape, dtype=tf.float32, name=None)

###tf.zeros_like(tensor, dtype=None, name=None)

###tf.ones(shape, dtype=tf.float32, name=None)

###tf.ones_like(tensor, dtype=None, name=None)

###tf.fill(dims, value, name=None)
Creates a tensor filled with a scalar value.

###tf.constant(value, dtype=None, shape=None, name=Const)


###tf.linspace(start, stop, num, name=None)

###tf.range(start, limit=None, delta=1, name=range)

##Random Tensors

###tf.random_normal(shape, mean=0.0, stddev=1.0, dtype=tf.float32, seed=None, name=None)

###tf.truncated_normal(shape, mean=0.0, stddev=1.0, dtype=tf.float32, seed=None, name=None)

###tf.random_uniform(shape, minval=0, maxval=None, dtype=tf.float32, seed=None, name=None)

###tf.random_shuffle(value, seed=None, name=None)

###tf.set_random_seed(seed)
