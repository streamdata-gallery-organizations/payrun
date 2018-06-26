---
name: PayRun
x-slug: payrun
description: An open, scalable, transparent and HMRC accredited payroll API. Put the
  power of payroll into your application today.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
x-kinRank: "7"
x-alexaRank: "0"
tags: PayRun
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/apis.md
specificationVersion: "0.14"
apis:
- name: Pay Run.IO Delete an Employer
  x-api-slug: pay-run-io
  description: Delete the specified employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}
  tags: Employer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployerid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployerid-delete-openapi.md
- name: Pay Run.IO Gets the employer
  x-api-slug: pay-run-io
  description: Get the specified employer object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}
  tags: Employer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployerid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployerid-get-openapi.md
- name: Pay Run.IO Patches the employer
  x-api-slug: pay-run-io
  description: Patches the specified employer with the supplied values
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}
  tags: Patches,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployerid-patch-openapi.md
- name: Pay Run.IO Updates the Employer
  x-api-slug: pay-run-io
  description: Updates the existing specified employer object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}
  tags: Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployerid-put-openapi.md
- name: Pay Run.IO Deletes the DPS message
  x-api-slug: pay-run-io
  description: Deletes the DPS message
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/DpsMessage/{DpsMessageId}
  tags: DPMessage
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeriddpsmessagedpsmessageid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeriddpsmessagedpsmessageid-delete-openapi.md
- name: Pay Run.IO Gets the DPS message
  x-api-slug: pay-run-io
  description: Gets the DPS message
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/DpsMessage/{DpsMessageId}
  tags: DPMessage
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeriddpsmessagedpsmessageid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeriddpsmessagedpsmessageid-get-openapi.md
- name: Pay Run.IO Patches the DPS message
  x-api-slug: pay-run-io
  description: Patches the specified DPS message with the supplied values
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/DpsMessage/{DpsMessageId}
  tags: Patches,DPMessage
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeriddpsmessagedpsmessageid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeriddpsmessagedpsmessageid-patch-openapi.md
- name: Pay Run.IO Gets the DPS messages
  x-api-slug: pay-run-io
  description: Gets the DPS message links
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/DpsMessages
  tags: DPMessages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeriddpsmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeriddpsmessages-get-openapi.md
- name: Pay Run.IO Delete an Employee
  x-api-slug: pay-run-io
  description: Delete the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}
  tags: Employee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeid-delete-openapi.md
- name: Pay Run.IO Get employee from employer
  x-api-slug: pay-run-io
  description: Gets the specified employee from employer by employee code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}
  tags: Employee,From,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeid-get-openapi.md
- name: Pay Run.IO Patches the employee
  x-api-slug: pay-run-io
  description: Patches the specified employee with the supplied values
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}
  tags: Patches,Employee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeid-patch-openapi.md
- name: Pay Run.IO Updates the Employee
  x-api-slug: pay-run-io
  description: Updates the existing specified employee object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}
  tags: Employee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeid-put-openapi.md
- name: Pay Run.IO Delete auto enrolment assessment
  x-api-slug: pay-run-io
  description: Deletes an existing auto enrolment assessment for the employee. Used
    to remove historical assessments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/AEAssessment/{AEAssessmentId}
  tags: Auto,Enrolment,Assessment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidaeassessmentaeassessmentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidaeassessmentaeassessmentid-delete-openapi.md
- name: Pay Run.IO Get the auto enrolment assessment
  x-api-slug: pay-run-io
  description: Gets the auto enrolment assessment from the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/AEAssessment/{AEAssessmentId}
  tags: Auto,Enrolment,Assessment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidaeassessmentaeassessmentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidaeassessmentaeassessmentid-get-openapi.md
- name: Pay Run.IO Insert new auto enrolment assessment
  x-api-slug: pay-run-io
  description: Creates a new auto enrolment assessment for the employee. Used to insert
    historical assessments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/AEAssessment/{AEAssessmentId}
  tags: Insert,New,Auto,Enrolment,Assessment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidaeassessmentaeassessmentid-put-openapi.md
- name: Pay Run.IO Get the auto enrolment assessments
  x-api-slug: pay-run-io
  description: Gets all auto enrolment assessments from the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/AEAssessments
  tags: Auto,Enrolment,Assessments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidaeassessments-get-openapi.md
- name: Pay Run.IO Insert new auto enrolment assessment
  x-api-slug: pay-run-io
  description: Creates a new auto enrolment assessment for the employee. Used to insert
    historical assessments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/AEAssessments
  tags: Insert,New,Auto,Enrolment,Assessment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidaeassessments-post-openapi.md
- name: Pay Run.IO Get links to all commentaries for the specified employee
  x-api-slug: pay-run-io
  description: Get links to all commentaries for the specified employee.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/Commentaries
  tags: Links,To,,Commentariesthe,Specified,Employee
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidcommentaries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidcommentaries-get-openapi.md
- name: Pay Run.IO Get commentary from employee
  x-api-slug: pay-run-io
  description: Gets the specified commentary report from the employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/Commentary/{CommentaryId}
  tags: Commentary,From,Employee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidcommentarycommentaryid-get-openapi.md
- name: Pay Run.IO Deletes a pay instruction
  x-api-slug: pay-run-io
  description: Delete the specified pay instruction
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/PayInstruction/{PayInstructionId}
  tags: Pay,Instruction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-delete-openapi.md
- name: Pay Run.IO Gets the specified pay instruction from the employee
  x-api-slug: pay-run-io
  description: Returns the specified pay instruction from employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/PayInstruction/{PayInstructionId}
  tags: Specified,Pay,Instruction,From,Employee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-get-openapi.md
- name: Pay Run.IO Sparse Update of a Pay Instruction
  x-api-slug: pay-run-io
  description: Patches the specified pay instruction with the supplied values
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/PayInstruction/{PayInstructionId}
  tags: Sparse,,Of,Pay,Instruction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-patch-openapi.md
- name: Pay Run.IO Update a Pay Instruction
  x-api-slug: pay-run-io
  description: Updates the existing specified pay instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/PayInstruction/{PayInstructionId}
  tags: Pay,Instruction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructionpayinstructionid-put-openapi.md
- name: Pay Run.IO Gets the pay instructions from the specified employee
  x-api-slug: pay-run-io
  description: Get links to all pay instructions for the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/PayInstructions
  tags: Pay,Instructions,From,Specified,Employee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructions-get-openapi.md
- name: Pay Run.IO Creates a new Pay Instruction
  x-api-slug: pay-run-io
  description: Creates a new pay instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/PayInstructions
  tags: Creates,New,Pay,Instruction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidpayinstructions-post-openapi.md
- name: Pay Run.IO Gets the specified pay line from the employee
  x-api-slug: pay-run-io
  description: Returns the specified pay line from employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/PayLine/{PayLineId}
  tags: Specified,Pay,Line,From,Employee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidpaylinepaylineid-get-openapi.md
- name: Pay Run.IO Gets the pay lines from the specified employee
  x-api-slug: pay-run-io
  description: Get links to all pay lines for the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/PayLines
  tags: Pay,Lines,From,Specified,Employee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidpaylines-get-openapi.md
- name: Pay Run.IO Gets the pay runs from the employee
  x-api-slug: pay-run-io
  description: Get links to all pay runs for the specified employee.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/PayRuns
  tags: Pay,Runs,From,Employee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidpayruns-get-openapi.md
- name: Pay Run.IO Delete employee tag
  x-api-slug: pay-run-io
  description: Deletes a tag from the employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/Tag/{TagId}
  tags: Employee,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidtagtagid-delete-openapi.md
- name: Pay Run.IO Get employee tag
  x-api-slug: pay-run-io
  description: Gets the tag from the employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/Tag/{TagId}
  tags: Employee,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidtagtagid-get-openapi.md
- name: Pay Run.IO Insert employee tag
  x-api-slug: pay-run-io
  description: Inserts a new tag on the employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/Tag/{TagId}
  tags: Insert,Employee,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidtagtagid-put-openapi.md
- name: Pay Run.IO Get employee revision tag
  x-api-slug: pay-run-io
  description: Gets the tag from the employee revision
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/Tag/{TagId}/{EffectiveDate}
  tags: Employee,Revision,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidtagtagideffectivedate-get-openapi.md
- name: Pay Run.IO Get all employee tags
  x-api-slug: pay-run-io
  description: Gets all the tags from the employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/Tags
  tags: Employee,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidtags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidtags-get-openapi.md
- name: Pay Run.IO Get all employee revision tags
  x-api-slug: pay-run-io
  description: Gets all the tags from the employee revision
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/Tags/{EffectiveDate}
  tags: Employee,Revision,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidtagseffectivedate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeidtagseffectivedate-get-openapi.md
- name: Pay Run.IO Delete an Employee revision matching the specified revision date.
  x-api-slug: pay-run-io
  description: Deletes the specified employee revision for the matching revision date
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/{EffectiveDate}
  tags: Employee,Revision,Matching,Specified,Revision,Date
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeideffectivedate-delete-openapi.md
- name: Pay Run.IO Get employee by effective date.
  x-api-slug: pay-run-io
  description: Returns the employee's state at the specified effective date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/{EffectiveDate}
  tags: Employee,By,Effective,Date
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeemployeeideffectivedate-get-openapi.md
- name: Pay Run.IO Get employees from employer.
  x-api-slug: pay-run-io
  description: Get links to all employees for the specified employer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employees
  tags: Employees,From,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployees-get-openapi.md
- name: Pay Run.IO Create a new Employee
  x-api-slug: pay-run-io
  description: Create a new employee object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employees
  tags: New,Employee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployees-post-openapi.md
- name: Pay Run.IO Get employees with tag
  x-api-slug: pay-run-io
  description: Gets the employees with the tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employees/Tag/{TagId}
  tags: Employees,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeestagtagid-get-openapi.md
- name: Pay Run.IO Get all employee tags
  x-api-slug: pay-run-io
  description: Gets all the employee tags
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employees/Tags
  tags: Employee,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeestags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeestags-get-openapi.md
- name: Pay Run.IO Get employees from employer at a given effective date.
  x-api-slug: pay-run-io
  description: Get links to all employees for the employer on specified effective
    date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employees/{EffectiveDate}
  tags: Employees,From,Employer,At,Given,Effective,Date
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridemployeeseffectivedate-get-openapi.md
- name: Pay Run.IO Deletes the nominal codes
  x-api-slug: pay-run-io
  description: Deletes the nominal code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/NominalCode/{NominalCodeId}
  tags: Nominal,Codes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridnominalcodenominalcodeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridnominalcodenominalcodeid-delete-openapi.md
- name: Pay Run.IO Gets the nominal code
  x-api-slug: pay-run-io
  description: Gets the nominal code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/NominalCode/{NominalCodeId}
  tags: Nominal,Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridnominalcodenominalcodeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridnominalcodenominalcodeid-get-openapi.md
- name: Pay Run.IO Insert nominal code
  x-api-slug: pay-run-io
  description: Inserts a new nominal code at the specified resource location
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/NominalCode/{NominalCodeId}
  tags: Insert,Nominal,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridnominalcodenominalcodeid-put-openapi.md
- name: Pay Run.IO Gets the nominal codes
  x-api-slug: pay-run-io
  description: Gets the nominal code links
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/NominalCodes
  tags: Nominal,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridnominalcodes-get-openapi.md
- name: Pay Run.IO Insert nominal code
  x-api-slug: pay-run-io
  description: Inserts a new nominal code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/NominalCodes
  tags: Insert,Nominal,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridnominalcodes-post-openapi.md
- name: Pay Run.IO Deletes a pay code
  x-api-slug: pay-run-io
  description: Delete the specified pay code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}
  tags: Pay,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodepaycodeid-delete-openapi.md
- name: Pay Run.IO Gets the specified pay code from the employer
  x-api-slug: pay-run-io
  description: Returns the specified pay code from the employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}
  tags: Specified,Pay,Code,From,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodepaycodeid-get-openapi.md
- name: Pay Run.IO Patches the pay code
  x-api-slug: pay-run-io
  description: Patches the specified pay code object with the supplied values
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}
  tags: Patches,Pay,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodepaycodeid-patch-openapi.md
- name: Pay Run.IO Updates a pay code
  x-api-slug: pay-run-io
  description: Updates the existing specified pay code object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}
  tags: Pay,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodepaycodeid-put-openapi.md
- name: Pay Run.IO Delete pay code tag
  x-api-slug: pay-run-io
  description: Deletes a tag from the pay code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}/Tag/{TagId}
  tags: Pay,Code,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodepaycodeidtagtagid-delete-openapi.md
- name: Pay Run.IO Get pay code tag
  x-api-slug: pay-run-io
  description: Gets the tag from the pay code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}/Tag/{TagId}
  tags: Pay,Code,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodepaycodeidtagtagid-get-openapi.md
- name: Pay Run.IO Insert pay code tag
  x-api-slug: pay-run-io
  description: Inserts a new tag on the pay code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}/Tag/{TagId}
  tags: Insert,Pay,Code,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodepaycodeidtagtagid-put-openapi.md
- name: Pay Run.IO Get all pay code tags
  x-api-slug: pay-run-io
  description: Gets all the tags from the pay code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}/Tags
  tags: Pay,Code,Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodepaycodeidtags-get-openapi.md
- name: Pay Run.IO Deletes a pay code revision
  x-api-slug: pay-run-io
  description: Delete the pay code revision for the specified date
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}/{EffectiveDate}
  tags: Pay,Code,Revision
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodepaycodeideffectivedate-delete-openapi.md
- name: Pay Run.IO Gets pay code for specified date
  x-api-slug: pay-run-io
  description: Gets the pay code revision for the specified effective date
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}/{EffectiveDate}
  tags: Pay,Codespecified,Date
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodepaycodeideffectivedate-get-openapi.md
- name: Pay Run.IO Gets the pay codes from the employer
  x-api-slug: pay-run-io
  description: Get links to all the pay codes for the specified employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCodes
  tags: Pay,Codes,From,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodes-get-openapi.md
- name: Pay Run.IO Create a new pay code
  x-api-slug: pay-run-io
  description: Create a new pay code object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCodes
  tags: New,Pay,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodes-post-openapi.md
- name: Pay Run.IO Get pay codes with tag
  x-api-slug: pay-run-io
  description: Gets the pay codes with the tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCodes/Tag/{TagId}
  tags: Pay,Codes,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodestagtagid-get-openapi.md
- name: Pay Run.IO Get all pay code tags
  x-api-slug: pay-run-io
  description: Gets all the pay code tags
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCodes/Tags
  tags: Pay,Code,Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodestags-get-openapi.md
- name: Pay Run.IO Gets all pay codes for specified date
  x-api-slug: pay-run-io
  description: Gets the effective pay code revision for the specified date
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCodes/{EffectiveDate}
  tags: ',Pay,Codesspecified,Date'
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpaycodeseffectivedate-get-openapi.md
- name: Pay Run.IO Deletes a pay schedule
  x-api-slug: pay-run-io
  description: Delete the specified pay schedule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}
  tags: Pay,Schedule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleid-delete-openapi.md
- name: Pay Run.IO Gets the specified pay schedule from the employer
  x-api-slug: pay-run-io
  description: Returns the specified pay schedule object from employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}
  tags: Specified,Pay,Schedule,From,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleid-get-openapi.md
- name: Pay Run.IO Updates a pay schedule
  x-api-slug: pay-run-io
  description: Updates the existing specified pay schedule object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}
  tags: Pay,Schedule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleid-put-openapi.md
- name: Pay Run.IO Get employees from a pay schedule.
  x-api-slug: pay-run-io
  description: Gets links to all employees included in the specified pay schedule.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/Employees
  tags: Employees,From,Pay,Schedule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidemployees-get-openapi.md
- name: Pay Run.IO Deletes a pay run
  x-api-slug: pay-run-io
  description: Delete the specified pay run
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRun/{PayRunId}
  tags: Pay,Run
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunpayrunid-delete-openapi.md
- name: Pay Run.IO Gets the pay run from the pay schedule
  x-api-slug: pay-run-io
  description: Returns the pay run from the pay schedule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRun/{PayRunId}
  tags: Pay,Run,From,Pay,Schedule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunpayrunid-get-openapi.md
- name: Pay Run.IO Get the auto enrolment assessments
  x-api-slug: pay-run-io
  description: Gets all auto enrolment assessments from the specified pay run
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRun/{PayRunId}/AEAssessments
  tags: Auto,Enrolment,Assessments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunpayrunidaeassessments-get-openapi.md
- name: Pay Run.IO Deletes a pay run employee
  x-api-slug: pay-run-io
  description: Delete pay run results for a single employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRun/{PayRunId}/Employee/{EmployeeId}
  tags: Pay,Run,Employee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunpayrunidemployeeemployeeid-delete-openapi.md
- name: Pay Run.IO Get employees from the pay run
  x-api-slug: pay-run-io
  description: Gets links to all employees included in the specified pay run.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRun/{PayRunId}/Employees
  tags: Employees,From,Pay,Run
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunpayrunidemployees-get-openapi.md
- name: Pay Run.IO Gets the report lines from the specified pay run
  x-api-slug: pay-run-io
  description: Returns all report lines associated with the specified pay run
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRun/{PayRunId}/ReportLines
  tags: Report,Lines,From,Specified,Pay,Run
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunpayrunidreportlines-get-openapi.md
- name: Pay Run.IO Delete pay run tag
  x-api-slug: pay-run-io
  description: Deletes a tag from the pay run
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRun/{PayRunId}/Tag/{TagId}
  tags: Pay,Run,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunpayrunidtagtagid-delete-openapi.md
- name: Pay Run.IO Get pay run tag
  x-api-slug: pay-run-io
  description: Gets the tag from the pay run
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRun/{PayRunId}/Tag/{TagId}
  tags: Pay,Run,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunpayrunidtagtagid-get-openapi.md
- name: Pay Run.IO Insert pay run tag
  x-api-slug: pay-run-io
  description: Inserts a new tag on the pay run
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRun/{PayRunId}/Tag/{TagId}
  tags: Insert,Pay,Run,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunpayrunidtagtagid-put-openapi.md
- name: Pay Run.IO Get all pay run tags
  x-api-slug: pay-run-io
  description: Gets all the tags from the pay run
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRun/{PayRunId}/Tags
  tags: Pay,Run,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunpayrunidtags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunpayrunidtags-get-openapi.md
- name: Pay Run.IO Gets the pay runs from the pay schedule
  x-api-slug: pay-run-io
  description: Get links to all pay runs for the specified pay schedule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRuns
  tags: Pay,Runs,From,Pay,Schedule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayruns-get-openapi.md
- name: Pay Run.IO Get pay runs with tag
  x-api-slug: pay-run-io
  description: Gets the pay runs with the tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRuns/Tag/{TagId}
  tags: Pay,Runs,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunstagtagid-get-openapi.md
- name: Pay Run.IO Get all pay run tags
  x-api-slug: pay-run-io
  description: Gets all the pay run tags
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRuns/Tags
  tags: Pay,Run,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunstags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidpayrunstags-get-openapi.md
- name: Pay Run.IO Delete pay schedule tag
  x-api-slug: pay-run-io
  description: Deletes a tag from the pay schedule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/Tag/{TagId}
  tags: Pay,Schedule,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidtagtagid-delete-openapi.md
- name: Pay Run.IO Get pay schedule tag
  x-api-slug: pay-run-io
  description: Gets the tag from the pay schedule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/Tag/{TagId}
  tags: Pay,Schedule,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidtagtagid-get-openapi.md
- name: Pay Run.IO Insert pay schedule tag
  x-api-slug: pay-run-io
  description: Inserts a new tag on the pay schedule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/Tag/{TagId}
  tags: Insert,Pay,Schedule,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidtagtagid-put-openapi.md
- name: Pay Run.IO Get all pay schedule tags
  x-api-slug: pay-run-io
  description: Gets all the tags from the pay schedule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/Tags
  tags: Pay,Schedule,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidtags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulepayscheduleidtags-get-openapi.md
- name: Pay Run.IO Gets the pay schedule from the specified employer
  x-api-slug: pay-run-io
  description: Get links to all pay schedules for the specified employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedules
  tags: Pay,Schedule,From,Specified,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedules-get-openapi.md
- name: Pay Run.IO Create a new pay schedule
  x-api-slug: pay-run-io
  description: Create a new pay schedule object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedules
  tags: New,Pay,Schedule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedules-post-openapi.md
- name: Pay Run.IO Get pay schedule with tag
  x-api-slug: pay-run-io
  description: Gets the pay schedules with the tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedules/Tag/{TagId}
  tags: Pay,Schedule,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulestagtagid-get-openapi.md
- name: Pay Run.IO Get all pay schedule tags
  x-api-slug: pay-run-io
  description: Gets all the pay schedule tags
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedules/Tags
  tags: Pay,Schedule,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulestags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpayschedulestags-get-openapi.md
- name: Pay Run.IO Delete a Pension
  x-api-slug: pay-run-io
  description: Delete the specified ppension
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Pension/{PensionId}
  tags: Pension
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpensionpensionid-delete-openapi.md
- name: Pay Run.IO Get pension from employer
  x-api-slug: pay-run-io
  description: Gets the specified pension from employer by pension code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Pension/{PensionId}
  tags: Pension,From,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpensionpensionid-get-openapi.md
- name: Pay Run.IO Patches the pension
  x-api-slug: pay-run-io
  description: Patches the specified pension with the supplied values
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Pension/{PensionId}
  tags: Patches,Pension
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpensionpensionid-patch-openapi.md
- name: Pay Run.IO Updates the Pension
  x-api-slug: pay-run-io
  description: Updates existing or inserts the specified pension object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Pension/{PensionId}
  tags: Pension
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpensionpensionid-put-openapi.md
- name: Pay Run.IO Delete an Pension revision matching the specified revision date.
  x-api-slug: pay-run-io
  description: Deletes the specified pension revision for the matching revision date
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Pension/{PensionId}/{EffectiveDate}
  tags: Pension,Revision,Matching,Specified,Revision,Date
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpensionpensionideffectivedate-delete-openapi.md
- name: Pay Run.IO Get pension by effective date.
  x-api-slug: pay-run-io
  description: Returns the penion's state at the specified effective date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Pension/{PensionId}/{EffectiveDate}
  tags: Pension,By,Effective,Date
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpensionpensionideffectivedate-get-openapi.md
- name: Pay Run.IO Get pensions from employer.
  x-api-slug: pay-run-io
  description: Get links to all pensions for the specified employer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Pensions
  tags: Pensions,From,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpensions-get-openapi.md
- name: Pay Run.IO Create a new Pension
  x-api-slug: pay-run-io
  description: Create a new pension object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Pensions
  tags: New,Pension
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpensions-post-openapi.md
- name: Pay Run.IO Get pensions from employer at a given effective date.
  x-api-slug: pay-run-io
  description: Get links to all pensions for the employer on specified effective date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Pensions/{EffectiveDate}
  tags: Pensions,From,Employer,At,Given,Effective,Date
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridpensionseffectivedate-get-openapi.md
- name: Pay Run.IO Gets the specified report line from the employer
  x-api-slug: pay-run-io
  description: Returns the specified pay line from employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/ReportLine/{ReportLineId}
  tags: Specified,Report,Line,From,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridreportlinereportlineid-get-openapi.md
- name: Pay Run.IO Gets the report lines from the specified employer
  x-api-slug: pay-run-io
  description: Get links to all report lines for the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/ReportLines
  tags: Report,Lines,From,Specified,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridreportlines-get-openapi.md
- name: Pay Run.IO Deletes a reporting instruction
  x-api-slug: pay-run-io
  description: Delete the specified reporting instruction
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/ReportingInstruction/{ReportingInstructionId}
  tags: Reporting,Instruction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-delete-openapi.md
- name: Pay Run.IO Gets the specified reporting instruction from the employer
  x-api-slug: pay-run-io
  description: Returns the specified pay instruction from employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/ReportingInstruction/{ReportingInstructionId}
  tags: Specified,Reporting,Instruction,From,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-get-openapi.md
- name: Pay Run.IO Update a reporting Instruction
  x-api-slug: pay-run-io
  description: Updates the existing specified reporting instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/ReportingInstruction/{ReportingInstructionId}
  tags: Reporting,Instruction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridreportinginstructionreportinginstructionid-put-openapi.md
- name: Pay Run.IO Gets the reporting instructions from the specified employer
  x-api-slug: pay-run-io
  description: Get links to all pay instructions for the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/ReportingInstructions
  tags: Reporting,Instructions,From,Specified,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridreportinginstructions-get-openapi.md
- name: Pay Run.IO Creates a new Reporting Instruction
  x-api-slug: pay-run-io
  description: Creates a new reporting instruction object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/ReportingInstructions
  tags: Creates,New,Reporting,Instruction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridreportinginstructions-post-openapi.md
- name: Pay Run.IO Get the RTI transaction
  x-api-slug: pay-run-io
  description: Returns the specified RTI transaction
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/RtiTransaction/{RtiTransactionId}
  tags: RTI,Transaction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridrtitransactionrtitransactionid-get-openapi.md
- name: Pay Run.IO Get all RTI transactions for the employer
  x-api-slug: pay-run-io
  description: Get links for all RTI transactions for the specified employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/RtiTransactions
  tags: RTI,Transactionsthe,Employer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridrtitransactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridrtitransactions-get-openapi.md
- name: Pay Run.IO Delete employer tag
  x-api-slug: pay-run-io
  description: Deletes a tag from the employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Tag/{TagId}
  tags: Employer,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridtagtagid-delete-openapi.md
- name: Pay Run.IO Get employer tag
  x-api-slug: pay-run-io
  description: Gets the tag from the employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Tag/{TagId}
  tags: Employer,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridtagtagid-get-openapi.md
- name: Pay Run.IO Insert employer tag
  x-api-slug: pay-run-io
  description: Inserts a new tag on the employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Tag/{TagId}
  tags: Insert,Employer,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridtagtagid-put-openapi.md
- name: Pay Run.IO Get employer revision tag
  x-api-slug: pay-run-io
  description: Gets the tag from the employer revision
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Tag/{TagId}/{EffectiveDate}
  tags: Employer,Revision,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridtagtagideffectivedate-get-openapi.md
- name: Pay Run.IO Get all employer tags
  x-api-slug: pay-run-io
  description: Gets all the tags from the employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Tags
  tags: Employer,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridtags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridtags-get-openapi.md
- name: Pay Run.IO Get all employer revision tags
  x-api-slug: pay-run-io
  description: Gets all the tags from the employer revision
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Tags/{EffectiveDate}
  tags: Employer,Revision,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridtagseffectivedate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployeridtagseffectivedate-get-openapi.md
- name: Pay Run.IO Delete an Employer revision matching the specified revision date.
  x-api-slug: pay-run-io
  description: Deletes the specified employer revision for the matching revision date
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/{EffectiveDate}
  tags: Employer,Revision,Matching,Specified,Revision,Date
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployerideffectivedate-delete-openapi.md
- name: Pay Run.IO Gets the employer at the specified effective
  x-api-slug: pay-run-io
  description: Returns the employer's state at the specified effective date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/{EffectiveDate}
  tags: Employer,At,Specified,Effective
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employeremployerideffectivedate-get-openapi.md
- name: Pay Run.IO Gets all employers
  x-api-slug: pay-run-io
  description: Gets links to all employers contained under the authorised application
    scope
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employers
  tags: ',Employers'
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employers-get-openapi.md
- name: Pay Run.IO Create a new Employer
  x-api-slug: pay-run-io
  description: Create a new employer object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employers
  tags: New,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employers-post-openapi.md
- name: Pay Run.IO Get employers with tag
  x-api-slug: pay-run-io
  description: Gets the employers with the tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employers/Tag/{TagId}
  tags: Employers,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employerstagtagid-get-openapi.md
- name: Pay Run.IO Get all employer tags
  x-api-slug: pay-run-io
  description: Gets all the employer tags
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employers/Tags
  tags: Employer,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employerstags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employerstags-get-openapi.md
- name: Pay Run.IO Gets all employers at the specified effective date
  x-api-slug: pay-run-io
  description: Gets links to all employers contained under the authorised application
    scope for the specified effective date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employers/{EffectiveDate}
  tags: ',Employers,At,Specified,Effective,Date'
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/employerseffectivedate-get-openapi.md
- name: Pay Run.IO Get health check status
  x-api-slug: pay-run-io
  description: Returns the health status of the application
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Healthcheck
  tags: Health,Check,Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/healthcheck-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/healthcheck-get-openapi.md
- name: Pay Run.IO Get all DPS jobs
  x-api-slug: pay-run-io
  description: Gets all the DPS jobs
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/Dps
  tags: DPJobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsdps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsdps-get-openapi.md
- name: Pay Run.IO Create new DPS job
  x-api-slug: pay-run-io
  description: Creates the new DPS job to the queue and returns the job info
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/Dps
  tags: New,DPJob
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsdps-post-openapi.md
- name: Pay Run.IO Delete the DPS job
  x-api-slug: pay-run-io
  description: Deletes the the DPS job
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/Dps/{JobId}
  tags: DPJob
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsdpsjobid-delete-openapi.md
- name: Pay Run.IO Get the DPS job information
  x-api-slug: pay-run-io
  description: Return the the DPS job information
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/Dps/{JobId}/Info
  tags: DPJob,Information
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsdpsjobidinfo-get-openapi.md
- name: Pay Run.IO Get the DPS job progress
  x-api-slug: pay-run-io
  description: Return the the DPS job progress
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/Dps/{JobId}/Progress
  tags: DPJob,Progress
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsdpsjobidprogress-get-openapi.md
- name: Pay Run.IO Get the DPS job status
  x-api-slug: pay-run-io
  description: Return the the DPS job status
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/Dps/{JobId}/Status
  tags: DPJob,Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsdpsjobidstatus-get-openapi.md
- name: Pay Run.IO Get all PayRun jobs
  x-api-slug: pay-run-io
  description: Gets all the pay run jobs
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/PayRuns
  tags: PayRun,Jobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobspayruns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobspayruns-get-openapi.md
- name: Pay Run.IO Create new PayRun job
  x-api-slug: pay-run-io
  description: Creates the new pay run job to the queue and returns the job info
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/PayRuns
  tags: New,PayRun,Job
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobspayruns-post-openapi.md
- name: Pay Run.IO Delete the pay run job
  x-api-slug: pay-run-io
  description: Deletes the the payrun job
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/PayRuns/{JobId}
  tags: Pay,Run,Job
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobspayrunsjobid-delete-openapi.md
- name: Pay Run.IO Get the pay run job information
  x-api-slug: pay-run-io
  description: Return the the payrun job information
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/PayRuns/{JobId}/Info
  tags: Pay,Run,Job,Information
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobspayrunsjobidinfo-get-openapi.md
- name: Pay Run.IO Get the pay run job progress
  x-api-slug: pay-run-io
  description: Return the the payrun job progress
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/PayRuns/{JobId}/Progress
  tags: Pay,Run,Job,Progress
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobspayrunsjobidprogress-get-openapi.md
- name: Pay Run.IO Get the pay run job status
  x-api-slug: pay-run-io
  description: Return the the payrun job status
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/PayRuns/{JobId}/Status
  tags: Pay,Run,Job,Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobspayrunsjobidstatus-get-openapi.md
- name: Pay Run.IO Get all RTI jobs
  x-api-slug: pay-run-io
  description: Gets all the RTI jobs
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/Rti
  tags: RTI,Jobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsrti-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsrti-get-openapi.md
- name: Pay Run.IO Create new RTI job
  x-api-slug: pay-run-io
  description: Creates the new RTI job to the queue and returns the job info
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/Rti
  tags: New,RTI,Job
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsrti-post-openapi.md
- name: Pay Run.IO Delete the RTI job
  x-api-slug: pay-run-io
  description: Deletes the the RTI job
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/Rti/{JobId}
  tags: RTI,Job
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsrtijobid-delete-openapi.md
- name: Pay Run.IO Get the RTI job information
  x-api-slug: pay-run-io
  description: Return the the RTI job information
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/Rti/{JobId}/Info
  tags: RTI,Job,Information
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsrtijobidinfo-get-openapi.md
- name: Pay Run.IO Get the RTI job progress
  x-api-slug: pay-run-io
  description: Return the the RTI job progress
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/Rti/{JobId}/Progress
  tags: RTI,Job,Progress
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsrtijobidprogress-get-openapi.md
- name: Pay Run.IO Get the RTI job status
  x-api-slug: pay-run-io
  description: Return the the RTI job status
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Jobs/Rti/{JobId}/Status
  tags: RTI,Job,Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/jobsrtijobidstatus-get-openapi.md
- name: Pay Run.IO Get the query result
  x-api-slug: pay-run-io
  description: Get the results for the specified query
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Query
  tags: Query,Result
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/query-post-openapi.md
- name: Pay Run.IO Runs the active pay instructions report
  x-api-slug: pay-run-io
  description: Returns the result of the executed active pay instructions report for
    the given query parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/ACTPAYINS/run
  tags: Runs,Active,Pay,Instructions,Report
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportactpayinsrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportactpayinsrun-get-openapi.md
- name: Pay Run.IO Runs the DPS message report
  x-api-slug: pay-run-io
  description: Returns the result of the executed DPS message report for the given
    query parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/DPSMSG/run
  tags: Runs,DPMessage,Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportdpsmsgrun-get-openapi.md
- name: Pay Run.IO Runs the gross to net report
  x-api-slug: pay-run-io
  description: Returns the result of the executed gross to net report for the given
    query parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/GRO2NET/run
  tags: Runs,Gross,To,Net,Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportgro2netrun-get-openapi.md
- name: Pay Run.IO Runs the net pay report
  x-api-slug: pay-run-io
  description: Returns the result of the executed net pay report for the given query
    parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/NETPAY/run
  tags: Runs,Net,Pay,Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportnetpayrun-get-openapi.md
- name: Pay Run.IO Runs the P11 summary report
  x-api-slug: pay-run-io
  description: Returns the result of the executed P11 summary report for the given
    query parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/P11SUM/run
  tags: Runs,P11,Summary,Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportp11sumrun-get-openapi.md
- name: Pay Run.IO Runs the P32 report
  x-api-slug: pay-run-io
  description: Returns the result of the executed P32 report for the given query parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/P32/run
  tags: Runs,P32,Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportp32run-get-openapi.md
- name: Pay Run.IO Runs the P32 summary report
  x-api-slug: pay-run-io
  description: Returns the result of the executed P32 summary report for the given
    query parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/P32SUM/run
  tags: Runs,P32,Summary,Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportp32sumrun-get-openapi.md
- name: Pay Run.IO Runs the P45 report
  x-api-slug: pay-run-io
  description: Returns the result of the executed P45 report for the given query parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/P45/run
  tags: Runs,P45,Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportp45run-get-openapi.md
- name: Pay Run.IO Runs the P60 report
  x-api-slug: pay-run-io
  description: Returns the result of the executed P60 report for the given query parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/P60/run
  tags: Runs,P60,Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportp60run-get-openapi.md
- name: Pay Run.IO Runs the payslip report
  x-api-slug: pay-run-io
  description: Returns the result of the executed payslip report for the given query
    parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/PAYSLIP/run
  tags: Runs,Payslip,Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportpaysliprun-get-openapi.md
- name: Pay Run.IO Runs the pension liability report
  x-api-slug: pay-run-io
  description: Returns the result of the executed pension liability report for the
    given query parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/PENLIABILITY/run
  tags: Runs,Pension,Liability,Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportpenliabilityrun-get-openapi.md
- name: Pay Run.IO Deletes a report definition
  x-api-slug: pay-run-io
  description: Delete the specified report definition
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/{ReportDefinitionId}
  tags: Report,Definition
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportreportdefinitionid-delete-openapi.md
- name: Pay Run.IO Get the report definition
  x-api-slug: pay-run-io
  description: Returns the specified report definition from the authroised application
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/{ReportDefinitionId}
  tags: Report,Definition
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportreportdefinitionid-get-openapi.md
- name: Pay Run.IO Updates a report definition
  x-api-slug: pay-run-io
  description: Updates the existing specified report definition object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/{ReportDefinitionId}
  tags: Report,Definition
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportreportdefinitionid-put-openapi.md
- name: Pay Run.IO Runs the specified report definition
  x-api-slug: pay-run-io
  description: Returns the result of the executed report definition
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/{ReportDefinitionId}/run
  tags: Runs,Specified,Report,Definition
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reportreportdefinitionidrun-get-openapi.md
- name: Pay Run.IO Gets all reports
  x-api-slug: pay-run-io
  description: Get links to all saved report definitions under authorised application
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Reports
  tags: ',Reports'
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reports-get-openapi.md
- name: Pay Run.IO Create a new report definition
  x-api-slug: pay-run-io
  description: Creates a new report defintion object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Reports
  tags: New,Report,Definition
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/reports-post-openapi.md
- name: Pay Run.IO Get a list of all available schemas
  x-api-slug: pay-run-io
  description: Returns a collection of links to all the available data object schemas
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas
  tags: List,Of,,Available,Schemas
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemas-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemas-get-openapi.md
- name: Pay Run.IO Get the AbsencePayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the AbsencePayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/AbsencePayInstruction.xsd
  tags: AbsencePayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasabsencepayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the AbsenceYtdPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the AbsenceYtdPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/AbsenceYtdPayInstruction.xsd
  tags: AbsenceYtdPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasabsenceytdpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the Address schema
  x-api-slug: pay-run-io
  description: Returns the Address schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/Address.xsd
  tags: Ress,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasaddress-xsd-get-openapi.md
- name: Pay Run.IO Get the ArrayOfEmployee schema
  x-api-slug: pay-run-io
  description: Returns the ArrayOfEmployee schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/ArrayOfEmployee.xsd
  tags: ArrayOfEmployee,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasarrayofemployee-xsd-get-openapi.md
- name: Pay Run.IO Get the BankAccount schema
  x-api-slug: pay-run-io
  description: Returns the BankAccount schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/BankAccount.xsd
  tags: BankAccount,Schema
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasbankaccount-xsd-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasbankaccount-xsd-get-openapi.md
- name: Pay Run.IO Get the BenefitPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the BenefitPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/BenefitPayInstruction.xsd
  tags: BenefitPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasbenefitpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the BenefitYtdPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the BenefitYtdPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/BenefitYtdPayInstruction.xsd
  tags: BenefitYtdPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasbenefitytdpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the Common schema
  x-api-slug: pay-run-io
  description: Returns the Common schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/Common.xsd
  tags: Common,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemascommon-xsd-get-openapi.md
- name: Pay Run.IO Get the Employee schema
  x-api-slug: pay-run-io
  description: Returns the Employee schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/Employee.xsd
  tags: Employee,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasemployee-xsd-get-openapi.md
- name: Pay Run.IO Get the EmployeePartner schema
  x-api-slug: pay-run-io
  description: Returns the EmployeePartner schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/EmployeePartner.xsd
  tags: EmployeePartner,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasemployeepartner-xsd-get-openapi.md
- name: Pay Run.IO Get the Employer schema
  x-api-slug: pay-run-io
  description: Returns the Employer schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/Employer.xsd
  tags: Employer,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasemployer-xsd-get-openapi.md
- name: Pay Run.IO Get the HmrcSettings schema
  x-api-slug: pay-run-io
  description: Returns the HmrcSettings schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/HmrcSettings.xsd
  tags: HmrcSettings,Schema
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemashmrcsettings-xsd-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemashmrcsettings-xsd-get-openapi.md
- name: Pay Run.IO Get the Link schema
  x-api-slug: pay-run-io
  description: Returns the Link schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/Link.xsd
  tags: Link,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemaslink-xsd-get-openapi.md
- name: Pay Run.IO Get the NiAdjustmentPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the NiAdjustmentPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/NiAdjustmentPayInstruction.xsd
  tags: NiAdjustmentPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasniadjustmentpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the NiPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the NiPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/NiPayInstruction.xsd
  tags: NiPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasnipayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the NiYtdPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the NiYtdPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/NiYtdPayInstruction.xsd
  tags: NiYtdPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasniytdpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the P45PayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the P45PayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/P45PayInstruction.xsd
  tags: P45PayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasp45payinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the PayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the PayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/PayInstruction.xsd
  tags: PayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemaspayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the PayRunJobInstruction schema
  x-api-slug: pay-run-io
  description: Returns the PayRunJobInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/PayRunJobInstruction.xsd
  tags: PayRunJobInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemaspayrunjobinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the PaySchedule schema
  x-api-slug: pay-run-io
  description: Returns the PaySchedule schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/PaySchedule.xsd
  tags: PaySchedule,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemaspayschedule-xsd-get-openapi.md
- name: Pay Run.IO Get the PensionPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the PensionPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/PensionPayInstruction.xsd
  tags: PensionPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemaspensionpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the PensionYtdPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the PensionYtdPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/PensionYtdPayInstruction.xsd
  tags: PensionYtdPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemaspensionytdpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the PrimitivePayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the PrimitivePayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/PrimitivePayInstruction.xsd
  tags: PrimitivePayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasprimitivepayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the RtiJobInstruction schema
  x-api-slug: pay-run-io
  description: Returns the RtiJobInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/RtiJobInstruction.xsd
  tags: RtiJobInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasrtijobinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the SalaryPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the SalaryPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/SalaryPayInstruction.xsd
  tags: SalaryPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemassalarypayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the SapPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the SapPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/SapPayInstruction.xsd
  tags: SapPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemassappayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the SapYtdPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the SapYtdPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/SapYtdPayInstruction.xsd
  tags: SapYtdPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemassapytdpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the ShppPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the ShppPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/ShppPayInstruction.xsd
  tags: ShppPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasshpppayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the ShppYtdPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the ShppYtdPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/ShppYtdPayInstruction.xsd
  tags: ShppYtdPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasshppytdpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the SmpPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the SmpPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/SmpPayInstruction.xsd
  tags: SmpPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemassmppayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the SmpYtdPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the SmpYtdPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/SmpYtdPayInstruction.xsd
  tags: SmpYtdPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemassmpytdpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the SppPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the SppPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/SppPayInstruction.xsd
  tags: SppPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasspppayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the SppYtdPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the SppYtdPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/SppYtdPayInstruction.xsd
  tags: SppYtdPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemassppytdpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the SspPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the SspPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/SspPayInstruction.xsd
  tags: SspPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasssppayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the SspYtdPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the SspYtdPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/SspYtdPayInstruction.xsd
  tags: SspYtdPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemassspytdpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the StudentLoanPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the StudentLoanPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/StudentLoanPayInstruction.xsd
  tags: StudentLoanPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasstudentloanpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the StudentLoanYtdPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the StudentLoanYtdPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/StudentLoanYtdPayInstruction.xsd
  tags: StudentLoanYtdPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemasstudentloanytdpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the TaxPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the TaxPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/TaxPayInstruction.xsd
  tags: TaxPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemastaxpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get the TaxYtdPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the TaxYtdPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/TaxYtdPayInstruction.xsd
  tags: TaxYtdPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/schemastaxytdpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Get a list of all available data object tempaltes
  x-api-slug: pay-run-io
  description: Returns a collection of links to all the available data object templates
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates
  tags: List,Of,,Available,Data,Object,Tempaltes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templates-get-openapi.md
- name: Pay Run.IO Gets the address template
  x-api-slug: pay-run-io
  description: Return the address data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/address
  tags: Address,Template
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesaddress-get-openapi.md
- name: Pay Run.IO Gets the application info template
  x-api-slug: pay-run-io
  description: Return the application info data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/applicationinfo
  tags: Application,Info,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesapplicationinfo-get-openapi.md
- name: Pay Run.IO Gets the bank account template
  x-api-slug: pay-run-io
  description: Return the bank account data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/bankaccount
  tags: Bank,Account,Template
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesbankaccount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesbankaccount-get-openapi.md
- name: Pay Run.IO Gets the benefit pay instruction template
  x-api-slug: pay-run-io
  description: Return the benefit pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/benefitpayinstruction
  tags: Benefit,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesbenefitpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the benefit YTD pay instruction template
  x-api-slug: pay-run-io
  description: Return the benefit YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/benefitytdpayinstruction
  tags: Benefit,YTD,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesbenefitytdpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the commentary template
  x-api-slug: pay-run-io
  description: Return the commentary data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/commentary
  tags: Commentary,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatescommentary-get-openapi.md
- name: Pay Run.IO Gets the employee template
  x-api-slug: pay-run-io
  description: Return the employee data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/employee
  tags: Employee,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesemployee-get-openapi.md
- name: Pay Run.IO Gets the employee partner template
  x-api-slug: pay-run-io
  description: Return the employee partner data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/employeepartner
  tags: Employee,Partner,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesemployeepartner-get-openapi.md
- name: Pay Run.IO Gets the employer template
  x-api-slug: pay-run-io
  description: Return the employer data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/employer
  tags: Employer,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesemployer-get-openapi.md
- name: Pay Run.IO Gets the error model template
  x-api-slug: pay-run-io
  description: Return the error model data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/errormodel
  tags: Error,Model,Template
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templateserrormodel-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templateserrormodel-get-openapi.md
- name: Pay Run.IO Gets the hmrc settings template
  x-api-slug: pay-run-io
  description: Return the hmrc settings data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/hmrcsettings
  tags: Hmrc,Settings,Template
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templateshmrcsettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templateshmrcsettings-get-openapi.md
- name: Pay Run.IO Gets the job info template
  x-api-slug: pay-run-io
  description: Return the job info data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/jobinfo
  tags: Job,Info,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesjobinfo-get-openapi.md
- name: Pay Run.IO Gets the link template
  x-api-slug: pay-run-io
  description: Return the link data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/link
  tags: Link,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templateslink-get-openapi.md
- name: Pay Run.IO Gets the link collection template
  x-api-slug: pay-run-io
  description: Return the link collection data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/linkcollection
  tags: Link,Collection,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templateslinkcollection-get-openapi.md
- name: Pay Run.IO Gets the NI adjustment pay instruction template
  x-api-slug: pay-run-io
  description: Return the NI adjustment pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/niadjustmentpayinstruction
  tags: NI,Adjustment,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesniadjustmentpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the NI pay instruction template
  x-api-slug: pay-run-io
  description: Return the NI pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/nipayinstruction
  tags: NI,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesnipayinstruction-get-openapi.md
- name: Pay Run.IO Gets the NI YTD pay instruction template
  x-api-slug: pay-run-io
  description: Return the NI YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/niytdpayinstruction
  tags: NI,YTD,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesniytdpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the P45 pay instruction template
  x-api-slug: pay-run-io
  description: Return the P45 pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/p45payinstruction
  tags: P45,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesp45payinstruction-get-openapi.md
- name: Pay Run.IO Gets the pay code template
  x-api-slug: pay-run-io
  description: Return the pay code data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/paycode
  tags: Pay,Code,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespaycode-get-openapi.md
- name: Pay Run.IO Gets the pay instruction template
  x-api-slug: pay-run-io
  description: Return the pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/payinstruction
  tags: Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespayinstruction-get-openapi.md
- name: Pay Run.IO Gets the pay line template
  x-api-slug: pay-run-io
  description: Return the pay line data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/payline
  tags: Pay,Line,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespayline-get-openapi.md
- name: Pay Run.IO Gets the pay line benefit template
  x-api-slug: pay-run-io
  description: Return the pay line benefit data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/paylinebenefit
  tags: Pay,Line,Benefit,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespaylinebenefit-get-openapi.md
- name: Pay Run.IO Gets the pay line NI template
  x-api-slug: pay-run-io
  description: Return the pay line NI data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/paylineni
  tags: Pay,Line,NI,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespaylineni-get-openapi.md
- name: Pay Run.IO Gets the pay line pension template
  x-api-slug: pay-run-io
  description: Return the pay line pension data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/paylinepension
  tags: Pay,Line,Pension,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespaylinepension-get-openapi.md
- name: Pay Run.IO Gets the pay line sap template
  x-api-slug: pay-run-io
  description: Return the pay line sap data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/paylinesap
  tags: Pay,Line,Sap,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespaylinesap-get-openapi.md
- name: Pay Run.IO Gets the pay line shpp template
  x-api-slug: pay-run-io
  description: Return the pay line shpp data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/paylineshpp
  tags: Pay,Line,Shpp,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespaylineshpp-get-openapi.md
- name: Pay Run.IO Gets the pay line smp template
  x-api-slug: pay-run-io
  description: Return the pay line smp data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/paylinesmp
  tags: Pay,Line,Smp,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespaylinesmp-get-openapi.md
- name: Pay Run.IO Gets the pay line spp template
  x-api-slug: pay-run-io
  description: Return the pay line spp data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/paylinespp
  tags: Pay,Line,Spp,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespaylinespp-get-openapi.md
- name: Pay Run.IO Gets the pay line ssp template
  x-api-slug: pay-run-io
  description: Return the pay line ssp data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/paylinessp
  tags: Pay,Line,Ssp,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespaylinessp-get-openapi.md
- name: Pay Run.IO Gets the pay line student loan template
  x-api-slug: pay-run-io
  description: Return the pay line student loan data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/paylinestudentloan
  tags: Pay,Line,Student,Loan,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespaylinestudentloan-get-openapi.md
- name: Pay Run.IO Gets the pay line tax template
  x-api-slug: pay-run-io
  description: Return the pay line tax data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/paylinetax
  tags: Pay,Line,Tax,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespaylinetax-get-openapi.md
- name: Pay Run.IO Gets the pay run template
  x-api-slug: pay-run-io
  description: Return the pay run data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/payrun
  tags: Pay,Run,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespayrun-get-openapi.md
- name: Pay Run.IO Gets the pay run job template
  x-api-slug: pay-run-io
  description: Return the pay run job data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/payrunjob
  tags: Pay,Run,Job,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespayrunjob-get-openapi.md
- name: Pay Run.IO Gets the pay run job instruction template
  x-api-slug: pay-run-io
  description: Return the pay run job instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/payrunjobinstruction
  tags: Pay,Run,Job,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespayrunjobinstruction-get-openapi.md
- name: Pay Run.IO Gets the pay schedule template
  x-api-slug: pay-run-io
  description: Return the pay schedule data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/payschedule
  tags: Pay,Schedule,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespayschedule-get-openapi.md
- name: Pay Run.IO Gets the pension pay instruction template
  x-api-slug: pay-run-io
  description: Return the pension pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/pensionpayinstruction
  tags: Pension,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespensionpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the pension YTD pay instruction template
  x-api-slug: pay-run-io
  description: Return the pension YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/pensionytdpayinstruction
  tags: Pension,YTD,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatespensionytdpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the primitive pay instruction template
  x-api-slug: pay-run-io
  description: Return the primitive pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/primitivepayinstruction
  tags: Primitive,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesprimitivepayinstruction-get-openapi.md
- name: Pay Run.IO Gets the report definition template
  x-api-slug: pay-run-io
  description: Return the report definition data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/reportdefinition
  tags: Report,Definition,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesreportdefinition-get-openapi.md
- name: Pay Run.IO Gets the rti eas transaction template
  x-api-slug: pay-run-io
  description: Return the rti eas transaction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/rtieastransaction
  tags: Rti,Eas,Transaction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesrtieastransaction-get-openapi.md
- name: Pay Run.IO Gets the rti eps transaction template
  x-api-slug: pay-run-io
  description: Return the rti eps transaction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/rtiepstransaction
  tags: Rti,Eps,Transaction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesrtiepstransaction-get-openapi.md
- name: Pay Run.IO Gets the rti eyu transaction template
  x-api-slug: pay-run-io
  description: Return the rti eyu transaction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/rtieyutransaction
  tags: Rti,Eyu,Transaction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesrtieyutransaction-get-openapi.md
- name: Pay Run.IO Gets the rti fps transaction template
  x-api-slug: pay-run-io
  description: Return the rti fps transaction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/rtifpstransaction
  tags: Rti,Fps,Transaction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesrtifpstransaction-get-openapi.md
- name: Pay Run.IO Gets the rti job template
  x-api-slug: pay-run-io
  description: Return the rti job data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/rtijob
  tags: Rti,Job,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesrtijob-get-openapi.md
- name: Pay Run.IO Gets the rti job instruction template
  x-api-slug: pay-run-io
  description: Return the rti job instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/rtijobinstruction
  tags: Rti,Job,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesrtijobinstruction-get-openapi.md
- name: Pay Run.IO Gets the rti nvr transaction template
  x-api-slug: pay-run-io
  description: Return the rti nvr transaction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/rtinvrtransaction
  tags: Rti,Nvr,Transaction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesrtinvrtransaction-get-openapi.md
- name: Pay Run.IO Gets the rti transaction base template
  x-api-slug: pay-run-io
  description: Return the rti transaction base data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/rtitransactionbase
  tags: Rti,Transaction,Base,Template
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesrtitransactionbase-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesrtitransactionbase-get-openapi.md
- name: Pay Run.IO Gets the salary pay instruction template
  x-api-slug: pay-run-io
  description: Return the salary pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/salarypayinstruction
  tags: Salary,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatessalarypayinstruction-get-openapi.md
- name: Pay Run.IO Gets the sap pay instruction template
  x-api-slug: pay-run-io
  description: Return the sap pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/sappayinstruction
  tags: Sap,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatessappayinstruction-get-openapi.md
- name: Pay Run.IO Gets the sap YTD pay instruction template
  x-api-slug: pay-run-io
  description: Return the sap YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/sapytdpayinstruction
  tags: Sap,YTD,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatessapytdpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the shpp pay instruction template
  x-api-slug: pay-run-io
  description: Return the shpp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/shpppayinstruction
  tags: Shpp,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesshpppayinstruction-get-openapi.md
- name: Pay Run.IO Gets the shpp YTD pay instruction template
  x-api-slug: pay-run-io
  description: Return the shpp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/shppytdpayinstruction
  tags: Shpp,YTD,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesshppytdpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the smp pay instruction template
  x-api-slug: pay-run-io
  description: Return the smp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/smppayinstruction
  tags: Smp,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatessmppayinstruction-get-openapi.md
- name: Pay Run.IO Gets the smp YTD pay instruction template
  x-api-slug: pay-run-io
  description: Return the smp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/smpytdpayinstruction
  tags: Smp,YTD,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatessmpytdpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the spp pay instruction template
  x-api-slug: pay-run-io
  description: Return the spp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/spppayinstruction
  tags: Spp,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesspppayinstruction-get-openapi.md
- name: Pay Run.IO Gets the spp YTD pay instruction template
  x-api-slug: pay-run-io
  description: Return the spp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/sppytdpayinstruction
  tags: Spp,YTD,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatessppytdpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the ssp pay instruction template
  x-api-slug: pay-run-io
  description: Return the ssp pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/ssppayinstruction
  tags: Ssp,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesssppayinstruction-get-openapi.md
- name: Pay Run.IO Gets the ssp YTD pay instruction template
  x-api-slug: pay-run-io
  description: Return the ssp YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/sspytdpayinstruction
  tags: Ssp,YTD,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatessspytdpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the student loan pay instruction template
  x-api-slug: pay-run-io
  description: Return the student loan pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/studentloanpayinstruction
  tags: Student,Loan,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesstudentloanpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the student loan YTD pay instruction template
  x-api-slug: pay-run-io
  description: Return the student loan YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/studentloanytdpayinstruction
  tags: Student,Loan,YTD,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatesstudentloanytdpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the tax pay instruction template
  x-api-slug: pay-run-io
  description: Return the tax pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/taxpayinstruction
  tags: Tax,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatestaxpayinstruction-get-openapi.md
- name: Pay Run.IO Gets the tax YTD pay instruction template
  x-api-slug: pay-run-io
  description: Return the tax YTD pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/taxytdpayinstruction
  tags: Tax,YTD,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/templatestaxytdpayinstruction-get-openapi.md
- name: Pay Run.IO Deletes a transform definition
  x-api-slug: pay-run-io
  description: Delete the specified transform definition
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Transform/{TransformDefinitionId}
  tags: Transform,Definition
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/transformtransformdefinitionid-delete-openapi.md
- name: Pay Run.IO Get the transform definition
  x-api-slug: pay-run-io
  description: Returns the specified transform definition from the authroised application
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Transform/{TransformDefinitionId}
  tags: Transform,Definition
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/transformtransformdefinitionid-get-openapi.md
- name: Pay Run.IO Updates a transform definition
  x-api-slug: pay-run-io
  description: Updates the existing specified transform definition object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Transform/{TransformDefinitionId}
  tags: Transform,Definition
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/transformtransformdefinitionid-put-openapi.md
- name: Pay Run.IO Gets all transform definitions
  x-api-slug: pay-run-io
  description: Get links to all saved transform definitions under authorised application
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Transforms
  tags: ',Transform,Definitions'
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/transforms-get-openapi.md
- name: Pay Run.IO Create a new transform definition
  x-api-slug: pay-run-io
  description: Creates a new transform defintion object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Transforms
  tags: New,Transform,Definition
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/transforms-post-openapi.md
- name: Pay Run.IO
  x-api-slug: pay-run-io
  description: An open, scalable, transparent and HMRC accredited payroll API. Put
    the power of payroll into your application today.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: PayRun
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/payrun/master/_listings/payrun/openapi.md
x-common:
- type: x-website
  url: http://www.payrun.io
- type: x-documentation
  url: https://developer.payrun.io/docs/home/index.html
- type: x-email
  url: support@payrun.io
- type: x-email
  url: info@payrun.io
- type: x-twitter
  url: https://twitter.com/PayRun_io
- type: x-website
  url: http://api.test.payrun.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---