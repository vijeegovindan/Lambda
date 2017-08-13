# Lambda

For these two "Mini-Activities" you will be solving some problems using your regular/OO techniques and then do the same thing with lambdas and streams.

Lambdas  

Let's start with anonymous inner classes and lambdas.

A "functional" interface is any interface that has one method.

Examples of functional interfaces are:

The run() method of Runnable
The compare() method of Comparator
The actionPerformed() method of ActionListener
(Even though Comparator has two methods, because equals() is contained in Object, it doesn't "count against" the 1 method limit - Comparator is still a functional interface)

An ActionListener can be added to a JButton (a class in AWT representing a button on a user interface). When the button is pressed the void actionPerformed(ActionEvent e) method will be called. This method can be coded using an anonymous inner class or a lambda, like in the example below.

See the starter files to code an anonymous class and a lambda for the Runnable and Comparator functional interfaces.
