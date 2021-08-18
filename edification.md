# Edification

`I seem to enjoy the feeling`<br>
of my body being kind of beat up<br>
after a hard workout/run/climbing session.<br>

It’s as if the soreness is some style of proving<br>
`that I tried hard -- really put my lifeforce into the thing`<br>
that I was doing.<br>

Somehow that feels purifying, as if my soul is a wild beast and by<br>
putting the body through its paces, I simultaneously domesticate it<br>
`just a bit more, enabling it to approach an actualized version of itself.`<br>

It is truly a salvation through works system of belief (_truly_).<br>
In it, climbing _is_ play, but also **absolution** and **edification**.<br> 
In it, salvation is wrought from tense muscles, sweaty skin, breathlessness.<br>
<br>

```python
class Salvation:
    mscl_tn: int
    skin_sweat_covering_ratio: float
    breathless: bool
    bndry = 1

    def __init__(self, tension, sweat, breathless_state) -> None:
        self.mscl_tn = tension
        self.skin_sweat_covering_ratio = sweat
        self.breathless = breathless_state

    def salvation_wrought(self) -> bool:
        if self.breathless and self.mscl_tn * self.skin_sweat_covering_ratio > self.bndry:
            self.bndry += 1
            return True
        else:
            return False
```