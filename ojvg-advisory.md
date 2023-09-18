Published at https://openjdk.org/groups/vulnerability/advisories
 
 - Advisory date
 - CVE ID
 - OpenJDK Component Affected
 - CVSSv3.1
   - (CVSS3.1 Vector)
 - OpenJDK Version Stream Affected
   - Specific release in freetext header
  
== Steps

1. Scrape OpenJDK website -> Intermediate OJVG info file
   This allows for isolating website changes from downstream
2. Combine Intermediate file with Temurin info and NIST info
   Create an adoptium/temurin/temurin-vdr.json
3. Update VDR on each Temurin release, Adoptium disclosure, and each OJVG website update
4. Extract a summary of the VDR to publish alongside the Temurin Release Notes.
   
