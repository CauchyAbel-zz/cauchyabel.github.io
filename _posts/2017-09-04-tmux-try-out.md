---
layout: post
title: tmux try out
---
Having been working on Linux and working on microservice architecture for a while. 
It has been really annoying to start up all dependent microservices whenever I restart my Linux box. 
So I was thinking of graceful way to handle all these dependent microservices once and for all. tmux was recommended by my colleague to do the job.  

tmux, i.e. '_terminal multiplexer_', is a very useful tool on top of bash to make multiple sessions under one bash window possible.
As is described on [tmux github repo](https://github.com/tmux/tmux),
> tmux enables a number of terminals (or windows)
  to be accessed and controlled from a single terminal. tmux is intended to be a
  simple, modern, BSD-licensed alternative to programs such as GNU screen.
  
So a simple and strightforward solution to my pain will be creating a tmux session and open a new window each time I need to start a microservice.
In this way I could easily switch between each microservice and monitor their console output.  

Here is my sample shell to this issue:

```shell
LUL test

```  

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}