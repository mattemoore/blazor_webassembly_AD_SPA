# blazor_webassembly_AD_SPA

PoC to confirm Blazor AD template (SPA) app uses PKCE in authorization (MSAL v2) code flow working against AzureAD.

## Update
The answer is no.  It still uses implict flow: https://github.com/dotnet/aspnetcore/issues/23572#issuecomment-653113187
