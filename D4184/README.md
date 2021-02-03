This board is sold via Amazon as a "Trigger Switch Drive Board 0-20KHz PWM" and various other titles. It is essentially a N-MOS breakout board. Literally functions as an n-channel mosfet with terminal lugs. And a spare terminal.

Inputs and Outputs:
- Vin(-) and J1(-) of the input are electrically common and are the "Source" of the mosfet. 
- TRIG / PWM J1 input goes to the "Gate" of the mosfet. There is a resistor between the input and the shared fet's Gate inputs.
- Vout(-) is the "Drain" output of the mosfet board. 
- Note that the Vin+ and Vout+ exist solely as a terminal connection; these "+" connections are not used anywhere else on the board. This should be made far more obvious on the silkscreen. 

A few listings of the board. *if you want to add more, ask to be a contributor and you maintain it*
* [Amazon ASIN:B07XJSRY6B 10 pcs](https://www.amazon.com/dp/B07XJSRY6B)
* [Amazon ASIN:B077TX1J44 1 pc](https://www.amazon.com/dp/B077TX1J44) $6.99, *great pics*
* [Amazon ASIN:B085VD5YZJ 8 pcs](https://www.amazon.com/dp/B085VD5YZJ) $12.99

Interestingly, the boards all have slightly different silk screen and different "part numbers" on the bottom in the center. Examples N-MOS, Z-MOS, XY-MOS

Additionally, the board may be seen simulated at [Falstad.com Circuit Simulator](https://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcMBsBmALAJhQdgWgJwAcYKCFICxVVkAUAE4gY1YIogC0rI7nkZAwBm4XJzKCsWDOBSDCE6EjS56ZLHw4g0kWfx0JNmgCYBTYQEMArgBsALl1tmT4KO5iQw9UYrmCwDFlJED8wZR01Zl40IxY2bQD4OCYtTgMDXVkA4hSAd3jDTUDZWM0GAr8DMPkoegKwcX8xdMT68CCWjtK4ir4ZLuke8vaSov7huoKh8cze9t5q1oF2qu1G5anB7Qy26YGxmbAwEYbOsYuTrcvjA6u+o6uy8Hv2rLluXjI6gDduDfGXAB30EggwASQoKgynaQKazxi8wKcIknB4NBBqWe32x93A9AAMp8EmjjsZEm4rLYAM5mWgMVSCd44uLfCCg+hAA)
