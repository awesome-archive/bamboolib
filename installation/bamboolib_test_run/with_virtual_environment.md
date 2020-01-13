## Test the library

First, start Jupyter Notebook or Jupyter Lab

```bash
jupyter notebook
# jupyter lab
```

Afterwards, create a new notebook choosing the *bamboolib_venv* kernel (**New** > *bamboolib_venv*).

Finally, run the following in a Jupyter Notebook / Lab code cell:

```python
import bamboolib as bam
import pandas as pd
df = pd.read_csv(bam.titanic_csv)
bam.show(df)
```

You should see a GUI if everything worked fine. If you don't see anything, please read [here](https://github.com/tkrabel/bamboolib/blob/master/installation/troubleshooting/with_virtual_environment.md#troubleshooting-installation-errors).
