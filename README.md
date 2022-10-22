# ImageToGif
ImageToGif

```shell
pip install imageio
pip install matplotlib
pip install numpy
```

```python
import matplotlib.pyplot as plt
import numpy as np
import imageio
from PIL import Image
import matplotlib.image as mpimg
path = [f"./complete_demo/{i}" for i in os.listdir("./complete_demo")]
paths = [Image.open(i) for i in path]
imageio.mimsave('./complete_demo.gif', paths, fps=5
```
