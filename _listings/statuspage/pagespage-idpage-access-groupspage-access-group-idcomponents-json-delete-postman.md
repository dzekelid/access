{
  "info": {
    "name": "StatusPage.io Remove all components from a page access group",
    "_postman_id": "a972c90c-ae3e-47ec-8404-af6d81fae518",
    "description": "Remove all components from a page access group",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Pages",
      "item": [
        {
          "id": "607f275e-3263-455c-ad99-d77a049a1f41",
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
              "id": "c1f57a50-3e5f-4221-83b9-1b96404750e2"
            }
          ]
        },
        {
          "id": "d23e6d11-709f-4240-84ec-5471b7153536",
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
              "id": "64105bb7-31bc-46b4-9a11-db2faa30b44d"
            }
          ]
        }
      ]
    },
    {
      "name": "Components",
      "item": [
        {
          "id": "2daa25e0-34b1-4d55-9cbb-76d528e32d97",
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
              "id": "aee2e7fa-63bf-48b2-abe7-a65167cdff9e"
            }
          ]
        },
        {
          "id": "4fd92a27-a83a-44e6-a61b-78e86731079c",
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
              "id": "7837872c-6e9e-472d-baed-bccfc88c8b4a"
            }
          ]
        },
        {
          "id": "31d74464-854f-472a-9f2a-753ca1af8de2",
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
              "id": "853647cc-5d83-4f9e-906f-4e06f92c9494"
            }
          ]
        }
      ]
    },
    {
      "name": "Page Access Group",
      "item": [
        {
          "id": "0c7a0d4e-c526-4246-bcad-a6eaf75462d0",
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
              "id": "acf12279-fd8b-4333-9ce5-aceb95be54cd"
            }
          ]
        },
        {
          "id": "fbd9b29e-8a75-4a57-812a-af12c6ab0a47",
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
              "id": "c708a7ac-431b-4493-90f0-85cd6a737bd6"
            }
          ]
        },
        {
          "id": "79b1d3bf-dc2f-4acf-91ad-669c1bab324a",
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
              "id": "88673c64-ec36-488e-a7a9-5e6fc2bef596"
            }
          ]
        },
        {
          "id": "aec67dde-b1fc-4b7a-a5c6-c6ce6ae299fe",
          "name": "delete-a-group",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_groups/[page_access_group_id].json?page_access_group[orphan_mode]=page_access_group%5Borphan_mode%5D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4d901586-62ae-48cb-8319-f13ff45312f7"
            }
          ]
        },
        {
          "id": "61f93364-20e4-4d11-86b7-fd0ae7965b58",
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
              "id": "de60459d-8b16-45e8-a443-34ff57be7210"
            }
          ]
        },
        {
          "id": "fe9793b4-aba4-4869-b473-92ea2be74dbc",
          "name": "assign-components-to-a-page-access-group-overwrites-existing-components",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_groups/[page_access_group_id]/components.json?component_ids=%5B%22component_ids%22%5D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Assign components to a page access group (overwrites existing components)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d4425fb8-046f-49c0-aff9-35761ee1b04b"
            }
          ]
        },
        {
          "id": "08ba79fe-d3bc-4f54-afad-cd0ca4f9b24b",
          "name": "remove-all-components-from-a-page-access-group",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_groups/[page_access_group_id]/components.json",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove all components from a page access group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ccf446fb-289a-4160-a164-f19e752998e4"
            }
          ]
        },
        {
          "id": "8af3f030-2313-44db-be24-eae82c41acec",
          "name": "assign-components-to-a-page-access-group-adds-new-components-to-a-group",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/page_access_groups/[page_access_group_id]/components.json?component_ids=%5B%22component_ids%22%5D",
            "method": "PATCH",
            "body": {
              "mode": "raw"
            },
            "description": "Assign components to a page access group (adds new components to a group)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b62723b-8f29-425b-a831-1056d9b7952c"
            }
          ]
        }
      ]
    },
    {
      "name": "Incidents",
      "item": [
        {
          "id": "fbbad50e-a46e-4d6a-92fc-70c59c8f17d1",
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
              "id": "9331b5a1-5d28-4bb7-84ed-6bcc13ae7238"
            }
          ]
        },
        {
          "id": "11d47340-8359-4984-b675-3937473c2af4",
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
              "id": "d81b7905-0621-4023-9f7d-f57d2220d4df"
            }
          ]
        },
        {
          "id": "31165fdb-c45c-4de4-8a8f-66c11ccccfdb",
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
              "id": "dd9f0873-5032-4eb2-b980-74c9980739d3"
            }
          ]
        },
        {
          "id": "6396d8f1-508d-46b7-a1ca-1a89eb6ac0e4",
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
              "id": "6a3716d7-bafc-47b5-87b1-b8583590f751"
            }
          ]
        },
        {
          "id": "804f5ffd-431c-47a6-8119-a58ed6b10458",
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
              "id": "60dfa085-5e74-4114-bf5d-403519aea318"
            }
          ]
        },
        {
          "id": "c38efc2c-dcb2-4532-916e-aa43a6397c6b",
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
              "id": "b8fe60f4-391d-409f-85a6-4beedd414bae"
            }
          ]
        },
        {
          "id": "d836efcc-6565-4a9d-88a7-986935ad5f69",
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
              "id": "76613330-65f4-43e7-91b3-3a25fd7a1cda"
            }
          ]
        }
      ]
    },
    {
      "name": "Subscribers",
      "item": [
        {
          "id": "6243038a-86e4-481b-b2f7-978e4ac1e75a",
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
              "id": "876aa468-019c-4c08-b670-7cb3fa1b7ff6"
            }
          ]
        }
      ]
    },
    {
      "name": "Metrics",
      "item": [
        {
          "id": "52cfbd51-e896-4069-a83f-a8b4c32c21aa",
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
              "id": "cd8a6811-2d88-4c74-906e-be5974b5a68b"
            }
          ]
        },
        {
          "id": "e07ab8d4-4b26-40bc-bb46-f607ee80184f",
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
              "id": "5e795e1e-d9f7-48a7-a3df-d7eee9345162"
            }
          ]
        },
        {
          "id": "ffa63d80-bdef-4f6f-bc7e-6a5e9ed74a34",
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
              "id": "379d8a0c-1796-4466-9149-1313b590372f"
            }
          ]
        }
      ]
    },
    {
      "name": "Metric Providers",
      "item": [
        {
          "id": "3408091e-7777-45f9-8b1b-6e5271fa8e41",
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
              "id": "6ba9969d-b6a0-41be-bf11-f85d263a9ae2"
            }
          ]
        },
        {
          "id": "a4d5525c-88c1-4db2-81cb-391ad9b3da99",
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
              "id": "96cac60f-18d2-474d-98f3-49dd962b7cc9"
            }
          ]
        },
        {
          "id": "e3d8b1ba-36a8-4c7b-8f83-d4a9645cdc17",
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
              "id": "aeb66965-f155-459f-9f5c-118969c9fbf9"
            }
          ]
        }
      ]
    },
    {
      "name": "Organizations",
      "item": [
        {
          "id": "fcd9d093-e45f-4ace-8f13-d707db7188d3",
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
              "id": "7560fb0c-e804-49e4-98fb-3a5a708f605d"
            }
          ]
        },
        {
          "id": "489fa43c-cfec-43d1-a6a0-7e5e21c583fa",
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
              "id": "9d188b49-3537-4b64-85d1-5fab40c24912"
            }
          ]
        },
        {
          "id": "b16d7f7d-5e1b-494d-abc2-a2c53969c460",
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
              "id": "47e53f2b-190e-491a-bbe4-5e3c6558158e"
            }
          ]
        }
      ]
    },
    {
      "name": "Page Access Users",
      "item": [
        {
          "id": "54bed867-6a58-40a1-9d92-6714955727f6",
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
              "id": "2bc9e3e5-6142-4fbd-bee5-d65e5280549d"
            }
          ]
        },
        {
          "id": "014eba40-4515-42d2-9db0-8d7687ba5e7c",
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
              "id": "fdfa1b69-2fd4-4aea-a7fa-fa41ddf36690"
            }
          ]
        },
        {
          "id": "0342ea8a-6af4-48e4-869b-4adfe4aebd0f",
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
              "id": "fac4ac4d-ad40-4d74-bf1c-17cc2869348b"
            }
          ]
        },
        {
          "id": "1d7348cf-6df4-4795-b278-dcee20884473",
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
              "id": "3d760883-8521-4906-b5ae-56c4edc9935b"
            }
          ]
        },
        {
          "id": "041be5ed-f8d9-4714-aee4-08413cbbf85a",
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
              "id": "b7d0f8b1-6ab1-482f-ae6c-f9b5db37ec56"
            }
          ]
        },
        {
          "id": "4579f30a-1272-44b8-a982-658daeab5c01",
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
              "id": "0a252d6d-6ea4-4294-8b1d-152af8a8ad7f"
            }
          ]
        },
        {
          "id": "dbb979fb-7ae9-449e-9644-1d54808691d1",
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
              "id": "11bc49cd-1b50-47c6-a6cc-b455553b63fe"
            }
          ]
        },
        {
          "id": "50735b9a-c442-4121-b312-a0683f8a221d",
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
              "id": "d2478c7d-f7b2-4f9f-a9ee-11bed945996e"
            }
          ]
        },
        {
          "id": "ffd364b8-cb76-4c66-a569-71f1604a3e43",
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
              "id": "2544cb0a-d916-41d1-8890-118dd04cf22e"
            }
          ]
        }
      ]
    }
  ]
}