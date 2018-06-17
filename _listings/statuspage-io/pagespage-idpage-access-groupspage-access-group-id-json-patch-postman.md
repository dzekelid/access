{
  "info": {
    "name": "StatusPage.io Change information for a group",
    "_postman_id": "ed90b972-83ac-4133-906e-b1b80fcefe78",
    "description": "Change information for a group",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Pages",
      "item": [
        {
          "id": "26c64f80-5ead-4424-8604-091b891e79be",
          "name": "get-your-page-profile",
          "request": {
            "url": "http://example.com/api/pages/[page_id].json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get your page profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "581853ab-9df8-4142-b780-9c2ce2759ea4"
            }
          ]
        },
        {
          "id": "51ed672b-d9fd-4fa1-a578-70b6db148e2a",
          "name": "update-your-page-profile",
          "request": {
            "url": "http://example.com/api/pages/[page_id].json?basic layout only, 170x45 or 340x90 is best=basic%20layout%20only%2C%20170x45%20or%20340x90%20is%20best&page[allow_email_subscribers]=page%5Ballow_email_subscribers%5D&page[allow_incident_subscribers]=page%5Ballow_incident_subscribers%5D&page[allow_page_subscribers]=page%5Ballow_page_subscribers%5D&page[allow_sms_subscribers]=page%5Ballow_sms_subscribers%5D&page[city]=page%5Bcity%5D&page[country]=page%5Bcountry%5D&page[css_body_background_color]=page%5Bcss_body_background_color%5D&page[css_font_color]=page%5Bcss_font_color%5D&page[css_greens]=page%5Bcss_greens%5D&page[css_light_font_color]=page%5Bcss_light_font_color%5D&page[css_oranges]=page%5Bcss_oranges%5D&page[css_reds]=page%5Bcss_reds%5D&page[css_yellows]=page%5Bcss_yellows%5D&page[domain]=page%5Bdomain%5D&page[hero_cover_url]=page%5Bhero_cover_url%5D&page[layout]=page%5Blayout%5D&page[name]=page%5Bname%5D&page[notifications_from_email]=page%5Bnotifications_from_email%5D&page[state]=page%5Bstate%5D&page[subdomain]=page%5Bsubdomain%5D&page[time_zone]=page%5Btime_zone%5D&page[transactional_logo_url]=page%5Btransactional_logo_url%5D&page[url]=page%5Burl%5D&premium layout only, 850x315 or 1700x630 is best=premium%20layout%20only%2C%20850x315%20or%201700x630%20is%20best",
            "method": "PATCH",
            "body": {
              "mode": "raw"
            },
            "description": "Update your page profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "243472bc-2c88-49a2-ad3f-92f7958e37f4"
            }
          ]
        }
      ]
    },
    {
      "name": "Components",
      "item": [
        {
          "id": "d26082ad-6a02-436b-a2a3-a465e0465d31",
          "name": "get-a-list-of-all-components",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/components.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all components"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "debc121e-bab5-403a-b7a8-afadd8215510"
            }
          ]
        },
        {
          "id": "4a64d037-cd7f-4531-b29c-21a495d6d905",
          "name": "create-a-component",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/components.json?component[description]=component%5Bdescription%5D&component[group_id]=component%5Bgroup_id%5D&component[name]=component%5Bname%5D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a component"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f74df97-18f8-4c9a-8fbf-b4820f471acb"
            }
          ]
        },
        {
          "id": "022a20d2-b7ec-4746-9e16-76a94cd9c00b",
          "name": "delete-a-component",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/components/[component_id].json",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a component"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f9929af-b4bf-4787-b480-441f00243d64"
            }
          ]
        }
      ]
    },
    {
      "name": "Page Access Group",
      "item": [
        {
          "id": "c19e69df-9c5d-4356-bd31-ea3ddcddcf6c",
          "name": "update-a-component",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/components/[component_id].json?component[description]=component%5Bdescription%5D&component[name]=component%5Bname%5D&component[status]=component%5Bstatus%5D",
            "method": "PATCH",
            "body": {
              "mode": "raw"
            },
            "description": "Update a component"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d5a10179-b5ff-4d6b-89ab-ad38577b988f"
            }
          ]
        },
        {
          "id": "d2a9f9c0-7072-4611-846c-3d37928edae5",
          "name": "retrieve-a-list-of-groups",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_groups.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a list of groups"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d2c810a-e08e-41ea-9c65-a84b6c9c12ed"
            }
          ]
        },
        {
          "id": "ee0301d5-73f4-4aed-a827-4a2104af0581",
          "name": "create-a-group-that-will-define-what-and-who-can-view-elements-of-your-status-page",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_groups.json?page_access_group[component_ids=%5B%22page_access_group%5Bcomponent_ids%22%5D&page_access_group[external_identifier]=page_access_group%5Bexternal_identifier%5D&page_access_group[metric_ids=%5B%22page_access_group%5Bmetric_ids%22%5D&page_access_group[name]=page_access_group%5Bname%5D&page_access_group[page_access_user_ids=%5B%22page_access_group%5Bpage_access_user_ids%22%5D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a group that will define what and who can view elements of your status page"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a0afa52-3b0b-4378-b82b-45505e44d1ac"
            }
          ]
        },
        {
          "id": "0a880d7d-4de8-4f8c-b29f-cda1ecbdbfae",
          "name": "change-information-for-a-group",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_groups/[page_access_group_id].json?page_access_group[component_ids=%5B%22page_access_group%5Bcomponent_ids%22%5D&page_access_group[external_identifier]=page_access_group%5Bexternal_identifier%5D&page_access_group[metric_ids=%5B%22page_access_group%5Bmetric_ids%22%5D&page_access_group[name]=page_access_group%5Bname%5D&page_access_group[page_access_user_ids=%5B%22page_access_group%5Bpage_access_user_ids%22%5D",
            "method": "PATCH",
            "body": {
              "mode": "raw"
            },
            "description": "Change information for a group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de0928c9-3c4b-4009-a070-e55cae1f3680"
            }
          ]
        }
      ]
    },
    {
      "name": "Incidents",
      "item": [
        {
          "id": "9715c700-bd66-4962-8e52-8b7577d98dbc",
          "name": "get-a-list-of-all-incidents",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all incidents"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a575190-ed6e-4dcb-8146-209aeeecb54a"
            }
          ]
        },
        {
          "id": "4175630b-e6e4-4303-b873-805e7ef86f56",
          "name": "create-a-realtime-incident",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents.json?incident[backfilled]=incident%5Bbackfilled%5D&incident[backfill_date]=incident%5Bbackfill_date%5D&incident[component_ids]=incident%5Bcomponent_ids%5D&incident[impact_override]=incident%5Bimpact_override%5D&incident[message]=incident%5Bmessage%5D&incident[name]=incident%5Bname%5D&incident[scheduled_auto_completed]=incident%5Bscheduled_auto_completed%5D&incident[scheduled_auto_in_progress]=incident%5Bscheduled_auto_in_progress%5D&incident[scheduled_for]=incident%5Bscheduled_for%5D&incident[scheduled_remind_prior]=incident%5Bscheduled_remind_prior%5D&incident[scheduled_until]=incident%5Bscheduled_until%5D&incident[status]=incident%5Bstatus%5D&incident[wants_twitter_update]=incident%5Bwants_twitter_update%5D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a realtime incident"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a95459f-eb00-4dea-ae6f-ed6663db3fc8"
            }
          ]
        },
        {
          "id": "b8dd1dd8-bd5f-4732-a3ba-2d628a193b7f",
          "name": "unresolved-only",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents/unresolved.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unresolved Only"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "407444bf-f55a-4a71-807e-a865ba5eb82e"
            }
          ]
        },
        {
          "id": "263c7f18-0bb9-48f6-936a-8bdf638b5273",
          "name": "scheduled-only",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents/scheduled.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Scheduled Only"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e457c5e1-1af7-448c-8442-aa1506909e46"
            }
          ]
        },
        {
          "id": "1b3a6747-a8f7-439e-b8e7-77a0a5391f10",
          "name": "delete-an-incident",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents/[incident_id].json",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete an incident"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ffc585fc-52e4-4fc3-badc-52bfb90dc6e3"
            }
          ]
        },
        {
          "id": "5c558117-6c4a-494f-9355-2ed917c7e5b0",
          "name": "update-an-incident-only-applies-to-realtime-and-scheduled-incidents",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents/[incident_id].json?at the same time to avoid two separate incident updates being generated.=at%20the%20same%20time%20to%20avoid%20two%20separate%20incident%20updates%20being%20generated.&ENDPOINT=ENDPOINT&incident[component_ids]=incident%5Bcomponent_ids%5D&incident[impact_override]=incident%5Bimpact_override%5D&incident[message]=incident%5Bmessage%5D&incident[name]=incident%5Bname%5D&incident[status]=incident%5Bstatus%5D&incident[wants_twitter_update]=incident%5Bwants_twitter_update%5D&MUTABLE=MUTABLE&PATCH /pages/[page_id]/incidents/[incident_id].json=PATCH%20%2Fpages%2F%5Bpage_id%5D%2Fincidents%2F%5Bincident_id%5D.json",
            "method": "PATCH",
            "body": {
              "mode": "raw"
            },
            "description": "Update an incident (only applies to realtime and scheduled incidents)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6cf9b4ff-d26c-4ad2-97dd-6de20856ae87"
            }
          ]
        },
        {
          "id": "b1819cfb-7ff3-4cca-82bf-147a6944c2e6",
          "name": "tune-an-incident-update",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/incidents/[incident_id]/incident_updates/[incident_update_id].json?incident_update[body]=incident_update%5Bbody%5D&incident_update[display_at]=incident_update%5Bdisplay_at%5D",
            "method": "PATCH",
            "body": {
              "mode": "raw"
            },
            "description": "Tune an Incident Update"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fd117fd9-6ce8-4a6a-8393-58214ef1632c"
            }
          ]
        }
      ]
    },
    {
      "name": "Subscribers",
      "item": [
        {
          "id": "c5c3b440-1955-451d-9fec-8148956c0916",
          "name": "delete-a-subscriber",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/subscribers/[subscriber_id].json",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a subscriber"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e2b7f48-06af-42ab-9a4d-3347e196541d"
            }
          ]
        }
      ]
    },
    {
      "name": "Metrics",
      "item": [
        {
          "id": "7007a4d1-2373-41b4-863b-61d33078a981",
          "name": "get-a-list-of-available-public-metric-providers",
          "request": {
            "url": "http://example.com/api/metrics_providers.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of available public metric providers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7da2e57b-223a-48dc-8d45-fc014e6109a0"
            }
          ]
        },
        {
          "id": "255c82e6-9c9c-40b5-874d-ea312a39694c",
          "name": "submit-data-for-a-custom-metric",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/metrics/[metric_id]/data.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Submit data for a custom metric"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fbd0c88-9e4a-4f00-8e9a-ce845c856f85"
            }
          ]
        },
        {
          "id": "56f0b1ba-45e4-4da8-8d0a-7c341386c41b",
          "name": "delete-all-data-for-a-custom-metric",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/metrics/[metric_id]/data.json",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete all data for a custom metric"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "48286545-b7f3-4893-b28f-474a5f1541c2"
            }
          ]
        }
      ]
    },
    {
      "name": "Metric Providers",
      "item": [
        {
          "id": "92c4b0f4-868b-4cad-a82b-0dec255cab7a",
          "name": "get-a-list-of-metric-providers-linked-to-your-page",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/metrics_providers.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of metric providers linked to your page"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3909e291-2aa2-4d97-911f-2e75059502ac"
            }
          ]
        },
        {
          "id": "247eba09-83d6-4bf2-9950-f8dc2fd64d9b",
          "name": "get-a-list-of-metrics-created-for-a-linked-metrics-provider",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/metrics_providers/[metrics_provider_id]/metrics.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of metrics created for a linked metrics provider"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "75c7b6cd-d7ae-442d-b189-54feab8be635"
            }
          ]
        },
        {
          "id": "3b9f927f-16a4-42bc-a585-b640dd42a351",
          "name": "create-a-custom-metric",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/metrics_providers/[metrics_provider_id]/metrics.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a custom metric"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c0a16df-fb85-4b11-b14e-7fb1c1da2a72"
            }
          ]
        }
      ]
    },
    {
      "name": "Organizations",
      "item": [
        {
          "id": "4871f4a6-48a6-47a5-9c8d-f8be5d984cb2",
          "name": "list-users",
          "request": {
            "url": "http://example.com/api/organizations/[organization_id]/users.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List users"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "192f336b-6b0f-4c60-9f23-1e61acf85ea4"
            }
          ]
        },
        {
          "id": "7bd45254-ce26-4851-b203-da4a4cbda46a",
          "name": "create-a-user",
          "request": {
            "url": "http://example.com/api/organizations/[organization_id]/users.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1216c125-baea-4a50-862c-123120e70e0c"
            }
          ]
        },
        {
          "id": "8e9c49f4-2b4c-42d4-b038-3d98cde35692",
          "name": "delete-a-user",
          "request": {
            "url": "http://example.com/api/organizations/[organization_id]/users/[user_id].json",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74b483b2-2fd4-4630-abd4-642f435b65aa"
            }
          ]
        }
      ]
    },
    {
      "name": "Page Access Users",
      "item": [
        {
          "id": "5c52960f-f1e7-4d6d-964a-50ed847b46f2",
          "name": "retrieve-a-list-of-users",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_users.json?email=email",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a list of users"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db20affd-6cf5-4fcf-b367-91dcceb8b94f"
            }
          ]
        },
        {
          "id": "84c09fc7-d3c1-4caf-8e71-1d6ca027831f",
          "name": "create-a-user-who-can-view-your-status-page",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_users.json?page_access_user[component_ids=%5B%22page_access_user%5Bcomponent_ids%22%5D&page_access_user[email]=page_access_user%5Bemail%5D&page_access_user[external_login]=page_access_user%5Bexternal_login%5D&page_access_user[metric_ids=%5B%22page_access_user%5Bmetric_ids%22%5D&page_access_user[page_access_group_ids=%5B%22page_access_user%5Bpage_access_group_ids%22%5D&page_access_user[subscribe_to_components]=page_access_user%5Bsubscribe_to_components%5D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a user who can view your status page"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6caeb8f9-9507-48df-81d0-d9b1b7d95b08"
            }
          ]
        },
        {
          "id": "e9381ffb-a429-4a91-b0d9-b91303531df8",
          "name": "delete-a-user-who-could-access-your-status-page",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_users/[page_access_user_id].json",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a user who could access your status page"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae08431e-abf9-487d-8943-bdeb3fdfe96d"
            }
          ]
        },
        {
          "id": "6bbff0a3-a156-4560-a6ce-454e32e5dbd9",
          "name": "change-information-for-a-user-who-can-view-your-status-page",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_users/[page_access_user_id].json?page_access_user[component_ids=%5B%22page_access_user%5Bcomponent_ids%22%5D&page_access_user[email]=page_access_user%5Bemail%5D&page_access_user[external_login]=page_access_user%5Bexternal_login%5D&page_access_user[metric_ids=%5B%22page_access_user%5Bmetric_ids%22%5D&page_access_user[page_access_group_ids=%5B%22page_access_user%5Bpage_access_group_ids%22%5D",
            "method": "PATCH",
            "body": {
              "mode": "raw"
            },
            "description": "Change information for a user who can view your status page"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "344f5453-5a80-4fe6-a5fd-a9048b178926"
            }
          ]
        },
        {
          "id": "dd9610f8-3969-4e1a-8a9a-1b2115faea59",
          "name": "assign-components-to-a-page-access-user-overwrites-existing-components",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_users/[page_access_user_id]/components.json?component_ids=%5B%22component_ids%22%5D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Assign components to a page access user (overwrites existing components)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19c512c0-b56d-44c0-99fd-8e630adc2b4d"
            }
          ]
        },
        {
          "id": "e7b94392-90d3-4b79-9665-2eeff57ebffa",
          "name": "remove-all-components-from-a-page-access-user",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_users/[page_access_user_id]/components.json",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove all components from a page access user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b9d0349-cb29-48fc-bddd-e4c3ad684a64"
            }
          ]
        },
        {
          "id": "a178bfd9-f6bd-4ec5-9468-11dbee3c6b8e",
          "name": "assign-components-to-a-page-access-user-adds-new-components-to-a-user",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_users/[page_access_user_id]/components.json?component_ids=%5B%22component_ids%22%5D",
            "method": "PATCH",
            "body": {
              "mode": "raw"
            },
            "description": "Assign components to a page access user (adds new components to a user)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "81a605df-1dc2-4cf4-a7e6-6080c3f0ed72"
            }
          ]
        },
        {
          "id": "6b4fa8bb-c5f6-4b7f-ae74-c1de080e08aa",
          "name": "assign-page-access-users-to-a-component",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/components/[component_id]/page_access_users.json?page_access_user_ids=%5B%22page_access_user_ids%22%5D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Assign page access users to a component"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "faddea26-01d5-4fdd-b2df-21333e54aa87"
            }
          ]
        },
        {
          "id": "3e29c86d-4ed7-493a-a200-08c6d5bc4b6a",
          "name": "remove-a-component-from-all-page-access-users",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/components/[component_id]/page_access_users.json",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a component from all page access users"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15f36188-cf19-4f31-8106-8ea5dcb7e8aa"
            }
          ]
        }
      ]
    }
  ]
}