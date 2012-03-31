#Sublime Behat Snippets

Speed up your bdd writes!

nb: for Mink snippets, please use Mink folder.

## Installation

Clone the repo in your personal SublimeText2/Packages folder.

## Basic Usage

The snippets are easily accessible by just typing the triggerNames followed by the tab key.

Fill in then the placeholders with the needed values

### Available snippets (triggerNames)

`feature`

````
Feature: (Your feature)
	In order to (to what?)
	As a (as a what?)
	I need (what da ya need?)
````

`scenario`

````
Scenario: (Scenario Description)
	Given I (Given?)
	And (And?)
	When I (when?)
	Then I (then?)
````

`iHave`

````
/**
* @Given /I have a (What da ya hav?) "([^"]*)"/
*/
public function iHaveA(What da ya hav?)($name)
{
	//(Your code here...)
}
````

`iShould`

````
/**
* @Then /I should (What should ya do?) "([^"]*)" in category "([^"]*)"/
*/
public function iShould(CamelShould)(Arguments)
{
	//Your code here
}
````

## Todo's

* Add more snippets for Behat
* Add Mink snippets

`Feel free to improve this package`
