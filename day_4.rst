.. code:: ipython3

    introduction to list datatype :

.. code:: ipython3

    students = ['salma','keerthi','naveen','mujeeb','sajith','meghana'] # 0,1,2,3,4,5

.. code:: ipython3

    print(students)


.. parsed-literal::

    ['salma', 'keerthi', 'naveen', 'mujeeb', 'sajith', 'meghana']
    

.. code:: ipython3

    introduction to indexing : 0,1,2,3,.......n

.. code:: ipython3

    print(students[1])


.. parsed-literal::

    keerthi
    

.. code:: ipython3

    print(students[1].title())


.. parsed-literal::

    Keerthi
    

.. code:: ipython3

    # req : i want to access mujeeb name in the output

.. code:: ipython3

    print(students[3].title())


.. parsed-literal::

    Mujeeb
    

.. code:: ipython3

    print(students)
    


.. parsed-literal::

    ['salma', 'keerthi', 'naveen', 'mujeeb', 'sajith', 'meghana']
    



.. code:: ipython3

    # req : i want to add sujitha to the above list...

.. code:: ipython3

    students.append('sujitha')

.. code:: ipython3

    print(students)


.. parsed-literal::

    ['salma', 'keerthi', 'naveen', 'mujeeb', 'sajith', 'meghana', 'sujitha']
    

.. code:: ipython3

    # req : i want to add harshitha to the above list...

.. code:: ipython3

    students.append('harshitha')
    

.. code:: ipython3

    print(students)


.. parsed-literal::

    ['salma', 'keerthi', 'naveen', 'mujeeb', 'sajith', 'meghana', 'sujitha', 'harshitha']
    

.. code:: ipython3

    # req : i want to add neha at 2nd index position....

.. code:: ipython3

    students.insert(2,'neha')

.. code:: ipython3

    print(students)


.. parsed-literal::

    ['salma', 'keerthi', 'neha', 'naveen', 'mujeeb', 'sajith', 'meghana', 'sujitha', 'harshitha']
    

.. code:: ipython3

    # req : i  want to modify keerthi name to kiran...

.. code:: ipython3

    students[1] = 'kiran'

.. code:: ipython3

    print(students)


.. parsed-literal::

    ['salma', 'kiran', 'neha', 'naveen', 'mujeeb', 'sajith', 'meghana', 'sujitha', 'harshitha']
    

.. code:: ipython3

    # req : i want to delete naveen in the above list...

.. code:: ipython3

    students[3].delete


::


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    Cell In[16], line 1
    ----> 1 students[3].delete
    

    AttributeError: 'str' object has no attribute 'delete'


.. code:: ipython3

    del students[3]

.. code:: ipython3

    print(students)


.. parsed-literal::

    ['salma', 'kiran', 'neha', 'mujeeb', 'sajith', 'meghana', 'sujitha', 'harshitha']
    



