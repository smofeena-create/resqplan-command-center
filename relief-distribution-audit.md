# Relief Fund Distribution Audit

ResQplan already has shared persistent state for zones, volunteer-collected citizen/household records, incident completion, Recovery & Restoration, Fund & Recovery Tracking, role-specific navigation, the interactive GIS map, and the SIH demo reset. The new relief feature should extend this shared controller rather than add a second citizen database or a separate application.

The Authority role can own relief-fund allocation, zone and volunteer assignment, distribution visibility, filters, verification, rejection reasons, and dashboard calculations. The Volunteer role should receive only the allocations assigned to V-101 and record a demo distribution against an eligible household derived from the existing citizen records. Organization and Responder roles should not receive relief approval or independent government-fund controls.

The optional map layer should aggregate activity by affected zone and show no individual beneficiary financial details. All beneficiary IDs, household IDs, amounts, evidence, dates, and names remain simulated. The lifecycle entry point belongs with the existing Recovery Overview, Recovery Projects, and Fund & Recovery Tracking navigation.
