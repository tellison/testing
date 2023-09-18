Published at https://openjdk.org/groups/vulnerability/advisories
and via [vuln-announce mailing list](https://mail.openjdk.org/mailman/listinfo/vuln-announce)

Contents
 - Advisory date
 - CVE ID
 - OpenJDK Component Affected
 - CVSSv3.1
   - (CVSS3.1 Vector)
 - OpenJDK Version Stream Affected
   - Specific release numbers
  
## Steps

1. Parse OpenJDK email -> Intermediate OJVG info json file.
   - This allows for isolating announcement format changes from downstream.
   - Subscribe to announce list to be event driven?
   - Can check validity with signing key.
2. Combine Intermediate file with Temurin info and NIST info
   - Create an adoptium/temurin/temurin-vdr.json
   - Captures CVE info, scores from others and affected Temurin products.
   - Allows for respin and minor upate etc to be linked back to earlier OpenJDK info (as we do for rel notes)
3. Update VDR on each Temurin release, Adoptium disclosure, and each OJVG update. 
4. Extract a summary of the VDR to publish alongside the Temurin Release Notes.
   
