# SwingGUI
This GUI is built with Swing and the NetBeans IDE.

The GUI is made to integrate the Swing API by designing a simple application that converts currency. 
Its GUI will be basic, focusing on only a subset of the available Swing components.
We will use the NetBeans IDE GUI builder, which makes user interface creation a simple matter of drag and drop.
Its automatic code generation feature simplifies the GUI development process, letting you focus on the application logic instead of the underlying infrastructure.

Because this module  is a step-by-step checklist of specific actions to take, it is recommended to run the NetBeans IDE and perform each step as moved forward.

With the exception of top-level containers, all Swing components whose names begin with "J" descend from the JComponent class. For example, JPanel, JScrollPane, JButton, and JTable all inherit from JComponent. However, JFrame and JDialog don't because they implement top-level containers.

The JComponent class extends the Container class, which itself extends Component. The Component class includes everything from providing layout hints to supporting painting and events. The Container class has support for adding components to the container and laying them out. 



If you prefer the traditional approach of programming each component manually (without the assistance of an IDE), think of this module 
as an entry point into the lower-level discussions already provided elsewhere in the tutorial.
