## Cash Drawer Shift Event

### Structure

`CashDrawerShiftEvent`

### Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `String` | Optional | The unique ID of the event. |
| `employee_id` | `String` | Optional | The ID of the employee that created the event. |
| `event_type` | [`String (Cash Drawer Event Type)`]($m/CashDrawerEventType) | Optional | The types of events on a CashDrawerShift.<br>Each event type represents an employee action on the actual cash drawer<br>represented by a CashDrawerShift. |
| `event_money` | [`Money Hash`](/doc/models/money.md) | Optional | Represents an amount of money. `Money` fields can be signed or unsigned.<br>Fields that do not explicitly define whether they are signed or unsigned are<br>considered unsigned and can only hold positive amounts. For signed fields, the<br>sign of the value indicates the purpose of the money transfer. See<br>[Working with Monetary Amounts](https://developer.squareup.com/docs/build-basics/working-with-monetary-amounts)<br>for more information. |
| `created_at` | `String` | Optional | The event time in ISO 8601 format. |
| `description` | `String` | Optional | An optional description of the event, entered by the employee that<br>created the event. |

### Example (as JSON)

```json
{
  "id": null,
  "employee_id": null,
  "event_type": null,
  "event_money": null,
  "created_at": null,
  "description": null
}
```
