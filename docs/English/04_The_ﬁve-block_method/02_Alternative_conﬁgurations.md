# 4.2 Alternative conﬁgurations
Consider the following hand. What would you discard and why?

<div class="no-border">

<img alt="drawtile" src="/assets/image/tiles/3-man.png">
<img alt="drawtile" src="/assets/image/tiles/3-man.png">
<img alt="drawtile" src="/assets/image/tiles/4-man.png">
<img alt="drawtile" src="/assets/image/tiles/6-man.png">
<img alt="drawtile" src="/assets/image/tiles/2-pin.png">
<img alt="drawtile" src="/assets/image/tiles/2-pin.png">
<img alt="drawtile" src="/assets/image/tiles/4-pin.png">
<img alt="drawtile" src="/assets/image/tiles/5-pin.png">
<img alt="drawtile" src="/assets/image/tiles/6-pin.png">
<img alt="drawtile" src="/assets/image/tiles/6-pin.png">
<img alt="drawtile" src="/assets/image/tiles/7-pin.png">
<img alt="drawtile" src="/assets/image/tiles/chun.png">
<img alt="drawtile" src="/assets/image/tiles/chun.png">
<img alt="drawtile" src="/assets/image/tiles/chun.png">



</div>

Let’s ﬁrst divide the hand into ﬁve tile blocks.

<fieldset class="no-border">
<legend>(4.3)</legend>
<div class="garisbawah">
    <div class="empty-container">
        <img alt="drawtile" src="/assets/image/tiles/3-man.png">
        <img alt="drawtile" src="/assets/image/tiles/3-man.png">
        <img alt="drawtile" src="/assets/image/tiles/4-man.png">
        <img alt="drawtile" src="/assets/image/tiles/6-man.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img alt="drawtile" src="/assets/image/tiles/2-pin.png">
        <img alt="drawtile" src="/assets/image/tiles/2-pin.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img alt="drawtile" src="/assets/image/tiles/4-pin.png">
        <img alt="drawtile" src="/assets/image/tiles/5-pin.png">
        <img alt="drawtile" src="/assets/image/tiles/6-pin.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img alt="drawtile" src="/assets/image/tiles/6-pin.png">
        <img alt="drawtile" src="/assets/image/tiles/7-pin.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
      <img alt="drawtile" src="/assets/image/tiles/chun.png">
      <img alt="drawtile" src="/assets/image/tiles/chun.png">
      <img alt="drawtile" src="/assets/image/tiles/chun.png">
    </div>
    <hr class="my-line">
</div>

</fieldset>


This makes it clearer that, just like the previous example, ![singletile](../../assets/image/tiles/6-man.png) is creating a redundant closed-wait protorun, so we should discard it. Also, discarding ![singletile](../../assets/image/tiles/6-man.png) makes this a three-tile block.

<br>

However, there is an alternative way to divide this hand into ﬁve blocks, and situational changes may call for such an alternative conﬁguration. Suppose that your opponents have already discarded all four tiles of ![singletile](../../assets/image/tiles/2-man.png). Suppose also that ![singletile](../../assets/image/tiles/3-pin.png) seems live in the wall. Or, suppose ![singletile](../../assets/image/tiles/3-man.png) ‌- ![singletile](../../assets/image/tiles/6-man.png) tiles seem too dangerous to discard against an opponent. Then, we might want to divide the hand in the following way instead.
‌‌
<br>

<fieldset class="no-border">
<legend>(4.4)</legend>
<div class="garisbawah">
    <div class="empty-container">
        <img alt="drawtile" src="/assets/image/tiles/3-man.png">
        <img alt="drawtile" src="/assets/image/tiles/3-man.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img alt="drawtile" src="/assets/image/tiles/4-man.png">
        <img alt="drawtile" src="/assets/image/tiles/6-man.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img alt="drawtile" src="/assets/image/tiles/2-pin.png">
        <img alt="drawtile" src="/assets/image/tiles/2-pin.png">
        <img alt="drawtile" src="/assets/image/tiles/4-pin.png">
        <img alt="drawtile" src="/assets/image/tiles/5-pin.png">
        <img alt="drawtile" src="/assets/image/tiles/6-pin.png">
        <img alt="drawtile" src="/assets/image/tiles/6-pin.png">
        <img alt="drawtile" src="/assets/image/tiles/7-pin.png">
    </div>
    <hr class="my-line">
    <div class="decrease-margin-top">2</div>
</div>

<div class="garisbawah">
    <div class="empty-container">
      <img alt="drawtile" src="/assets/image/tiles/chun.png">
      <img alt="drawtile" src="/assets/image/tiles/chun.png">
      <img alt="drawtile" src="/assets/image/tiles/chun.png">
    </div>
    <hr class="my-line">
</div>

</fieldset>


That is, we aim to make the pair of ![singletile](../../assets/image/tiles/3-man.png) the head of this hand, and we seek to have two runs in pinzu (dots). If we discard ![singletile](../../assets/image/tiles/2-pin.png), this block becomes ![singletile](../../assets/image/tiles/2-pin.png) ![singletile](../../assets/image/tiles/4-pin.png) ![singletile](../../assets/image/tiles/5-pin.png) ![singletile](../../assets/image/tiles/6-pin.png) ![singletile](../../assets/image/tiles/6-pin.png) ![singletile](../../assets/image/tiles/7-pin.png). Recall that a block like this can be split into ![singletile](../../assets/image/tiles/2-pin.png) ![singletile](../../assets/image/tiles/4-pin.png) ![singletile](../../assets/image/tiles/6-pin.png) + ![singletile](../../assets/image/tiles/5-pin.png) ![singletile](../../assets/image/tiles/6-pin.png) ![singletile](../../assets/image/tiles/7-pin.png) (recall the discussion of double closed shape in Section 3.3.1). Therefore, this block can accept ![singletile](../../assets/image/tiles/3-pin.png) as well as ![singletile](../../assets/image/tiles/5-pin.png)- ![singletile](../../assets/image/tiles/9-pin.png) to make two runs in pinzu. The block in pinzu will have six tiles, but this is OK because this block is worth two.

To master the ﬁve-block method, we need to be able to instanta- neously envision the ﬁrst block conﬁguration (4.3) the moment we see this hand. However, that is not enough. We should also be able to imagine an alternative conﬁguration (4.4) at the same time. In the game of mahjong, situations change very quickly each time a new tile gets drawn or a new tile gets discarded. Therefore, the ideal ﬁve-block conﬁguration would also change accordingly as situations evolve. We thus need to develop our skills to picture many possible ﬁve-block conﬁgurations and to prepare for possible situational changes that would call for a change in the conﬁguration.

I provide several exercises in the following pages. The answer key to each exercise is provided on the next page. Try not to look at the answers before you actually derive your own answer.


## **Exercises: ﬁnding a redundant tile**

### Excersise 1

<fieldset class="mahjong-group">
<legend class="left-align">Exercise 1</legend>

<div class="discard-question">What would you discard?</div>
<div class="discard-question">How do you divide the hand into tile blocks</div>

<img class="drawtile" src="/assets/image/tiles/3-man.png">
<img class="drawtile" src="/assets/image/tiles/4-man.png">
<img class="drawtile" src="/assets/image/tiles/6-man.png">
<img class="drawtile" src="/assets/image/tiles/6-man.png">
<img class="drawtile" src="/assets/image/tiles/3-pin.png">
<img class="drawtile" src="/assets/image/tiles/4-pin.png">
<img class="drawtile" src="/assets/image/tiles/5-pin.png">
<img class="drawtile" src="/assets/image/tiles/3-sou.png">
<img class="drawtile" src="/assets/image/tiles/3-sou.png">
<img class="drawtile" src="/assets/image/tiles/5-sou.png">
<img class="drawtile" src="/assets/image/tiles/6-sou.png">
<img class="drawtile" src="/assets/image/tiles/7-sou.png">
<img class="drawtile" src="/assets/image/tiles/7-sou.png">


<figure class="caption2">
    <img src="/assets/image/tiles/4-sou.png"
         alt="checktile">
    <figcaption>Draw</figcaption>
</figure>

</fieldset>

<fieldset class="mahjong-group">
<legend>Answer 1</legend>


<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/3-man.png">
        <img class="drawtile" src="/assets/image/tiles/4-man.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/6-man.png">
        <img class="drawtile" src="/assets/image/tiles/6-man.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/3-pin.png">
        <img class="drawtile" src="/assets/image/tiles/4-pin.png">
        <img class="drawtile" src="/assets/image/tiles/5-pin.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/3-sou.png">
        <img class="drawtile" src="/assets/image/tiles/3-sou.png">
        <img class="drawtile" src="/assets/image/tiles/4-sou.png">
        <img class="drawtile" src="/assets/image/tiles/5-sou.png">
        <img class="drawtile" src="/assets/image/tiles/6-sou.png">
        <img class="drawtile" src="/assets/image/tiles/7-sou.png">
        <img class="drawtile" src="/assets/image/tiles/7-sou.png">
    </div>
    <hr class="my-line">
    <div class="decrease-margin-top">2</div>
</div>


<div class="discard-question">With the draw of <img src="/assets/image/tiles/4-pin.png" alt="singletile">, we now have a 3-way side-wait block in
souzu (bamboos). 
<img src="/assets/image/tiles/3-pin.png" alt="singletile"> or 
<img src="/assets/image/tiles/7-pin.png" alt="singletile"> could be our back-up candidate for
the head, in case we draw another 
<img src="/assets/image/tiles/6-man.png" alt="singletile">. Since there is a potential
for sanshoku (Mixed Triple Chow) of 345, we discard 
<img src="/assets/image/tiles/3-pin.png" alt="singletile">
.</div>

</fieldset>


### Excersise 2


<fieldset class="mahjong-group">
<legend class="left-align">Exercise 2</legend>

<div class="discard-question">What would you discard?</div>
<div class="discard-question">How do you divide the hand into tile blocks</div>

<img alt="drawtile" src="/assets/image/tiles/5-man.png">
<img alt="drawtile" src="/assets/image/tiles/7-man.png">
<img alt="drawtile" src="/assets/image/tiles/1-pin.png">
<img alt="drawtile" src="/assets/image/tiles/1-pin.png">
<img alt="drawtile" src="/assets/image/tiles/2-pin.png">
<img alt="drawtile" src="/assets/image/tiles/3-pin.png">
<img alt="drawtile" src="/assets/image/tiles/4-pin.png">
<img alt="drawtile" src="/assets/image/tiles/4-pin.png">
<img alt="drawtile" src="/assets/image/tiles/5-pin.png">
<img alt="drawtile" src="/assets/image/tiles/7-pin.png">
<img alt="drawtile" src="/assets/image/tiles/3-sou.png">
<img alt="drawtile" src="/assets/image/tiles/5-sou.png">
<img alt="drawtile" src="/assets/image/tiles/5-sou.png">


<figure class="caption2">
    <img src="/assets/image/tiles/4-pin.png"
         alt="checktile">
    <figcaption>Draw</figcaption>
</figure>


</fieldset>




<fieldset class="mahjong-group">
<legend>Answer 2</legend>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/5-man.png">
        <img class="drawtile" src="/assets/image/tiles/7-man.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/1-pin.png">
    </div>
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/1-pin.png">
        <img class="drawtile" src="/assets/image/tiles/2-pin.png">
        <img class="drawtile" src="/assets/image/tiles/3-pin.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/4-pin.png">
        <img class="drawtile" src="/assets/image/tiles/4-pin.png">
        <img class="drawtile" src="/assets/image/tiles/4-pin.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/5-pin.png">
        <img class="drawtile" src="/assets/image/tiles/7-pin.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/3-sou.png">
        <img class="drawtile" src="/assets/image/tiles/5-sou.png">
        <img class="drawtile" src="/assets/image/tiles/5-sou.png">
    </div>
    <hr class="my-line">
</div>


<div class="analysis">Before we drew the third <img class="singletile" src="/assets/image/tiles/4-pin.png">, the pinzu (dots) tiles were 
<img class="singletile" src="/assets/image/tiles/1-pin.png">
<img class="singletile" src="/assets/image/tiles/1-pin.png">
+ 
<img class="singletile" src="/assets/image/tiles/2-pin.png">
<img class="singletile" src="/assets/image/tiles/3-pin.png">
<img class="singletile" src="/assets/image/tiles/4-pin.png">
 + 
<img class="singletile" src="/assets/image/tiles/4-pin.png">
<img class="singletile" src="/assets/image/tiles/5-pin.png"> , so the 
<img class="singletile" src="/assets/image/tiles/7-pin.png"> was simply a ﬂoating tile. Now
that we have another 
<img class="singletile" src="/assets/image/tiles/4-pin.png"> , the ﬁve-block conﬁguration changes accordingly.
The ideal discard is 
<img class="singletile" src="/assets/image/tiles/1-pin.png"> , as this has become redundant.</div>

</fieldset>


### Excersise 3

<fieldset class="excercise">
<legend class="left-align">Exercise 3</legend>

<div class="discard-question">What would you discard?</div>
<div class="discard-question">How do you divide the hand into tile blocks</div>

<img alt="drawtile" src="/assets/image/tiles/4-man.png">
<img alt="drawtile" src="/assets/image/tiles/4-man.png">
<img alt="drawtile" src="/assets/image/tiles/6-man.png">
<img alt="drawtile" src="/assets/image/tiles/6-man.png">
<img alt="drawtile" src="/assets/image/tiles/7-man.png">
<img alt="drawtile" src="/assets/image/tiles/8-man.png">
<img alt="drawtile" src="/assets/image/tiles/2-pin.png">
<img alt="drawtile" src="/assets/image/tiles/3-pin.png">
<img alt="drawtile" src="/assets/image/tiles/3-sou.png">
<img alt="drawtile" src="/assets/image/tiles/4-sou.png">
<img alt="drawtile" src="/assets/image/tiles/6-sou.png">
<img alt="drawtile" src="/assets/image/tiles/6-sou.png">
<img alt="drawtile" src="/assets/image/tiles/7-sou.png">
<img alt="drawtile" src="/assets/image/tiles/3-man.png">


<figure class="caption2">
    <img src="/assets/image/tiles/3-man.png"
         alt="checktile">
    <figcaption>Draw</figcaption>
</figure>


</fieldset>




<fieldset class="excercise">
<legend class="right-align">Answer 3</legend>


<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/3-man.png">
        <img class="drawtile" src="/assets/image/tiles/4-man.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/6-man.png">
    </div>
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/6-man.png">
        <img class="drawtile" src="/assets/image/tiles/7-man.png">
        <img class="drawtile" src="/assets/image/tiles/8-man.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/2-pin.png">
        <img class="drawtile" src="/assets/image/tiles/3-pin.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/3-sou.png">
        <img class="drawtile" src="/assets/image/tiles/4-sou.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/6-sou.png">
        <img class="drawtile" src="/assets/image/tiles/6-sou.png">
        <img class="drawtile" src="/assets/image/tiles/7-sou.png">
    </div>
    <hr class="my-line">
</div>

<div class="analysis">There are two “side wait plus one” shapes, <img class="singletile" src="/assets/image/tiles/3-man.png">
<img class="singletile" src="/assets/image/tiles/4-man.png">
<img class="singletile" src="/assets/image/tiles/4-man.png"> and 
<img class="singletile" src="/assets/image/tiles/6-sou.png">
<img class="singletile" src="/assets/image/tiles/6-sou.png">
<img class="singletile" src="/assets/image/tiles/7-sou.png">,
that might later become the head or a run. At this point, however,
we cannot determine which one will be which, so we should
keep them as they are. One of the two 
<img class="singletile" src="/assets/image/tiles/6-man.png"> has become an obvious
redundancy so we should discard one.</div>

</fieldset>

### Excersise 4


<fieldset class="excercise">
<legend class="left-align">Exercise 4</legend>

<div class="discard-question">What would you discard?</div>
<div class="discard-question">How do you divide the hand into tile blocks</div>

<img alt="drawtile" src="/assets/image/tiles/2-man.png">
<img alt="drawtile" src="/assets/image/tiles/3-man.png">
<img alt="drawtile" src="/assets/image/tiles/5-man.png">
<img alt="drawtile" src="/assets/image/tiles/6-man.png">
<img alt="drawtile" src="/assets/image/tiles/4-pin.png">
<img alt="drawtile" src="/assets/image/tiles/4-pin.png">
<img alt="drawtile" src="/assets/image/tiles/6-pin.png">
<img alt="drawtile" src="/assets/image/tiles/8-pin.png">
<img alt="drawtile" src="/assets/image/tiles/9-pin.png">
<img alt="drawtile" src="/assets/image/tiles/2-sou.png">
<img alt="drawtile" src="/assets/image/tiles/3-sou.png">
<img alt="drawtile" src="/assets/image/tiles/5-sou.png">
<img alt="drawtile" src="/assets/image/tiles/pei.png">

<figure class="caption2">
    <img src="/assets/image/tiles/4-man.png"
         alt="checktile">
    <figcaption>Draw</figcaption>
</figure>


</fieldset>




<fieldset class="excercise">
<legend class="right-align">Answer 4</legend>


<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/2-man.png">
        <img class="drawtile" src="/assets/image/tiles/3-man.png">
        <img class="drawtile" src="/assets/image/tiles/4-man.png">
        <img class="drawtile" src="/assets/image/tiles/5-man.png">
        <img class="drawtile" src="/assets/image/tiles/6-man.png">
    </div>
    <hr class="my-line">
    <div class="decrease-margin-top">2</div>
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/4-pin.png">
        <img class="drawtile" src="/assets/image/tiles/4-pin.png">
    </div>
    <hr class="my-line">
</div>


<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/6-pin.png">
        <img class="drawtile" src="/assets/image/tiles/8-pin.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/9-pin.png">
    </div>
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/2-sou.png">
        <img class="drawtile" src="/assets/image/tiles/3-sou.png">
        <img class="drawtile" src="/assets/image/tiles/5-sou.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/pei.png">
    </div>
</div>

<div class="analysis">The <img class="singletile" src="/assets/image/tiles/pei.png"> is obviously redundant, but 
<img class="singletile" src="/assets/image/tiles/9-pin.png"> is also useless. Without
<img class="singletile" src="/assets/image/tiles/9-pin.png">, the hand can accept 
<img class="singletile" src="/assets/image/tiles/7-pin.png">. Since honor tiles can be used as a
safety tile (see Chapter 8), we discard 
<img class="singletile" src="/assets/image/tiles/9-pin.png"> ﬁrst.</div>

</fieldset>

### Excersise 5

<fieldset class="excercise">
<legend class="left-align">Exercise 5</legend>

<div class="discard-question">What would you discard?</div>
<div class="discard-question">How do you divide the hand into tile blocks</div>

<img alt="drawtile" src="/assets/image/tiles/2-man.png">
<img alt="drawtile" src="/assets/image/tiles/3-man.png">
<img alt="drawtile" src="/assets/image/tiles/5-man.png">
<img alt="drawtile" src="/assets/image/tiles/7-man.png">
<img alt="drawtile" src="/assets/image/tiles/7-man.png">
<img alt="drawtile" src="/assets/image/tiles/2-pin.png">
<img alt="drawtile" src="/assets/image/tiles/4-pin.png">
<img alt="drawtile" src="/assets/image/tiles/6-pin.png">
<img alt="drawtile" src="/assets/image/tiles/8-pin.png">
<img alt="drawtile" src="/assets/image/tiles/2-sou.png">
<img alt="drawtile" src="/assets/image/tiles/5-sou.png">
<img alt="drawtile" src="/assets/image/tiles/7-sou.png">
<img alt="drawtile" src="/assets/image/tiles/8-sou.png">


<figure class="caption2">
    <img src="/assets/image/tiles/8-sou.png"
         alt="checktile">
    <figcaption>Draw</figcaption>
</figure>


<figure class="caption2">
    <img src="/assets/image/tiles/4-pin.png"
         alt="checktile">
    <figcaption>Dora</figcaption>
</figure>


</fieldset>




<fieldset class="excercise">
<legend class="right-align">Answer 5</legend>


<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/2-man.png">
        <img class="drawtile" src="/assets/image/tiles/3-man.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/5-man.png">
        <img class="drawtile" src="/assets/image/tiles/7-man.png">
        <img class="drawtile" src="/assets/image/tiles/7-man.png">
    </div>
    <hr class="my-line">
</div>


<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/2-pin.png">
        <img class="drawtile" src="/assets/image/tiles/4-pin.png">
        <img class="drawtile" src="/assets/image/tiles/6-pin.png">
        <img class="drawtile" src="/assets/image/tiles/8-pin.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/4-sou.png">
        <img class="drawtile" src="/assets/image/tiles/5-sou.png">
    </div>
    <hr class="my-line">    
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/7-sou.png">
        <img class="drawtile" src="/assets/image/tiles/8-sou.png">
        <img class="drawtile" src="/assets/image/tiles/8-sou.png">
    </div>
    <hr class="my-line">
</div>


<div class="analysis">This is a bit diﬃcult, as there are so many closed-wait protoruns.
Recall that each tile block should have at most three tiles and that
pairs are most valuable when there are two of them in a hand.
The block in pinzu (dots) has four tiles, so we discard one from
this block. Since <img class="singletile" src="/assets/image/tiles/4-pin.png"> is dora, we discard 
<img class="singletile" src="/assets/image/tiles/8-pin.png">, leaving the double
closed shape around dora: 
<img class="singletile" src="/assets/image/tiles/2-pin.png">
<img class="singletile" src="/assets/image/tiles/4-pin.png">
<img class="singletile" src="/assets/image/tiles/6-pin.png"> .</div>

</fieldset>


### Excersise 6


<fieldset class="excercise">
<legend class="left-align">Exercise 6</legend>

<div class="discard-question">What would you discard?</div>
<div class="discard-question">How do you divide the hand into tile blocks</div>

<img alt="drawtile" src="/assets/image/tiles/2-man.png">
<img alt="drawtile" src="/assets/image/tiles/3-man.png">
<img alt="drawtile" src="/assets/image/tiles/4-man.png">
<img alt="drawtile" src="/assets/image/tiles/4-man.png">
<img alt="drawtile" src="/assets/image/tiles/3-pin.png">
<img alt="drawtile" src="/assets/image/tiles/4-pin.png">
<img alt="drawtile" src="/assets/image/tiles/5-pin.png">
<img alt="drawtile" src="/assets/image/tiles/6-pin.png">
<img alt="drawtile" src="/assets/image/tiles/4-sou.png">
<img alt="drawtile" src="/assets/image/tiles/5-sou.png">
<img alt="drawtile" src="/assets/image/tiles/5-sou.png">
<img alt="drawtile" src="/assets/image/tiles/6-sou.png">
<img alt="drawtile" src="/assets/image/tiles/6-sou.png">



<figure class="caption2">
    <img src="/assets/image/tiles/4-pin.png"
         alt="checktile">
    <figcaption>Draw</figcaption>
</figure>


</fieldset>




<fieldset class="excercise">
<legend class="right-align">Answer 6</legend>


<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/2-man.png">
        <img class="drawtile" src="/assets/image/tiles/3-man.png">
        <img class="drawtile" src="/assets/image/tiles/4-man.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/4-man.png">
    </div>
</div>


<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/3-pin.png">
        <img class="drawtile" src="/assets/image/tiles/4-pin.png">
        <img class="drawtile" src="/assets/image/tiles/4-pin.png">
        <img class="drawtile" src="/assets/image/tiles/5-pin.png">
        <img class="drawtile" src="/assets/image/tiles/6-pin.png">
    </div>
    <hr class="my-line">
    <div class="decrease-margin-top">2</div>
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/4-sou.png">
        <img class="drawtile" src="/assets/image/tiles/5-sou.png">
        <img class="drawtile" src="/assets/image/tiles/5-sou.png">
        <img class="drawtile" src="/assets/image/tiles/6-sou.png">
        <img class="drawtile" src="/assets/image/tiles/6-sou.png">
    </div>
    <hr class="my-line">    
    <div class="decrease-margin-top">2</div>
</div>


<div class="analysis">Finding the best discard by actually comparing tile acceptance
counts for each possible discard candidate is super tedious. The
ﬁve-block method simpliﬁes the process quite a bit. Since we
have two blocks in pinzu (dots) and two blocks in souzu (bamboos),
we only need one block in manzu (cracks), hence one <img class="singletile" src="/assets/image/tiles/4-man.png"> is
redundant. If we discard 
<img class="singletile" src="/assets/image/tiles/4-man.png">, the hand can be made ready with
11 kinds–34 tiles. If we discard 
<img class="singletile" src="/assets/image/tiles/3-pin.png">
<img class="singletile" src="/assets/image/tiles/4-pin.png"> or 
<img class="singletile" src="/assets/image/tiles/5-sou.png">, the hand can be
ready only with 6 kinds–19 tiles .</div>

</fieldset>

### Excersise 7


<fieldset class="excercise">
<legend class="left-align">Exercise 7</legend>

<div class="discard-question">What would you discard?</div>
<div class="discard-question">How do you divide the hand into tile blocks</div>

<img alt="drawtile" src="/assets/image/tiles/3-man.png">
<img alt="drawtile" src="/assets/image/tiles/4-man.png">
<img alt="drawtile" src="/assets/image/tiles/7-man.png">
<img alt="drawtile" src="/assets/image/tiles/2-pin.png">
<img alt="drawtile" src="/assets/image/tiles/3-pin.png">
<img alt="drawtile" src="/assets/image/tiles/4-pin.png">
<img alt="drawtile" src="/assets/image/tiles/7-pin.png">
<img alt="drawtile" src="/assets/image/tiles/7-pin.png">
<img alt="drawtile" src="/assets/image/tiles/8-pin.png">
<img alt="drawtile" src="/assets/image/tiles/4-sou.png">
<img alt="drawtile" src="/assets/image/tiles/5-sou.png">
<img alt="drawtile" src="/assets/image/tiles/7-sou.png">
<img alt="drawtile" src="/assets/image/tiles/9-sou.png">

<figure class="caption2">
    <img src="/assets/image/tiles/6-sou.png"
         alt="checktile">
    <figcaption>Draw</figcaption>
</figure>



</fieldset>




<fieldset class="excercise">
<legend class="right-align">Answer 7</legend>


<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/3-man.png">
        <img class="drawtile" src="/assets/image/tiles/4-man.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/7-man.png">
    </div>
</div>


<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/2-pin.png">
        <img class="drawtile" src="/assets/image/tiles/3-pin.png">
        <img class="drawtile" src="/assets/image/tiles/4-pin.png">
    </div>
    <hr class="my-line">
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/7-pin.png">
        <img class="drawtile" src="/assets/image/tiles/7-pin.png">
        <img class="drawtile" src="/assets/image/tiles/8-pin.png">
    </div>
    <hr class="my-line">    
</div>

<div class="garisbawah">
    <div class="empty-container">
        <img class="drawtile" src="/assets/image/tiles/4-sou.png">
        <img class="drawtile" src="/assets/image/tiles/5-sou.png">
        <img class="drawtile" src="/assets/image/tiles/6-sou.png">
        <img class="drawtile" src="/assets/image/tiles/7-sou.png">
        <img class="drawtile" src="/assets/image/tiles/9-sou.png">
    </div>
    <hr class="my-line">
    <div class="decrease-margin-top">2</div>
</div>


<div class="analysis">Do not discard the <img class="singletile" src="/assets/image/tiles/9-sou.png"> just because it forms a closed wait or
because discarding it gets us tanyao (All Simples). Avoiding
closed wait too much and being hung up on tanyao are two
pathologies common among intermediate players.
The block in souzu (bamboos) is actually not too bad; this is a
stretched single plus one, which can become either two runs immediately
(if we draw 
<img class="singletile" src="/assets/image/tiles/8-sou.png">), one run plus one side-wait protorun
(if we draw any of 
<img class="singletile" src="/assets/image/tiles/3-sou.png">
<img class="singletile" src="/assets/image/tiles/5-sou.png">
<img class="singletile" src="/assets/image/tiles/6-sou.png">), or one run plus the head (if we draw
<img class="singletile" src="/assets/image/tiles/4-sou.png"> or 
<img class="singletile" src="/assets/image/tiles/7-sou.png">). Note also that we need both 
<img class="singletile" src="/assets/image/tiles/7-pin.png"> and 
<img class="singletile" src="/assets/image/tiles/8-pin.png">, because this
part may become the head if we get two runs in souzu (bamboos);
when we get the head in souzu (bamboos), we will treat
this part as a side-wait protorun. We thus discard 
<img class="singletile" src="/assets/image/tiles/7-man.png">.</div>

</fieldset>
