STABL mirror of CMock ![CI](https://github.com/ThrowTheSwitch/CMock/workflows/CI/badge.svg)
=====
Welcome to the STABL mirror of CMock. This mirror was made to make small changes to better incorporate CMock in to our Make build system. More changes will likely come to this repository.

To get started, find the C Unittest guideline in Confluence.

Introduction
=====
CMock is a mock and stub generator and runtime for unit testing C. It's been designed
to work smoothly with Unity Test, another of the embedded-software testing tools
developed by ThrowTheSwitch.org. CMock automagically parses your C headers and creates
useful and usable mock interfaces for unit testing. Give it a try!

If you don't care to manage unit testing builds yourself, consider checking out Ceedling,
a test-centered build manager for unit testing C code.

Getting Started
================

If you're using Ceedling, there is no need to install CMock. It will handle it for you.
For everyone else, the simplest way is to grab it off github. You can also download it
as a zip if you prefer. The Github method looks something like this:

    > git clone --recursive https://github.com/throwtheswitch/cmock.git
    > cd cmock
    > bundle install # Ensures you have all RubyGems needed

If you plan to help with the development of CMock (or just want to verify that it can
perform its self tests on your system) then you can enter the test directory and then
ask it to test:

    > cd test
    > rake # Run all CMock self tests

API Documentation
=================

* Not sure what you're doing?
	* [View docs/CMock_Summary.md](docs/CMock_Summary.md)
* Interested in our MIT-style license?
	* [View docs/license.txt](LICENSE.txt)
* Are there examples?
	* They are all in [/examples](examples/)
* Any other resources to check out?
	* Definitely! Check out our developer portal on [ThrowTheSwitch.org](http://throwtheswitch.org)
