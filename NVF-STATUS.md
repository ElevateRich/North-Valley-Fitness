# North Valley Fitness funnels: status and next steps

Last updated: 2026-11-04

## Where the real build is

- Code: `Tommy0550/nvf` (this repo is an early mock-up and is no longer used).
- Hosting: Cloudflare Worker `nvf`; every push to `main` of `Tommy0550/nvf` deploys.
- Starter Pack: `src/clients/nvf.ts`, preview https://nvf.elevate-pages.com
- Black Friday: `src/clients/nvf-bf.ts`, preview https://nvf-bf.elevate-pages.com
- Videos: Cloudflare R2 bucket `nvf`. Upload page: https://nvf-bf.elevate-pages.com/upload
  (Black Friday files named `bf-landing` and `bf-thanks`).
- Leads: Zenoti guest + note + 24h opportunity, and an email to the club (cc Mike, Jonathon, Rich).

## Who has Cloudflare access

- Tom (on holiday).
- **Jane** can get into the Cloudflare account that holds `elevate-pages.com`.

## Go-live checklist

1. [ ] NVF adds the DNS record: `CNAME join -> clients.elevate-pages.com` (DNS only / grey cloud).
2. [ ] **Rich sends Jane the instructions below** (can be done before or after step 1).
3. [ ] Hostname shows Active in Cloudflare.
4. [ ] Test both funnels on the real domain with a TEST lead:
   - https://join.northvalleyfitness.com (Starter Pack)
   - https://join.northvalleyfitness.com/nvf-bf (Black Friday)
5. [ ] Point the Meta ads at the live addresses.

## Instructions to send Jane

> Hi Jane, thanks for helping with this. It takes about 2 minutes:
>
> 1. Log in at https://dash.cloudflare.com and click **elevate-pages.com**.
> 2. In the left menu, click **SSL/TLS**, then **Custom Hostnames**.
> 3. If `join.northvalleyfitness.com` is already listed, you're done. Just tell me its status.
> 4. If not, click **Add Custom Hostname**, type `join.northvalleyfitness.com`, leave everything else as it is and click **Add**.
> 5. If Cloudflare asks you to enable "Cloudflare for SaaS" first, or asks to set a "fallback origin", stop and send me a screenshot.
>
> Once North Valley's DNS record is in, the status turns **Active** on its own. Please send me a screenshot of that page when you're done. Thanks!

## Open items

- Black Friday: confirm the free PT session, the offer end date, and whether the form should ask Basic or Lifestyle.
- Meta ad creatives from NVF.
- NVF to confirm every lead in the leak spreadsheet has been called.
- Where the team finds leads in Zenoti: TBC from the John call transcript.
