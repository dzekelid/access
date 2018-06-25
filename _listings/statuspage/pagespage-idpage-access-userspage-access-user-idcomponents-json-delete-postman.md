{
  "info": {
    "name": "StatusPage.io Remove all components from a page access user",
    "_postman_id": "212bb445-9d93-40cb-a32c-81b18c7f84b0",
    "description": "Remove all components from a page access user",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Pages",
      "item": [
        {
          "id": "946fecf6-8fc2-45db-80ac-1d301ebd1bc3",
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
              "id": "eb1bfe68-6cd3-497f-9541-6da9ab467eb9"
            }
          ]
        },
        {
          "id": "f51255ce-c76d-434b-8aeb-7c0717ac8f1a",
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
              "id": "94d40e10-a88e-4ecc-b374-c7fd11b77ed4"
            }
          ]
        }
      ]
    },
    {
      "name": "Components",
      "item": [
        {
          "id": "e80060a5-5b91-46aa-8272-f23ac63ca6c5",
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
              "id": "2f6190c8-b51a-46b1-9e7e-13d1bc4f2d83"
            }
          ]
        },
        {
          "id": "4afd563c-e5fd-4f13-a0ce-cfc01c4a3b25",
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
              "id": "08e52bff-1246-49a4-bef9-035db04ecfb4"
            }
          ]
        },
        {
          "id": "e7e77618-c03c-43d5-b12b-5b35f3631b69",
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
              "id": "61ad4be0-8a09-40c8-bb73-a70d157fab2d"
            }
          ]
        }
      ]
    },
    {
      "name": "Page Access Group",
      "item": [
        {
          "id": "2f4d6fa4-e1a0-4f4b-9cbc-17bb7f63c368",
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
              "id": "2c511321-c4bf-4573-b2c9-750b614a35c9"
            }
          ]
        }
      ]
    },
    {
      "name": "Incidents",
      "item": [
        {
          "id": "71d55220-620a-4c94-a3c5-56ade7cc247d",
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
              "id": "13caa3d0-d4cc-462d-b54d-ba3fbe54c5bf"
            }
          ]
        },
        {
          "id": "2585c028-e9b8-48ac-88e2-e3fa286404c4",
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
              "id": "0b2376dc-e3f9-4f78-b1c2-fbb889658cd0"
            }
          ]
        },
        {
          "id": "01248271-6b1a-4afd-a046-989e3d5d5fe0",
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
              "id": "7db547b8-b6fd-4ab4-8a82-3799b57ce543"
            }
          ]
        },
        {
          "id": "82fc1e72-592a-4ed5-b5a0-05d112f61f09",
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
              "id": "8785360d-29ac-4b72-ae6c-7750f7fcfc0f"
            }
          ]
        },
        {
          "id": "b426b60e-87ea-41b4-9cdd-554c6455d4f6",
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
              "id": "db79f594-dc66-4bb8-96b2-be50e3e583c6"
            }
          ]
        },
        {
          "id": "f51dc41f-d325-4149-a62a-c93645fbc50d",
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
              "id": "af903bff-bf7e-47da-bda4-99941c882c6e"
            }
          ]
        },
        {
          "id": "975c0237-c837-4ebd-bae3-098c1d7482b7",
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
              "id": "736ead88-2571-4556-aebf-6cae77ea0a56"
            }
          ]
        }
      ]
    },
    {
      "name": "Subscribers",
      "item": [
        {
          "id": "1c0d338b-8d10-4440-bcb1-526fee6f6762",
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
              "id": "218800b4-d0bb-4e4c-8083-a7613030917a"
            }
          ]
        }
      ]
    },
    {
      "name": "Metrics",
      "item": [
        {
          "id": "0fc14d37-6531-4ba9-8143-7544873fcbca",
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
              "id": "f0cdaf6b-bf5c-43c1-8901-fbf8941dba32"
            }
          ]
        },
        {
          "id": "31fdb012-41eb-4b38-89e3-86a296c42a9a",
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
              "id": "bfc77e65-25e9-4705-a1c0-47efb914d63b"
            }
          ]
        },
        {
          "id": "54fb65d9-26c3-448b-949d-1fc41ab461ba",
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
              "id": "c3a6a08a-bc5f-4d1e-a5c6-9f0ab55b5ad9"
            }
          ]
        }
      ]
    },
    {
      "name": "Metric Providers",
      "item": [
        {
          "id": "eac1954b-4028-4b5a-8154-eb61c78efd93",
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
              "id": "147082ad-0749-4e05-a683-71a0fedcd7c9"
            }
          ]
        },
        {
          "id": "6bd5ceda-2485-4c94-92d5-7a152905e944",
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
              "id": "096b6d4f-c849-4ab1-aa7d-0a7f74b7dd77"
            }
          ]
        },
        {
          "id": "5a248f4d-5c85-47e3-8e01-93ec9a0b6a52",
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
              "id": "6a1908b7-f9f3-4eb2-af31-4c7cc2718143"
            }
          ]
        }
      ]
    },
    {
      "name": "Organizations",
      "item": [
        {
          "id": "b80b1d71-ad1d-485e-8ccd-00ddce96bb86",
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
              "id": "0cca91a2-14ca-4d27-a57d-7ac805f2de9b"
            }
          ]
        },
        {
          "id": "3ba3249c-d804-41ad-90ac-8f8b8a72d8ba",
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
              "id": "a31f7790-bc4b-4b40-af38-e5518a86150c"
            }
          ]
        },
        {
          "id": "946e11c5-9191-467b-ba43-b7b54f445a0d",
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
              "id": "8967b482-a754-4a03-8d67-bd36a8df048e"
            }
          ]
        }
      ]
    },
    {
      "name": "Page Access Users",
      "item": [
        {
          "id": "9ddcc828-8e58-4ab0-b58c-465e67a35b76",
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
              "id": "570dcc3f-7b61-41cc-98e1-05031e6503fa"
            }
          ]
        },
        {
          "id": "c0331180-2652-4aa9-9a65-a42b50ba7826",
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
              "id": "e93fbde3-cbf5-40c3-8fa0-8e9d7307af37"
            }
          ]
        },
        {
          "id": "3d61d625-67e6-4e89-8ef5-b2efe817f6ac",
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
              "id": "6ab82484-7741-4c87-bf07-4ef39de63bd1"
            }
          ]
        },
        {
          "id": "e9062683-7e8c-4005-8e20-5f1d5dd492ae",
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
              "id": "0455887a-3a67-4a11-b44e-d3cad49f9d32"
            }
          ]
        },
        {
          "id": "a73edbbe-ed43-492e-aef4-5d7c5c5ac1b0",
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
              "id": "a71da14d-faf7-4328-8256-3096486a2425"
            }
          ]
        },
        {
          "id": "87f23e6b-6e8b-4990-a220-1d55015d4539",
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
              "id": "8b75e700-bfc0-420b-9d97-b9ec6cdaf7c6"
            }
          ]
        },
        {
          "id": "ef8932d1-a371-4a68-904c-7ab2d311a39e",
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
              "id": "de4fcf08-5520-48fa-b8a0-b7f0050a8268"
            }
          ]
        }
      ]
    }
  ]
}