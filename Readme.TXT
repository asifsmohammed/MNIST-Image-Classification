I made one modification to the file since it's resulting in errors

I changed bbelow code

from tensorflow import set_random_seed
set_random_seed(1)

to

tf.random.set_seed(1)