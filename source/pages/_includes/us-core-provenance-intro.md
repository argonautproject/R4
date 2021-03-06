This profile sets minimum expectations for the [Provenance] resource to record, search and fetch Provenance information associated with a record. It identifies which core elements, extensions, vocabularies and value sets **SHALL** be present in the resource when using this profile. This FHIR Provenance profile here covers the minimal (basic) information to support lineage of information.      

**Example Usage Scenarios:**

The following are example usage scenarios for the US Core Provenance profile:

-   Query for the Provenance records associated with an Allergy
-   Query for the Provenance records associated with a Problem


### Mandatory and Must Support Data Elements

The following data-elements are mandatory (i.e. data MUST be present) or must be supported if the data is present in the sending system ([Must Support] definition). They are presented below in a simple human-readable explanation.  Profile specific guidance and examples are provided as well.  The [Formal Profile Definition] below provides the  formal summary, definitions, and  terminology requirements.  

**Each Provenance must have:**

1.  resource(s) the Provenance record is supporting (target)
1.  a date and time for the activity


**Each Provenance must support:**

1.  an author responsible for the update
1.  the author organization responsible for the information
1.  the transmitter device or organization that provided the information
1.  if the transmitter device is provided, the transmitter organization responsible for the transmission is also required.

**Profile specific implementation guidance:**

* If a system receives a provider in `Provenance.agent.who` as free text they must capture who sent them the information as the organization. On request they  **SHALL** provide this organization as the source and **MAY** include the free text provider.

### Examples

- [Allergyintolerance Provenance Example](Bundle-c887e62f-6166-419f-8268-b5ecd6c7b901.html):  A `searchset` Bundle including both AllergyIntolerance and Provenance

{% include link-list.md %}
