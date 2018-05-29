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

So when I write some JavaScript code might be portable between JavaScript executing environments/implementations/platforms I don't need to replace all the ```alert```s to ```WSH.Echo```s, or vice versa.

But that dream never came true.

Until the day I learned about how ```import``` works in ECMAScript 6.

It's how the idea sparked.

If there isn't a standard ```echo```, why don't not define it ourself?

So with a "standardized" ```echo```, I don't have to write one manually every time I need one!

And that is why I started this.

### In case you don't know or don't understand yet:

Initially ```import``` was defined in ECMAScript 4, but have been dropped in ECMAScript 5, because there is basically no way to make it work in the way web developers expected due to how web browsers locate and load script files for HTML(web pages) is significantly different from other platforms, in which ECMAScript 4 was initially thought would suit for due to ECMAScript's general-purposed nature.

That's why ECMAScript 6 doesn't say much about how ```import``` should work and leave to implementations -- in case of HTML(web pages), it's a responsibility for W3C/WHATWG.
