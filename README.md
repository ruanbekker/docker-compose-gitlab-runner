# docker-compose-gitlab-runner

Gitlab Runner orchestrated by Docker Compose.

## Token Registration

Head over to runners registration page in Gitlab, create a runner (untagged), and set the token to `REGISTRATION_TOKEN=xx` in `.env`.

## Start the Runners

Start the runners:

```bash
docker-compose up -d
```

## Verify

From the runners page, you should see the runner shows as "Online".
