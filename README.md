# Event Management API

This Flask API manages simple event data using an in-memory list. It supports creating, updating, and deleting events with RESTful routes.

## Routes

### POST /events

Creates a new event.

Example request:

```json
{
  "title": "Hackathon"
}