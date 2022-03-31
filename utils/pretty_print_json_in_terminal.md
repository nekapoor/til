## Pretty print a json string in the terminal

Let's say I have this json string: 

```
"{\"id\":78,\"tutor_id\":1,\"student_id\":14,\"disconnected_by_id\":null,\"disconnected_at\":null,\"disconnection_reason\":null,\"status\":\"active\",\"created_at\":\"2021-09-18T01:36:29.886Z\",\"updated_at\":\"2021-09-18T01:36:29.886Z\",\"connected_on\":\"2021-09-18T01:36:29.884Z\",\"last_activity\":\"tutoring_connection_made\",\"last_activity_at\":\"2021-09-18T01:36:29.886Z\",\"staleness\":\"no_staleness\",\"connected_by_id\":null,\"connection_type\":null}"
```

If I want to pretty print this in the terminal, I can run the following command: 

```
echo "{\"id\":78,\"tutor_id\":1,\"student_id\":14,\"disconnected_by_id\":null,\"disconnected_at\":null,\"disconnection_reason\":null,\"status\":\"active\",\"created_at\":\"2021-09-18T01:36:29.886Z\",\"updated_at\":\"2021-09-18T01:36:29.886Z\",\"connected_on\":\"2021-09-18T01:36:29.884Z\",\"last_activity\":\"tutoring_connection_made\",\"last_activity_at\":\"2021-09-18T01:36:29.886Z\",\"staleness\":\"no_staleness\",\"connected_by_id\":null,\"connection_type\":null}" | npx json
```



The output will be 
```
{
  "id": 78,
  "tutor_id": 1,
  "student_id": 14,
  "disconnected_by_id": null,
  "disconnected_at": null,
  "disconnection_reason": null,
  "status": "active",
  "created_at": "2021-09-18T01:36:29.886Z",
  "updated_at": "2021-09-18T01:36:29.886Z",
  "connected_on": "2021-09-18T01:36:29.884Z",
  "last_activity": "tutoring_connection_made",
  "last_activity_at": "2021-09-18T01:36:29.886Z",
  "staleness": "no_staleness",
  "connected_by_id": null,
  "connection_type": null
}
```
