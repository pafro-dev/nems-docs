# nems-docs
Documentation for NEMS Linux

## Guidelines

### Images

When embedding an image, please place the image in /img and use the following format:

```
.. figure:: ../../img/relative_filename.jpg
  :width: 600
  :align: center
  :alt: Alt text describing image goes here

  Caption goes here
```

### Blocks

### Code Blocks

```
.. code-block:: console

    Here is some code.
    Here is the second line of code.
    If this is the final line of code, simply have a carriage return follwoing it.
```

#### Tip Block

```
.. Tip:: Text for the tip is here
```

#### Excercise Block

```
.. admonition:: Exercise
  :class: note
  
  Text for the exercise is here
```
