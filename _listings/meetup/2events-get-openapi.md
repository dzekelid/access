---
swagger: "2.0"
x-collection-name: Meetup
x-complete: 0
info:
  title: Meetup Events
  description: Access Meetup events using a group, member, or event id. Events in
    private groups are available only to authenticated members of those groups. To
    search events by topic or location, see [Open Events](/meetup_api/docs/2/open_events).
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2/events:
    get:
      summary: Events
      description: Access Meetup events using a group, member, or event id. Events
        in private groups are available only to authenticated members of those groups.
        To search events by topic or location, see [Open Events](/meetup_api/docs/2/open_events).
      operationId: events
      x-api-path-slug: 2events-get
      parameters:
      - in: query
        name: event_id
        description: Multiple ids may be separated with commas
        type: string
      - in: query
        name: fields
        description: Request that additional fields (separated by commas) be included
          in the output
        type: string
      - in: query
        name: group_domain
        description: Group custom domain
        type: string
      - in: query
        name: group_id
        description: Multiple ids may be separated with commas
        type: string
      - in: query
        name: group_urlname
        description: Path to group from meetup
        type: string
      - in: query
        name: limited_events
        description: Include limited event information for private groups that wish
          to expose only a small amount of information about their events
        type: string
      - in: query
        name: member_id
        description: Single member id, to find events in this members groups
        type: string
      - in: query
        name: rsvp
        description: Filters events by the currently authenticated members RSVP status
        type: string
      - in: query
        name: status
        description: Status may be upcoming, past, proposed, suggested, cancelled,
          draft or multiple separated by a comma
        type: string
      - in: query
        name: text_format
        description: Format of the description text, html or plain
        type: string
      - in: query
        name: time
        description: Return events scheduled within the given time range, defined
          by two times separated with a single comma
        type: string
      - in: query
        name: venue_id
        description: Multiple ids may be separated with commas
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
x-streamrank:
  polling_total_time_average: "0.11"
  polling_size_download_average: "1941.69"
  streaming_total_time_average: "0.06"
  streaming_size_download_average: "983.16"
  change_yes: "84"
  change_no: "1779"
  time_percentage: "45"
  size_percentage: "49"
  change_percentage: "5"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---