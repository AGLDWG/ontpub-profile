# Vocabularies Publication Profile
This is a *profile* of the [Simple Knowledge Organization System (SKOS)](https://www.w3.org/TR/skos-reference/) implemented by [SURROUND Australia](https://surroundaustralia.com) to allow for the validation of vocabularies according to their business needs.

By *profile*, what is meant here is "A specification that constrains, extends, combines, or provides guidance or explanation about the usage of other specifications." (from [PROF](https://www.w3.org/TR/dx-prof/#definitions)) and, here the *other specification* is SKOS.

This profile is formulated according to the [Profiles Vocabulary](https://www.w3.org/TR/dx-prof/) and provides [Shapes Constraint Language (SHACL)](https://www.w3.org/TR/shacl/) validator files that can be used to determine whether vocabularies conform to this profile.

This profile is hosted online in [Linked Data](https://www.w3.org/standards/semanticweb/data) form using a persistent web address:

* <https://w3id.org/profile/vocpub>


## Profile Resources

### Specification
This profile's _specification_ - the resource that contains the normative rules - is within the file [specification.html](specification.html) and it is able to be viewed online at:

* <https://raw.githack.com/surroundaustralia/vocpub-profile/master/specification.html>

### Validator
This profile's rules, as defined in the _specification_ are presented for machine validation of RDF vocabularies in the shape file [validator.shacl.ttl](validator.shacl.ttl) which conforms to the [SHACL](https://www.w3.org/TR/shacl/) standard.

Tools such as [pySHACL](https://github.com/RDFLib/pySHACL) and the online [SHACL Playground](https://shacl.org/playground/) or [SHACL Play!](https://shacl-play.sparna.fr/play/) can be used with this shape file to validate vocabulary files.

## License  
This code is licensed using the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) licence. See the [LICENSE file](LICENSE) for the deed. 

Note [Citation](#citation) below for attribution.


## Citation
To cite this profile, please use the following (formulated in [BibTex](http://www.bibtex.org/)):

```
@software{vocpub-profile,
  author = {{SURROUND Australia Pty Ltd}},
  title = {{Vocabulary Publication Profile}},
  version = {1.0},
  date = {2021},
  publisher = {{SURROUND Australia Pty Ltd}},
  url = {https://w3id.org/profile/vocpub}
}
``` 


## Contact
*publisher:*  
![](style/SURROUND-logo-100.png)  
**SURROUND Australia Pty. Ltd.**  
<https://surroundaustralia.com>  

*creator:*  
**Dr Nicholas J. Car**  
*Data Systems Architect*  
SURROUND Australia Pty. Ltd.  
<nicholas.car@surroudaustralia.com>  
<https://orcid.org/0000-0002-8742-7730>