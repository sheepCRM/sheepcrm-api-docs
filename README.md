# sheepcrm-api-docs
Documentation for sheepCRM APIs

## Progress

40 / ~180
[########------------------------------]
5 per "#"

## Core
# Atom
# Events
# Notifications
# Search

# Segments
app.add_route("/segments/v2/{bucket}", segments)
app.add_route("/segments/v2/{bucket}/all", segments, suffix="all")
app.add_route("/segments/v2/{bucket}/trees", segments, suffix="trees")
app.add_route("/segments/v2/{bucket}/{view_context}", segments, suffix="view_context")


# Core
path: /api/v2/{bucket}/{resource_type}/{uid}/avatar
path: /api/v2/{bucket}/{resource_type}/{uid}/avatar/large
path: '/api/v2/{bucket}/{resource_type}/{uid}/display'
path: '/api/v2/{bucket}/find/person'
path: '/api/v2/{bucket}/{resource_type}/{uid}/image/{field}/{style}'
path: '/api/v2/{bucket}/{resource_type}/{uid}/image/{field}/{style}'
'GET /v2/{bucket}/{resource_type}/schema'
'GET /v2/{bucket}/{resource_type}/schema/fields'
'GET /v2/{bucket}/{resource_type}/schema/parameters/yaml'
'GET /v2/{bucket}/{resource_type}/schema/policy/{policy_name}'
'GET /v2/system/{bucket}/{resource_type}/schema'
'GET /v2/system/{bucket}/{resource_type}/schema/fields'
'GET /v2/system/{bucket}/{resource_type}/schema/parameters/yaml'
'GET /v2/system/{bucket}/{resource_type}/schema/policy/{policy_name}'
path: '/v2/{bucket}/notices'
path: '/v2/{bucket}/notices/errors'
path: '/v2/{bucket}/notices/action_required'
'GET /v2/{bucket}/system/notices' # deprecate?
'GET /api/v2/{bucket}/system/notices/errors'
'GET /api/v2/{bucket}/system/notices'
'GET /api/v2/{bucket}/system/notices/action_required'
path: '/api/v2/{bucket}/{resource_type}/{uid}/validate'
'GET /api/v2/{bucket}/person/{uid}/session/all'
'GET /api/v2/{bucket}/person/{uid}/session/detail'
'GET /api/v2/{bucket}/person/{uid}/session/future'
'GET /api/v2/{bucket}/person/{uid}/session/past'
'GET /api/v2/{bucket}/person/{uid}/session/summary'
'GET /api/v2/{bucket}/{resource_type}/{uid}/event/order/{euid}'
'GET /api/v2/{bucket}/{resource_type}/{uid}/events/all'
'GET /api/v2/{bucket}/{resource_type}/{uid}/events/summary'
'DELETE /api/v2/{bucket}/{resource_type}/{uid}/event/order/{euid}'
'GET /api/v2/{bucket}/form/{uid}'
'GET /api/v2/{bucket}/member/{uid}'
'GET /api/v2/{bucket}/member/{uid}/detail'
'GET /api/v2/{bucket}/organisation/{uid}/communications/detail'
'GET /api/v2/{bucket}/organisation/{uid}/detail'
'GET /api/v2/{bucket}/organisation/{uid}/gdpr/all'
'GET /api/v2/{bucket}/organisation/{uid}/membership/all'
'GET /api/v2/{bucket}/organisation/{uid}/summary'
'GET /api/v2/{bucket}/person/{uid}/communications/detail'
'GET /api/v2/{bucket}/person/{uid}/edi/detail'
'GET /api/v2/{bucket}/person/{uid}/edi/summary'
'GET /api/v2/{bucket}/person/{uid}/equalops/detail'
'GET /api/v2/{bucket}/person/{uid}/equalops/summary'
'GET /api/v2/{bucket}/person/{uid}/gdpr/all'
'GET /api/v2/{bucket}/person/{uid}/group/detail'
'GET /api/v2/{bucket}/person/{uid}/group/summary'
'GET /api/v2/{bucket}/person/{uid}/health/detail'
'GET /api/v2/{bucket}/person/{uid}/health/summary'
'GET /api/v2/{bucket}/person/{uid}/membership/all'
'GET /api/v2/{bucket}/person/{uid}/membership/summary'
'GET /api/v2/{bucket}/person/{uid}/personal/detail'
'GET /api/v2/{bucket}/person/{uid}/summary'
'GET /api/v2/{bucket}/person/{uid}/vehicles/all'
'GET /api/v2/{bucket}/person/{uid}/vehicles/detail'
'GET /api/v2/{bucket}/{resource_type}/{uid}/achievements/detail'
'GET /api/v2/{bucket}/{resource_type}/{uid}/achievements/summary'
'GET /api/v2/{bucket}/{resource_type}/{uid}/badges/detail'
'GET /api/v2/{bucket}/{resource_type}/{uid}/badges/summary'
'GET /api/v2/{bucket}/{resource_type}/{uid}/card'
'GET /api/v2/{bucket}/{resource_type}/{uid}/duplicates'
'GET /api/v2/{bucket}/{resource_type}/{uid}/form/detail'
'GET /api/v2/{bucket}/{resource_type}/{uid}/form/summary'
'GET /api/v2/{bucket}/{resource_type}/{uid}/evidence/detail'
'GET /api/v2/{bucket}/{resource_type}/{uid}/evidence/summary'
'PUT /api/v2/{bucket}/person/{uid}/summary'
'GET /api/v2/{bucket}/organisation/{uid}/finance/all'
'GET /api/v2/{bucket}/organisation/{uid}/finance/summary'
'GET /api/v2/{bucket}/person/{uid}/finance/all'
'GET /api/v2/{bucket}/person/{uid}/finance/summary'
'GET /api/v2/{bucket}/{resource_type}/{uid}/invoices/detail'
'GET /api/v2/{bucket}/{resource_type}/{uid}/invoices/summary'
'GET /api/v2/{bucket}/{resource_type}/{uid}/giving/all'
'GET /api/v2/{bucket}/{resource_type}/{uid}/giving/summary'
'GET /api/v2/{bucket}/{resource_type}/{uid}/documents/detail'
'GET /api/v2/{bucket}/{resource_type}/{uid}/documents/summary'
'GET /api/v2/{bucket}/{resource_type}/{uid}/messages/detail'
'GET /api/v2/{bucket}/{resource_type}/{uid}/messages/summary'
'GET /api/v2/{bucket}/{resource_type}/{uid}/notes/detail'
'GET /api/v2/{bucket}/{resource_type}/{uid}/notes/summary'
'GET /api/v2/{bucket}/{resource_type}/{uid}/tasks/detail'
'GET /api/v2/{bucket}/{resource_type}/{uid}/tasks/summary'
'GET /api/v2/selfservice/{bucket}/segment/{uid}/lookup'
'GET /api/v2/{bucket}/bookings'
'GET /api/v2/{bucket}/bookings/all'
'GET /api/v2/{bucket}/bookings/current'
'GET /api/v2/{bucket}/bookings/draft'
'GET /api/v2/{bucket}/bookings/future'
'GET /api/v2/{bucket}/bookings/past'
'GET /api/v2/{bucket}/bookings/running'
'GET /api/v2/{bucket}/group'
'GET /api/v2/{bucket}/group/all'
'GET /api/v2/{bucket}/group/{uid}/achievements'
'GET /api/v2/{bucket}/group/{uid}/achievements/{achievement_type_uid}'
'GET /api/v2/{bucket}/group/{uid}/members/all'
'GET /api/v2/{bucket}/group/{uid}/session/summary'
'GET /api/v2/{bucket}/group/{uid}/news'
'GET /api/v2/{bucket}/group/{uid}/tasks'
'GET /api/v2/{bucket}/group/{uid}/tasks/all'
'GET /api/v2/{bucket}/groups'
'GET /api/v2/{bucket}/reports/registry'
path: '/api/v2/{bucket}/booking/{uid}/attendance/export'
path: '/api/v2/{bucket}/group/{uid}/export'
path: '/api/v2/{bucket}/segment/{uid}/mailmerge'
path: '/api/v2/{bucket}/segment/{uid}/all/xlsx'
'GET /api/v2/{bucket}/{resource_type}/{uid}/download'
'POST /api/v2/partner/intercom/hook'
'POST /api/v2/partner/sparkpost/hook'
'POST /api/v2/partner/thesmsworks/hook'
'GET /api/v2/{bucket}/groupby/{resource_type}/{field}/count'
'GET /api/v2/{bucket}/distinct/{resource_type}/{field}'
'GET /api/v2/{bucket}/user/permissions'
'GET /api/v2/{bucket}/user/{uid}'
'GET /api/v2/{bucket}/users/detail'
'GET /api/v2/{bucket}/users/summary'
'GET /api/v2/{bucket}/user/{uid}/permissions'
'GET /api/v2/{bucket}/search/help'
'GET /api/v2/{bucket}/search'
path: /api/v2/{bucket}/lookup/{resource_type}
'GET /search/v2/{bucket}'
'GET /search/v2/{bucket}/help'
'GET /api/v2/{bucket}/audit'
'GET /api/v2/{bucket}/{resource_type}/{uid}/audit'


## Self Service
# Passes
0/1
'/v2/{bucket}/{resource_type}/{uid}/apple'

# PDF
3/3

# Public
1/1

# Self Service
0/50

'/v2/{bucket}/distinct/{resource_type}/{field}'
'/v2/{bucket}/invoices'
GET /v2/{bucket}/achievements
GET /v2/{bucket}/directory/members/
GET /v2/{bucket}/documents
GET /v2/{bucket}/donation/{appeal_uid}
GET /v2/{bucket}/donations
GET /v2/{bucket}/donations/all/
GET /v2/{bucket}/enum/{resource_type}/{field}
GET /v2/{bucket}/event/{event_uid}
POST /v2/{bucket}/event/{event_uid}
DELETE /v2/{bucket}/event/{event_uid}
GET /v2/{bucket}/event/{event_uid}/boxoffice
GET /v2/{bucket}/event/{event_uid}/tickets
GET /v2/{bucket}/events
GET /v2/{bucket}/feedback
GET /v2/{bucket}/forms
GET /v2/{bucket}/giving
GET /v2/{bucket}/giving/taxyear/{startyear}/{endyear}
GET /v2/{bucket}/interactions
GET /v2/{bucket}/message/{uid}
GET /v2/{bucket}/message/{uid}/acknowledge
GET /v2/{bucket}/message/{uid}/read
GET /v2/{bucket}/messages
GET /v2/{bucket}/messages/summary
GET /v2/{bucket}/order/{euid}
GET /v2/{bucket}/payment/{uid}
GET /v2/{bucket}/payments
GET /v2/{bucket}/payments/section/{section}
GET /v2/{bucket}/payments/summary
GET /v2/{bucket}/profile/public
PUT /v2/{bucket}/profile/public
GET /v2/{bucket}/profile/{resource_type}/{uid}
GET /v2/{bucket}/reservation/{uid}
GET /v2/{bucket}/reservations
GET /v2/{bucket}/reservations/future
GET /v2/{bucket}/segment/{uid}/lookup
GET /v2/{bucket}/team/{uid}
GET /v2/{bucket}/teams
GET /v2/{bucket}/vehicles/
GET /v2/{bucket}/vehicles/find
GET /v2/{bucket}/vehicles/{uid}
GET /v2/{bucket}/{resource_type}/{uid}/interactions
POST /v2/{bucket}/{resource_type}/{uid}/bookmark
DELETE /v2/{bucket}/{resource_type}/{uid}/bookmark
POST /v2/{bucket}/{resource_type}/{uid}/follow
DELETE /v2/{bucket}/{resource_type}/{uid}/follow
POST /v2/{bucket}/{resource_type}/{uid}/like
DELETE /v2/{bucket}/{resource_type}/{uid}/like