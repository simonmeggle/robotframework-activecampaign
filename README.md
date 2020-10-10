# robotframework-activecampaign

Robot Framework library for testing ActiveCampaign resources and automations

This repository is a placeholder for my thoughts about a [Robot Framework](http://robotframework.org) library which can test [ActiveCampaign](https://activecampaign.com). 

ActiveCampaign is a great tool. 

But the more automations you build, the harder it is to keep track that all of this is working properly. 

This is where **automated testing** with the great tool [Robot Framework](http://robotframework.org) jumps in. 

The [robotframework-activecampaign](https://github.com/simonmeggle/robotframework-activecampaign) library can be used to ...

* check that a test user has certain tags
* assure that a list has certain members
* contacts exist
* automations work properly
* etc. 

There are still RF libraries which can email inboxes so that the complete cycle for a double opt-in could be tested. 

Automations could be expanded by a "test" mode so that if the contact is a certain test user, then time delays etc. will be shortened to speed up the execution time of the test.

If you are interested in such a library then file a new issue and let me know your thoughts/ideas! :-)
