# What I have done:

- Research how others have already done this (ie. taught robotics from home in a similar fashion)
1. Find out if there is any precedence and what the pedagogy was
2. May be able to find inspiration in how to implement

Useful links found so far:
https://www.therobotreport.com/tips-for-teaching-robotics-remotely-during-covid-19/
(How a lecturer taught ROS remotely)

https://www.youtube.com/watch?v=YXrKJHRPFBQ
(Mistakes when teaching ROS)

https://robomakerworkshops.com/
(Workshops conducted by AWS; content and structure are pretty good starting points for the actual project curriculum, though intensity may be rather substantial for a newcomer)

Notes to self:
Searches so far yielded little in terms of precedence beyond the case detailed in The Robot Report. Does open opportunities to be creative with the lesson plan however...

AWS Educate Robomaker course could be inspiration, though it has its flaws
i.e. It assumes you already know ROS to some degree. Will be seeking to address its weaknesses as part of writing my own course

# Ongoing:

- Curate and write content for the course instructions and gather AV media to complement (Eg. Videos made by others explaining concepts relevant to the course)

Notes to self:
1. Need to ensure that instructions and explanations are clear to non-technical persons as a number of instructions and explanations in the AWS Robomaker badge assume prior knowledge, like programming terms (classes, objects, etc.)
2. Need to determine what content is essential to teaching and what is not, i.e. what is just marketing in disguise, what are actual technical details to be distilled for the learners


- Study and experiment with ROS, associated tools, the various AWS services to be used

- Need to understand them better to aid writing explanations and instructions; understanding the tools and services involved would make it easier to distil important information for the non-technically inclined

Useful links found so far:

https://www.youtube.com/playlist?list=PLK0b4e05LnzZWg_7QrIQWyvSPX2WN2ncc
(The Construct’s Introduction to ROS)

https://www.youtube.com/playlist?list=PL_2PosskAdC25idJVMLOhu-4VAn8OYkQ1
(Course in programming a Raspberry Pi-based ROS robot; not directly related to AWS but is useful)

http://wiki.ros.org/turtlesim/Tutorials/Moving%20in%20a%20Straight%20Line
(ROS Wiki tutorial to move a robot based on user input. Can be useful for coming up with a lab session different from the AWS Educate lab)

https://github.com/timrobotson/aws-robomaker-tutorial-helloworld
(Can use the file structure, manifests, etc. without needing to come up with everything from scratch; good for teaching the project structure)


# Up next:
- Need to work out how to deploy course for trials IRL
- Need to format contents properly, design course flow, insert a feedback form for the actual course

*More things that I have not thought of following or between the items above…*

Eventually…

*More things that I have not thought of preceding or between the items below*

- Upload the content gathered into the chosen LMS/platform and format the course contents appropriately
1. Placement of images and videos must complement text instructions
2. Favour diagrams/screencaps over great walls of text

Trial the course with other students upon completion (Trial with other students)

Very important to test with those that have little to no technical background to test clarity of instructions and curriculum flow, and to test with the experienced ones to gauge technical accuracy

As a note to this point, consultations and trials have begun for the introductory module, as a form of checking whether the content flow is coherent, easily understood

Get general feedback (regardless of ability) on lesson materials and supplementary AV materials

Stretch goals:
Have the practical involve actual deployment to a real robot (Note that the Educate course has something like this already)
Criteria for robot:
Cheap (Ideally < $100)
Easy to build and maintain
	Potential candidates:

CamJam Edukit 3
https://thepihut.com/collections/camjam-edukit/products/camjam-edukit-3-robotics
(GBP 18 for an almost complete kit + chassis can be whatever that can be imagined; 3d printed chassis here: https://www.thingiverse.com/thing:1113796; need to determine if cargo forwarding or something similar can happen for this, if economical otherwise this is no go)

Waveshare Alphabot Basic Kit
https://www.amazon.sg/Arduino-Supplies-Waveshare-AlphaBot-Building/dp/B08D76B6PM/
OR https://www.waveshare.com/alphabot-pi.htm

(SGD 124, way more complete than the CamJam; does go above the budget but can be shipped here)

Notes to self: Need to determine how to deploy code from Cloud9 to the candidate robot above, if possible

Could look at these sites on how to do the deployment assuming i can get my hands on a robot to try it out myself
https://devopstar.com/2019/10/07/aws-iot-greengrass-cloudformation-raspberry-pi
https://devopstar.com/2019/10/27/aws-robomaker-raspberry-pi-bootstrap
