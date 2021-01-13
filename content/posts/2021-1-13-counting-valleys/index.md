---
title: Counting Valleys
author: AskChandra
date: 2021-01-13
excerpt: Counting Valleys
---


# Counting Valleys


### Javascript

```js

function countingValleys(steps, path) {
    // Write your code here
    var currentLevel = 0;
    var seaLevel = 0 ;
    
    path = path.split('');
    for(var i = 0; i < path.length; i++ ) {
        
        if(path[i] === 'U') {
            currentLevel+= 1;
            if(currentLevel === 0 ) {
                seaLevel++;
            }
        } else {
            currentLevel-= 1; 
        }
    }
    
    return seaLevel;
}

```
