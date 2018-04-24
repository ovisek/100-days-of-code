# 100 Days Of Code - Log

## Day 1: April 3, Tuesday

**Today's Progress**:

- Started with an introduction to AWS IAM services. 
- Configured SSH access to EC2 instance (AWS Linux AMI) via Putty on Windows
- Created new role and assigned to instance
- Installed boto3

**Thoughts**:

- I would like to get a clear picture how the SSH connections work - the maths and concepts behind assymetric keys / public / private keys. This may lead to digressing from the actual learning objectives , but I feel spending sometime on it is worth it.
- Also, I had started on getting an overview of the various AWS services and concepts - `refernce`:[Amazon Web Services (AWS) - Zero to Hero][2]. Few topics are yet to be covered. This isn't a exhaustive study but a general overview - will take up each of these one at a time while working on these from a programers perspective.
Atleast as of now I would like to be clear with all the available services and their use cases.

**Link(s)**:


## Day 2: April 4, Wednesday

**Today's Progress**:

 - Created user with API access . Configured aws-cli with the given API access key id / API secret key before making API requests.
 - Used boto3 to connect to ec2 client and S3 resource.
 - Brief introduction to S3
 - Static website hosting on github - changing the github username had broken the menu links - fixed that.
 
**Thoughts**:

- Need to read the docs on aws-cli and using AWS API
- The jekyll personal blog project is long pending. Still some things are there that I need to get fixed.

**Link(s)**:
[personal blog](ovisek.github.io)


## Day 3: April 5, Thursday

**Today's Progress**:

- AWS - no new topics covered. Things I am pondering right now - IAM,S3. More reading / hands one required on these
- Struggling with testing the changes on a new development branch

**Thoughts**:

- I don't think I can dive right away into aws-cli and the AWS API calls - the core services need to be understood well and fiddle withe management console on these.
- Setting by the ruby dependencies on windows is a pain to say the least. Previously too lot of time was wasted in getting things set up and I'm repeating the same again - tried using Linux subsystem on Windows 10 , tried on CentOS-7 VM (this will work but couldn't get the guest additions enabled - so no way of syncing local copy with remote VM)
- Adding collections / tags to the blog is something I need to figure out.

**Link(s)**:
[personal blog](ovisek.github.io)


## Day 4: April 6, Friday

**Today's Progress**:

- Checked out how to host static website on S3
- Used aws-cli to get some basic details about the ec2 instance

**Thoughts**:

- Had this idea today of automating the #100DaysOfCode tweet to log the daily progress in response to a git commit.
Explored about webhooks, twitter API and also IFTTT service.

**Link(s)**:


## Day 5: April 7, Saturday

**Today's Progress**:

 - Going through the contents from the course [AWS Developer: Building on AWS][1]

**Thoughts**:

- Still pondering on automating the tweet for daily progress log.

**Link(s)**:


## Day 6: April 8, Sunday

**Today's Progress**:

- No progress.

**Thoughts**:

- In typical Sunday mode - but that's fine I guess - still determined to continue the next day with new vigour.

**Link(s)**:


## Day 7: April 9, Monday

**Today's Progress**:

- Week 1-2 : [AWS Developer: Building on AWS][1].
- Discovered that the webhook had been tweeting on my behalf - not quite the format I wanted : but some success here.

**Thoughts**:

- The additional readings and related whitepapers/docs needs to be read. Would concentrate next few days doing that before moving on to next week's content.

**Link(s)**:


## Day 8: April 10, Tuesday

**Today's Progress**

- Watched video on Flask app development.

**Thoughts**:

- This is something I would need to work on later - this digresses from current schedule . Passive video watching doesn't help much unless some actual code is wriiten and tested using the things learnt.

**Link(s)**:


## Day 9: April 11, Wednesday

**Today's Progress**:

- Can't think of anything concrete that was done today.

**Thoughts**:

- Need to focus and decide on the next plan.

**Link(s)**:


## Day 10: April 12, Thursday

**Today's Progress**:

- Didn't learn new concepts . Exploring some new resources.

**Thoughts**:

- Fell sick today. Couldn't go to work as well

**Link(s)**


## Day 11: April 13, Friday

**Today's Progress**:

- Started with the basics of [node.js + express][11-1].

**Thoughts**:

**Link(s)**

[11-1]:https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs


## Day 12: April 14, Saturday

**Today's Progress**:

- Did some more reading from [Express+Node.js][11-1]. 

**Thoughts**:

- Looking for resources to learn about building a REST API using node.js

**Link(s)**

[12-1]:https://medium.freecodecamp.org/building-a-simple-node-js-api-in-under-30-minutes-a07ea9e390d2


## Day 13: April 15, Sunday

**Today's Progress**:

- Setup the development environment and started on a very basic app.

**Thoughts**:

- Next need to learn about [mongoose][13-1] and integrating with [MongoDB][13-2]

**Link(s)**

[13-1]:http://mongoosejs.com/docs/index.html
[13-2]:https://www.mongodb.com/


## Day 14: April 16, Monday

**Today's Progress**:

- Created an initial version of a Node.js app with express-generator that accepts github webhook events and processes the JSON request 
- Next step is to format the tweet message and send out a tweet using the twitter API
- Learnt about [dotenv][14-1] : working with .env files

**Thoughts**:

- The introduction has gone fine so far. There's so much more to explore - hopefully I'll get to learn while  doing app specific work

**Link(s)**

[14-1]: https://github.com/motdotla/dotenv


## Day 15: April 17, Tuesday

**Today's Progress**:

- Going through the Twitter API docs to understand the structure of a tweet object

**Thoughts**:

**Link(s)**:

## Day 16: April 18, Wednesday

**Today's Progress**:

**Thoughts**:

**Link(s)**:

[16-1]:https://zeit.co/now
[16-2]:https://ngrok.com/

## Day 17: April 19, Thursday

**Today's Progress**:

**Thoughts**:

**Link(s)**:

## Day 18: April 20, Friday

**Today's Progress**:

**Thoughts**:

**Link(s)**:

## Day 19: April 21, Saturday

**Today's Progress**:

**Thoughts**:

**Link(s)**:

## Day 20: April 22, Sunday

**Today's Progress**:

**Thoughts**:

**Link(s)**:

## Day 21: April 23, Monday

**Today's Progress**:

**Thoughts**:

**Link(s)**:

## Day 22: April 24, Tuesday

**Today's Progress**:

**Thoughts**:

**Link(s)**:

------
[1]: https://courses.edx.org/courses/course-v1:AWS+OTP-AWSD1+1T2018/course/
[2]: https://www.udemy.com/amazon-web-services-aws-v/learn/v4/content
[3]: https://github.com/desmondmorris/node-twitter
[4]: https://github.com/BoyCook/TwitterJSClient
