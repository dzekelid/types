---
name: AWS Route 53
x-slug: aws-route-53
description: Amazon Route 53 is a highly available and scalable cloud Domain Name
  System (DNS) web service. It is designed to give developers and businesses an extremely
  reliable and cost effective way to route end users to Internet applications by translating
  names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers
  use to connect to each other. Amazon Route 53 is fully compliant with IPv6 as well.Amazon
  Route 53 effectively connects user requests to infrastructure running in AWS &ndash;
  such as Amazon EC2 instances, Elastic Load Balancing load balancers, or Amazon S3
  buckets &ndash; and can also be used to route users to infrastructure outside of
  AWS. You can use Amazon Route 53 to configure DNS health checks to route traffic
  to healthy endpoints or to independently monitor the health of your application
  and its endpoints. Amazon Route 53 Traffic Flow makes it easy for you to manage
  traffic globally through a variety of routing types, including Latency Based Routing,
  Geo DNS, and Weighted Round Robin&mdash;all of which can be combined with DNS Failover
  in order to enable a variety of low-latency, fault-tolerant architectures. Using
  Amazon Route 53 Traffic Flow&rsquo;s simple visual editor, you can easily manage
  how your end-users are routed to your application&rsquo;s endpoints&mdash;whether
  in a single AWS region or distributed around the globe. Amazon Route 53 also offers
  Domain Name Registration &ndash; you can purchase and manage domain names such as
  example.com and Amazon Route 53 will automatically configure DNS settings for your
  domains.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Types
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/aws-route-53/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Route 53 API - List Resource Record Sets
  x-api-slug: 20130401hostedzoneidrrsetampidentifierstartrecordidentifierampmaxitemsmaxitemsnamestartrecordnameamptypestartrecordtype-get
  description: 'Lists the resource record sets in a specified hosted zone.            ListResourceRecordSets
    returns up to 100 resource record sets at a time in ASCII order, beginning at
    a position specified by the name and type elements. The action sorts results first
    by DNS name with the labels reversed, for example:            com.example.www.         Note
    the trailing dot, which can change the sort order in some circumstances.When multiple
    records have the same DNS name, the action sorts results by the record type.You
    can use the name and type elements to adjust the beginning position of the list
    of resource record sets returned:If you do not specify Name or TypeThe results
    begin with the first resource record set that the hosted zone contains.If you
    specify Name but not TypeThe results begin with the first resource record set
    in the list whose name is greater than or equal to Name.If you specify Type but
    not NameAmazon Route 53 returns the InvalidInput error.If you specify both Name
    and TypeThe results begin with the first resource record set in the list whose
    name is greater than or equal to Name, and whose type is greater than or equal
    to Type.This action returns the most current version of the records. This includes
    records that are PENDING, and that are not yet available on all Amazon Route 53
    DNS servers.To ensure that you get an accurate listing of the resource record
    sets for a hosted zone at a point in time, do not submit a ChangeResourceRecordSets
    request while you''re paging through the results of a ListResourceRecordSets request.
    If you do, some pages may display results without the latest changes while other
    pages display results with the latest changes.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/aws-route-53/20130401hostedzoneidrrsetampidentifierstartrecordidentifierampmaxitemsmaxitemsnamestartrecordnameamptypestartrecordtype-get-openapi.md
- name: AWS Route 53 API - List Resource Record Sets
  x-api-slug: 20130401hostedzoneidrrsetampidentifierstartrecordidentifierampmaxitemsmaxitemsnamestartrecordnameamptypestartrecordtype-get
  description: 'Lists the resource record sets in a specified hosted zone.            ListResourceRecordSets
    returns up to 100 resource record sets at a time in ASCII order, beginning at
    a position specified by the name and type elements. The action sorts results first
    by DNS name with the labels reversed, for example:            com.example.www.         Note
    the trailing dot, which can change the sort order in some circumstances.When multiple
    records have the same DNS name, the action sorts results by the record type.You
    can use the name and type elements to adjust the beginning position of the list
    of resource record sets returned:If you do not specify Name or TypeThe results
    begin with the first resource record set that the hosted zone contains.If you
    specify Name but not TypeThe results begin with the first resource record set
    in the list whose name is greater than or equal to Name.If you specify Type but
    not NameAmazon Route 53 returns the InvalidInput error.If you specify both Name
    and TypeThe results begin with the first resource record set in the list whose
    name is greater than or equal to Name, and whose type is greater than or equal
    to Type.This action returns the most current version of the records. This includes
    records that are PENDING, and that are not yet available on all Amazon Route 53
    DNS servers.To ensure that you get an accurate listing of the resource record
    sets for a hosted zone at a point in time, do not submit a ChangeResourceRecordSets
    request while you''re paging through the results of a ListResourceRecordSets request.
    If you do, some pages may display results without the latest changes while other
    pages display results with the latest changes.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/aws-route-53/20130401hostedzoneidrrsetampidentifierstartrecordidentifierampmaxitemsmaxitemsnamestartrecordnameamptypestartrecordtype-get-openapi.md
- name: AWS Route 53 API - Change Resource Record Sets
  x-api-slug: 20130401hostedzoneidrrset-post
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/aws-route-53/20130401hostedzoneidrrset-post-openapi.md
- name: AWS Route 53 API - List Tags For Resources
  x-api-slug: 20130401tagsresourcetype-post
  description: Lists tags for up to 10 health checks or hosted zones.For information
    about using tags for cost allocation, see Using Cost Allocation Tags in the AWS
    Billing and Cost Management User Guide.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/aws-route-53/20130401tagsresourcetype-post-openapi.md
- name: AWS Route 53 API - Change Tags For Resource
  x-api-slug: 20130401tagsresourcetyperesourceid-post
  description: Adds, edits, or deletes tags for a health check or a hosted zone.For
    information about using tags for cost allocation, see Using Cost Allocation Tags
    in the AWS Billing and Cost Management User Guide.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/aws-route-53/20130401tagsresourcetyperesourceid-post-openapi.md
- name: AWS Route 53 API - List Tags For Resource
  x-api-slug: 20130401tagsresourcetyperesourceid-get
  description: Lists tags for one health check or hosted zone. For information about
    using tags for cost allocation, see Using Cost Allocation Tags in the AWS Billing
    and Cost Management User Guide.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/aws-route-53/20130401tagsresourcetyperesourceid-get-openapi.md
- name: AWS Route 53 API - Test D N S Answer
  x-api-slug: 20130401testdnsanswerampedns0clientsubnetipedns0clientsubnetipampedns0clientsubnetmaskedns0clientsubnetmaskhostedzoneidhostedzoneidamprecordnamerecordnameamprecordtyperecordtypeampresolveripresolverip-get
  description: Gets the value that Amazon Route 53 returns in response to a DNS request
    for a specified record name and type. You can optionally specify the IP address
    of a DNS resolver, an EDNS0 client subnet IP address, and a subnet mask.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/aws-route-53/20130401testdnsanswerampedns0clientsubnetipedns0clientsubnetipampedns0clientsubnetmaskedns0clientsubnetmaskhostedzoneidhostedzoneidamprecordnamerecordnameamprecordtyperecordtypeampresolveripresolverip-get-openapi.md
- name: AWS Route 53 API - List Traffic Policy Instances By Hosted Zone
  x-api-slug: 20130401trafficpolicyinstanceshostedzoneidhostedzoneidampmaxitemsmaxitemsamptrafficpolicyinstancenametrafficpolicyinstancenamemarkeramptrafficpolicyinstancetypetrafficpolicyinstancetypemarker-get
  description: 'Gets information about the traffic policy instances that you created
    in a specifiedhosted zone.NoteAfter you submit an UpdateTrafficPolicyInstance
    request, there''s a briefdelay while Amazon Route 53 creates the resource record
    sets that are specified in the traffic policydefinition. For more information,
    see the State response element.Send a GET request to the /Amazon Route 53 APIversion/trafficpolicyinstance
    resource and include the ID of the hostedzone.Amazon Route 53 returns a maximum
    of 100 items in each response. If you have a lot of trafficpolicy instances, you
    can use the MaxItems parameter to list them in groups of upto 100.The response
    includes four values that help you navigate from one group ofMaxItems traffic
    policy instances to the next:             IsTruncated               If the value
    of IsTruncated in the response is true, there aremore traffic policy instances
    associated with the current AWS account.If IsTruncated is false, this response
    includes the lasttraffic policy instance that is associated with the current account.             MaxItems           The
    value that you specified for the MaxItems parameter in the requestthat produced
    the current response.                  TrafficPolicyInstanceNameMarker and TrafficPolicyInstanceTypeMarker               If
    IsTruncated is true, these two values in the responserepresent the first traffic
    policy instance in the next group of MaxItemstraffic policy instances. To list
    more traffic policy instances, make another call toListTrafficPolicyInstancesByHostedZone,
    and specify these values in thecorresponding request parameters.If IsTruncated
    is false, all three elements are omittedfrom the response.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/aws-route-53/20130401trafficpolicyinstanceshostedzoneidhostedzoneidampmaxitemsmaxitemsamptrafficpolicyinstancenametrafficpolicyinstancenamemarkeramptrafficpolicyinstancetypetrafficpolicyinstancetypemarker-get-openapi.md
- name: AWS Route 53 API - List Traffic Policy Instances By Policy
  x-api-slug: 20130401trafficpolicyinstancestrafficpolicyamphostedzoneidhostedzoneidmarkeridtrafficpolicyidampmaxitemsmaxitemsamptrafficpolicyinstancenametrafficpolicyinstancenamemarkeramptrafficpolicyinstancetypetrafficpolicyinstancetypemarker-get
  description: 'Gets information about the traffic policy instances that you created
    by using a specifytraffic policy version.NoteAfter you submit a CreateTrafficPolicyInstance
    or anUpdateTrafficPolicyInstance request, there''s a brief delay while Amazon
    Route 53creates the resource record sets that are specified in the traffic policy
    definition. Formore information, see the State response element.Send a GET request
    to the /Route 53 APIversion/trafficpolicyinstance resource and include the ID
    and version ofthe traffic policy.Amazon Route 53 returns a maximum of 100 items
    in each response. If you have a lot of trafficpolicy instances, you can use the
    MaxItems parameter to list them in groups of upto 100.The response includes five
    values that help you navigate from one group ofMaxItems traffic policy instances
    to the next:             IsTruncated               If the value of IsTruncated
    in the response is true,there are more traffic policy instances associated with
    the specified trafficpolicy.If IsTruncated is false, this response includes the
    lasttraffic policy instance that is associated with the specified traffic policy.             MaxItems               The
    value that you specified for the MaxItems parameter in the requestthat produced
    the current response.                  HostedZoneIdMarker, TrafficPolicyInstanceNameMarker,
    and TrafficPolicyInstanceTypeMarker               If IsTruncated is true, these
    values in the responserepresent the first traffic policy instance in the next
    group of MaxItemstraffic policy instances. To list more traffic policy instances,
    make another call toListTrafficPolicyInstancesByPolicy, and specify these values
    in thecorresponding request parameters.If IsTruncated is false, all three elements
    are omittedfrom the response.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/aws-route-53/20130401trafficpolicyinstancestrafficpolicyamphostedzoneidhostedzoneidmarkeridtrafficpolicyidampmaxitemsmaxitemsamptrafficpolicyinstancenametrafficpolicyinstancenamemarkeramptrafficpolicyinstancetypetrafficpolicyinstancetypemarker-get-openapi.md
- name: AWS Route 53 API - List Traffic Policy Instances
  x-api-slug: 20130401trafficpolicyinstanceshostedzoneidhostedzoneidmarkerampmaxitemsmaxitemsamptrafficpolicyinstancenametrafficpolicyinstancenamemarkeramptrafficpolicyinstancetypetrafficpolicyinstancetypemarker-get
  description: 'Gets information about the traffic policy instances that you created
    by using thecurrent AWS account.NoteAfter you submit an UpdateTrafficPolicyInstance
    request, there''s a briefdelay while Amazon Route 53 creates the resource record
    sets that are specified in the traffic policydefinition. For more information,
    see the State response element.Send a GET request to the /Amazon Route 53 APIversion/trafficpolicyinstance
    resource.Amazon Route 53 returns a maximum of 100 items in each response. If you
    have a lot of trafficpolicy instances, you can use the MaxItems parameter to list
    them in groups of upto 100.The response includes five values that help you navigate
    from one group ofMaxItems traffic policy instances to the next:             IsTruncated           If
    the value of IsTruncated in the response is true,there are more traffic policy
    instances associated with the current AWSaccount.If IsTruncated is false, this
    response includes the lasttraffic policy instance that is associated with the
    current account.             MaxItems           The value that you specified for
    the MaxItems parameter in the requestthat produced the current response.                  HostedZoneIdMarker,
    TrafficPolicyInstanceNameMarker, and TrafficPolicyInstanceTypeMarker               If
    IsTruncated is true, these three values in theresponse represent the first traffic
    policy instance in the next group ofMaxItems traffic policy instances. To list
    more traffic policy instances,make another call to ListTrafficPolicyInstances,
    and specify these values inthe corresponding request parameters.If IsTruncated
    is false, all three elements are omittedfrom the response.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/aws-route-53/20130401trafficpolicyinstanceshostedzoneidhostedzoneidmarkerampmaxitemsmaxitemsamptrafficpolicyinstancenametrafficpolicyinstancenamemarkeramptrafficpolicyinstancetypetrafficpolicyinstancetypemarker-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.rekognition.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.route.53.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/Route53/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/route53/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=87
- type: x-pricing
  url: https://aws.amazon.com/route53/pricing/
- type: x-registrar-policies
  url: https://aws.amazon.com/route53/amazon-registrar-policies/
- type: x-service-health
  url: http://status.aws.amazon.com/
- type: x-service-level-agreement
  url: https://aws.amazon.com/route53/sla
- type: x-sla
  url: https://aws.amazon.com/route53/sla/
- type: x-website
  url: https://aws.amazon.com/route53/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---