---
layout: page
title: Animal Social Network Visualization
description: ASNViz, a multimedia analytics solution that facilitates the visualization and analysis of animal social networks (ASNs). 
img: assets/img/asn.jpg
importance: 1
category: Masters

---
We present ASNViz, a multimedia analytics solution that facilitates the visualization and analysis of animal social networks (ASNs). By modeling ASNs as networks of nodes and edges, ASNViz provides valuable insights into the dynamics and evolution of animal communities. The tool quantifies and visualizes the social structure at node and network levels, predicts future interactions when new individuals are added using deep-learning, and allows for manual updates based on empirical observations. The predictions of future interactions are made using Variational Graph Auto-Encoder models, which can be retrained and stored by the user while updating the network. A separate view gives insights to the evolution of networks based on the nodes and interactions observed and predicted between versions. ASNViz aims to bridge the gap between biology and complex network sciences, providing accessible network visualizations, interactions, and analytics for researchers interested in studying ASNs.


The following are the main user and system tasks:
<ul>
    <li><b>Task 1 (T1) User interacts with social network: </b> The user wants to interact with the animal nodes of the social network to know their particular features. The user should be able to manually add nodes and edges to the network. </li>
    <li><b> Task 2 (T2) System provides feedback to user interactions: </b> The system should be able to actively monitor user actions, and provide feedback in the form of real-time updates to the network. </li>
    <li><b> Task 3 (T3) Analyze the social network: </b> The user should be presented with insightful visualizations summarising information of various aspects - nodes, interactions, and the full network structure. These analytics should adapt to possible changes to the network. </li>
    <li> <b> Task 4 (T4) Visualizing the iterative evolution of network: </b> The user should be able to see a timeline of how the network has changed from the base snapshot to any updated snapshot. </li> 
    <li> <b> Task 5 (T5) System is adaptable to other networks: </b> The system should be dynamic, and should be able to adapt to any other animal social network.  </li>
</ul>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/asn_design_sketch.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Workflow Diagram of ASNViz. The arrows are labeled with tasks enumerated above. 
</div>


For an in-depth understanding of ASNViz, find our paper [here](https://github.com/madhu221b/animal_social_network/blob/main/report.pdf).

Also find the code of the project [here](https://github.com/madhu221b/animal_social_network/).

