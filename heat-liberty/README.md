# heat templates for liberty

|file|description|
|---|---|
|simple_NW.yml|create one simple network|
|simple_VM.yml|create one simple VM|



# how to use
```
# create stack from file
heat stack-create mystack \
  --template-file ~/simple_NW.yml \
  --parameters "NetworkName=mynetwork_100"


```
