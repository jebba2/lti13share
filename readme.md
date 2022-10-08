Here’s the spec document for LTI 1.3:
 
https://www.imsglobal.org/spec/lti/v1p3/#role-vocabularies
 
Here’s the variables from $launch->get_launch_data()
 
Array
(
    [nbf] => 1664997643
    [exp] => 1664999443
    [iss] => https://gastatetest2.view.usg.edu
    [aud] => 38b0c94e-5b1a-4e0f-9616-d3b77ab6874a
    [iat] => 1664997643
    [sub] => 1019d47b-e5e1-43e2-843a-3c9a825650ef_1826270
    [given_name] => Admin
    [family_name] => Jeb
    [name] => Admin Jeb
    [email] => jbarger@gsu.edu
    [nonce] => nonce-633dd90bda6ec0.43272697
    [https://purl.imsglobal.org/spec/lti/claim/message_type] => LtiResourceLinkRequest
    [https://purl.imsglobal.org/spec/lti/claim/version] => 1.3.0
    [https://purl.imsglobal.org/spec/lti/claim/deployment_id] => 2ff21e97-79cf-4794-9244-5bfb55b7a330
    [https://purl.imsglobal.org/spec/lti/claim/target_link_uri] => https://jebbarger.com/lti1p32/test.php
    [https://purl.imsglobal.org/spec/lti/claim/resource_link] => Array
        (
            [id] => usgxtest-17557021_2273803
            [title] => test
            [description] =>
        )
 
    [https://purl.imsglobal.org/spec/lti/claim/roles] => Array
        (
            [0] => http://purl.imsglobal.org/vocab/lis/v2/membership#Instructor
            [1] => http://purl.imsglobal.org/vocab/lis/v2/membership#Administrator
            [2] => http://purl.imsglobal.org/vocab/lis/v2/institution/person#Instructor
            [3] => http://purl.imsglobal.org/vocab/lis/v2/institution/person#Administrator
        )
 
    [https://purl.imsglobal.org/spec/lti/claim/context] => Array
        (
            [id] => 2273803
            [label] => Jeb Course O Fun
            [title] => Jeb Course O Fun
            [type] => Array
                (
                    [0] => http://purl.imsglobal.org/vocab/lis/v2/course#CourseOffering
                )
 
        )
 
    [https://purl.imsglobal.org/spec/lti/claim/lis] => Array
        (
            [course_offering_sourcedid] => gastatetest2.view.usg.edu:Jeb Course O Fun
            [course_section_sourcedid] => gastatetest2.view.usg.edu:Jeb Course O Fun
        )
 
    [https://purl.imsglobal.org/spec/lti/claim/launch_presentation] => Array
        (
            [locale] => en-us
        )
 
    [http://www.brightspace.com] => Array
        (
            [tenant_id] => ca4d7f6b-e6bf-43ef-a263-6e76d66678ef
            [org_defined_id] => 123456
            [user_id] => 1826270
            [username] => admin.jeb
            [Context.id.history] =>
            [ResourceLink.id.history] =>
            [content_topic_id] => 33677592
        )
 
    [https://purl.imsglobal.org/spec/lti-ags/claim/endpoint] => Array
        (
            [scope] => Array
                (
                    [0] => https://purl.imsglobal.org/spec/lti-ags/scope/lineitem
                    [1] => https://purl.imsglobal.org/spec/lti-ags/scope/lineitem.readonly
                    [2] => https://purl.imsglobal.org/spec/lti-ags/scope/result.readonly
                    [3] => https://purl.imsglobal.org/spec/lti-ags/scope/score
                )
 
            [lineitem] => https://gastatetest2.view.usg.edu/d2l/api/lti/ags/2.0/deployment/2ff21e97-79cf-4794-9244-5bfb55b7a330/orgunit/2273803/lineitems/3106e6da-b85b-4ac4-9a04-5dd8ff0394c3
            [lineitems] => https://gastatetest2.view.usg.edu/d2l/api/lti/ags/2.0/deployment/2ff21e97-79cf-4794-9244-5bfb55b7a330/orgunit/2273803/lineitems
        )
 
    [https://purl.imsglobal.org/spec/lti-nrps/claim/namesroleservice] => Array
        (
            [context_memberships_url] => https://gastatetest2.view.usg.edu/d2l/api/lti/nrps/2.0/deployment/2ff21e97-79cf-4794-9244-5bfb55b7a330/orgunit/2273803/memberships
            [service_versions] => Array
                (
                    [0] => 2.0
                )
 
        )
 
    [https://purl.imsglobal.org/spec/lti/claim/tool_platform] => Array
        (
            [guid] => ca4d7f6b-e6bf-43ef-a263-6e76d66678ef
            [product_family_code] => desire2learn
        )
 
)
 
