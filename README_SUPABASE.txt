KL REAL ESTATE - SUPABASE CONNECTED VERSION

1. Supabase project URL is already configured in index.html.
2. The website uses the Supabase Publishable key in the browser. This is intended for client-side use with RLS.
3. The database tables/policies should already be created using the SQL from the setup instructions.
4. Before using the Admin section, create an admin user in Supabase:
   Authentication -> Users -> Add user -> Create new user
   Use an email and password you control.
5. Open index.html in a browser. Public visitors can view Available/featured properties and submit enquiries.
6. Admin login uses the Supabase Auth email/password account.

IMPORTANT:
- Never put a service_role or secret key in index.html.
- No photo upload system is included.
- The admin property form saves properties directly to Supabase.
- Customer enquiries and selling enquiries are saved to the enquiries table.
