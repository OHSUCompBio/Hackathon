# Hackathon
Computational Biology Hackathon
```
Stories
  Focus is on creating a list of potential stories with the intent to narrow the list via:
  *  mgt review
  *  ability to accomplish [resources, infrastructure, etc]
```
## 1. GA4GH::G2P / variant annotation / clinical decision support

CIViC as a GA4GH G2P endpoint
Story: As a clinician or researcher, given a genomic location, return the evidence in CIViC of associated drug treatment options and evidence of the association using G2P API.
Context: "Add API to CIViC Rails app"

CIViC /GA4GH Ontology Server
Story: Integrate CIViC with a GA4GH compatible ontology
Language Bindings:
Story: "As a GA4GH developer, I'll be more productive if I had a binding from GA4GH to my favorite language [java, python, groovy, scala, javascript]."
Context: "Easier to define." "Which languages?"

G2P: Unify disparate repositories: Navigation and strength of evidence between different G2P sites
Story: As a curator of genotype/phenotype relationships, I find limited overlap between different public ontologies. Is there an analysis method that can create a unified ontology that best fits the supporting cross-references?
Context: http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4383880/table/tbl3/

Create reference implementation of G2P API

Implement variant annotation service using GA4GH variant API


Visualize summary clinical decision support report based on a patients variants and drug treatment options returned from G2P query API

Analytics API -- create initial Avro specification for representing machine learning inferred associations in format compatible with literature curated G2P associations


## 2. Visualization

General concept -- create visualization "widget" for each GA4GH API
Story: "As a clinicial or researcher, given a set of GA4GH data, it would be (helpful) if I had (vizualization)"
Context: "Need Examples; Leverage Standard Products; Targeted at FullStack developers; Needs Bio Product Owner"

Variant Database: Create queryable variant database to interact with clinical genomics data from Knight diagnostic lab


As a cancer researcher, I'd like to know how strong clinicians studying genetic diseases would consider the evidence for my patient's cancer's exome mutation.Tool / CCC"More like this"
Story: As a clinician or researcher, given a artifact [MAF,VCF,…] are there other artifacts within CCC like this?
Context: "GeneMatcher: Leverage Elastic Search component within CCC to return similar datasets" https://github.com/MatchmakerExchange/mme-apis



Cell Profiler (imaging @ ohsu, Workflow with Cell Profiler, Cell Profiler to Galaxy)
Story: "As a imaging user at OHSU, I need help to create a cell profiler workflow"
Story: "As a imaging user at OHSU, I need help to publish my cell profiler pipeline to Galaxy"
Context: "TODO"

Add a genomic browser to CCC
Can we add one of these js visualizations to our workflow? 
* https://github.com/opencb/genome-maps
* http://www.biodalliance.org/embed.html
* http://wtsi-web.github.io/Genoverse/



## 3. General tooling

Parsers to convert other workflow description languages to Galaxy's
Story: "As a workflow author, it would be useful to convert [common workflow language] to/from galaxy"
Context: "TODO"

Add functionality to particular tool eg GATK
Story: "As a researcher or clinicial, given X , add Y functionality "
Story: "Select a tool for performance improvements"
Context: "Leverage scatter/gather / Spark/ Adam to increase performance"

Dockerize my Genomic Workflow
Story: "As a Galaxy user, in order to increase efficiency and portability, I need a Docker container for Tool X"
Context: "TODO"

Wrap my tool in Galaxy
Story: "As a tool author/user, in order to increase the distribution for my tool, it would be useful to have a Galaxy wrapper"
Context: "TODO"

OtherData Dashboard; Data Want Ads; Data For Sale:
Story: "As a informatics community member, I'd like to publish my data repotire or needs"
Context: "TODO"

Find Model Organisms
Story: As a researcher proposing therapies for patients and validating them outside the clinic, can I find a model organism in which to test a genotype/phenotype relationship?
Context: http://jmg.bmj.com/content/early/2014/10/03/jmedgenet-2014-102633.full
