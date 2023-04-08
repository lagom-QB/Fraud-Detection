# Fraud Detection

## Introduction
The goal of the project was to build a knowledge system to classify a transaction as fraudulent or non-fraudulent and using specified rules, define what sort of fraud was carried out.  
The client provided us with a _.owl_ file.

## Progression of the project
### Text extraction from the ontology data
Had to :
- Load the ontology in order to understand classes, properties and relationship between the classes, instances and subclasses.
- Download a dataset which would represent any of the classes of the ontology.  
Performing texte extraction using an ontology and a dataset requires us to integrate hte dataset into the ontology. That is, mapping the dataset's concepts to the ontology's classes and properties.  
Mapping the dataset to the Ontology :
- Create corresponding classes and properties for the dataset in the ontology.
- Create instances of the classes for the dataset. _("Insert" the datasewt into the ontology)_  
We made sure to verify the instances were added to the ontology.

### Using extracted text to create ruless for fraud detection
Fortunately, the client had provided us with specified rules for the system, so the task was cut out for us since we just had to translate to code.

### Test the rules
The functions created to check for fraud had checks built in to help us validate against the ontology.

## Challenges
- I had never worked with ontology data before so it was like shooting blanks in the dark.
- There was no defined time limit for the duration of the project.  

__Lessons learnt__
- Working with ontology data is somewhat tricky, but it is important to explore and understand the ontology before starting anything.
- Don't start a project until you understand the end goal and expected deliverables.
- Functional programming is important for debugging and understanding now and in the future.
