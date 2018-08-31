---
swagger: "2.0"
x-collection-name: PayRun
x-complete: 0
info:
  title: Pay Run.IO Gets the specified pay instruction from the employee
  description: Returns the specified pay instruction from employee
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