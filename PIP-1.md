---
PIP: 1
Title: The PIP Governance Proposal Process
Author: Vivi
Status: Approved
Created: 2019-10-21
---

# PIP-1: The PlatON Governance Proposal Process

**Version 1.0**

## What is an PIP?
PIP stands for PlatON Governance Proposal. An PIP is a document that details a change to the management, allocation, or use of shared resources owned or directly influenced by the PlatON Network. The PIP author is responsible for building consensus within the community for their PIP and documenting dissenting opinions.

## PIP process rationale
The purpose of the PlatON Governance Proposal Process is to provide a structured process for making changes to the shared resources of the PlatON Network. For these shared resources, governance processes are needed to grant or deny access and approve or reject proposed changes. By creating a fair, lightweight, and transparent PlatON process, the PIP-1 authors hope to give Energon holders a meaningful say in the PlatON Network and increase the chances of success.

## Proposal workflow
Parties directly involved in the process are the _PIP author_ (you) and the _PIP Editors_.

Proposals follow this workflow:

* Stage I: Draft Proposal
* Stage II: Final Proposal

### Stage I: Draft
During this stage you should seek feedback on your PIP idea by sharing it with your peers in the PIP community and soliciting their feedback. After you have asked the PIP community whether an idea has any chance of support and have received sufficient feedback to feel confident going forward, you can create a draft PIP as a pull request to the PIP repo. Use a template from the Templates section below to ensure you are including all the necessary information. The draft PIP file should be given a temporary name, which the PIP Editors will rename when the PIP is assigned a number.

PIP Editors will preliminarily review the draft content, and if the preliminary review is passed, the pull request will be labeled draft,otherwise the pull request will be closed.

**Templates**  
Below is a list of PIP templates for each type. Copy the template for the your PIP, fill it out, and submit the pull request with your PIP for review. Sections marked as “required” in the template must be completed. Note that all proposals must be licensed CC-0.

* [Cancellation](../templates/Cancellation-template.md)
* [Parameter](../templates/Parameter-template.md)
* [Text](../templates/Text_template.md)
* [Upgrade](../templates/Upgrade-template.md)


### Stage II: Final
After a PIP has been submitted as a draft to the PIPs repo, you can constantly revise your draft by submitting pull requests until the PIP is finalized. After finalizing, inform the editor to set the label to final. If it hasn't been finalized in two weeks, PIP Editors will consider the proposal withdrawn and close the pull request.

PIP Editors will carefully review the final draft, if agreeable, the proposal will be merged to PIPs repo.  No changes can be made to a PIP after merging.

## PIP Editors
PIP Editors are experienced and active members of the PIP community selected to manage the PIP workflow.PIP Editors exist to make proposals submitted to the PIP repo easier to review.

PIP Editors have two responsibilities:

* Tag the pull request
* Review the proposal, if the proposal is approved, assign PIP number, modify the document name, and merge it into the repo.

## License
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
