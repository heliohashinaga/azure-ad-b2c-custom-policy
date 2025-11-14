# Azure AD B2C - Custom Policies

## 📘 Overview

This repository contains resources and references for implementing Custom Policies in Azure Active Directory B2C (Azure AD B2C).

## 🧠 Key Concepts

Custom Policies concepts:

- TrustFrameworkBase.xml: Defines common reusable elements across all policies, such as Claims, ClaimsTransformations, and TechnicalProfiles.
- TrustFrameworkExtensions.xml: Extends TrustFrameworkBase with application-specific configurations.
- Policy Files (SignUpOrSignin.xml, PasswordReset.xml, ProfileEdit.xml): Define user interaction and authentication flows.
- Claims: Information about the user, such as name, email, etc.
- ClaimsTransformations: Rules to modify or validate Claims.
- TechnicalProfiles: Define how data is collected, validated, and persisted (e.g., REST APIs, Azure AD).
- OrchestrationSteps: Steps that make up the authentication flow.

## 🚀 Getting Started

To start using Custom Policies in Azure AD B2C:

1. Register Identity Experience Framework applications in Azure AD B2C.
2. Download the Custom Policy Starter Pack from GitHub.
3. Customize the XML policy files according to your business logic.
4. Upload the policies to your Azure AD B2C tenant.
5. Test and monitor using Application Insights.

## 🔗 Useful References

- [Overview of Custom Policies](https://learn.microsoft.com/en-us/azure/active-directory-b2c/custom-policy-overview)
- [Custom Policy Concepts](https://azure-ad-b2c.github.io/azureadb2ccommunity.io/docs/custom-policy-concepts/)
- [Tutorial: Create User Flows with Custom Policies](https://learn.microsoft.com/en-us/azure/active-directory-b2c/tutorial-create-user-flows?pivots=b2c-custom-policy)
- [Identity Experience Framework App Configuration](https://learn.microsoft.com/en-us/azure/active-directory-b2c/tutorial-create-user-flows?pivots=b2c-custom-policy#register-identity-experience-framework-applications)
- [VS Code Extension](https://github.com/azure-ad-b2c/vscode-extension/tree/master)
- [Application Insights Troubleshooting]( https://learn.microsoft.com/en-us/azure/active-directory-b2c/troubleshoot-with-application-insights?pivots=b2c-custom-policy)
- [GitHub Samples](https://github.com/azure-ad-b2c/samples)
- [Custom Policy Starter Pack](https://github.com/Azure-Samples/active-directory-b2c-custom-policy-starterpack)
- [Enable Javascript](https://learn.microsoft.com/en-us/azure/active-directory-b2c/javascript-and-page-layout?pivots=b2c-custom-policy)
- [Send verification code with Send Grid](https://learn.microsoft.com/en-us/azure/active-directory-b2c/custom-email-sendgrid?pivots=b2c-custom-policy)