# hiveplotanimation
Short example of attempt to animate a hive plot that I haven't been able to make work.

The goal is to show time series network attack data, where there are destination and source ip addresses on two axes,
and a link between them during the time an attack was detected. The animation runs from a start date to end date, with
the links appearing and disappearing at the correct time.

I have the data to drive the animation, but have been unable to control the appearance and disappearance using D3.
My approach has been to draw all the links with zero opactity, and change opacities across time.
