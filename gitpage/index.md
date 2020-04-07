# Towards Production Ready Jolie

> Author: Narongrit Unwerawattana(Kie) (narongrit.kie@gmail.com)
> 
> Last Update: 31/10/2019
> 
> Discussion: jolie_lang.slack.com#jolie2_0
>
> Repository: https://github.com/kicito/jolie/tree/jolie-module-3

Modular Jolie are a mechanism for import an Identifier from other Jolie file to reuse a 

The approach for dividing Jolie code is achievable by 

## import statement
	
## import system

## Open questions

6/05/2020

### Exposing Identifier



# Service Node

## Parameterize Port

## 



		
parametric ports, i.e., `input/outputPort Name( t )`
		service as a symbol, i.e., `service Name( t: T ){ ... }`
		export/import of types, interfaces, and services as symbols
		embedding of services, i.e., `embed Console( myData )`
	
	
	Refinement types (here we endow types with predicates checked to hold for any element of the refined type)
	

		
Consider having a plugin system based on quasi-quotation
	
	
	Checks
	

		
co/contravariance wrt input/outputPorts used in service embedding
		linear use of declared ports in service embedding
		 