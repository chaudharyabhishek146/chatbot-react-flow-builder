# chatbot-react-flow-builder

A chatbot flow is built by connecting multiple messages together to decide the
order of execution.
<img width="910" alt="image" src="https://github.com/chaudharyabhishek146/chatbot-react-flow-builder/assets/71595464/2faf4181-3839-4fdf-aa92-6da3d39f39dd">

# Features:
  1. Text Node
    a. Our flow builder currently supports only one type of message (i.e Text Message).
    b. There can be multiple Text Nodes in one flow.
    c. Nodes are added to the flow by dragging and dropping a Node from the Nodes Panel.
  2. Nodes Panel
    a. This panel houses all kind of Nodes that our Flow Builder supports.
    b. Right now there is only Message Node, but we’d be adding more types of Nodes in the future so make this section extensible
  3. Edge
    a. Connects two Nodes together
  4. Source Handle
    a. Source of a connecting edge
    b. Can only have one edge originating from a source handle
  5. Target Handle
    a. Target of a connecting edge
    b. Can have more than one edge connecting to a target handle
  6. Settings Panel
     a. Settings Panel will replace the Nodes Panel when a Node is selected.
     <img width="910" alt="image" src="https://github.com/chaudharyabhishek146/chatbot-react-flow-builder/assets/71595464/fd5bdb80-b519-4f5a-a175-2b1b6cbbe0f6">

     b. It has a text field to edit text of the selected Text Node
  8. Save Button
    a. Button to save the flow
    b. Save button press will show an error if there are more than one Nodes and more than one Node has empty target handles.

Deploy a working version on a free hosting versios on Heruko  " ".
