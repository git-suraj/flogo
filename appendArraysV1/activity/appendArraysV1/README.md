---
title: Append Arrays
weight: 4609
---

# Appnd arrays
This activity allows you to append teo arrays

## Installation
### Flogo Web
This activity needs to be installed - https://github.com/git-suraj/flogo/blob/master/flogo/appendArrays
### Flogo CLI
```bash
flogo add activity github.com/git-suraj/flogo/blob/master/flogo/appendArrays
```

## Schema
Inputs and Outputs:

```json
{
  "input":[
    {
      "name": "array1",
      "type": "array",
      "required": true
    },
    {
      "name": "array2",
      "type": "array",
      "required": true
    }
  ],
  "output": [
    {
      "name": "output",
      "type": "array",
      "required": true
    }
  ]
}
```