# What is this?

This "Project" currently defines one and only one function, and it looks like this:
```
function echo(s){
  /* actual code which outputs s to somewhere else */
}
```

And as hinted by the comment, I will also provide some reference implementations for environment/platforms I have experiences with.

# Why?

Since the day I wrote my very first line of JavaScript code back in 2003, I always dream of having a universal ```echo``` function being implemented in every single JavaScript-running environment, or some kind of interfaces like that.

So when I move something between JavaScript executing environments/implementations/platforms it's no longer necessary to replace all the ```alert``` to ```WSH.Echo```, or something similar.

But that dream never came true.

Until the day I learned about how ```import``` works in ECMAScript 6.

That's where the inspiration kicks in.

If there isn't a standard ```echo```, why not just define it ourself?

So with a "standardized" ```echo```, I don't have to write one manually every time I need one!

**And this is the very beginning of *echo.js*.**

*In case you don't know or not fully understand yet:*

*Initially ```import``` was defined in ECMAScript 4, but have been dropped in ECMAScript 5, because there is essentially no way to effectively make it work for browsers in the way average developers would expect due to the way browsers deal with script files is significantly different from other platforms, in which ECMAScript 4 was initially thought should suit for given its general-purposed nature.*

*That's why ECMAScript 6 doesn't say much about how ```import``` should work and leave to implementations -- in case of HTML(web pages), it's a responsibility for W3C/WHATWG.*
