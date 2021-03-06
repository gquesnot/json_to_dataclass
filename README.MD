Json to Dataclass
==================

Generate typed dataclass from json file or url.


## Installation

```bash
pip install -r requirements.txt
# or using poetry
poetry install
```

## Usage

### Create a dataclass from json

```bash
usage: python main.py [-h] [--generate-only] [--load-only] [--show-data] [--show-schema] [--name NAME] [--output OUTPUT] [--verbose] {json,url} input [input ...]
                                                                                                                                                          
positional arguments:                                                                                                                                     
  {json,url}       chose between raw json or url                                                                                                          
  input            url or json file or directory                                                                                                          
                                                                                                                                                          
options:                                                                                                                                                  
  -h, --help       show this help message and exit                                                                                                        
  --generate-only  Only generate the dataclass                                                                                                            
  --load-only      Only load the dataclass                                                                                                                
  --show-data      show datas if --with-data                                                                                                              
  --show-schema    show dtc schema                                                                                                                        
  --name NAME      name of the dataclass required if url                                                                                                  
  --output OUTPUT  where to write class                                                                                                                   
  --verbose        verbose mode # not implemented
```

## Test

```bash
  python test.py
```



