# babette_example_3

Branch   |[![Travis CI logo](pics/TravisCI.png)](https://travis-ci.org)                                                                                           |[![AppVeyor logo](pics/AppVeyor.png)](https://appveyor.com)                                                                                               
---------|--------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
`master` |[![Build Status](https://travis-ci.org/richelbilderbeek/babette_example_3.svg?branch=master)](https://travis-ci.org/richelbilderbeek/babette_example_3) |[![Build status](https://ci.appveyor.com/api/projects/status/k2cwbmf06f7qwkf8/branch/master?svg=true)](https://ci.appveyor.com/project/richelbilderbeek/babette-example-3/branch/master)
`develop`|[![Build Status](https://travis-ci.org/richelbilderbeek/babette_example_3.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/babette_example_3)|[![Build status](https://ci.appveyor.com/api/projects/status/k2cwbmf06f7qwkf8/branch/develop?svg=true)](https://ci.appveyor.com/project/richelbilderbeek/babette-example-3/branch/develop)

A [babette example](https://github.com/richelbilderbeek/babette_examples).

## Example #3: JC69 site model

![Example #3: JC69 site model](jc69_2_4.png)

```
posterior <- bbt_run(
  "my_alignment.fas",
  site_model = create_jc69_site_model()
)
```

All other parameters are set to their defaults, as in BEAUti.

## Result

![](result.png)
