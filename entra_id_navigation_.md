## 🏠 Microsoft Entra ID: Full Navigation Tree with Descriptions

```
Microsoft Entra ID
├─ Overview
│  └─ Summary of your tenant: secure score, alerts, license status, domains
├─ Preview features
│  └─ Enables preview of upcoming features in Entra ID
├─ Diagnose and solve problems
│  └─ Troubleshooting guided steps based on your issues
├─ Users
│  ├─ All users – View/search all users
│  ├─ New user – Create user manually
│  ├─ Bulk operations – Import/export users in bulk via CSV
│  ├─ Provisioning – Set up SCIM sync from other identity systems (e.g. Workday)
│  ├─ Deleted users – Recover soft-deleted users within 30 days
│  ├─ Password reset – Reset user passwords manually or enforce policy
│  └─ [User blade]
│     ├─ Overview – Basic info, sign-in activity
│     ├─ Activity – Audit logs, risky sign-ins, sign-in logs
│     ├─ Groups – View/assign groups
│     ├─ Devices – View devices user has signed in to
│     ├─ Licenses – Assign and view license plans
│     ├─ Applications – View applications assigned
│     ├─ Authentication methods – View and reset MFA, phone, passwordless
│     └─ Profile – View/edit user profile fields
├─ Groups
│  ├─ All groups – Static/Dynamic group list
│  ├─ New group – Create security or M365 group
│  ├─ Dynamic membership rules – Define rules for dynamic group population
│  ├─ Bulk operations – Import/export group membership
│  ├─ Group settings
│  │  ├─ General – Who can create groups, self-service options
│  │  └─ Expiration – Set lifecycle rules for groups
│  └─ [Group blade]
│     ├─ Overview – Group type, creation date
│     ├─ Members – View/add/remove users
│     ├─ Owners – View/add group owners
│     ├─ Membership rules – View logic (for dynamic groups)
│     ├─ Assignments – Licenses or app access assigned
│     ├─ Settings – Visibility (public/private), subscriptions
│     └─ Activity – Audit logs related to this group
├─ External Identities
│  ├─ Overview – Status of B2B and B2C setup
│  ├─ User flows – Design user sign-up/sign-in flows for B2C
│  ├─ Customization – Change branding for B2C flows
│  ├─ Identity providers – Connect social/federated IDPs
│  └─ Invitations & restrictions – Control who can invite and how
├─ Roles and administrators
│  ├─ All roles – View directory roles
│  └─ [Role blade]
│     ├─ Overview – Permissions and description
│     ├─ Assignments – View or assign to users/groups
│     └─ Settings – Role activation settings (linked to PIM)
├─ Administrative units
│  ├─ All units – Admin boundaries for delegated control
│  └─ [Unit blade]
│     ├─ Overview
│     ├─ Members – Assign users to this unit
│     ├─ Roles – Define role scopes
│     └─ Assignments – View/manage scoped role assignments
├─ Delegated admin partners
│  └─ [Partner blade]
│     ├─ Overview – Partner name and details
│     ├─ Roles – Delegated roles assigned
│     └─ Audit logs – Changes/actions from the partner
├─ Enterprise Applications
│  ├─ All applications – All apps integrated with SSO/provisioning
│  ├─ New application – Add gallery or custom app
│  ├─ User settings – Self-service and assignment policies
│  └─ [App blade]
│     ├─ Overview – App type, sign-in URL
│     ├─ Users and groups – Assign access
│     ├─ Single sign-on – SAML/OIDC config
│     ├─ Provisioning – SCIM sync with external apps
│     ├─ Conditional Access – CA policies scoped to app
│     ├─ Properties – App metadata
│     ├─ Audit logs – All admin changes
│     └─ Usage & insights – Who used the app and how often
├─ App Registrations
│  ├─ All registrations – Apps where tenant is app developer
│  ├─ New registration – Create app ID/client ID
│  ├─ Owned applications – Apps owned by current user
│  └─ [Registration blade]
│     ├─ Overview – App ID, redirect URIs
│     ├─ Authentication – Platform configs and redirect URIs
│     ├─ Certificates & secrets – Auth credentials
│     ├─ Token configuration – Claims and optional claims
│     ├─ API permissions – App permissions granted/required
│     ├─ Expose an API – Define scopes and roles
│     ├─ Owners – Add app co-owners
│     ├─ Branding – UI settings for consent prompts
│     ├─ Roles – App-defined roles
│     └─ Manifest – JSON file to configure app
├─ Identity Governance
│  ├─ Access reviews – Review who has access to what
│  ├─ Entitlement management – Set up access packages for onboarding
│  ├─ Privileged Identity Management – Just-in-time role assignments
│  │  ├─ My roles – What you're eligible/active for
│  │  ├─ Assignments – Current assignments
│  │  ├─ Alerts – PIM-related alerts
│  │  ├─ Azure AD roles – Admin roles eligible for PIM
│  │  └─ Settings – PIM configuration
│  └─ Terms of use – Present agreements to users at sign-in
├─ Application proxy
│  └─ Publish on-premises apps securely via Azure
├─ Custom security attributes (Preview)
│  └─ Define and assign custom identity attributes to objects
├─ Licenses
│  ├─ All products – View assigned and unassigned licenses
│  ├─ Assign – Grant licenses to users/groups
│  └─ Billing notifications – Alerts related to license expiration
├─ Cross-tenant synchronization
│  └─ Sync users across tenants (B2B/B2B Direct sync)
├─ Microsoft Entra Connect
│  └─ Sync tool linking on-prem AD to Entra ID
├─ Custom domain names
│  ├─ Domain list – All domains in the tenant
│  ├─ Add domain – Add custom DNS domain
│  ├─ Verify domain – TXT/MX verification steps
│  └─ Set primary domain – Default domain for new users
├─ Mobility (MDM and MAM)
│  └─ Register and manage MDM apps like Intune. Requires platform registration.
├─ Password reset
│  └─ Policy configuration for SSPR (who can reset and how)
├─ Company branding
│  └─ Customize sign-in pages, logos, background, and CSS
├─ User settings
│  └─ Manage guest access, admin consent, self-service options
├─ Properties
│  ├─ Directory name
│  ├─ Region
│  ├─ Access restrictions – Admin-only portal, password policies
│  ├─ MDM authority – Define if Intune/3rd-party manages devices
│  └─ Contact info – Tech contacts for Microsoft
├─ Security
│  ├─ Secure Score – Security best practice rating
│  ├─ Authentication methods
│  │  ├─ Password – Default settings for password policy
│  │  ├─ FIDO2 – Passwordless auth device policy
│  │  ├─ Temporary Access Pass – Time-limited OTP
│  │  ├─ Microsoft Authenticator – Approvals from app
│  │  └─ SMS-based sign-in – Login with mobile OTP
│  ├─ MFA settings – Legacy MFA admin center (for classic tenants)
│  └─ Password reset – SSPR policy blade shortcut
├─ Monitoring
│  ├─ Sign-in logs – User login records
│  ├─ Audit logs – Admin activity logs
│  ├─ Provisioning logs – SCIM/HR sync status and errors
│  ├─ Health – Directory service health dashboard
│  ├─ Log Analytics – Export logs to Azure Monitor
│  ├─ Diagnostic settings – Enable export to Storage/Event Hub
│  ├─ Workbooks – Visualization templates
│  ├─ Usage & insights – Activity reports on users/apps
│  └─ Bulk operation results – History of bulk actions
├─ Troubleshooting + Support
│  └─ New support request – Open ticket with Microsoft
```

