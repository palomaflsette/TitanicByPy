=======================================
Joining the training and test datasets
=======================================

As we are preparing data for an ML model, it is a good idea to merge the training and test datasets into a single one, to separate again at the end, to ensure that the data will follow the same structure when we do feature engineering, so we will train the model on top of this architecture .

.. image:: images/_9.png
    :width: 700
    :alt: Alternative text


As with any real world dataset, we will always come across data that won't do any good and others that won't be very significant in the model. We will have to choose which features will be used for the ML model we are going to develop. In this case, let's consider the variables

*[‘PassengerId’, ‘Name’, ‘Ticket’, ‘Cabin’]*

because apparently they don't seem relevant.

.. image:: images/_10.png
    :width: 700
    :alt: Alternative text