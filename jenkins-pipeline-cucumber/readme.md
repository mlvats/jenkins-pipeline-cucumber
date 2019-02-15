## Feature file is the starting point of Cucumber


Scenario: Play FizzBuzz to get Fizz
    Given Create a FizzBuzz game play
    When I play with number 3
    Then The result is "Fizz"
    
    
### Scenario: 
    Given  ->> We provide some pre-condition. This is before running test
    When -?We Provide Action
    Then ->> Output needs to be verfivied
 
Given -> precondition,
When -> provide Action
Then -> Asserttion


## Each Cucmber test case is called Scenario

git remote add origin https://github.com/mlvats/jenkins-pipeline-cucumber.git