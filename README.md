This Java program demonstrates a basic Event Scheduling System with integrated real-time communication functionality. 
The program uses Java's AWT (Abstract Window Toolkit) library to create a graphical user interface (GUI) 
and socket programming to enable client-server communication. It features a chat interface, allowing users to exchange messages.
The GUI includes a TextField for input, a TextArea to display messages, and a "Send" button to transmit user input. 
The application sets up a Socket connection to a server running on localhost at port 12000. 
Messages sent via the TextField are displayed in the TextArea and transmitted to the server using a DataOutputStream.
Incoming messages from the server are received using a DataInputStream and displayed in the chat interface
