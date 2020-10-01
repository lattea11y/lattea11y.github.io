Submitted to CHI 2021

## Source Code

Latte's source code and other supplementary materials can be found [here](https://drive.google.com/file/d/1_SAfUIVaEYfgSn_fx_jKjYYLQXwv_S2f/view?usp=sharing). It consists of several directories:

- Apps: APK files of apps under experiment
- Tests: The original test cases written for Appium testing framework
- UseCaseGenerator: The code corresponding to generating use cases from test scripts
- UseCases: The generated use cases 
- UseCaseExecutor: The code correspnding to executing use cases with an accessibility service.

## Approach

<img src="Approach.png" alt="An overview of Latte's approach" class="inline"/>


## Use-Case Executor

### Test Case (without any accessibility services)

This is the original test case in Walmart app representing signing in use case.

<iframe width="560" height="315" src="https://www.youtube.com/embed/gRzhExSEyMA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Use Case with TalkBack

This is the signing in use case execute by Latte using TalkBack.

<iframe width="560" height="315" src="https://www.youtube.com/embed/_1sGcqTrDqc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Accessibility Failure Examples

### Dynamic Layout

### TripIt

<iframe width="560" height="315" src="https://www.youtube.com/embed/BgKsD1d1zk8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


### Navigation Loop

#### Geek 

<iframe width="560" height="315" src="https://www.youtube.com/embed/aj0-JF6ioiE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

#### Calorie Counter

<iframe width="560" height="315" src="https://www.youtube.com/embed/LizH5yvNEcg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Non-Standard Implementation

### Yelp

<iframe width="560" height="315" src="https://www.youtube.com/embed/E0PMeGmNRk0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Feedly

<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipp6JBuhBE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Accessibility Warnings Examples

### Overlapping Layout

#### School Planner

<iframe width="560" height="315" src="https://www.youtube.com/embed/lV9in_-bjo8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Far-off Widgets

#### TripIt

<iframe width="560" height="315" src="https://www.youtube.com/embed/Kpor2-pzT-0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Grid Layout

#### Todo List

<iframe width="560" height="315" src="https://www.youtube.com/embed/vhyPKWqGv4E" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Web View

#### Dictionary

<iframe width="560" height="315" src="https://www.youtube.com/embed/VetWTdYKv1g" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
