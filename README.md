<!DOCTYPE html>
<h1 class="snake">
>++++++++[<+++++++++>-]<.>++++[<+++++++>-]<+.+++++++..+++.>>++++++[<+++++++>-]<+ +.------------.>++++++[<+++++++++>-]<+.<.+++.------.--------.>>>++++[<++++++++>- ]<+.
</h1>

var animation = new TimelineMax({
    paused: !0,
    ease: Linear.easeNone
});
var T = 0;
var f = 30;

animation.add(
  TweenMax.to(e(".snake").parent(), f, {
        left: -5e3
}), T);

![swan.svg](swan.svg)[[swan.svg)]

</body>
</html> 
