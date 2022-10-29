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

</body>
</html> 



![swan.svg](swan.svg)[[https://raw.githubusercontent.com/ungtb10d/kaos/main/swan.svg](https://github.com/ungtb10d/ungtb10d/raw/master/swan.svg)]
