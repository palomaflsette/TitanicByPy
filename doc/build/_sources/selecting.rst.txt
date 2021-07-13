===================
Selecting features
===================

As with any real world dataset, we will always come across data that won't do any good and others that won't be very significant in the model. We will have to choose which features will be used for the ML model we are going to develop. In this case, let's consider the variables

*[‘PassengerId’, ‘Name’, ‘Ticket’, ‘Cabin’]*

because apparently they don't seem relevant.

.. image:: images/_10_.png
    :width: 600
    :alt: Alternative text


Thus, we are left with the following variables to be treated and prepared:

*['Pclass', 'Sex', 'Age', 'SibSp', 'Parch', 'Fare', 'Embarked']*.
