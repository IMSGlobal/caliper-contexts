# IMS Global Learning Consortium, Inc.


# This is an archived repository

This repository's master branch represents the Caliper Context as of May 24, 2018.

The maintained contexts now lives in the main [Caliper repo's develop branch](https://github.com/IMSGlobal/caliper-spec/tree/develop)

# caliper-contexts
The [Caliper Analytics® Specification](https://www.imsglobal.org/caliper/v1p1/caliper-spec-v1p1) 
provides a structured approach to describing, collecting and exchanging learning activity data at 
scale. Caliper also defines an application programming interface (the Sensor API™) for marshalling 
and transmitting event data from instrumented applications to target endpoints for storage, analysis 
and use.  

IMS Global provides a remote Caliper JSON-LD context documents for mapping Caliper terms to IRIs. 
Implementers are encouraged to familiarize themselves with the term definitions described therein.

## Branches
* __master__: stable, deployable branch that stores the official release history.  
* __develop__: unstable development branch.  Current work that targets a future release is merged to 
this branch.

## Tags
*caliper-contexts* releases are tagged and versioned MAJOR.MINOR.PATCH\[-label\] (e.g., 1.1.0). 
Pre-release tags are identified with an extensions label (e.g., "1.2.0-RC01").  The tags are stored 
in this repository.

## Contributing
We welcome the posting of issues by non IMS Global Learning Consortium members (e.g., feature 
requests, bug reports, questions, etc.) but we *do not* accept contributions in the form of pull 
requests from non-members. See [CONTRIBUTING.md](./CONTRIBUTING.md) for more 
information.

## Getting Started
Caliper JSON-LD documents require inclusion of a context, denoted by the `@context` keyword, a 
property employed to map document terms to IRIs. JSON-LD contexts can be embedded inline or 
referenced externally in a document. Inclusion of a JSON-LD context provides an economical way for 
Caliper to communicate document semantics to services interested in consuming Caliper event data.

```
{
  "@context": "http://purl.imsglobal.org/ctx/caliper/v1p1",
  ...
}
```

For requirements and examples see the Caliper Analytics&reg; Specification, version 1.1, 
[section 4.1](https://github.com/IMSGlobal/caliper-spec/blob/master/caliper-spec.md#41-json-ld-context).

## License
This project is licensed under the terms of the GNU Lesser General Public License (LGPL), version 3. 
See the [LICENSE](./LICENSE) file for details. For additional information on licensing options for 
IMS members, please see the [NOTICE](./NOTICE.md) file.

©2018 IMS Global Learning Consortium, Inc. All Rights Reserved.
Trademark Information - http://www.imsglobal.org/copyright.html
