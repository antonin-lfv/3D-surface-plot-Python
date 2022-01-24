# 3D-surface-plot-Python

The n*m Z matrix can contain heights of water for example, to plot the submarine surface.
If you have any question, tell me!

## First setp

```py
import numpy as np
from Interpolation_3D.LinearInterpolation3D import *

Z = np.array([[7.894736842105264, 7.894736842105264, 7.894736842105264, 8.947368421052632, 8.947368421052632, 10.0,
               10.0, 10.0, 10.0, 10.0, 10.0],
              [6.842105263157896, 6.842105263157896, 7.894736842105264, 8.947368421052632, 8.947368421052632,
               8.947368421052632, 10.0, 10.0, 10.0, 10.0, 10.0],
              [5.789473684210527, 5.789473684210527, 5.789473684210527, 6.842105263157896, 6.842105263157896,
               7.894736842105264, 8.947368421052632, 10.0, 10.0, 10.0, 10.0],
              [5.789473684210527, 5.789473684210527, 5.789473684210527, 5.789473684210527, 5.789473684210527,
               6.842105263157896, 6.842105263157896, 8.947368421052632, 10.0, 10.0, 10.0],
              [3.6842105263157894, 4.736842105263158, 4.736842105263158, 5.789473684210527, 5.789473684210527,
               5.789473684210527, 6.842105263157896, 7.894736842105264, 8.947368421052632, 10.0, 10.0],
              [3.6842105263157894, 3.6842105263157894, 3.6842105263157894, 3.6842105263157894, 4.736842105263158,
               5.789473684210527, 5.789473684210527, 6.842105263157896, 8.947368421052632, 8.947368421052632, 8.95],
              [2.6315789473684212, 2.6315789473684212, 2.6315789473684212, 3.6842105263157894, 3.6842105263157894,
               5.789473684210527, 5.789473684210527, 6.842105263157896, 8.947368421052632, 8.947368421052632, 8.95],
              [1.5789473684210527, 1.5789473684210527, 2.6315789473684212, 2.6315789473684212, 3.6842105263157894,
               4.736842105263158, 5.789473684210527, 5.789473684210527, 7.894736842105264, 7.894736842105264, 7.9],
              [0.5263157894736843, 0.5263157894736843, 1.5789473684210527, 2.6315789473684212, 3.6842105263157894,
               4.736842105263158, 5.789473684210527, 5.789473684210527, 6.842105263157896, 7.894736842105264, 7.9],
              [-0.5263157894736843, 0.5263157894736843, 1.5789473684210527, 2.6315789473684212, 3.6842105263157894,
               3.6842105263157894, 5.789473684210527, 5.789473684210527, 6.842105263157896, 7.894736842105264, 7.9]])

if __name__ == "__main__":
    mon_interpolateur = Interpolator(matrix=Z)
    # With color gradient
    mon_interpolateur.graph_3D_color()
    # With lines
    mon_interpolateur.graph_3D_line()

```

<img width="1177" alt="interpolation_linéaire" src="https://user-images.githubusercontent.com/63207451/92334896-65152f00-f092-11ea-9b81-fd24accc9d89.png">
<img width="465" alt="Capture d’écran 2022-01-24 à 19 39 18" src="https://user-images.githubusercontent.com/63207451/150843744-92841d9a-b79c-46c7-b84e-ff108201280c.png">


<br/>

<p align="center">
  <a href="https://github.com/antonin-lfv" class="fancybox" ><img src="https://user-images.githubusercontent.com/63207451/97302854-e484da80-1859-11eb-9374-5b319ca51197.png" title="GitHub" width="40" height="40"></a>
  <a href="https://www.linkedin.com/in/antonin-lefevre-565b8b141" class="fancybox" ><img src="https://user-images.githubusercontent.com/63207451/97303444-b2c04380-185a-11eb-8cfc-864c33a64e4b.png" title="LinkedIn" width="40" height="40"></a>
  <a href="mailto:antoninlefevre45@icloud.com" class="fancybox" ><img src="https://user-images.githubusercontent.com/63207451/97303543-cec3e500-185a-11eb-8adc-c1364e2054a9.png" title="Mail" width="40" height="40"></a>
</p>
