swagger: "2.0"
x-collection-name: Atlassian
x-complete: 1
info:
  title: Stride API
  description: this-service-provides-public-api-for-the-stride-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /content/{id}/child/{type}:
    get:
      summary: Get content children by type
      description: "Returns all children of a given type, for a piece of content.
        \nA piece of content has different types of child content, depending on its
        type:\n\n- `page`: child content is `page`, `comment`, `attachment`\n- `blogpost`:
        child content is `comment`, `attachment`\n- `attachment`: child content is
        `comment`\n- `comment`: child content is `attachment`\n\nCustom content types
        that are provided by apps can also be returned.\n\nNote, this method only
        returns direct children. To return children at all \nlevels, use [Get descendants
        by type](#api-content-id-descendant-type-get).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: 'View' permission for the space, \nand permission to view the
        content if it is a page."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ChildContentResource.getContentChildrenByType_get
      x-api-path-slug: contentidchildtype-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the new
          content to expand
      - in: path
        name: id
        description: The ID of the content to be queried for its children
      - in: query
        name: limit
        description: The maximum number of content to return per page
      - in: query
        name: parentVersion
        description: The version of the parent content to retrieve children for
      - in: query
        name: start
        description: The starting index of the returned content
      - in: path
        name: type
        description: The type of children to return
      responses:
        200:
          description: OK
      tags:
      - Content
      - Children
      - By
      - Type
  /content/{id}/descendant/{type}:
    get:
      summary: Get content descendants by type
      description: "Returns all descendants of a given type, for a piece of content.
        This is \nsimilar to [Get content children by type](#api-content-id-child-type-get),
        \nexcept that this method returns child pages at all levels, rather than just
        \nthe direct child pages.\n\nA piece of content has different types of descendants,
        depending on its type:\n\n- `page`: descendant is `page`, `comment`, `attachment`\n-
        `blogpost`: descendant is `comment`, `attachment`\n- `attachment`: descendant
        is `comment`\n- `comment`: descendant is `attachment`\n\nCustom content types
        that are provided by apps can also be returned.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \n'View' permission for the space, and permission to view the
        content if it \nis a page."
      operationId: com.atlassian.confluence.plugins.restapi.resources.DescendantContentResource.descendantsOfType_get
      x-api-path-slug: contentiddescendanttype-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the new
          content to expand
      - in: path
        name: id
        description: The ID of the content to be queried for its descendants
      - in: query
        name: limit
        description: The maximum number of content to return per page
      - in: query
        name: start
        description: The starting index of the returned content
      - in: path
        name: type
        description: The type of descendants to return
      responses:
        200:
          description: OK
      tags:
      - Content
      - Descendants
      - By
      - Type
  /api/2/issueLinkType:
    get:
      summary: Get issue link types
      description: Returns a list of available issue link types, if issue linking
        is enabled. Each issue link type has an id, a name and a label for the outward
        and inward link relationship.
      operationId: com.atlassian.jira.rest.v2.issue.IssueLinkTypeResource.getIssueLinkTypes_get
      x-api-path-slug: api2issuelinktype-get
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Link
      - Types
    post:
      summary: Create issue link type
      description: Create a new issue link type.
      operationId: com.atlassian.jira.rest.v2.issue.IssueLinkTypeResource.createIssueLinkType_post
      x-api-path-slug: api2issuelinktype-post
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Link
      - Type
  /api/2/issuetype/{id}/alternatives:
    get:
      summary: Get alternative issue types
      description: Returns a list of issue types that can be used to replace the issue
        type. The alternative issue types are those assigned to the same workflow
        scheme, field configuration scheme, and screen scheme. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** Permission to access Jira.
      operationId: com.atlassian.jira.rest.v2.issue.IssueTypeResource.getAlternativeIssueTypes_get
      x-api-path-slug: api2issuetypeidalternatives-get
      parameters:
      - in: path
        name: id
        description: The ID of the issue type
      responses:
        200:
          description: OK
      tags:
      - Alternative
      - Issue
      - Types
  /api/2/project/type:
    get:
      summary: Get all project types
      description: |-
        Returns all [project types](https://confluence.atlassian.com/x/Var1Nw), whether or not the instance has a valid license for each type.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
      operationId: com.atlassian.jira.rest.v2.project.type.ProjectTypeResource.getAllProjectTypes_get
      x-api-path-slug: api2projecttype-get
      responses:
        200:
          description: OK
      tags:
      - Project
      - Types
  /api/2/issueLinkType/{issueLinkTypeId}:
    get:
      summary: Get issue link type
      description: Returns for a given issue link type id all information about this
        issue link type.
      operationId: com.atlassian.jira.rest.v2.issue.IssueLinkTypeResource.getIssueLinkType_get
      x-api-path-slug: api2issuelinktypeissuelinktypeid-get
      parameters:
      - in: path
        name: issueLinkTypeId
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Link
      - Type
    put:
      summary: Update issue link type
      description: Update the specified issue link type.
      operationId: com.atlassian.jira.rest.v2.issue.IssueLinkTypeResource.updateIssueLinkType_put
      x-api-path-slug: api2issuelinktypeissuelinktypeid-put
      parameters:
      - in: path
        name: issueLinkTypeId
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Link
      - Type
    delete:
      summary: Delete issue link type
      description: Delete the specified issue link type.
      operationId: com.atlassian.jira.rest.v2.issue.IssueLinkTypeResource.deleteIssueLinkType_delete
      x-api-path-slug: api2issuelinktypeissuelinktypeid-delete
      parameters:
      - in: path
        name: issueLinkTypeId
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Link
      - Type
  /api/2/issuetype:
    post:
      summary: Create issue type
      description: Creates an issue type and adds it to the default issue type scheme.
        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
        Jira_ [global permission](href=).
      operationId: com.atlassian.jira.rest.v2.issue.IssueTypeResource.createIssueType_post
      x-api-path-slug: api2issuetype-post
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Type
  /api/2/issuetype/{id}:
    get:
      summary: Get issue type
      description: |-
        Returns an issue type. [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

        *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
        *   _Browse projects_ project permission to get the details of any issue type associated with the projects the user has permission to browse.
      operationId: com.atlassian.jira.rest.v2.issue.IssueTypeResource.getIssueType_get
      x-api-path-slug: api2issuetypeid-get
      parameters:
      - in: path
        name: id
        description: The ID of the issue type
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Type
    put:
      summary: Update issue type
      description: Updates the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** _Administer Jira_ [global permission](href=).
      operationId: com.atlassian.jira.rest.v2.issue.IssueTypeResource.updateIssueType_put
      x-api-path-slug: api2issuetypeid-put
      parameters:
      - in: path
        name: id
        description: The ID of the issue type
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Type
    delete:
      summary: Delete issue type
      description: Deletes the issue type. If the issue type is in use, all uses are
        updated with the alternative issue type (`alternativeIssueTypeId`). A list
        of alternative issue types can be obtained from the [Get alternative issue
        types](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-alternatives-get)
        resource. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**
        _Administer Jira_ [global permission](href=).
      operationId: com.atlassian.jira.rest.v2.issue.IssueTypeResource.deleteIssueType_delete
      x-api-path-slug: api2issuetypeid-delete
      parameters:
      - in: query
        name: alternativeIssueTypeId
        description: The ID of the replacement issue type
      - in: path
        name: id
        description: The ID of the issue type
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Type
  /api/2/issuetype/{id}/avatar2:
    post:
      summary: Create issue type avatar
      description: |-
        Creates an avatar for the issue type. Specify the avatar's local file location as binary data in the body of the request. Also, include the following headers:

        *   `X-Atlassian-Token: no-check`
        *   `Content-Type: image/_image type_` Valid image types are JPEG, GIF, or PNG.

        For example: `curl --request POST \ --user email@example.com: \ --header 'X-Atlassian-Token: no-check' \ --header 'Content-Type: image/< image_type>' \ --data-binary "" \ --url 'https://your-domain.atlassian.net/rest/api/2/issuetype/{issueTypeId}'This` The avatar is cropped to a square. If no crop parameters are specified, the square originates at the top left of the image. The length of the square's sides is set to the smaller of the height or width of the image. The cropped image is then used to create avatars of 16x16, 24x24, 32x32, and 48x48 in size. After creating the avatar, use [Update issue type](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-put) to set it as the issue type's active avatar. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](href=).
      operationId: com.atlassian.jira.rest.v2.issue.IssueTypeResource.createIssueTypeAvatar_post
      x-api-path-slug: api2issuetypeidavatar2-post
      parameters:
      - in: path
        name: id
        description: The ID of the issue type
      - in: query
        name: size
        description: The length of each side of the crop region
      - in: query
        name: x
        description: The X coordinate of the top-left corner of the crop region
      - in: query
        name: "y"
        description: The Y coordinate of the top-left corner of the crop region
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Type
      - Avatar
  /api/2/issuetype/{issueTypeId}/properties:
    get:
      summary: Get issue type property keys
      description: |-
        Returns all the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys of the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

        *   _Administer Jira_ [global permission](href=) to get the property keys of any issue type.
        *   _Browse projects_ project permission to get the property keys of any issue types associated with the projects the user has permission to browse.
      operationId: com.atlassian.jira.rest.v2.issue.IssueTypePropertyResource.getIssueTypePropertyKeys_get
      x-api-path-slug: api2issuetypeissuetypeidproperties-get
      parameters:
      - in: path
        name: issueTypeId
        description: The ID of the issue type
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Type
      - Property
      - Keys
  /api/2/issuetype/{issueTypeId}/properties/{propertyKey}:
    get:
      summary: Get issue type property
      description: |-
        Returns the key and value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

        *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
        *   _Browse projects_ project permission to get the details of any issue types associated with the projects the user has permission to browse.
      operationId: com.atlassian.jira.rest.v2.issue.IssueTypePropertyResource.getIssueTypeProperty_get
      x-api-path-slug: api2issuetypeissuetypeidpropertiespropertykey-get
      parameters:
      - in: path
        name: issueTypeId
        description: The ID of the issue type
      - in: path
        name: propertyKey
        description: The key of the property
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Type
      - Property
    put:
      summary: Set issue type property
      description: Creates or updates the value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
        Use this resource to store and update data against an issue type. The value
        of the request body must be a [valid](http://tools.ietf.org/html/rfc4627),
        non-empty JSON blob. The maximum length of the property value is 32768 bytes.
        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
        Jira_ [global permission](href=).
      operationId: com.atlassian.jira.rest.v2.issue.IssueTypePropertyResource.setIssueTypeProperty_put
      x-api-path-slug: api2issuetypeissuetypeidpropertiespropertykey-put
      parameters:
      - in: path
        name: issueTypeId
        description: The ID of the issue type
      - in: path
        name: propertyKey
        description: The key of the issue type property
      responses:
        200:
          description: OK
      tags:
      - Set
      - Issue
      - Type
      - Property
    delete:
      summary: Delete issue type property
      description: Deletes the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
        Jira_ [global permission](href=).
      operationId: com.atlassian.jira.rest.v2.issue.IssueTypePropertyResource.deleteIssueTypeProperty_delete
      x-api-path-slug: api2issuetypeissuetypeidpropertiespropertykey-delete
      parameters:
      - in: path
        name: issueTypeId
        description: The ID of the issue type
      - in: path
        name: propertyKey
        description: The key of the property
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Type
      - Property
  /api/2/project/type/{projectTypeKey}:
    get:
      summary: Get project type by key
      description: |-
        Returns a [project type](https://confluence.atlassian.com/x/Var1Nw).

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
      operationId: com.atlassian.jira.rest.v2.project.type.ProjectTypeResource.getProjectTypeByKey_get
      x-api-path-slug: api2projecttypeprojecttypekey-get
      parameters:
      - in: path
        name: projectTypeKey
        description: The key of the project type
      responses:
        200:
          description: OK
      tags:
      - Project
      - Type
      - By
      - Key
  /api/2/project/type/{projectTypeKey}/accessible:
    get:
      summary: Get accessible project type by key
      description: |-
        Returns a [project type](https://confluence.atlassian.com/x/Var1Nw) if it is accessible to the logged in user.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
      operationId: com.atlassian.jira.rest.v2.project.type.ProjectTypeResource.getAccessibleProjectTypeByKey_get
      x-api-path-slug: api2projecttypeprojecttypekeyaccessible-get
      parameters:
      - in: path
        name: projectTypeKey
        description: The key of the project type
      responses:
        200:
          description: OK
      tags:
      - Accessible
      - Project
      - Type
      - By
      - Key
  /api/2/project/{projectIdOrKey}/type/{newProjectTypeKey}:
    put:
      summary: Update project type
      description: |-
        Updates the [project type](https://confluence.atlassian.com/x/GwiiLQ).

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.updateProjectType_put
      x-api-path-slug: api2projectprojectidorkeytypenewprojecttypekey-put
      parameters:
      - in: path
        name: newProjectTypeKey
        description: The key of the new project type
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Type
  /api/2/workflowscheme/{id}/draft/issuetype/{issueType}:
    get:
      summary: Get workflow scheme draft issue type
      description: Returns the issue type mapping for the passed draft workflow scheme.
      operationId: com.atlassian.jira.rest.v2.admin.workflowscheme.WorkflowSchemeResource.getWorkflowSchemeDraftIssueTy
      x-api-path-slug: api2workflowschemeiddraftissuetypeissuetype-get
      parameters:
      - in: path
        name: id
        description: the id of the parent scheme
      - in: path
        name: issueType
        description: the issue type to query
      responses:
        200:
          description: OK
      tags:
      - Workflow
      - Scheme
      - Draft
      - Issue
      - Type
    put:
      summary: Set workflow scheme draft issue type
      description: |-
        Set the issue type mapping for the passed draft scheme.

        The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
      operationId: com.atlassian.jira.rest.v2.admin.workflowscheme.WorkflowSchemeResource.setWorkflowSchemeDraftIssueTy
      x-api-path-slug: api2workflowschemeiddraftissuetypeissuetype-put
      parameters:
      - in: path
        name: id
        description: the id of the parent scheme
      - in: path
        name: issueType
        description: the issue type being set
      responses:
        200:
          description: OK
      tags:
      - Set
      - Workflow
      - Scheme
      - Draft
      - Issue
      - Type
    delete:
      summary: Delete workflow scheme draft issue type
      description: Remove the specified issue type mapping from the draft scheme.
      operationId: com.atlassian.jira.rest.v2.admin.workflowscheme.WorkflowSchemeResource.deleteWorkflowSchemeDraftIssu
      x-api-path-slug: api2workflowschemeiddraftissuetypeissuetype-delete
      parameters:
      - in: path
        name: id
        description: the parent of the draft scheme
      - in: path
        name: issueType
        description: the issue type to remove
      responses:
        200:
          description: OK
      tags:
      - Workflow
      - Scheme
      - Draft
      - Issue
      - Type
  /api/2/workflowscheme/{id}/issuetype/{issueType}:
    get:
      summary: Get workflow scheme issue type
      description: Returns the issue type mapping for the passed workflow scheme.
      operationId: com.atlassian.jira.rest.v2.admin.workflowscheme.WorkflowSchemeResource.getWorkflowSchemeIssueType_ge
      x-api-path-slug: api2workflowschemeidissuetypeissuetype-get
      parameters:
      - in: path
        name: id
        description: the id of the scheme
      - in: path
        name: issueType
        description: the issue type to query
      - in: query
        name: returnDraftIfExists
        description: when true indicates that a schemes draft, if it exists, should
          be queried instead of the scheme itself
      responses:
        200:
          description: OK
      tags:
      - Workflow
      - Scheme
      - Issue
      - Type
    put:
      summary: Set workflow scheme issue type
      description: |-
        Set the issue type mapping for the passed scheme.

        The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
      operationId: com.atlassian.jira.rest.v2.admin.workflowscheme.WorkflowSchemeResource.setWorkflowSchemeIssueType_pu
      x-api-path-slug: api2workflowschemeidissuetypeissuetype-put
      parameters:
      - in: path
        name: id
        description: the id of the scheme
      - in: path
        name: issueType
        description: the issue type being set
      responses:
        200:
          description: OK
      tags:
      - Set
      - Workflow
      - Scheme
      - Issue
      - Type
    delete:
      summary: Delete workflow scheme issue type
      description: Remove the specified issue type mapping from the scheme.
      operationId: com.atlassian.jira.rest.v2.admin.workflowscheme.WorkflowSchemeResource.deleteWorkflowSchemeIssueType
      x-api-path-slug: api2workflowschemeidissuetypeissuetype-delete
      parameters:
      - in: path
        name: id
        description: the id of the scheme
      - in: path
        name: issueType
        description: the issue type to remove
      - in: query
        name: updateDraftIfNeeded
        description: when true will create and return a draft when the workflow scheme
          cannot be edited (e
      responses:
        200:
          description: OK
      tags:
      - Workflow
      - Scheme
      - Issue
      - Type
  /api/2/issue:
    post:
      summary: Create issue
      description: |-
        Creates an issue or a sub-task from a JSON representation.

        You can provide two parameters in request's body: `update` or `fields`. The fields, that can be set on an issue create operation, can be determined using the **/rest/api/2/issue/createmeta** resource. If a particular field is not configured to appear on the issue's Create screen, then it will not be returned in the createmeta response. A field validation error will occur if such field is submitted in request.

        Creating a sub-task is similar to creating an issue with the following differences:

        *   `issueType` field must be set to a sub-task issue type (use `/issue/createmeta` to find sub-task issue types), and
        *   You must provide a `parent` field with the ID or key of the parent issue.
      operationId: com.atlassian.jira.rest.v2.issue.IssueResource.createIssue_post
      x-api-path-slug: api2issue-post
      parameters:
      - in: query
        name: updateHistory
        description: If set to true, then project an issue was created in is added
          to the current users project history
      responses:
        200:
          description: OK
      tags:
      - Issue