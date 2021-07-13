<!--
    Copyright 2020 TWO SIGMA OPEN SOURCE, LLC

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

           http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
-->

# BeakerX: Beaker extensions for Jupyter - Groovy kernel (3.0.8)

This fork is an update to groovy kernel to work with groovy 3.0.8

BeakerX is a collection of JVM kernels and interactive widgets for
plotting, tables, autotranslation, and other extensions to Jupyter
Notebook.

This repository contains BeakerX kernel for Groovy.

Please check the main repositoy for further informations:
[beakerx](https://github.com/twosigma/beakerx)


### Build and Install (linux and mac)

```
./gradlew build
```

### Kernel Install in Conda (linux and mac)

```
cd ./groovy-dist
conda env create -n beakerx -f configuration.yml
conda activate beakerx # For conda versions prior to 4.6, run: source activate beakerx
(pip install -r requirements.txt --verbose)
beakerx_kernel_groovy install
cd ..
```
