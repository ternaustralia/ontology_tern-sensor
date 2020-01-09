# TERN SSN Ontology Extension

Documentation online: https://ternaustralia.github.io/ontology_tern-ssn/


## Building the documentation

In the directory of `docs/`, run:

```
docker run --rm -it --name pylode -e ONTOLOGY_FILE=tern-ssn.ttl -e OPTIONS="--css true" -v ${PWD}:/pyLODE/src/pylode/input edmondchuc/pylode
```

## Cleaning the TopBraid OWL2SHACL output

We use TopBraid Composer for the OWL2SHACL feature where a SHACL file containing shapes is generated from the OWL ontology. Running this docker container performs some post-processing on the SHACL file such as adding `sh:targetClass` to each `sh:NodeShape`. 

```
docker run --rm --name tbc-shacl-cleaner -e SHACL_FILE="tern-ssn.shapes.ttl" -v ${PWD}:/home/input edmondchuc/tbc-shacl-cleaner
```


## Contact

**Edmond Chuc**  
e.chuc@uq.edu.au  