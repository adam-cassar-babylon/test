## Refer Friend

**category**|**action**|**label**|**trigger**
:-----:|:-----:|:-----:|:-----:
refer a friend|click|invite friend *or* referred|user clicks invite friends link *or* clicks on referred link
refer a friend|return|invite friend *or* referred|user returns from *mention me* modal


#### Refer a friend events - JS
##### invite friend
```JavaScript
window.snowplow('trackSelfDescribingEvent',
  {
    schema: 'iglu:com.babylonhealth/generic_events/jsonschema/1-0-0',
    data: {
    category: 'refer a friend',
    action: 'click',
    label: 'invite friend'
  }}
  );
```
##### invite friend return
```JavaScript
window.snowplow('trackSelfDescribingEvent',
  {
    schema: 'iglu:com.babylonhealth/generic_events/jsonschema/1-0-0',
    data: {
    category: 'refer a friend',
    action: 'return',
    label: 'invite friend'
  }}
  );
```
##### invite friend consultation
```JavaScript
window.snowplow('trackSelfDescribingEvent',
  {
    schema: 'iglu:com.babylonhealth/generic_events/jsonschema/1-0-0',
    data: {
    category: 'refer a friend',
    action: 'click',
    label: 'invite friend consultation'
  }}
  );
```
##### invite friend consultation return
```JavaScript
window.snowplow('trackSelfDescribingEvent',
  {
    schema: 'iglu:com.babylonhealth/generic_events/jsonschema/1-0-0',
    data: {
    category: 'refer a friend',
    action: 'return',
    label: 'invite friend consultation'
  }}
  );
```
##### invite friend chatbot
```JavaScript
window.snowplow('trackSelfDescribingEvent',
  {
    schema: 'iglu:com.babylonhealth/generic_events/jsonschema/1-0-0',
    data: {
    category: 'refer a friend',
    action: 'click',
    label: 'invite friend chatbot'
  }}
  );
```
##### invite friend chatbot return
```JavaScript
window.snowplow('trackSelfDescribingEvent',
  {
    schema: 'iglu:com.babylonhealth/generic_events/jsonschema/1-0-0',
    data: {
    category: 'refer a friend',
    action: 'return',
    label: 'invite friend chatbot'
  }}
  );
```
##### referred
```JavaScript
window.snowplow('trackSelfDescribingEvent',
  {
    schema: 'iglu:com.babylonhealth/generic_events/jsonschema/1-0-0',
    data: {
    category: 'refer a friend',
    action: 'click',
    label: 'referred'
  }}
  );
```
##### referred return
```JavaScript
window.snowplow('trackSelfDescribingEvent',
  {
    schema: 'iglu:com.babylonhealth/generic_events/jsonschema/1-0-0',
    data: {
    category: 'refer a friend',
    action: 'return',
    label: 'referred'
  }}
  );
```
