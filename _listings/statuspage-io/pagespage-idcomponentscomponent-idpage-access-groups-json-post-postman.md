{
  "info": {
    "name": "StatusPage.io Assign page access groups to a component",
    "_postman_id": "e5b75100-ecee-49a2-9721-26d56ffd9fa6",
    "description": "Assign page access groups to a component",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Pages",
      "item": [
        {
          "id": "90cd8112-b540-409b-8076-ffeda61acd79",
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
              "id": "57fda04c-1164-4e55-885d-da7e1544d6aa"
            }
          ]
        },
        {
          "id": "fe7d4968-f517-4012-b203-4793f398444f",
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
              "id": "d0fbee55-98a6-4e72-a8f5-2c1dd1bc62f4"
            }
          ]
        }
      ]
    },
    {
      "name": "Components",
      "item": [
        {
          "id": "f2d02293-1914-4e01-b595-c5bcdafdebba",
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
              "id": "acc76d51-539d-4a3f-ba7a-e92dc76ca15c"
            }
          ]
        },
        {
          "id": "eca5f399-c828-444d-b53d-8e06d5241948",
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
              "id": "761e47a4-a940-4704-9e6f-ef01c6805dd9"
            }
          ]
        },
        {
          "id": "826aa74e-3215-4815-9e88-687973415ae9",
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
              "id": "b96541ec-eeb5-4ebe-99a8-8b83e0c0c077"
            }
          ]
        }
      ]
    },
    {
      "name": "Page Access Group",
      "item": [
        {
          "id": "0fab4840-de80-4fdc-93e7-8d4e04a7b593",
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
              "id": "0266ed82-9c6e-4d4f-b27b-f476609495d6"
            }
          ]
        },
        {
          "id": "9d0a972b-8b1c-422d-a855-d20754b3ef39",
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
              "id": "bf0c38e0-c3e7-46d5-ae05-52ba60c8a514"
            }
          ]
        },
        {
          "id": "a2afe234-a71c-4ca9-8579-7a7fe67a5cb6",
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
              "id": "537873ce-71ec-4a34-a128-1d4af200b3ec"
            }
          ]
        },
        {
          "id": "4c29727d-0437-46f0-874d-7407626f746d",
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
              "id": "bd7dfe69-8806-4097-b753-03c8dc464f8c"
            }
          ]
        },
        {
          "id": "3fb11619-3a70-4abe-a281-3d36ef482891",
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
              "id": "259bcec6-d961-46cd-8792-b1fe17b18d4b"
            }
          ]
        },
        {
          "id": "1f59ce19-c50a-46a9-8087-9a7cf2eb3e6c",
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
              "id": "91935e58-73f7-43c0-abdc-bbb8218c0aaf"
            }
          ]
        },
        {
          "id": "f824c3b3-ab50-4b17-95c3-a20429a3e337",
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
              "id": "ee7e8f8c-ee45-4f28-a9f3-db4d09091e8e"
            }
          ]
        },
        {
          "id": "d70fe135-3534-470c-9100-61667a34dc1e",
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
              "id": "8fba5567-1c37-4801-a238-46dabfb4d67d"
            }
          ]
        }
      ]
    },
    {
      "name": "Incidents",
      "item": [
        {
          "id": "b9300964-c3a2-45ac-ad44-d42937f6b80a",
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
              "id": "70b5e377-fd58-4aaa-8525-3ff5f767fa85"
            }
          ]
        },
        {
          "id": "539bc5d5-afc7-4009-a5bc-8e8a06a86698",
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
              "id": "c514ef03-f1de-4ccd-8727-302c3d84b339"
            }
          ]
        },
        {
          "id": "799f2383-278b-4c0b-9a54-5cbb427b0789",
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
              "id": "77a15b74-30ec-4151-b17b-dbf3434c3587"
            }
          ]
        },
        {
          "id": "b0f83d8f-fe75-48e0-9b43-cb47b0804edc",
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
              "id": "8b255d5d-32d9-4769-83ba-c1b4746bb20f"
            }
          ]
        },
        {
          "id": "8b188d5f-5d71-4de8-ad56-2fcc8d0a00b6",
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
              "id": "ab8ecfbb-33d6-4c94-be3e-a66d48485dae"
            }
          ]
        },
        {
          "id": "98669b7b-e848-4276-abab-f2d930d49696",
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
              "id": "89fb96f3-f719-44bc-ae8b-6fffacd392d4"
            }
          ]
        },
        {
          "id": "620af9e9-4fa4-414a-9402-58269d401c56",
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
              "id": "4b2a34e0-b1f6-444d-9e1e-2f67571411ba"
            }
          ]
        }
      ]
    },
    {
      "name": "Subscribers",
      "item": [
        {
          "id": "123a0627-4343-455e-84e7-455716362fbc",
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
              "id": "696fea18-ddef-426e-96ce-65cf8572a82f"
            }
          ]
        }
      ]
    },
    {
      "name": "Metrics",
      "item": [
        {
          "id": "3b6f1fd4-3029-452d-a924-010effd1fc5b",
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
              "id": "5205c6f1-f79d-432c-b9f2-a4dade284e52"
            }
          ]
        },
        {
          "id": "d674100b-c6c7-413a-b306-9c9db241b15d",
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
              "id": "b1bf4c52-c0ba-444e-8bda-6f3e835f582d"
            }
          ]
        },
        {
          "id": "99d77db7-0a35-421c-96e0-4736c832da31",
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
              "id": "8b424278-33eb-4ada-95bc-ba4f60323420"
            }
          ]
        }
      ]
    },
    {
      "name": "Metric Providers",
      "item": [
        {
          "id": "d30fa70d-efc6-4857-8c67-fe7fb45c1a47",
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
              "id": "eaa1de3f-aa84-4803-89fd-ab88ae744770"
            }
          ]
        },
        {
          "id": "e2d81f55-2faa-4676-80f9-7e6162be845b",
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
              "id": "65be32f6-5793-469f-bf4f-fd16ee70fd2f"
            }
          ]
        },
        {
          "id": "d1fcc96b-9e7d-4651-86f1-cdf6c7ee8de7",
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
              "id": "5553144e-147c-48fa-88ee-8d56dba6cf29"
            }
          ]
        }
      ]
    },
    {
      "name": "Organizations",
      "item": [
        {
          "id": "9d22d437-db64-4aeb-b9e9-30c0191b6a78",
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
              "id": "e1b64d1e-f72b-4096-83ff-991dea417895"
            }
          ]
        },
        {
          "id": "a52e0100-f5ad-44a9-8e76-e6fee22bc6bc",
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
              "id": "9204862c-1a07-4f80-b890-462fba928b97"
            }
          ]
        },
        {
          "id": "04f7c30d-f6f6-4dac-9ae4-2925a81b456e",
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
              "id": "aee080cf-3d25-4f25-bedb-c19c63c721bc"
            }
          ]
        }
      ]
    },
    {
      "name": "Page Access Users",
      "item": [
        {
          "id": "9f4d3311-b713-4a4f-9180-98bf932ef646",
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
              "id": "dec9ce8f-23a6-4ea9-9322-6889bba1cdd8"
            }
          ]
        },
        {
          "id": "15546ed8-dd28-4399-8c9d-5f70331348f4",
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
              "id": "9a9e3398-5f0a-4340-91ea-dba460e5a7b6"
            }
          ]
        },
        {
          "id": "315cdd51-ff49-42f9-9979-2185e27a70a0",
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
              "id": "d4d3c8b6-e9c3-46ea-8bfa-ed1fd0905436"
            }
          ]
        },
        {
          "id": "5641c9c5-8e9f-4038-8cf9-72245fb978ec",
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
              "id": "2a8a9b1c-53a5-4b79-8e22-12e1c75343a5"
            }
          ]
        },
        {
          "id": "b828eb48-8be9-41bc-a61e-545c2961888f",
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
              "id": "51538282-dcbb-4e86-9903-3e1c7c1fc4b9"
            }
          ]
        },
        {
          "id": "34f12ade-b028-46aa-a2b1-b3ee7c976752",
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
              "id": "b3d3dee2-1909-41ca-8942-8aa09e38d563"
            }
          ]
        },
        {
          "id": "445f62e1-cab1-49f8-9bd9-cf6313e5319a",
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
              "id": "660be5c9-9a56-4351-809e-8dd8ddaea1c3"
            }
          ]
        },
        {
          "id": "9c6931a6-4998-4ba4-996b-89c4c8aaa2fe",
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
              "id": "cfc2c64f-19cc-4d95-81d4-e740bba43398"
            }
          ]
        },
        {
          "id": "e4b023b3-5b83-4cc2-86ef-112f5a315366",
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
              "id": "bfbdeeb9-2e5c-45d6-990f-05b359622997"
            }
          ]
        },
        {
          "id": "c8848630-3b63-4f97-bdf4-73ecf9a05ebd",
          "name": "assign-page-access-groups-to-a-component",
          "request": {
            "url": "http://example.com/api/pages/[page_id]/components/[component_id]/page_access_groups.json?page_access_group_ids=%5B%22page_access_group_ids%22%5D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Assign page access groups to a component"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dcc94850-6983-4215-9d76-d4ad855225cd"
            }
          ]
        }
      ]
    }
  ]
}