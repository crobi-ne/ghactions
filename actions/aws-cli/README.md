# Using latchy for aws-cli
This simple composite action provides latchy as a AWS credentail process provider. It creates the necessary config file instructing aws-cli to call latchy while feeding it the encrypted credential JSON object. This object is in the clevis / tang JWE format.

