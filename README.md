# Petrol Pipeline Anamoly Detection

## Problem
Detect the position of anamolies/flaws in petrol pipelines(each pipe) using a device called "Pig" that travels inside the pipes.

<img src='Blog-Become-a-Book-Banner.jpg'>

### Business Understanding
    - A long Petrol pipeline is not a singular material. It is a serial combination of smaller pipes fused with wielding process.
    - Pipeline pigging is a concept in pipeline maintenance that involves the use of devices known as pigs, which clean pipelines and are capable of checking pipeline condition.
    - This Pig will inspects the pipeline by sending magnetic flux into the walls of the pipe, detecting flaws in the pipeline.
    - Pipeline pigging is used in number of industries including oil & gas, lube oil, chemical plants and hygienic applications such as pharmaceutical or food.

![alt text](https://www.google.com/search?q=adsf&safe=active&sxsrf=ALeKk023tu3xZKJY_LzdkMkoSZvOgtOtQA:1594054267143&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjX1OHyirnqAhXWc30KHV1LBJMQ_AUoAnoECAwQBA&biw=1440&bih=740#imgrc=qD1rgGhQlsU8KM)

### Clean, Fast, Readable and Memory effecient Code

> - [x] Using DefaultDict to Accumulate Votes from all different bills
> - [x] Using Counter to count all senators with same voting patterns
> - [x] Using python comprehentions to make business logic clearer
> - [x] Using Iterator Protocols to save memory and increase execution time
> - [x] Improving Function definition and Tuple structures for comeback code readibility

### Testing done using
> - [x] Pytest
> - [x] PyFlakes

## Output
-------------- CLUSTER 1 --------------\
Senator(name='Sen. James Lankford [R]', party='Republican', state='OK')\
Senator(name='Sen. Dan Sullivan [R]', party='Republican', state='AK')\
Senator(name='Sen. Roger Wicker [R]', party='Republican', state='MS')\
Senator(name='Sen. John Boozman [R]', party='Republican', state='AR')\
Senator(name='Sen. Claire McCaskill [D]', party='Democrat', state='MO')\
Senator(name='Sen. David Vitter [R]', party='Republican', state='LA')\
Senator(name='Sen. Barbara Mikulski [D]', party='Democrat', state='MD')\
Senator(name='Sen. Patrick “Pat” Toomey [R]', party='Republican', state='PA')\
Senator(name='Sen. Ron Johnson [R]', party='Republican', state='WI')\
Senator(name='Sen. Daniel Coats [R]', party='Republican', state='IN')\
Senator(name='Sen. John McCain [R]', party='Republican', state='AZ')\
Senator(name='Sen. Bob Corker [R]', party='Republican', state='TN')\
Senator(name='Sen. Heidi Heitkamp [D]', party='Democrat', state='ND')\
Senator(name='Sen. Timothy Kaine [D]', party='Democrat', state='VA')

## Insights
We can observe that senates from different parties also have similar interests in certain bills other than members belonging to the same party. 

###### Tribute Raymond Hettinger
