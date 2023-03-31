## FOI Request Base Power Pages Site and Solution

DISCLAIMER: This solution is provided as is, intended as a proof of concept to demonstrate Power Platform capability and is not intended for production use in its current state. UBDS makes no representation or warranty, express or implied for this solution. If you would like to arrange for support with further development of this solution, please reach out to us at hello@ubds.com. Please ensure you have consulted with your IT administrator before installing this solution.

# Prerequisites
- Custom components have been enabled on the Power Platform environment where the solution is to be imported to
- The creator kit solution, supplied by Microsoft has been imported into the Power Platform environment where the solution is to be imported to
- Ability to install and run Power Platform CLI

# Components
- Power Apps Canvas App – Front end app to be used by Information Governance Officers
- Multiple Power Automate Flows - Facilitate approval and chase business logic automation
- AI Model - Help determine the service the request has been made against.
- Virtual Agent Chat Bot - Surfaced in the Power Pages site.

# Installation
- Ensure all prerequisites have been met
- Import Power Platform Solution file
- Import Power Pages Site export by way of Power Platform CLI
- Create new Power Pages site and use the option of referencing the imported site made available by way of the previous installation step
