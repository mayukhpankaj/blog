---
layout: post
title:  "Boolean bit or byte ?"
date:   2021-10-10 3:15:00
categories: programming
---
Yesteday I stumbled on a question, Do you know how much memory a boolean variable takes ?

1 bit right ? cause boolean is just about the vaule is 1 or 0, true or false !
but actually it takes 1 byte. 

{% highligh c++ %}
int main(){

cout<<sizeof(bool);

return 0;
}

{% endhighlight %}

it returns 1 byte. So why a bool takes 1 byte that is 8 bits instead of 1 bit ? wasting 7 bits ?

It is because a Byte is the smallest addressable memory unit in C/C++. 


Thank you for reading !
