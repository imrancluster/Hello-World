# Hello-World

This is a custom module for explore very basic Drupal Tests.

###Installation
1. Install the [simpletest](https://www.drupal.org/project/simpletest) module
2. Install the Hello World module
3. Go to the http://example.com/admin/config/development/testing
4. Find and select and click on the **Run tests** button
5. You can also run the following command for testing-

* php ./scripts/run-tests.sh --url http://example.com/ --class HelloworldTests
* php ./scripts/run-tests.sh --url http://example.com/ --directory /full-path/drupal7/sites/all/modules/helloworld