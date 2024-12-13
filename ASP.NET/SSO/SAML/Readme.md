# SAML SSO Demo Applications for .NET Framework & .NET Core

Welcome to the SAML SSO Demo Applications! 🚀 This repository contains two demo applications:

- 🌐 **A .NET Framework-based application**
- 🌐 **A .NET Core-based application**

These prototype will demonstrate how to integrate SAML SSO using the **miniOrange NuGet package** into your .NET applications.

---

## 📂 Contents of the Zip File

The ZIP file includes:

- 📘 **miniOrangeDemoApp-Net-Framework**: The demo application for .NET Framework.
- 📘 **miniOrangeDemoApp-Net-Core**: The demo application for .NET Core.
- 📄 **README.md**: Instructions for running the demo applications.

---

## ✅ Prerequisites

Before running the demo applications, ensure the following:

1. **Visual Studio Installed**:
   - 🛠️ Visual Studio 2013 or later is recommended.
2. **NuGet Package**:
   - 📦 Our SAML SSO NuGet package is pre-integrated into the applications. No manual installation is required.

---

## 🚀 Getting Started

### Step 1️⃣: Open the Solution in Visual Studio of .NET Framework or .NET Core

- Open `miniOrangeDemoApp.sln` using Visual Studio.

### Step 2️⃣: Run the Project through IIS Express in your Visual Studio

- Use IIS Express to run the project in your development environment.

### Step 3️⃣: Configure SAML Settings

1. Click on the **"Configure-SSO"** button on the .NET Application Homepage.
2. You will now see a plugin administrator dashboard to configure the SAML Settings between your application and your IDP.
3. Follow the instructions from this [LINK](https://plugins.miniorange.com/asp-net-saml-sso-setup-guides) to complete the end-to-end SAML setup.

---

## 🔄 Application Workflow

1. Navigate to the application in your browser.
2. Click the **"Login with SSO"** button to initiate the SAML SSO process.
3. You will be redirected to your Identity Provider for authentication.
4. After successful login, you will be redirected back to the application with user details.

---

## 🛠️ Troubleshooting

- **NuGet Package Issues**:
  - Ensure the NuGet package is correctly installed and referenced.
- **Debugging Logs**:
  - Navigate to the **"TroubleShooting"** tab in the plugin under the **"Identity Provider Configuration"** and enable it to generate debugging logs to review SSO flow logs.
- **FAQs**:
  - Check out our Frequently Asked Questions (FAQs) using this [LINK](https://faq.miniorange.com/kb/asp-net/).

---

## 📞 Support

If you encounter any issues or have questions, please contact our support team at 📧 **aspnetsupport@xecurify.com**.

---

Thank you for using our SAML SSO solution! 🙌

