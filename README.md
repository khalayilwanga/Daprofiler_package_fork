## Daprofiler Fork

This is a simple fork of the original [Daprofiler tool](https://github.com/daprofiler/DaProfiler).
It is turned into a python package that can be easily installed using the [wheel]() provided in this repo using the command:

`python -m pip install <wheel here> `

To import the main file and use in your project:

```
from daprofiler_tool import profiler.main

//use main in your project
res = main(first_name ='john',
           last_name ='doe',
           zip_code =90006,

         //optional parameter if you want the result printed on screen
           json_print='true'
           )

```

NB/
In case the `daprofiler_tool` folder does not open refer to `daprofiler_too copy`
