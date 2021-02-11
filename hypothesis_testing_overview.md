
Codeup DS Students drink more coffee
than Codeup WD students

Null Hypothesis = same consumption rates
Alternative Hypothesis = consumption rates are different


alpha = 1 - confidence level
a = 1 - (what is our threshold for accepting findings even if they're random)

let's set our confidence level to be 95%
a = 1 - .95 = .05

a = 1 - .99 = .01 

a = 1 - .999 = .001 

lower alpha means lower tolerance for getting the results we get from chance/randomness

Set your confidence level and your alpha before you run any experiment




Boy who cried wold and Hypothesis Testing
- Type I error
- Boy cries wolf (making a hypothesis)
- villagers believe it 
- but it's not the case
- False Alarm
- False Positive
- Type I error
- Your check engine light comes on, but everything is OK
- boy cries wolf a second time (no actual wolf)
- villagers make another false alarm (type I error)

Type II 
- there IS a wolf, and the boy cries wolf!
- villagers disbelieve the hypothesis
- but the wolf was real 
- False Negative
- another way to say "false negative" is a miss.
- check engine lights stays off, but your engine actually has a problem

True/False is the reality
Positive/Negative is the prediction

True Positive = check engine light turns on, and there is a problem.
True Negative = check engine light remains off, and everything is find
False Positive = false alarm (engine light on, but no problem)
False Negative = miss = engine light stays off, but there's actually a problem


if p < alpha:
    print("Reject the null hypothesis")
else:
    print("Fail to reject the null hypothesis")


Null Hypothesis is that there is null difference, null effect, null relationship between things we're measuring
