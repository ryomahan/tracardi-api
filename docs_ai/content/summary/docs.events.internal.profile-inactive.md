This documentation describes an event called "Profile Inactive" which is used to indicate that a customer profile has been marked as inactive. This could be due to a variety of reasons such as the customer closing their account, failing to meet certain requirements, a violation of terms of service, or defined period of inactivity. The event is expected to have an optional property called "reason" which should be a string. No data will be indexed and when the event occurs, the data associated with it will be automatically duplicated in certain profile properties, with the "active" field being set to false.