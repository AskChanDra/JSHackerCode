---
title: Sales by Match
author: AskChandra
date: 2021-01-13
excerpt: Sales by Match
---


# Jumping on the cloud


### Javascript

function jumpingOnClouds(c) {
var steps = [];
   
    let i=0;
    while(i < c.length - 1){
       
        if ((i+2<c.length) && (c[i+2] === 0)) {
            steps.push(c[i + 2]);
            i+=2;
        } else{
            steps.push(c[i + 1]);
            i+=1;
        } 
        
    }
    return steps.length

}
