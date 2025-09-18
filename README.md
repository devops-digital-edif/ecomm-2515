# ecomm application code

## Learn YAML

- YAML is used to feed the data to system, just like JSON {....}, XML

### YAML Syntaxes

- FIle extention should be .yml or .yaml
    - ex: my-file.yaml
- there is no mandotary lines or script need to mention
    - if you want mention ... as starting and --- as ending, if you are going with 2 config in single file you need to mention --- in between them
    - ex: config-1
          ---
          config-2
- the data inside YAML is going to key and values format
- each key should have value, the value can be number, string, list...
- keys and values are separated by colon (:) and follwed by space
    - ex: name: murali --valid
    - name:murali  -- invalid
- in a single indentation block the keys should be unique
- indentation: 2 spaces not the tab is used to map the data into block
    - ex: movies:     # actors is value for movie
            actors:   # ntr and prbhas will be the values for actors
              ntr: war2  # war2 becomes the value for ntr
              prabhas: salar
- comments are represented with hash tag - #        
    - ex: # this is comment      

### Data Types:
1. Scalar Data types
    - numbers: integer and floating, ex: age: 21
    - strings: text enclosed in single or double quotes, ex: "this is string"
        - folded block(>):  output given in single line
        - literal block(|): prints output same as input format
    - boolean: true or false
    - null: null or ~
2. Sequence/Array Data Type
    - list of items, represented by dash (-) followed by space
    - ex: fruits:
            -mango
            - cherry
            
3. Mapping Data Type
    - key-value pairs, separated by colon followed by space
    - ex: name: murali


### Folded block 
ex: 
jobDescription: "Need 3 years exp person in cloud devops. He/she should be familier with kubernetes and docker. Should be able to lead the scrum team"

