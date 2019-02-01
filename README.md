# alba - Analysis of LSST Batch Activity

This repository contains some Python notebook-based tools for exploring and analysing the data processing activity performed at [CC-IN2P3](http://cc.in2p3.fr) by [LSST](https://www.lsst.org) and [DESC](http://lsst-desc.org).

### Requirements

To execute the notebook you need a working environment including **Python** (at least v3.6), `pandas`, `bokeh`, `numpy` and `jupyter`.

In addition, you need the batch accounting data files which are available at CC-IN2P3, the [LSST science platform](https://nb.lsst.io) and [NERSC](http://www.nersc.gov). The location of those files in each of those sites can be found in the notebook itself.

### How to execute

```
git clone https://github.com/airnandez/alba.git
cd alba
jupyter lab
```

## Credits

### Author
These tools were developed and are maintained by Fabio Hernandez at [IN2P3 / CNRS computing center](http://cc.in2p3.fr) (Lyon, France). 

## License
Copyright 2019 Fabio Hernandez

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
