<h1 align="center">Multi-Robot Path Finding</h1>

<p>This project focuses on the development of a multi-robot path finding solution in industrial applications. The goal is to enable multiple robots to navigate in a shared environment while avoiding collisions with each other and obstacles. The project utilizes a combination of Rapidly-exploring Random Trees (RRT), Artificial Potential Fields (APF), and coverage path planning techniques</p>

<h2>Rapidly Exploring Random Trees (RRT)</h2>
<p>The RRT algorithm is a significant category of path planning algorithms. In its original form, the RRT algorithm explores a vast unexplored region by expanding a tree randomly, eventually reaching the desired state. RRT offers several notable benefits, including probability completeness, ease of implementation, and excellent scalability.</p>

<h2>Artificial Potential Field (APF)</h2>
<p>The artificial potential field (APF) algorithm utilized in robot path planning, calculates the total force experienced by the robot by combining the attractive potential field and the repulsive potential field. The Swarm of Robots are guided through the space via the interactions of the Potential Field. </p>

<h2>Coverage Path Planning (CPP)</h2>
<p>Coverage Path Planning (CPP) in multi-robot path finding refers to the process of determining paths for multiple robots to collectively cover an entire area or region efficiently. The objective of CPP is to devise an optimal path for the robot that covers the maximum area with minimum time, energy, or cost.</p>

<h2>Layered Path Planning</h2>
<p>The Randomly Exploring Random Forest (RRT), Artificial Potential Field (APF) and Coverage Path Planning (CPP) algorithms are individually implemented and the results are included in the following sections. A layered planning strategy is then implemented which employs the three algorithms working together to find the
optimal path for multiple robots from a Start node to a Goal Node, all while avoiding Static and Dynamic obstacles encountered in the path.</p>
