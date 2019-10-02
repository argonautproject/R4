## List all US Core Required and Must Support Elements

Note that:

1. this DOES NOT consider the [FHIR Observation Vitals elements](http://build.fhir.org/observation-vitalsigns.html) since they are not defined in US Core.
1. Many of the elements that are defined as required inherited from the the base specification.


[**CSV version**](https://github.com/argonautproject/R4/blob/master/conf_summary.csv)  



|Profile|Element|isRequired|isMustSupport|
|-----------------|-------|---|---|
|US Core Pediatric BMI for Age Observation Profile|Observation|||
|US Core Pediatric BMI for Age Observation Profile|Observation.code|X||
|US Core Pediatric Weight for Height Observation Profile|Observation|||
|US Core Pediatric Weight for Height Observation Profile|Observation.code|X||
|US  Core AllergyIntolerance Profile|AllergyIntolerance|||
|US  Core AllergyIntolerance Profile|AllergyIntolerance.clinicalStatus||X|
|US  Core AllergyIntolerance Profile|AllergyIntolerance.verificationStatus||X|
|US  Core AllergyIntolerance Profile|AllergyIntolerance.code|X|X|
|US  Core AllergyIntolerance Profile|AllergyIntolerance.patient|X|X|
|US Core Birth Sex Extension|Extension|||
|US Core Birth Sex Extension|Extension.url|X||
|US Core Birth Sex Extension|Extension.valueCode|||
|US Core CarePlan Profile|CarePlan|||
|US Core CarePlan Profile|CarePlan.text|X|X|
|US Core CarePlan Profile|CarePlan.text.status|X|X|
|US Core CarePlan Profile|CarePlan.status|X|X|
|US Core CarePlan Profile|CarePlan.intent|X|X|
|US Core CarePlan Profile|CarePlan.category|X|X|
|US Core CarePlan Profile|CarePlan.category|X|X|
|US Core CarePlan Profile|CarePlan.subject|X|X|
|US Core CareTeam Profile|CareTeam|||
|US Core CareTeam Profile|CareTeam.status||X|
|US Core CareTeam Profile|CareTeam.subject|X|X|
|US Core CareTeam Profile|CareTeam.participant|X|X|
|US Core CareTeam Profile|CareTeam.participant.role|X|X|
|US Core CareTeam Profile|CareTeam.participant.member|X|X|
|US Core Condition Profile|Condition|||
|US Core Condition Profile|Condition.clinicalStatus||X|
|US Core Condition Profile|Condition.verificationStatus||X|
|US Core Condition Profile|Condition.category|X|X|
|US Core Condition Profile|Condition.code|X|X|
|US Core Condition Profile|Condition.subject|X|X|
|US Core DiagnosticReport Profile for Laboratory Results Reporting|DiagnosticReport|||
|US Core DiagnosticReport Profile for Laboratory Results Reporting|DiagnosticReport.status|X|X|
|US Core DiagnosticReport Profile for Laboratory Results Reporting|DiagnosticReport.category|X|X|
|US Core DiagnosticReport Profile for Laboratory Results Reporting|DiagnosticReport.category|X|X|
|US Core DiagnosticReport Profile for Laboratory Results Reporting|DiagnosticReport.code|X|X|
|US Core DiagnosticReport Profile for Laboratory Results Reporting|DiagnosticReport.subject|X|X|
|US Core DiagnosticReport Profile for Laboratory Results Reporting|DiagnosticReport.effective[x]|X|X|
|US Core DiagnosticReport Profile for Laboratory Results Reporting|DiagnosticReport.issued|X|X|
|US Core DiagnosticReport Profile for Laboratory Results Reporting|DiagnosticReport.performer||X|
|US Core DiagnosticReport Profile for Laboratory Results Reporting|DiagnosticReport.result||X|
|US Core DiagnosticReport Profile for Laboratory Results Reporting|DiagnosticReport.media||X|
|US Core DiagnosticReport Profile for Laboratory Results Reporting|DiagnosticReport.presentedForm||X|
|US Core DiagnosticReport Profile for Report and Note exchange|DiagnosticReport|||
|US Core DiagnosticReport Profile for Report and Note exchange|DiagnosticReport.status|X|X|
|US Core DiagnosticReport Profile for Report and Note exchange|DiagnosticReport.category|X|X|
|US Core DiagnosticReport Profile for Report and Note exchange|DiagnosticReport.code|X|X|
|US Core DiagnosticReport Profile for Report and Note exchange|DiagnosticReport.subject|X|X|
|US Core DiagnosticReport Profile for Report and Note exchange|DiagnosticReport.encounter||X|
|US Core DiagnosticReport Profile for Report and Note exchange|DiagnosticReport.effective[x]|X|X|
|US Core DiagnosticReport Profile for Report and Note exchange|DiagnosticReport.issued||X|
|US Core DiagnosticReport Profile for Report and Note exchange|DiagnosticReport.performer||X|
|US Core DiagnosticReport Profile for Report and Note exchange|DiagnosticReport.media||X|
|US Core DiagnosticReport Profile for Report and Note exchange|DiagnosticReport.presentedForm||X|
|US Core Direct email Extension|Extension|||
|US Core Direct email Extension|Extension.url|X||
|US Core Direct email Extension|Extension.valueBoolean|||
|US Core DocumentReference Profile|DocumentReference|||
|US Core DocumentReference Profile|DocumentReference.identifier||X|
|US Core DocumentReference Profile|DocumentReference.status|X|X|
|US Core DocumentReference Profile|DocumentReference.type|X|X|
|US Core DocumentReference Profile|DocumentReference.category|X|X|
|US Core DocumentReference Profile|DocumentReference.subject|X|X|
|US Core DocumentReference Profile|DocumentReference.date||X|
|US Core DocumentReference Profile|DocumentReference.author||X|
|US Core DocumentReference Profile|DocumentReference.custodian||X|
|US Core DocumentReference Profile|DocumentReference.content|X|X|
|US Core DocumentReference Profile|DocumentReference.content.attachment|X|X|
|US Core DocumentReference Profile|DocumentReference.content.attachment.contentType|X|X|
|US Core DocumentReference Profile|DocumentReference.content.attachment.data||X|
|US Core DocumentReference Profile|DocumentReference.content.attachment.url||X|
|US Core DocumentReference Profile|DocumentReference.content.format||X|
|US Core DocumentReference Profile|DocumentReference.context||X|
|US Core DocumentReference Profile|DocumentReference.context.encounter||X|
|US Core DocumentReference Profile|DocumentReference.context.period||X|
|US Core Encounter Profile|Encounter|||
|US Core Encounter Profile|Encounter.identifier||X|
|US Core Encounter Profile|Encounter.identifier.system|X|X|
|US Core Encounter Profile|Encounter.identifier.value|X|X|
|US Core Encounter Profile|Encounter.status|X|X|
|US Core Encounter Profile|Encounter.class|X|X|
|US Core Encounter Profile|Encounter.type|X|X|
|US Core Encounter Profile|Encounter.subject|X|X|
|US Core Encounter Profile|Encounter.participant||X|
|US Core Encounter Profile|Encounter.participant.type||X|
|US Core Encounter Profile|Encounter.participant.period||X|
|US Core Encounter Profile|Encounter.participant.individual||X|
|US Core Encounter Profile|Encounter.period||X|
|US Core Encounter Profile|Encounter.reasonCode||X|
|US Core Encounter Profile|Encounter.hospitalization||X|
|US Core Encounter Profile|Encounter.hospitalization.dischargeDisposition||X|
|US Core Encounter Profile|Encounter.location||X|
|US Core Encounter Profile|Encounter.location.location|X|X|
|US Core Ethnicity Extension|Extension|||
|US Core Ethnicity Extension|Extension.extension|||
|US Core Ethnicity Extension|Extension.extension||X|
|US Core Ethnicity Extension|Extension.extension.url|X||
|US Core Ethnicity Extension|Extension.extension.valueCoding|X||
|US Core Ethnicity Extension|Extension.extension|||
|US Core Ethnicity Extension|Extension.extension.url|X||
|US Core Ethnicity Extension|Extension.extension.valueCoding|X||
|US Core Ethnicity Extension|Extension.extension|X|X|
|US Core Ethnicity Extension|Extension.extension.url|X||
|US Core Ethnicity Extension|Extension.extension.valueString|X||
|US Core Ethnicity Extension|Extension.url|X||
|US Core Goal Profile|Goal|||
|US Core Goal Profile|Goal.lifecycleStatus|X|X|
|US Core Goal Profile|Goal.description|X|X|
|US Core Goal Profile|Goal.subject|X|X|
|US Core Goal Profile|Goal.target||X|
|US Core Immunization Profile|Immunization|||
|US Core Immunization Profile|Immunization.status|X|X|
|US Core Immunization Profile|Immunization.statusReason||X|
|US Core Immunization Profile|Immunization.vaccineCode|X|X|
|US Core Immunization Profile|Immunization.patient|X|X|
|US Core Immunization Profile|Immunization.occurrence[x]|X|X|
|US Core Immunization Profile|Immunization.primarySource|X|X|
|US Core Implantable Device Profile|Device|||
|US Core Implantable Device Profile|Device.udiCarrier||X|
|US Core Implantable Device Profile|Device.udiCarrier.deviceIdentifier|X|X|
|US Core Implantable Device Profile|Device.udiCarrier.carrierAIDC||X|
|US Core Implantable Device Profile|Device.udiCarrier.carrierHRF||X|
|US Core Implantable Device Profile|Device.distinctIdentifier||X|
|US Core Implantable Device Profile|Device.manufactureDate||X|
|US Core Implantable Device Profile|Device.expirationDate||X|
|US Core Implantable Device Profile|Device.lotNumber||X|
|US Core Implantable Device Profile|Device.serialNumber||X|
|US Core Implantable Device Profile|Device.type|X|X|
|US Core Implantable Device Profile|Device.patient|X|X|
|US Core Location Profile|Location|||
|US Core Location Profile|Location.status||X|
|US Core Location Profile|Location.name|X|X|
|US Core Location Profile|Location.telecom||X|
|US Core Location Profile|Location.address||X|
|US Core Location Profile|Location.address.line||X|
|US Core Location Profile|Location.address.city||X|
|US Core Location Profile|Location.address.state||X|
|US Core Location Profile|Location.address.postalCode||X|
|US Core Location Profile|Location.managingOrganization||X|
|US Core Medication Profile|Medication|||
|US Core Medication Profile|Medication.code|X|X|
|US Core MedicationRequest Profile|MedicationRequest|||
|US Core MedicationRequest Profile|MedicationRequest.status|X|X|
|US Core MedicationRequest Profile|MedicationRequest.intent|X|X|
|US Core MedicationRequest Profile|MedicationRequest.reported[x]||X|
|US Core MedicationRequest Profile|MedicationRequest.medication[x]|X|X|
|US Core MedicationRequest Profile|MedicationRequest.subject|X|X|
|US Core MedicationRequest Profile|MedicationRequest.encounter||X|
|US Core MedicationRequest Profile|MedicationRequest.authoredOn|X|X|
|US Core MedicationRequest Profile|MedicationRequest.requester|X|X|
|US Core MedicationRequest Profile|MedicationRequest.dosageInstruction||X|
|US Core MedicationRequest Profile|MedicationRequest.dosageInstruction.text||X|
|US Core Laboratory Result Observation Profile|Observation|||
|US Core Laboratory Result Observation Profile|Observation.status|X|X|
|US Core Laboratory Result Observation Profile|Observation.category|X|X|
|US Core Laboratory Result Observation Profile|Observation.category|X|X|
|US Core Laboratory Result Observation Profile|Observation.code|X|X|
|US Core Laboratory Result Observation Profile|Observation.subject|X|X|
|US Core Laboratory Result Observation Profile|Observation.effective[x]||X|
|US Core Laboratory Result Observation Profile|Observation.value[x]||X|
|US Core Laboratory Result Observation Profile|Observation.dataAbsentReason||X|
|US Core Organization Profile|Organization|||
|US Core Organization Profile|Organization.identifier||X|
|US Core Organization Profile|Organization.identifier.system||X|
|US Core Organization Profile|Organization.identifier.value||X|
|US Core Organization Profile|Organization.identifier||X|
|US Core Organization Profile|Organization.identifier||X|
|US Core Organization Profile|Organization.active|X|X|
|US Core Organization Profile|Organization.name|X|X|
|US Core Organization Profile|Organization.telecom||X|
|US Core Organization Profile|Organization.address||X|
|US Core Organization Profile|Organization.address.line||X|
|US Core Organization Profile|Organization.address.city||X|
|US Core Organization Profile|Organization.address.state||X|
|US Core Organization Profile|Organization.address.postalCode||X|
|US Core Organization Profile|Organization.address.country||X|
|US Core Organization Profile|Organization.endpoint||X|
|US Core Patient Profile|Patient|||
|US Core Patient Profile|Patient.extension|||
|US Core Patient Profile|Patient.extension||X|
|US Core Patient Profile|Patient.extension||X|
|US Core Patient Profile|Patient.extension||X|
|US Core Patient Profile|Patient.identifier|X|X|
|US Core Patient Profile|Patient.identifier.system|X|X|
|US Core Patient Profile|Patient.identifier.value|X|X|
|US Core Patient Profile|Patient.name|X|X|
|US Core Patient Profile|Patient.name.family||X|
|US Core Patient Profile|Patient.name.given||X|
|US Core Patient Profile|Patient.telecom||X|
|US Core Patient Profile|Patient.telecom.system|X|X|
|US Core Patient Profile|Patient.telecom.value|X|X|
|US Core Patient Profile|Patient.telecom.use||X|
|US Core Patient Profile|Patient.gender|X|X|
|US Core Patient Profile|Patient.birthDate||X|
|US Core Patient Profile|Patient.address||X|
|US Core Patient Profile|Patient.address.line||X|
|US Core Patient Profile|Patient.address.city||X|
|US Core Patient Profile|Patient.address.state||X|
|US Core Patient Profile|Patient.address.postalCode||X|
|US Core Patient Profile|Patient.address.period||X|
|US Core Patient Profile|Patient.communication||X|
|US Core Patient Profile|Patient.communication.language|X|X|
|US Core Practitioner Profile|Practitioner|||
|US Core Practitioner Profile|Practitioner.identifier|X|X|
|US Core Practitioner Profile|Practitioner.identifier.system|X|X|
|US Core Practitioner Profile|Practitioner.identifier.value|X|X|
|US Core Practitioner Profile|Practitioner.identifier||X|
|US Core Practitioner Profile|Practitioner.name|X|X|
|US Core Practitioner Profile|Practitioner.name.family|X|X|
|US Core PractitionerRole Profile|PractitionerRole|||
|US Core PractitionerRole Profile|PractitionerRole.practitioner|X|X|
|US Core PractitionerRole Profile|PractitionerRole.organization|X|X|
|US Core PractitionerRole Profile|PractitionerRole.code||X|
|US Core PractitionerRole Profile|PractitionerRole.specialty||X|
|US Core PractitionerRole Profile|PractitionerRole.location||X|
|US Core PractitionerRole Profile|PractitionerRole.telecom||X|
|US Core PractitionerRole Profile|PractitionerRole.telecom.system|X|X|
|US Core PractitionerRole Profile|PractitionerRole.telecom.value|X|X|
|US Core PractitionerRole Profile|PractitionerRole.endpoint||X|
|US Core Procedure Profile|Procedure|||
|US Core Procedure Profile|Procedure.status|X|X|
|US Core Procedure Profile|Procedure.code|X|X|
|US Core Procedure Profile|Procedure.subject|X|X|
|US Core Procedure Profile|Procedure.performed[x]|X|X|
|US Core Provenance Profile|Provenance|||
|US Core Provenance Profile|Provenance.target|X|X|
|US Core Provenance Profile|Provenance.recorded|X|X|
|US Core Provenance Profile|Provenance.agent|X|X|
|US Core Provenance Profile|Provenance.agent.type||X|
|US Core Provenance Profile|Provenance.agent.who|X|X|
|US Core Provenance Profile|Provenance.agent.onBehalfOf||X|
|US Core Provenance Profile|Provenance.agent||X|
|US Core Provenance Profile|Provenance.agent.type|X|X|
|US Core Provenance Profile|Provenance.agent.who|X||
|US Core Provenance Profile|Provenance.agent.onBehalfOf|||
|US Core Provenance Profile|Provenance.agent||X|
|US Core Provenance Profile|Provenance.agent.type|X|X|
|US Core Provenance Profile|Provenance.agent.who|X||
|US Core Provenance Profile|Provenance.agent.onBehalfOf|||
|US Core Pulse Oximetry Profile|Observation|||
|US Core Pulse Oximetry Profile|Observation.code|X|X|
|US Core Pulse Oximetry Profile|Observation.code.coding||X|
|US Core Pulse Oximetry Profile|Observation.code.coding|X||
|US Core Pulse Oximetry Profile|Observation.code.coding.system|X||
|US Core Pulse Oximetry Profile|Observation.code.coding.code|X||
|US Core Pulse Oximetry Profile|Observation.code.coding|X|X|
|US Core Pulse Oximetry Profile|Observation.code.coding.system|X|X|
|US Core Pulse Oximetry Profile|Observation.code.coding.code|X|X|
|US Core Pulse Oximetry Profile|Observation.component||X|
|US Core Pulse Oximetry Profile|Observation.component.code|X|X|
|US Core Pulse Oximetry Profile|Observation.component||X|
|US Core Pulse Oximetry Profile|Observation.component.code|X|X|
|US Core Pulse Oximetry Profile|Observation.component||X|
|US Core Pulse Oximetry Profile|Observation.component.code|X|X|
|US Core Race Extension|Extension|||
|US Core Race Extension|Extension.extension|||
|US Core Race Extension|Extension.extension||X|
|US Core Race Extension|Extension.extension.url|X||
|US Core Race Extension|Extension.extension.valueCoding|X||
|US Core Race Extension|Extension.extension|||
|US Core Race Extension|Extension.extension.url|X||
|US Core Race Extension|Extension.extension.valueCoding|X||
|US Core Race Extension|Extension.extension|X|X|
|US Core Race Extension|Extension.extension.url|X||
|US Core Race Extension|Extension.extension.valueString|X||
|US Core Race Extension|Extension.url|X||
|US Core Smoking Status Observation Profile|Observation|||
|US Core Smoking Status Observation Profile|Observation.status|X|X|
|US Core Smoking Status Observation Profile|Observation.code|X|X|
|US Core Smoking Status Observation Profile|Observation.subject|X|X|
|US Core Smoking Status Observation Profile|Observation.issued|X|X|
