---
swagger: "2.0"
x-collection-name: AWS Route 53
x-complete: 0
info:
  title: AWS Route 53 API Change Resource Record Sets
  version: 1.0.0
  description: 'Create, change, update, or delete authoritative DNS information on
    all Amazon Route 53 servers.Send a POST request to:             /2013-04-01/hostedzone/Amazon
    Route 53 hosted ZoneID/rrset resource. The request body must include a document
    with aChangeResourceRecordSetsRequest element. The request body contains a list
    ofchange items, known as a change batch. Change batches are considered transactional
    changes.When using the Amazon Route 53 API to change resource record sets, Amazon
    Route 53 either makes all or none of thechanges in a change batch request. This
    ensures that Amazon Route 53 never partially implements theintended changes to
    the resource record sets in a hosted zone. For example, a change batch request
    that deletes the CNAME record forwww.example.com and creates an alias resource
    record set for www.example.com. Amazon Route 53 deletesthe first resource record
    set and creates the second resource record set in a singleoperation. If either
    the DELETE or the CREATE action fails, thenboth changes (plus any other changes
    in the batch) fail, and the original CNAMErecord continues to exist.ImportantDue
    to the nature of transactional changes, you can''t delete the same resourcerecord
    set more than once in a single change batch. If you attempt to delete the same
    changebatch more than once, Amazon Route 53 returns an InvalidChangeBatch error.NoteTo
    create resource record sets for complex routing configurations, use either thetraffic
    flow visual editor in the Amazon Route 53 console or the API actions for traffic
    policies andtraffic policy instances. Save the configuration as a traffic policy,
    then associate thetraffic policy with one or more domain names (such as example.com)
    or subdomain names (suchas www.example.com), in the same hosted zone or in multiple
    hosted zones. You can roll backthe updates if the new configuration isn''t performing
    as expected. For more information, seeUsing Traffic Flow to Route DNSTraffic in
    the Amazon Route 53 Developer Guide.Use ChangeResourceRecordsSetsRequest to perform
    the following actions:                  CREATE: Creates a resource record set
    that has the specified values.                  DELETE: Deletes an existing resource
    record set that has the specified values.                  UPSERT: If a resource
    record set does not already exist, AWS createsit. If a resource set does exist,
    Amazon Route 53 updates it with the values in the request. The values that you
    need to include in the request depend on the type of resource record set that
    you''re creating, deleting, or updating:            Basic resource record sets
    (excluding alias, failover, geolocation, latency, and weighted resource record
    sets)                           Name                                 Type                                 TTL                           Failover,
    geolocation, latency, or weighted resource record sets (excluding alias resource
    record sets)                           Name                                 Type                                 TTL                                 SetIdentifier                           Alias
    resource record sets (including failover alias, geolocation alias, latency alias,
    and weighted alias resource record sets)                           Name                                 Type                                 AliasTarget
    (includes DNSName, EvaluateTargetHealth, and HostedZoneId)                  SetIdentifier
    (for failover, geolocation, latency, and weighted resource record sets)When you
    submit a ChangeResourceRecordSets request, Amazon Route 53 propagates your changes
    to all of the Amazon Route 53 authoritative DNS servers. While your changes are
    propagating, GetChange returns a status of PENDING. When propagation is complete,
    GetChange returns a status of INSYNC. Changes generally propagate to all Amazon
    Route 53 name servers in a few minutes. In rare circumstances, propagation can
    take up to 30 minutes. For more information, see GetChange       For information
    about the limits on a ChangeResourceRecordSets request, see Limits in the Amazon
    Route 53 Developer Guide.'
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /2013-04-01/hostedzone/Id/rrset&amp;identifier=StartRecordIdentifier&amp;maxitems=MaxItems?name=StartRecordName&amp;type=StartRecordType
  : get:
      summary: List Resource Record Sets
      description: 'Lists the resource record sets in a specified hosted zone.            ListResourceRecordSets
        returns up to 100 resource record sets at a time in ASCII order, beginning
        at a position specified by the name and type elements. The action sorts results
        first by DNS name with the labels reversed, for example:            com.example.www.         Note
        the trailing dot, which can change the sort order in some circumstances.When
        multiple records have the same DNS name, the action sorts results by the record
        type.You can use the name and type elements to adjust the beginning position
        of the list of resource record sets returned:If you do not specify Name or
        TypeThe results begin with the first resource record set that the hosted zone
        contains.If you specify Name but not TypeThe results begin with the first
        resource record set in the list whose name is greater than or equal to Name.If
        you specify Type but not NameAmazon Route 53 returns the InvalidInput error.If
        you specify both Name and TypeThe results begin with the first resource record
        set in the list whose name is greater than or equal to Name, and whose type
        is greater than or equal to Type.This action returns the most current version
        of the records. This includes records that are PENDING, and that are not yet
        available on all Amazon Route 53 DNS servers.To ensure that you get an accurate
        listing of the resource record sets for a hosted zone at a point in time,
        do not submit a ChangeResourceRecordSets request while you''re paging through
        the results of a ListResourceRecordSets request. If you do, some pages may
        display results without the latest changes while other pages display results
        with the latest changes.'
      operationId: listresourcerecordsets
      x-api-path-slug: 20130401hostedzoneidrrsetampidentifierstartrecordidentifierampmaxitemsmaxitemsnamestartrecordnameamptypestartrecordtype-get
      parameters:
      - in: path
        name: Id
        description: The ID of the hosted zone that contains the resource record sets
          that you want toget
        type: string
      responses:
        200:
          description: OK
      tags:
      - Resource Record Sets
  /2013-04-01/hostedzone/Id/rrset/:
    post:
      summary: Change Resource Record Sets
      description: 'Create, change, update, or delete authoritative DNS information
        on all Amazon Route 53 servers.Send a POST request to:             /2013-04-01/hostedzone/Amazon
        Route 53 hosted ZoneID/rrset resource. The request body must include a document
        with aChangeResourceRecordSetsRequest element. The request body contains a
        list ofchange items, known as a change batch. Change batches are considered
        transactional changes.When using the Amazon Route 53 API to change resource
        record sets, Amazon Route 53 either makes all or none of thechanges in a change
        batch request. This ensures that Amazon Route 53 never partially implements
        theintended changes to the resource record sets in a hosted zone. For example,
        a change batch request that deletes the CNAME record forwww.example.com and
        creates an alias resource record set for www.example.com. Amazon Route 53
        deletesthe first resource record set and creates the second resource record
        set in a singleoperation. If either the DELETE or the CREATE action fails,
        thenboth changes (plus any other changes in the batch) fail, and the original
        CNAMErecord continues to exist.ImportantDue to the nature of transactional
        changes, you can''t delete the same resourcerecord set more than once in a
        single change batch. If you attempt to delete the same changebatch more than
        once, Amazon Route 53 returns an InvalidChangeBatch error.NoteTo create resource
        record sets for complex routing configurations, use either thetraffic flow
        visual editor in the Amazon Route 53 console or the API actions for traffic
        policies andtraffic policy instances. Save the configuration as a traffic
        policy, then associate thetraffic policy with one or more domain names (such
        as example.com) or subdomain names (suchas www.example.com), in the same hosted
        zone or in multiple hosted zones. You can roll backthe updates if the new
        configuration isn''t performing as expected. For more information, seeUsing
        Traffic Flow to Route DNSTraffic in the Amazon Route 53 Developer Guide.Use
        ChangeResourceRecordsSetsRequest to perform the following actions:                  CREATE:
        Creates a resource record set that has the specified values.                  DELETE:
        Deletes an existing resource record set that has the specified values.                  UPSERT:
        If a resource record set does not already exist, AWS createsit. If a resource
        set does exist, Amazon Route 53 updates it with the values in the request.
        The values that you need to include in the request depend on the type of resource
        record set that you''re creating, deleting, or updating:            Basic
        resource record sets (excluding alias, failover, geolocation, latency, and
        weighted resource record sets)                           Name                                 Type                                 TTL                           Failover,
        geolocation, latency, or weighted resource record sets (excluding alias resource
        record sets)                           Name                                 Type                                 TTL                                 SetIdentifier                           Alias
        resource record sets (including failover alias, geolocation alias, latency
        alias, and weighted alias resource record sets)                           Name                                 Type                                 AliasTarget
        (includes DNSName, EvaluateTargetHealth, and HostedZoneId)                  SetIdentifier
        (for failover, geolocation, latency, and weighted resource record sets)When
        you submit a ChangeResourceRecordSets request, Amazon Route 53 propagates
        your changes to all of the Amazon Route 53 authoritative DNS servers. While
        your changes are propagating, GetChange returns a status of PENDING. When
        propagation is complete, GetChange returns a status of INSYNC. Changes generally
        propagate to all Amazon Route 53 name servers in a few minutes. In rare circumstances,
        propagation can take up to 30 minutes. For more information, see GetChange       For
        information about the limits on a ChangeResourceRecordSets request, see Limits
        in the Amazon Route 53 Developer Guide.'
      operationId: changeresourcerecordsets
      x-api-path-slug: 20130401hostedzoneidrrset-post
      parameters:
      - in: body
        name: ChangeBatch
        description: A complex type that contains an optional comment and the Changeselement
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: ChangeResourceRecordSetsRequest
        description: Root level tag for the ChangeResourceRecordSetsRequest parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: Id
        description: The ID of the hosted zone that contains the resource record sets
          that you want tochange
        type: string
      responses:
        200:
          description: OK
      tags:
      - Changes
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