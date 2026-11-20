VEHARI PHOTO STAT & PRINTERS — WEBSITE PACKAGE

This is for your NEW GitHub repository:
aliwali8475-debug/vehari-photo-stat-website
It does not overwrite your existing Netlify website.

UPLOAD TO GITHUB
1. Download this ZIP and choose Extract All.
2. Open https://github.com/aliwali8475-debug/vehari-photo-stat-website
3. Choose Add file > Upload files.
4. Upload all extracted items: index.html, assets, content, admin and netlify.toml.
5. Click Commit changes.

DEPLOY A NEW NETLIFY SITE
1. Open https://app.netlify.com/
2. Choose Add new project / Import an existing project.
3. Connect GitHub and select vehari-photo-stat-website.
4. Leave Build command blank. Set Publish directory to ".".
5. Deploy. This creates a separate site; your existing site remains unchanged.

ADMIN LOGIN — IMPORTANT
The admin interface uses Decap CMS with its GitHub backend. The GitHub backend needs an OAuth authentication flow. Do not put a GitHub Personal Access Token or OAuth Client Secret in website files.
Before using /admin/, configure a supported GitHub OAuth provider for Decap CMS. Follow the current official instructions:
https://decapcms.org/docs/github-backend/
https://docs.netlify.com/manage/security/secure-access-to-sites/oauth-provider-tokens/
If your Netlify account does not offer a compatible GitHub OAuth provider, stop and ask for help rather than entering a token into public code.

After authentication is configured, open your new site URL + /admin/ and sign in with your GitHub account. You can then edit business details, services and equipment and publish changes.

SECURITY
- Never share your GitHub password, OAuth secret or recovery codes.
- Keep repository write access limited to trusted accounts.
- The admin URL is not itself a password; login authentication is required.
