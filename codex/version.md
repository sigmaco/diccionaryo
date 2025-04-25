# Term: version

## v1.0.0

**Definition**  
A specific, immutable iteration of a term’s definition, used to preserve semantic integrity over time.

**Domain**: system, archival  
**Forms**: version (noun), versioned (adj), versioning (gerund)

**Depends on**:  
- definition@1.0.0  
- time@1.0.0  
- identity@1.0.0

**Justification**  
Every definition in Logotecture must be versioned to prevent accidental drift or hostile redefinition.

**Sideloading Risk**:  
Low — consistent usage in software and publishing.

**Governance Notes**  
Once locked, a version is permanent. Changes must trigger new version entries, traceable via `based_on`.

**Status**: locked  
**Version**: 1.0.0
