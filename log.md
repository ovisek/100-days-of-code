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

**Link(s) to work**:

N/A


## Day 2: April 4, Wednesday

**Today's Progress**:

 - Created user with API access . Configured aws-cli with the given API access key id / API secret key before making API requests.
 - Used boto3 to connect to ec2 client and S3 resource.
 - Brief introduction to S3
 - Static website hosting on github - changing the github username had broken the menu links - fixed that.
 
**Thoughts**:

- Need to read the docs on aws-cli and using AWS API
- The jekyll personal blog project is long pending. Still some things are there that I need to get fixed.

**Link(s) to work**:

[personal blog](ovisek.github.io)

## Day 3: April 5, Thursday

**Today's Progress**:

- AWS - no new topics covered. Things I am pondering right now - IAM,S3. More reading / hands one required on these
- Struggling with testing the changes on a new development branch

**Thoughts**:

- I don't think I can dive right away into aws-cli and the AWS API calls - the core services need to be understood well and fiddle withe management console on these.
- Setting by the ruby dependencies on windows is a pain to say the least. Previously too lot of time was wasted in getting things set up and I'm repeating the same again - tried using Linux subsystem on Windows 10 , tried on CentOS-7 VM (this will work but couldn't get the guest additions enabled - so no way of syncing local copy with remote VM)
- Adding collections / tags to the blog is something I need to figure out.

**Link(s) to work**:

[personal blog](ovisek.github.io)

## Day 4: April 6, Friday

**Today's Progress**:

- Checked out how to host static website on S3
- Used aws-cli to get some basic details about the ec2 instance

**Thoughts**:

- Had this idea today of automating the #100DaysOfCode tweet to log the daily progress in response to a git commit.
Explored about webhooks, twitter API and also IFTTT service.

**Link(s) to work**:

N/A

## Day 5: April 7, Saturday

**Today's Progress**:

 - Going through the contents from the course [AWS Developer: Building on AWS][1]

**Thoughts**:

- Still pondering on automating the tweet for daily progress log.

**Link(s) to work**:
N/A

## Day 6: April 8, Sunday

**Today's Progress**:

- No progress.

**Thoughts**:

- In typical Sunday mode - but that's fine I guess - still determined to continue the next day with new vigour.

**Link(s) to work**:
N/A

## Day 7: April 9, Monday

**Today's Progress**:

- Week 1-2 : [AWS Developer: Building on AWS][1].
- Discovered that the webhook had been tweeting on my behalf - not quite the format I wanted : but some success here.

**Thoughts**:

- The additional readings and related whitepapers/docs needs to be read. Would concentrate next few days doing that before moving on to next week's content.

**Link(s) to work**:
N/A

## Day 8: April 10, Tuesday

**Thoughts**:


**Link(s) to work**:
N/A


------
[1]: https://courses.edx.org/courses/course-v1:AWS+OTP-AWSD1+1T2018/course/
[2]: https://www.udemy.com/amazon-web-services-aws-v/learn/v4/content
