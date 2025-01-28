---
title: SVGs in RFCs
abbrev: svgsinfrcs
docname: draft-rossi-svgsinrfcs-00

venue:
#  group: RSWG
#  type: Working Group
#  mail: rswg@rfc-editor.org
#  arch: https://datatracker.ietf.org/edwg/rswg/
  github: "id-svgsinrfcs"
  latest: "[https://github.com/alexisannerossi/id-svgsinrfcs/blob/main/svgsinrfcs.md]"

stand_alone: true
v: 3
obsoletes: 7996

ipr: trust200902
kw: Internet-Draft
cat: info
submissionType: editorial

keyword:
 - SVG

author:

   -
   ins: A. Rossi
   fullname: "Alexis Rossi"
   organization: RFC Series Consulting Editor
   email: "rsce@rfc-editor.org"
   -
   ins: N. Brownlee
   fullname: "Nevil Brownlee"
   organization: 
   email: "nevil.brownlee@gmail.com"
    -
   ins: J. Mahoney
   fullname: "Jean Mahoney"
   organization: RPC
   email: "jmahoney@amsl.com"

normative:
  

informative:
  RFC7996:
  https://www.w3.org/Graphics/SVG/About:
  https://www.w3.org/WAI/standards-guidelines/:

--- abstract

This document sets policy for the inclusion of SVGs in the definitive versions of RFCs and relevant publication formats. It contains policy requirements from {{RFC7996}} and removes all requirements related to using a specific SVG profile or specific implementation code. It also makes the RFC Publication Center (RPC) responsible for implementation decisions regarding SVGs.

There is a repository for this draft at <https://github.com/alexisannerossi/id-svgsinrfcs>

--- middle

# Introduction

This document sets policy for the inclusion of SVGs (Scalable Vector Graphics) in the definitive versions of RFCs and relevant publication formats. It contains policy requirements taken from {{RFC7996}} and removes all requirements related to using a specific SVG profile or specific implementation code.

SVG has been developed by W3C, the World Wide Web Consortium ([https://www.w3.org/Graphics/SVG/About](https://www.w3.org/Graphics/SVG/About)). 

The RFC Publication Center (RPC) is responsible for making SVG tooling and implementation decisions. They may want to use the content of {{RFC7996}} as a starting point for those decisions, but they are not bound by {{RFC7996}} and they may change elements of the implementation as needed to support the RFC authoring community as long as those changes are aligned with the policy requirements in this document.

# Policy Requirements

* SVG tooling and implementation decisions are made or overseen by the RPC, and must adhere to the policy requirements in this document. The RPC is expected to solicit community input before making these decisions and to publicly explain their reasoning. Documentation for SVG usage in RFCs will be publicly available.  
* SVGs may be included in RFCs to help explain a concept more clearly, but cannot be the only representation of that concept and must not contain details relevant to the RFC that are not also represented in the text. Normative descriptions of protocols, systems, etc. must be fully represented in the text of the RFC, and must not be contingent on comprehension of any SVG. SVGs are never to be considered as specifications in themselves.  
* SVGs in RFCs must render well on a wide variety of common devices, including those with smaller screens.   
* SVGs must remain static after publication of the RFC, so there may be interactive, multimedia, or other elements that cannot be used.  
* SVGs must not contain pointers to external resources.  
* SVGs must not contain executable script.  
* If an SVG is included in an RFC, it should also be included in any publication format that can adequately represent the SVG. The RPC may choose to support conversions from SVG to another image format if a publication format requires it.  
* SVGs should be as accessible as possible to people with visual disabilities, including those who have color blindness, those who need to scale or change fonts, and those who use screen reading software. The RPC will refer to [W3C Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/) when making decisions regarding accessibility.  
* SVG vocabulary and implementation may change over time and is not required to remain backwards-compatible.  
* The RPC’s implementation should strive to allow SVGs produced by widely used drawing tools. Where possible, implementation decisions should focus on specifying what is disallowed, rather than attempting to specify exactly what is allowed.

# Security Considerations

This document has no security considerations.


# IANA Considerations

This document has no IANA actions.


--- back

