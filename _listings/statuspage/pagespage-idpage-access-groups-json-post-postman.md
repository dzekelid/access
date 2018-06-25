{
  "info": {
    "name": "StatusPage.io Create a group that will define what and who can view elements of your status page",
    "_postman_id": "7993cc44-e1d9-425d-a8d8-3ea7717a3696",
    "description": "Create a group that will define what and who can view elements of your status page",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Pages",
      "item": [
        {
          "id": "08966758-13ea-417b-90f8-86dc56ab2e5e",
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
              "id": "4a163d88-5cba-44e1-9207-f3fe9a669f1f"
            }
          ]
        },
        {
          "id": "87886b0f-457d-4136-83a4-8506ed426259",
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
              "id": "7666d3de-5531-46b5-afc9-6a71309292c6"
            }
          ]
        }
      ]
    },
    {
      "name": "Components",
      "item": [
        {
          "id": "7749dbd6-8d44-432f-acbf-3b17dcf233c2",
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
              "id": "21e85624-5d56-482b-a7c8-b93eeb15f606"
            }
          ]
        },
        {
          "id": "d7cd84e2-b0fa-4014-976b-b8c7821c809d",
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
              "id": "d949ba6a-7c9c-442f-be3e-6e7505deac6b"
            }
          ]
        },
        {
          "id": "53011d79-3c83-4bc5-8432-59ae9c9c56d8",
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
              "id": "165787f2-64bd-4fe9-9a47-e5ed7929d50a"
            }
          ]
        }
      ]
    },
    {
      "name": "Page Access Group",
      "item": [
        {
          "id": "4bad78d1-efba-4798-91ba-1194e824588b",
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
              "id": "826b1cda-080d-4714-aa9c-4946b7d1c256"
            }
          ]
        },
        {
          "id": "ae6196ba-00e5-418a-ac21-9569396947e1",
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
              "id": "c81e0ade-ade7-4a9a-abf6-1dc98c4db853"
            }
          ]
        },
        {
          "id": "cf3af7a0-5b39-4a48-a9c7-ab6e8843b9f9",
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
              "id": "d3df39f7-2a6a-49e7-a739-d67725fe34d8"
            }
          ]
        }
      ]
    },
    {
      "name": "Incidents",
      "item": [
        {
          "id": "1bdeb100-58cf-4f26-965b-9d0cdd3bfa83",
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
              "id": "7fcfe35e-8a25-4988-8004-21b6021e3eb2"
            }
          ]
        },
        {
          "id": "3d35927e-b2bc-4f85-a3b3-0e7140bd9c84",
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
              "id": "b04888df-b05d-401f-802e-651f1227fdea"
            }
          ]
        },
        {
          "id": "0aa73b44-75ec-470c-ae64-81a2d7616000",
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
              "id": "04472513-80bc-4955-be07-489a214b5286"
            }
          ]
        },
        {
          "id": "c9e11404-ccea-46e5-aeb1-a17d2d1c3255",
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
              "id": "05ef060e-e35a-48ad-bb37-62932ce4247e"
            }
          ]
        },
        {
          "id": "07bf4e79-1af1-4bc1-afbc-5c34d116a1bc",
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
              "id": "87982aab-8334-4939-b291-aa022e48e3bc"
            }
          ]
        },
        {
          "id": "1030dd92-b451-458b-8a10-43cc1c4955d7",
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
              "id": "7a5bd877-01f2-4a99-88d5-7860e27a7d3b"
            }
          ]
        },
        {
          "id": "47c6b1d0-bcd0-4c7b-b3c4-d3d013d304c7",
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
              "id": "365f2f75-a34d-4b1c-809b-7dfde5cc9839"
            }
          ]
        }
      ]
    },
    {
      "name": "Subscribers",
      "item": [
        {
          "id": "cfb4daaf-841c-4857-8d8b-744d5db593fc",
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
              "id": "dea137f3-1bc8-437a-9f7b-33f1e0798a38"
            }
          ]
        }
      ]
    },
    {
      "name": "Metrics",
      "item": [
        {
          "id": "c801450e-c178-43c7-b270-89b06e08dee2",
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
              "id": "d2e6b3c1-01f7-42e7-ac90-d5d20f6431a6"
            }
          ]
        },
        {
          "id": "4ea26f8a-7eda-4c32-bbf3-b47eefd6a1b6",
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
              "id": "eec67db9-d599-48aa-8606-80ec3174ebff"
            }
          ]
        },
        {
          "id": "2153cd9b-fe69-4991-85a2-3c52333150a1",
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
              "id": "e324dbf2-fbb1-4317-9c65-276eb778cfb1"
            }
          ]
        }
      ]
    },
    {
      "name": "Metric Providers",
      "item": [
        {
          "id": "7d9301eb-060d-4144-95a2-786596f74a71",
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
              "id": "f9c45a6c-d654-4e69-a814-1db770f3f5ec"
            }
          ]
        },
        {
          "id": "d7488e11-06a5-4498-a817-a9ec76d539f2",
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
              "id": "38a8699b-0b5e-4750-87ff-5201caf55e87"
            }
          ]
        },
        {
          "id": "92b2253d-b86b-4a94-8be7-95845ea4d084",
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
              "id": "1a614fe8-7846-4345-9386-3fc0c0fd8546"
            }
          ]
        }
      ]
    },
    {
      "name": "Organizations",
      "item": [
        {
          "id": "08eb1c69-62c0-48fb-a644-54ec982a799b",
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
              "id": "50ed83b7-3ec2-4196-a544-7bc26d453086"
            }
          ]
        },
        {
          "id": "1dfe9623-235d-4799-aee4-67078d7f63c8",
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
              "id": "6bcb3cff-adbb-47e7-a6e8-ed72f39873e2"
            }
          ]
        },
        {
          "id": "2217680e-6cfd-4bf9-8f32-02fee709ad92",
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
              "id": "8099be24-aa7b-47cb-a834-47a701a1ab87"
            }
          ]
        }
      ]
    },
    {
      "name": "Page Access Users",
      "item": [
        {
          "id": "e1097a5d-6147-49a0-8f2e-e075bca31f54",
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
              "id": "f95b621c-2e0f-4c99-8206-add8678ac0f2"
            }
          ]
        },
        {
          "id": "ce729bed-f788-4ac1-b193-50d814e6b58f",
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
              "id": "c680c77e-b1d3-4896-a491-ecb4a9c0a68f"
            }
          ]
        },
        {
          "id": "72638801-1dd5-4e5f-ab3e-de7ca6174249",
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
              "id": "3b6c4913-c501-4346-89a9-5912907366e6"
            }
          ]
        },
        {
          "id": "b3bb3766-1820-497d-ad2a-d92c196c8655",
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
              "id": "004aeb20-1749-43b0-87a6-d0c010e3a217"
            }
          ]
        },
        {
          "id": "9aa6325e-993a-43a8-adac-62329a4e0ee1",
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
              "id": "a7eda002-8aba-43b3-b017-dc84a4eb19f5"
            }
          ]
        },
        {
          "id": "831399b6-19c6-444b-8fed-d0c9adc44889",
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
              "id": "4c9e20b3-fcf8-425e-bb9a-0bdbd84e0786"
            }
          ]
        },
        {
          "id": "ca98592c-ad5e-47fb-8f01-982ad5247de9",
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
              "id": "5f48b3a1-feff-4cef-89a3-bd8b356dac76"
            }
          ]
        },
        {
          "id": "d6c3b0bd-82c3-4969-8803-eacf505d654e",
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
              "id": "08fe928b-57ed-44ec-a329-ff19642dd877"
            }
          ]
        },
        {
          "id": "172e3784-9c14-4a6e-81ac-49f210811efc",
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
              "id": "d2da1c69-388b-4a12-994d-6a965196b69f"
            }
          ]
        }
      ]
    }
  ]
}