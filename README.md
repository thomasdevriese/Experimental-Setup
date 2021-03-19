# Experimental-Setup
The experimental setup and results of my master's thesis titled 'Scaling networks of personal data stores through Approximate Membership Functions'. This is an extension of the [Decentralized LDBC SNB dataset generator tool](https://github.com/rubensworks/ldbc-snb-decentralized).

After the prepare.sh and serve.sh scripts are executed, the experiments can be performed by executing the experiment-amf.sh and experiment-default.sh scripts. Note that the paths to the Nodejs experiment scripts may have to be changed first. In this Nodejs script and the AMF-builder script, some paths will have to be changed as well.

The results from the experiments with false positive probabilities 1/4096, 1/4 and 1/2 were added later and can be found in the file results_amf_extra_probabilities.csv. Note that the data in the results_amf.csv and results_amf_extra_probabilities.csv files are ordered differently. This can be seen in their headers.
