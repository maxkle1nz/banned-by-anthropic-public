# First Hours Monitoring

## Watch closely in the first hours
- new submissions actually save
- public count moves when expected
- public record renders approved public cases
- voices render only when intended
- spam volume stays manageable
- no obvious UI confusion in the submit flow

## Highest-risk open item
- Turnstile is still not enabled in production

## Fast checks
- home: https://bannedbyanthropic.com/
- public repo: https://github.com/maxkle1nz/banned-by-anthropic-public
- intake health: https://bannedbyanthropic.com/health
- api health: https://bannedbyanthropic.com/api/health

## If something goes weird
1. stop broad promotion
2. inspect whether submissions still save
3. check whether counts/public rendering are stale or broken
4. patch only the real blocker
5. resume promotion after one clean submission cycle
