# Launch in 2 Hours — Tactical Checklist

## T-120 to T-90
- confirm production home page is live
- confirm production submit path actually works end-to-end
- confirm one real GitHub login works
- confirm one real record can be submitted
- confirm the record is visible or private exactly as intended

## T-90 to T-60
- enable Turnstile in production
- verify `/health` reports `turnstileRequired=true`
- verify a valid submission still works
- verify spam resistance/cooldown still behaves correctly

## T-60 to T-40
- create public institutional repo
- paste README + docs
- add link to official site
- add contact channel
- do final secret sweep before first push

## T-40 to T-20
- soft-launch to a small trusted circle
- observe first real submissions
- verify public totals / voices / moderation behavior
- fix any obvious UI or copy breakage immediately

## T-20 to T-0
- publish public repo
- announce the site
- keep operator eyes on submissions, logs, and moderation surface

## Hard no-go items
- Turnstile still disabled
- submit flow not verified in production
- admin/moderation/export path unknown
- secrets or raw exports present in public repo push
