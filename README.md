# node-config-battle
A scientific comparison of Node config packages

See example in the folder /convict

Fefine an hirearchical config. override 1 value with env var, override other key with command args, override few keys with additional file (local dev environment definition),one key should be a password and its value should not be set within the JSON rather through env var, if a supplied key is missing or has incorrect value - fail fast with exception