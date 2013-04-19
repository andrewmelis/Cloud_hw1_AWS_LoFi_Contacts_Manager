Andrew Melis
Cloud Computing, Spring 2013
HW 1


LoFi AWS Contacts Manager

================================



To begin, you'll need to have a file in your local directory called config.yml.
It can be and should be the exact same file that you set up for Amazon's S3 samples.
However, I've also included a config.yml template--you can simply paste in your credentials if you don't have the sample.
The script will not run correctly if either the config.yml file is missing or if the access credentials inside are bad.

You'll also need to make sure you have the other included files,
contacts.rb, config.rb, and template_contact.html,
as well as the included directory, called contacts,
in order for this script to work.

Also note that the script will create local contact files in the included "contacts" directory.


To run the script, type "ruby contacts.rb" in the command line.


One question, that may be worth addressing to the entire class:
  Is there a built-in way to check whether the current user
  has access to a given bucket?

  I could not find one in Amazon's documentation, 
  and writing the testBucketAccess method
  was more difficult than expected
