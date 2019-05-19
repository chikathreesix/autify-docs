# API Document

## How to use Personal Access Token

You can use a personal access token to authenticate with API by passing it in either the Authorization header:

```
curl -H "Authorization: Bearer PERSONAL-ACCESS-TOKEN" https://app.autify.com/api/v1
```

## Schedule API

Trigger schedule via API.

```
POST /schedules/:id
```

### Parameters:

- `id` (required) - The ID of the schedule owned by the authenticated user.  You can find the id from URL.  `https://app.autify.com/projects/<:project_id>/schedules/<:id>`

![](https://paper-attachments.dropbox.com/s_4D4D0D734A035220AE5A2053120BC0FB57F2BB2E117D5B16B3FAB4EB5D6E22D2_1557720980763_Screen+Shot+2019-05-13+at+13.16.01.png)
