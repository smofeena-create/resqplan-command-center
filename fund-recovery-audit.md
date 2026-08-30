# Fund & Recovery Tracking Audit

The existing ResQplan prototype already has Recovery & Restoration cases, a lifecycle map, simulated demo state, persistent browser state, and Authority-only navigation. The brief can be added without redesigning the site by extending the existing recovery model with approved funding, utilized funding, calculated remaining funding, progress, evidence, responsible authority, verification, and delayed status.

The implementation will add three Authority navigation entries under the existing Recovery & Restoration area: Recovery Overview (the current recovery view), Recovery Projects (a clean project register), and Fund & Recovery Tracking (the new KPI, utilization, project detail, evidence, and verification surface). Recovery project markers will be added to the existing recovery map popup without adding a separate financial dashboard. All records will be simulated and clearly labeled.

The write path will remain Authority-only. Organization, Volunteer, and Responder roles will continue to use their existing role-specific navigation and will not receive financial editing controls. Remaining funding will always be calculated as approved minus utilized and displayed with Indian currency formatting.
