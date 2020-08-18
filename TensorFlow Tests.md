```python
import tensorflow as tf
```


```python
A = tf.constant([[1,2,3], [4,5,6]])
B = tf.constant([[0,0], [1,0],[0,1]])
X = tf.constant([0,1,0])
```


```python
print(tf(A))
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    <ipython-input-3-5de12cf6fc78> in <module>
    ----> 1 print(tf.Session().run(A))
    

    AttributeError: module 'tensorflow' has no attribute 'Session'

