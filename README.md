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

**[About Configurations]** We will provide 5 types of configuration files for the same configuration of each experiment. The
  1. \*.json ;
  2. \*.properties ;
  3. \*.yaml ;
  4. \*.hocon ;
  5. A directory that contains multiple [HOCON](https://github.com/lightbend/config/blob/master/HOCON.md) configuration files that using the include semantics.

**[About Models]** All the models that produce the best experimental results will be shared on OneDrive for download.

--------------------------------------------------------------------------------

## Baselines

### Transformer

#### WMT16 En-Ro

Here are the results of the experiment of WMT16 English to Romania, the best model is obtained at training step **15,000**:

  En-Ro                 | MultiBLEU | SacreBLEU
  ----------------------|-----------|----------
  newsdev2016  (valid)  | 33.41     | - 
  newstest2016 (test)   | 32.88     | - 

The configurations can be obtained [here](https://github.com/Jason-Young-AI/YoungNMT-configs/tree/master/Transformer/wmt16_en-ro).
The best model can be downloaded at [here](https://1drv.ms/u/s!AkKq-gTqmfT0jTmKAZaeI0hLSJNh?e=JpaVES)


#### WMT16 En-De

Here are the results of the experiment of WMT16 English to German, the best model is obtained at training step **174,000**:

  En-De                 | MultiBLEU | SacreBLEU
  ----------------------|-----------|----------
  newstest2013 (valid)  | 26.37     | - 
  newstest2014 (test)   | 27.58     | - 

The configurations can be obtained [here](https://github.com/Jason-Young-AI/YoungNMT-configs/tree/master/Transformer/wmt16_en-de).
The best model can be downloaded at [here](https://1drv.ms/u/s!AkKq-gTqmfT0jToWKiBxtsNKd2xZ?e=bsMz1l)
