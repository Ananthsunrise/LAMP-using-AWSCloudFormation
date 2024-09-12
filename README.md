# LAMP-using-CloudFormation

AWS CloudFormation is Amazon’s “infrastructure as code” solution, and is core to a lot of other services, especially on medium to large projects.  Rather than setting up infrastructure manually, just define what you want through code (in a JSON or YAML template), and let AWS do the rest of the work for you.  It’s repeatable, trackable, and can also help with cost savings.


**Benfits of cloudformation:**
1.huge time savibgs over manual work
2.repeatable
3.changes are also made as code
4.can delete all resources at once
5.estimate costs based on the template.

**Description:**
   In this , we create a new CloudFormation stack using a sample LAMP (Linux, Apache, MySQL and PHP) template provided by AWS.Finally we’ll ultimately look at the webpage that was created by deploying the stack.

**Step 1:
Creating stack in CloudFormation**

Go to aws cloudformation->click create a stack->click use a sample template->select LAMP Stack->create stack

**Step 2 :
View Webpage created by stack**

Go to aws cloudformation->Click the stack you created->click output->copy and paste the link in new browser

Now you can view that webpage.

**Step 3:
Deleting a stack and it's resources**

Go to aws cloudformation->Click the stack you created->click delete

By a single click you can delete all resources which was created....!

