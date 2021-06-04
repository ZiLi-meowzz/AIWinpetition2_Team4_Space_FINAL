# AIWinpetition2_Team4_Space_FINAL

==The significance of the problem:==

According to the BBC science focus website, the density of the junk may become so great that it could hinder our ability to use weather satellites, and hence to monitor weather changes caused by our own ground-based pollution. This will adversely impact us as we may not be able to clear up the pollution quickly. For example, China's 2007 anti-satellite test, which used a missile to destroy an old weather satellite, added more than 3,500 pieces of large, trackable debris and many more smaller debris to the debris problem. This is only one of the problems that are caused by space debris. 

==How does clearance help?== 

Debris can endanger the lives of our astronauts and damage our spaceships. These debris travel quickly (approximately 15,700 m/h in low Earth orbit). Hence , if the debris and spaceship crashes against each other , the impact would be detrimental. So, the satellites have to make way for the space debris that are going in their direction so that the spaceships will not be damaged. The results would still remain the same regardless of the size of the debris.We can reduce these problems using the debris identifier.

What we have come up for the solution to this problem:

==Object detection:==

Using supervised learning, we can input a huge amount of data regarding the properties of common artificial debris found, so as to train the identifier to identify whether the type of debris is 'useful' ,'useless' or ‘unknown’. Most artificial debris in space comes from disposed or broken spacecraft such as spaceships, satellites. 

---> Useful debris means items that can bring more benefits than harm to our planet. These debris can be recycled to form meaningful items, or analysed to obtain extra information about that particular item which could benefit science. These examples of useful debris include fragments of airplane wings and bolts. 

---> Useless debris are generally items that are unnecessary, can bring more harm than benefit to the Earth, or cannot be reused. These examples include small paint fragments and garbage trash bags. 

---> Unknown debris are items that the debris identifier and mankind are unaware of. These items could be brought back to Earth to be examined and researched. 
Then unsupervised learning can be applied to train the identifier to find a pattern of which debris is 'useful', 'useless' and 'unknown'. 

Next, we will train and test the identifier to identify some data that is unknown to them and then use a confusion matrix to predict our model accuracy. 

==What does the identifier do:==

As shown from our prototype, the green area is where the identifier will scan the debris and classify it. After that, we are planning to have its bottom machine claw extended to reach out to the useful debris identified, while the one at the top, which will be made to be stronger to break parts of the identified 'unknown' debris for scientists to do research. When useless materials are detected, the identifier will alert the debris picker(which is another machine that has been used to clean up debris)(an image is shown under ‘inspiration’) to pick up the useless materials to be sent back to earth to destroy so that they will not loiter around the space to cause trouble to existing spacecraft and astronauts. When either of the 10% of storage for unknown materials or the 90% of storage for useful resources are filled up, the identifier will return to the space station to dispose of the resources collected, before setting off for another journey of identifying and collecting materials again.

