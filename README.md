# tps-connect

Sign-in and consent pages for the TPS app connector in Claude: `index.html` for the dev (test) project, `live/index.html` for the live project (read only).

Supabase's OAuth server sends Claude's sign-in here. A care lead or admin signs in with her TPS email and a code, then allows or declines the connection.

Each page holds only its project's public address and publishable key. Row-level security protects the data.

**Before go-live:** move this page to the TPS website and check with TJ first.
