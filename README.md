# opportunity-trend-research
Local-first research tool that runs Pinterest Trends and Google Trends lookups in parallel for a submitted keyword, keeps source metrics separate, and returns a unified comparison for internal product-opportunity analysis. Pinterest access uses OAuth, with credentials stored locally.

- OAuth tokens are stored only in the application's private runtime environment.
- Pinterest credentials and browser session cookies are never collected.
- Pinterest data is used only for authorized internal trend research.
- Pinterest data is not sold, shared, or used for advertising profiles.
- Data can be deleted upon request.
- Cached API responses are retained for 7 days.
