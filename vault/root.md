---
id: ba2ce51c-3981-4122-8cae-c1d54cf3ea2f
title: Schema Templates
desc: ''
updated: 1621287901499
created: 1621280247407
---


This is a schema repository for [Dendron](https://dendron.so/).

## Getting Started

To use an individual schema, follow the instructions below:
1. Click the `link` section of the schema you would like to use
1. In your Dendron Workspace, use [Lookup Schema](https://wiki.dendron.so/notes/eea2b078-1acc-4071-a14e-18299fc28f47.html#lookup-schema) to create the schema in your workspace
1. Copy and paste the schema from this repo into your newly created workspace schema
1. Run [Reload Index](https://wiki.dendron.so/notes/eea2b078-1acc-4071-a14e-18299fc28f47.html#reload-index) to use the scema

If you would like to add all the schemas, you can add this entire project as a [remote vault](https://wiki.dendron.so/notes/eea2b078-1acc-4071-a14e-18299fc28f47.html#remote-vault).

## Schemas

### lang
- link: [lang](lang.schema.yml)

Track programming languages

#### Summary
```yml
- l
    - {programming-language} # eg. python
        - d # data structure
            - boolean
            - string
            - ...
        - t # topics
            - system
            - net # network
            - time
            - image # image manipulation
        - ....
```

### proj
- link: [proj](proj.schema.yml)

Track projects

#### Summary
```yml
- pro
    - journal
        - concepts
        - quickstart
        - qa
        - debug
        - ...
```


