Now I recommend to use https://github.com/RolandVyens/PixelManager-Super-OCIO instead of this OCIO, for all in one experience.

![agx vs aces](https://github.com/RolandVyens/AgX-Punchy-For-Maya/assets/30930721/eecd0b5e-3f27-42fd-bf19-e3c24775d351)
left AgX Punchy, right ACES (both rendered in ACEScg colorspace).

Compared to ACES, AgX transform handles over saturation much better, you get a smooth saturation fall off towards white.

Based on AgX by Troy Sobotka. Further Developed by Zijun Eary Zhou法纤净, Mark Faderbauer, and Sakari Kapanen.

Modified for Maya by Roland Vyens, changes down below:

1. Modified working space to ACEScg that matches Maya default working space
2. Changed the Non-color name to Raw for seamless experience with Maya default data name
3. Added AgX Punchy in viewport color management

Download method:
Click "Code", then download zip
