Demonstration of:

```
org.hl7.fhir.exceptions.FHIRException: Invalid candidate version: null
        at org.hl7.fhir.utilities.VersionUtilities.checkVersionNotNullAndValid(VersionUtilities.java:1169)
        at org.hl7.fhir.utilities.VersionUtilities.isThisOrLater(VersionUtilities.java:534)
        at org.hl7.fhir.validation.instance.type.ValueSetValidator.validateValueSetInclude(ValueSetValidator.java:458)
        at org.hl7.fhir.validation.instance.type.ValueSetValidator.validateValueSetCompose(ValueSetValidator.java:289)
        at org.hl7.fhir.validation.instance.type.ValueSetValidator.validateValueSet(ValueSetValidator.java:243)
        at org.hl7.fhir.validation.instance.InstanceValidator.checkSpecials(InstanceValidator.java:6513)
        at org.hl7.fhir.validation.instance.InstanceValidator.startInner(InstanceValidator.java:6443)
        at org.hl7.fhir.validation.instance.InstanceValidator.start(InstanceValidator.java:6188)
        at org.hl7.fhir.validation.instance.InstanceValidator.validateResource(InstanceValidator.java:8247)
        at org.hl7.fhir.validation.instance.InstanceValidator.validate(InstanceValidator.java:955)
        at org.hl7.fhir.igtools.publisher.PublisherProcessor.validate(PublisherProcessor.java:546)
        at org.hl7.fhir.igtools.publisher.PublisherProcessor.validate(PublisherProcessor.java:1728)
        at org.hl7.fhir.igtools.publisher.PublisherProcessor.validate(PublisherProcessor.java:1953)
        at org.hl7.fhir.igtools.publisher.PublisherProcessor.loadConformance2(PublisherProcessor.java:99)
        at org.hl7.fhir.igtools.publisher.Publisher.createIg(Publisher.java:366)
        at org.hl7.fhir.igtools.publisher.Publisher.execute(Publisher.java:218)
        at org.hl7.fhir.igtools.publisher.Publisher.main(Publisher.java:1482)
```
