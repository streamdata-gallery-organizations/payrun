---
swagger: "2.0"
x-collection-name: PayRun
x-complete: 0
info:
  title: Pay Run.IO Deletes a pay code revision
  description: Delete the pay code revision for the specified date
  version: 17.18.6.206
host: api.test.payrun.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Employer/{EmployerId}:
    delete:
      summary: Delete an Employer
      description: Delete the specified employer
      operationId: DeleteEmployer
      x-api-path-slug: employeremployerid-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employer
    get:
      summary: Gets the employer
      description: Get the specified employer object
      operationId: GetEmployer
      x-api-path-slug: employeremployerid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employer
    patch:
      summary: Patches the employer
      description: Patches the specified employer with the supplied values
      operationId: PatchEmployer
      x-api-path-slug: employeremployerid-patch
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: body
        name: Employer
        description: The employer object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Patches
      - Employer
    put:
      summary: Updates the Employer
      description: Updates the existing specified employer object
      operationId: PutEmployer
      x-api-path-slug: employeremployerid-put
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: body
        name: Employer
        description: The employer object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employer
  /Employer/{EmployerId}/DpsMessage/{DpsMessageId}:
    delete:
      summary: Deletes the DPS message
      description: Deletes the DPS message
      operationId: DeleteDpsMessage
      x-api-path-slug: employeremployeriddpsmessagedpsmessageid-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: DpsMessageId
        description: The DPS message unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - DPMessage
    get:
      summary: Gets the DPS message
      description: Gets the DPS message
      operationId: GetDpsMessageFromEmployer
      x-api-path-slug: employeremployeriddpsmessagedpsmessageid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: DpsMessageId
        description: The DPS message unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - DPMessage
    patch:
      summary: Patches the DPS message
      description: Patches the specified DPS message with the supplied values
      operationId: PatchDpsMessage
      x-api-path-slug: employeremployeriddpsmessagedpsmessageid-patch
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: DpsMessageId
        description: The DPS message unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Patches
      - DPMessage
  /Employer/{EmployerId}/DpsMessages:
    get:
      summary: Gets the DPS messages
      description: Gets the DPS message links
      operationId: GetDpsMessagesFromEmployer
      x-api-path-slug: employeremployeriddpsmessages-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - DPMessages
  /Employer/{EmployerId}/Employee/{EmployeeId}:
    delete:
      summary: Delete an Employee
      description: Delete the specified employee
      operationId: DeleteEmployee
      x-api-path-slug: employeremployeridemployeeemployeeid-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employee
    get:
      summary: Get employee from employer
      description: Gets the specified employee from employer by employee code.
      operationId: GetEmployeeFromEmployer
      x-api-path-slug: employeremployeridemployeeemployeeid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employee
      - From
      - Employer
    patch:
      summary: Patches the employee
      description: Patches the specified employee with the supplied values
      operationId: PatchEmployee
      x-api-path-slug: employeremployeridemployeeemployeeid-patch
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: body
        name: Employee
        description: The employee object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Patches
      - Employee
    put:
      summary: Updates the Employee
      description: Updates the existing specified employee object
      operationId: PutEmployeeIntoEmployer
      x-api-path-slug: employeremployeridemployeeemployeeid-put
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: body
        name: Employee
        description: The employee object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employee
  /Employer/{EmployerId}/Employee/{EmployeeId}/AEAssessment/{AEAssessmentId}:
    delete:
      summary: Delete auto enrolment assessment
      description: Deletes an existing auto enrolment assessment for the employee.
        Used to remove historical assessments
      operationId: DeleteAEAssessment
      x-api-path-slug: employeremployeridemployeeemployeeidaeassessmentaeassessmentid-delete
      parameters:
      - in: path
        name: AEAssessmentId
        description: The auto enrolment assessment unique identifier
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Auto
      - Enrolment
      - Assessment
    get:
      summary: Get the auto enrolment assessment
      description: Gets the auto enrolment assessment from the specified employee
      operationId: GetAEAssessmentFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidaeassessmentaeassessmentid-get
      parameters:
      - in: path
        name: AEAssessmentId
        description: The auto enrolment assessment unique identifier
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Auto
      - Enrolment
      - Assessment
    put:
      summary: Insert new auto enrolment assessment
      description: Creates a new auto enrolment assessment for the employee. Used
        to insert historical assessments
      operationId: PutNewAEAssessment
      x-api-path-slug: employeremployeridemployeeemployeeidaeassessmentaeassessmentid-put
      parameters:
      - in: body
        name: AEAssessment
        description: The auto enrolment assessment object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: AEAssessmentId
        description: The auto enrolment assessment unique identifier
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insert
      - New
      - Auto
      - Enrolment
      - Assessment
  /Employer/{EmployerId}/Employee/{EmployeeId}/AEAssessments:
    get:
      summary: Get the auto enrolment assessments
      description: Gets all auto enrolment assessments from the specified employee
      operationId: GetAEAssessmentsFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidaeassessments-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Auto
      - Enrolment
      - Assessments
    post:
      summary: Insert new auto enrolment assessment
      description: Creates a new auto enrolment assessment for the employee. Used
        to insert historical assessments
      operationId: PostNewAEAssessment
      x-api-path-slug: employeremployeridemployeeemployeeidaeassessments-post
      parameters:
      - in: body
        name: AEAssessment
        description: The auto enrolment assessment object
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insert
      - New
      - Auto
      - Enrolment
      - Assessment
  /Employer/{EmployerId}/Employee/{EmployeeId}/Commentaries:
    get:
      summary: Get links to all commentaries for the specified employee
      description: Get links to all commentaries for the specified employee.
      operationId: GetCommentariesFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidcommentaries-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Links
      - To
      - ""
      - Commentariesthe
      - Specified
      - Employee
  /Employer/{EmployerId}/Employee/{EmployeeId}/Commentary/{CommentaryId}:
    get:
      summary: Get commentary from employee
      description: Gets the specified commentary report from the employee
      operationId: GetCommentaryFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidcommentarycommentaryid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: CommentaryId
        description: The commentary unique identifier
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Commentary
      - From
      - Employee
  /Employer/{EmployerId}/Employee/{EmployeeId}/PayInstruction/{PayInstructionId}:
    delete:
      summary: Deletes a pay instruction
      description: Delete the specified pay instruction
      operationId: DeletePayInstruction
      x-api-path-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayInstructionId
        description: The pay instruction unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Instruction
    get:
      summary: Gets the specified pay instruction from the employee
      description: Returns the specified pay instruction from employee
      operationId: GetPayInstructionFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayInstructionId
        description: The pay instruction unique identifier
      responses:
        200:
          description: OK
      tags:
      - Specified
      - Pay
      - Instruction
      - From
      - Employee
    patch:
      summary: Sparse Update of a Pay Instruction
      description: Patches the specified pay instruction with the supplied values
      operationId: PatchPayInstruction
      x-api-path-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-patch
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: body
        name: PayInstruction
        description: The pay instruction object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: PayInstructionId
        description: The pay instruction unique identifier
      responses:
        200:
          description: OK
      tags:
      - Sparse
      - ""
      - Of
      - Pay
      - Instruction
    put:
      summary: Update a Pay Instruction
      description: Updates the existing specified pay instruction object
      operationId: PutPayInstruction
      x-api-path-slug: employeremployeridemployeeemployeeidpayinstructionpayinstructionid-put
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: body
        name: PayInstruction
        description: The pay instruction object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: PayInstructionId
        description: The pay instruction unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Instruction
  /Employer/{EmployerId}/Employee/{EmployeeId}/PayInstructions:
    get:
      summary: Gets the pay instructions from the specified employee
      description: Get links to all pay instructions for the specified employee
      operationId: GetPayInstructionsFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidpayinstructions-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Instructions
      - From
      - Specified
      - Employee
    post:
      summary: Creates a new Pay Instruction
      description: Creates a new pay instruction object
      operationId: PostPayInstruction
      x-api-path-slug: employeremployeridemployeeemployeeidpayinstructions-post
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: body
        name: PayInstruction
        description: The pay instruction object
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Pay
      - Instruction
  /Employer/{EmployerId}/Employee/{EmployeeId}/PayLine/{PayLineId}:
    get:
      summary: Gets the specified pay line from the employee
      description: Returns the specified pay line from employee
      operationId: GetPayLineFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidpaylinepaylineid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayLineId
        description: The pay line unique identifier
      responses:
        200:
          description: OK
      tags:
      - Specified
      - Pay
      - Line
      - From
      - Employee
  /Employer/{EmployerId}/Employee/{EmployeeId}/PayLines:
    get:
      summary: Gets the pay lines from the specified employee
      description: Get links to all pay lines for the specified employee
      operationId: GetPayLinesFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidpaylines-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Lines
      - From
      - Specified
      - Employee
  /Employer/{EmployerId}/Employee/{EmployeeId}/PayRuns:
    get:
      summary: Gets the pay runs from the employee
      description: Get links to all pay runs for the specified employee.
      operationId: GetPayRunsFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidpayruns-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Runs
      - From
      - Employee
  /Employer/{EmployerId}/Employee/{EmployeeId}/Tag/{TagId}:
    delete:
      summary: Delete employee tag
      description: Deletes a tag from the employee
      operationId: DeleteEmployeeTag
      x-api-path-slug: employeremployeridemployeeemployeeidtagtagid-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: TagId
        description: The tag unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employee
      - Tag
    get:
      summary: Get employee tag
      description: Gets the tag from the employee
      operationId: GetTagFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidtagtagid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: TagId
        description: The tag unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employee
      - Tag
    put:
      summary: Insert employee tag
      description: Inserts a new tag on the employee
      operationId: PutEmployeeTag
      x-api-path-slug: employeremployeridemployeeemployeeidtagtagid-put
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: TagId
        description: The tag unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Employee
      - Tag
  /Employer/{EmployerId}/Employee/{EmployeeId}/Tag/{TagId}/{EffectiveDate}:
    get:
      summary: Get employee revision tag
      description: Gets the tag from the employee revision
      operationId: GetTagFromEmployeeRevision
      x-api-path-slug: employeremployeridemployeeemployeeidtagtagideffectivedate-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EffectiveDate
        description: The effective date to be applied
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: TagId
        description: The tag unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employee
      - Revision
      - Tag
  /Employer/{EmployerId}/Employee/{EmployeeId}/Tags:
    get:
      summary: Get all employee tags
      description: Gets all the tags from the employee
      operationId: GetTagsFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidtags-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employee
      - Tags
  /Employer/{EmployerId}/Employee/{EmployeeId}/Tags/{EffectiveDate}:
    get:
      summary: Get all employee revision tags
      description: Gets all the tags from the employee revision
      operationId: GetTagsFromEmployeeRevision
      x-api-path-slug: employeremployeridemployeeemployeeidtagseffectivedate-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EffectiveDate
        description: The effective date to be applied
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employee
      - Revision
      - Tags
  /Employer/{EmployerId}/Employee/{EmployeeId}/{EffectiveDate}:
    delete:
      summary: Delete an Employee revision matching the specified revision date.
      description: Deletes the specified employee revision for the matching revision
        date
      operationId: DeleteEmployeeRevision
      x-api-path-slug: employeremployeridemployeeemployeeideffectivedate-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EffectiveDate
        description: The effective date to be applied
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employee
      - Revision
      - Matching
      - Specified
      - Revision
      - Date
    get:
      summary: Get employee by effective date.
      description: Returns the employee's state at the specified effective date.
      operationId: GetEmployeeByEffectiveDate
      x-api-path-slug: employeremployeridemployeeemployeeideffectivedate-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EffectiveDate
        description: The effective date to be applied
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employee
      - By
      - Effective
      - Date
  /Employer/{EmployerId}/Employees:
    get:
      summary: Get employees from employer.
      description: Get links to all employees for the specified employer.
      operationId: GetEmployeesFromEmployer
      x-api-path-slug: employeremployeridemployees-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employees
      - From
      - Employer
    post:
      summary: Create a new Employee
      description: Create a new employee object
      operationId: PostEmployeeIntoEmployer
      x-api-path-slug: employeremployeridemployees-post
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: body
        name: Employee
        description: The employee object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - New
      - Employee
  /Employer/{EmployerId}/Employees/Tag/{TagId}:
    get:
      summary: Get employees with tag
      description: Gets the employees with the tag
      operationId: GetEmployeesWithTag
      x-api-path-slug: employeremployeridemployeestagtagid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: TagId
        description: The tag unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employees
      - Tag
  /Employer/{EmployerId}/Employees/Tags:
    get:
      summary: Get all employee tags
      description: Gets all the employee tags
      operationId: GetAllEmployeeTags
      x-api-path-slug: employeremployeridemployeestags-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employee
      - Tags
  /Employer/{EmployerId}/Employees/{EffectiveDate}:
    get:
      summary: Get employees from employer at a given effective date.
      description: Get links to all employees for the employer on specified effective
        date.
      operationId: GetEmployeesByEffectiveDate
      x-api-path-slug: employeremployeridemployeeseffectivedate-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EffectiveDate
        description: The effective date to be applied
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Employees
      - From
      - Employer
      - At
      - Given
      - Effective
      - Date
  /Employer/{EmployerId}/NominalCode/{NominalCodeId}:
    delete:
      summary: Deletes the nominal codes
      description: Deletes the nominal code
      operationId: DeleteNominalCode
      x-api-path-slug: employeremployeridnominalcodenominalcodeid-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: NominalCodeId
        description: The nominal code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Nominal
      - Codes
    get:
      summary: Gets the nominal code
      description: Gets the nominal code
      operationId: GetNominalCodeFromEmployer
      x-api-path-slug: employeremployeridnominalcodenominalcodeid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: NominalCodeId
        description: The nominal code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Nominal
      - Code
    put:
      summary: Insert nominal code
      description: Inserts a new nominal code at the specified resource location
      operationId: PutNominalCode
      x-api-path-slug: employeremployeridnominalcodenominalcodeid-put
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: body
        name: NominalCode
        description: The nominal code object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: NominalCodeId
        description: The nominal code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Nominal
      - Code
  /Employer/{EmployerId}/NominalCodes:
    get:
      summary: Gets the nominal codes
      description: Gets the nominal code links
      operationId: GetNominalCodesFromEmployer
      x-api-path-slug: employeremployeridnominalcodes-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - Nominal
      - Codes
    post:
      summary: Insert nominal code
      description: Inserts a new nominal code
      operationId: PostNominalCode
      x-api-path-slug: employeremployeridnominalcodes-post
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: body
        name: NominalCode
        description: The nominal code object
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Nominal
      - Code
  /Employer/{EmployerId}/PayCode/{PayCodeId}:
    delete:
      summary: Deletes a pay code
      description: Delete the specified pay code
      operationId: DeletePayCode
      x-api-path-slug: employeremployeridpaycodepaycodeid-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
    get:
      summary: Gets the specified pay code from the employer
      description: Returns the specified pay code from the employer
      operationId: GetPayCodeFromEmployer
      x-api-path-slug: employeremployeridpaycodepaycodeid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Specified
      - Pay
      - Code
      - From
      - Employer
    patch:
      summary: Patches the pay code
      description: Patches the specified pay code object with the supplied values
      operationId: PatchPayCode
      x-api-path-slug: employeremployeridpaycodepaycodeid-patch
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: body
        name: PayCode
        description: The pay code object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Patches
      - Pay
      - Code
    put:
      summary: Updates a pay code
      description: Updates the existing specified pay code object
      operationId: PutPayCode
      x-api-path-slug: employeremployeridpaycodepaycodeid-put
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: body
        name: PayCode
        description: The pay code object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
  /Employer/{EmployerId}/PayCode/{PayCodeId}/Tag/{TagId}:
    delete:
      summary: Delete pay code tag
      description: Deletes a tag from the pay code
      operationId: DeletePayCodeTag
      x-api-path-slug: employeremployeridpaycodepaycodeidtagtagid-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      - in: path
        name: TagId
        description: The tag unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
      - Tag
    get:
      summary: Get pay code tag
      description: Gets the tag from the pay code
      operationId: GetTagFromPayCode
      x-api-path-slug: employeremployeridpaycodepaycodeidtagtagid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      - in: path
        name: TagId
        description: The tag unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
      - Tag
    put:
      summary: Insert pay code tag
      description: Inserts a new tag on the pay code
      operationId: PutPayCodeTag
      x-api-path-slug: employeremployeridpaycodepaycodeidtagtagid-put
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      - in: path
        name: TagId
        description: The tag unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Pay
      - Code
      - Tag
  /Employer/{EmployerId}/PayCode/{PayCodeId}/Tags:
    get:
      summary: Get all pay code tags
      description: Gets all the tags from the pay code
      operationId: GetTagsFromPayCode
      x-api-path-slug: employeremployeridpaycodepaycodeidtags-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
      - Tags
  /Employer/{EmployerId}/PayCode/{PayCodeId}/{EffectiveDate}:
    delete:
      summary: Deletes a pay code revision
      description: Delete the pay code revision for the specified date
      operationId: DeletePayCodeRevision
      x-api-path-slug: employeremployeridpaycodepaycodeideffectivedate-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EffectiveDate
        description: The effective date to be applied
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
      - Revision
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---