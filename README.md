# LabelNode
Places The LabelNode Between Two SCNNodes,Basically we can show the distance and difference between two nodes etc..


## Usage

       let p1 = SCNNode() //Start Node
       let p2 =  SCNNode() //End Node
       
       //Adding the label node type and colour
       let distanceLabel = LabelNode(text: "meter", colour: .white)
       
       //Passing the nodes to Label nodes
       distanceLabel.placeBetweenNodes(p1, and: p2)
       //Add the Label node as child view of ARSCNView
       sceneView.scene.rootNode.addChildNode(distanceLabel)
