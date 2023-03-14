# The Data Source Description Vocabulary (DSD)

The Data Source Description Vocabulary (DSD) is an vocabulary based on RDF and OWL that can be used to represent data sources and their internal structure in ontologies.

A documentation describing the available OWL classes and properties of the current version (4.0) of the vocabulary can be found at <https://w3id.org/dsd>.

The vocabulary itself can be downloaded in the release section of this repository. Additionally, it can be imported directly in tools like Protégé by using the IRI <https://w3id.org/dsd>.

A scientific publication about the DSD vocabulary is currently submitted for review.

## FAIR

Starting with version 4.0, the DSD vocabulary is evaluated automatically and manually against the FAIR principles [[1]](#1).

- The result of a manual evalaution is available at <https://w3id.org/dsd/evaluation>
- The vocabulary in version 4.0 was evaluated using the [Fair Ontology Pitfall Scanner (FOOPS!)](https://w3id.org/foops). It received a score of 78%, although several issues highlighted by FOOPS! are not present when looking at the DSD manually (e.g., metadata for authors are indeed present). We therefore claim that the real score will be higher than 78%.

### Provenance

We see provenance information not as part of a vocabulary. Therefore, such information is not included in the vocabulary, but can be retrieved using this repository.

[Changes between the current version (4.0) and DSD version 3.0](https://github.com/FAW-JKU/dsd-vocabulary/compare/3.0...4.0)

[Changes between DSD version 2.0 and 3.0](https://github.com/FAW-JKU/dsd-vocabulary/compare/2.0...3.0)

## Contribution

We appreciate contributions and encourage you to submit suggestions by [creating an issue](https://github.com/FAW-JKU/dsd-vocabulary/issues) in this GitHub repository.

## License

The Data Source Description Vocabulary (DSD) is available under the LGPL-2.1 license. Please see the [LICENSE file](https://github.com/FAW-JKU/dsd-vocabulary/blob/main/LICENSE) for details.

## Contact information

- Author: Lisa Ehrlinger (<lisa.ehrlinger@scch.at>)
- Contributor: Johannes Schrott (<johannes.schrott@jku.at>, <johannes.schrott@scch.at>)

Homepage: <https://dqm.faw.jku.at>

## References

<span id=1>[1]</span> Wilkinson et al. ‘The FAIR Guiding Principles for Scientific Data Management and Stewardship’. Scientific Data 3, no. 1 (December 2016): 160018. <https://doi.org/10.1038/sdata.2016.18>.
