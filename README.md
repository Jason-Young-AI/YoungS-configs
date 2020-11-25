# YoungNMT-configs

--------------------------------------------------------------------------------

* [Baselines](#baselines)
  * [Transformer](#transformer)
     * [WMT16 En-Ro](#wmt16-en-ro)
     * [WMT16 En-De](#wmt16-en-de)
 
--------------------------------------------------------------------------------

**[About Results]** All the experimental results are produced in the following way:
  1. Select the model with the highest BLEU score on the validation set;
  2. Test the model on the testing set to get the correponding BLEU score.

**[About Configurations]** We will provide 3 types of configuration files for the same configuration of each experiment:
  1. \*.json ;
  2. \*.hocon ;
  3. A directory that contains multiple [HOCON](https://github.com/lightbend/config/blob/master/HOCON.md) configuration files that using the include semantics.

**[About Models]** All the models that produce the best experimental results will be shared on OneDrive for download.

--------------------------------------------------------------------------------

## Baselines

### Transformer

#### WMT16 En-Ro

[ [Configurations](https://github.com/Jason-Young-AI/YoungNMT-configs/tree/master/Transformer/wmt16_en-ro) ]
[ [Best Model](https://1drv.ms/u/s!AkKq-gTqmfT0jTmKAZaeI0hLSJNh?e=JpaVES) ]
[ [Corpus](http://storage.live.com/items/F4F499EA04FAAA42!1846:/WMT16_English-Romania.zip) ]

Here are the results of the experiment of WMT16 English to Romania, the best model is obtained at training step **15,000**:

  En-Ro                 | MultiBLEU | SacreBLEU
  ----------------------|-----------|----------
  newsdev2016  (valid)  | 33.41     | - 
  newstest2016 (test)   | 32.88     | - 


#### WMT16 En-De

[ [Configurations](https://github.com/Jason-Young-AI/YoungNMT-configs/tree/master/Transformer/wmt16_en-de) ]
[ [Best Model](https://1drv.ms/u/s!AkKq-gTqmfT0jToWKiBxtsNKd2xZ?e=bsMz1l) ]
[ [Corpus](http://storage.live.com/items/F4F499EA04FAAA42!1847:/WMT16_English-German.zip) ]


Here are the results of the experiment of WMT16 English to German, the best model is obtained at training step **174,000**:

  En-De                 | MultiBLEU | SacreBLEU
  ----------------------|-----------|----------
  newstest2013 (valid)  | 26.37     | - 
  newstest2014 (test)   | 27.58     | - 
