# Privacy Policy

**Bitrise CI/CD Plugin for JetBrains IDEs**
Plugin ID: `com.horizonloop.idea.plugin.bitrise`

**Effective Date:** March 22, 2026
**Last Updated:** March 22, 2026

[Home](index.html) | [Terms & Conditions](TERMS.html) | [License](LICENSE.html) | [Copyright](COPYRIGHT.html)

---

## 1. Who We Are

This plugin is developed and maintained by HorizonLoop ("we", "us", "our").

- **Contact:** support@horizonloop.com
- **Plugin Marketplace:** [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/com.horizonloop.idea.plugin.bitrise)

This Privacy Policy explains what data the Bitrise CI/CD plugin collects, why, and how you can control it.

---

## 2. Data We Collect

We organize data into three categories. You control which optional categories are active.

### 2.1 Essential Data (Always Active — Stored Locally Only)

This data is required for the plugin to function and **never leaves your machine**.

| Data | Purpose | Storage |
|---|---|---|
| Bitrise API Token | Authenticate with the Bitrise API | IntelliJ's encrypted credential store (PasswordSafe) |
| App Slug & App Name | Identify your Bitrise app | Local IDE project settings (`bitrisePlugin.xml`) |
| Auto-refresh / Log refresh intervals | Your preferences | Local IDE project settings |
| Log panel position | Your UI preferences | Local IDE project settings |

**Your API token is stored in IntelliJ's encrypted credential store on your local machine. It is sent only to the Bitrise API (`api.bitrise.io`) as part of normal plugin operation. We never receive, store, or have access to your API token.**

### 2.2 Crash & Performance Data (Opt-In)

If you consent, we collect anonymized crash and performance data to identify and fix bugs.

| Data | Purpose |
|---|---|
| Exception class and message | Identify the bug |
| Stack trace (file names, line numbers) | Locate the bug in our code |
| Plugin version | Track regressions across releases |
| IDE type and version (e.g., IntelliJ IDEA 2025.2) | Reproduce IDE-specific issues |
| Operating system and version | Diagnose platform-specific bugs |
| JVM version | Diagnose JVM-specific issues |
| Available memory / heap statistics | Investigate memory-related crashes |
| Anonymous device identifier (generated UUID) | Deduplicate crash reports |

**We never collect:** your API tokens, source code, file contents, project names, branch names, commit messages, build data, or any personally identifiable information.

### 2.3 Usage Analytics (Opt-In)

If you consent, we collect anonymous feature usage data to understand how the plugin is used and prioritize development.

| Data | Purpose |
|---|---|
| Feature usage events (e.g., "build_triggered", "filter_applied") | Understand which features are used |
| Event timestamps | Understand usage patterns |
| Session duration | Measure engagement |
| Number of configured apps | Understand scale of usage |
| UI layout preference (split/tab) | Inform UI decisions |
| Plugin version | Correlate with releases |
| IDE type | Understand our audience |
| Anonymous user identifier (generated UUID) | Deduplicate analytics |

**We never collect:** the same exclusions as Section 2.2, plus: specific filter values, search queries, workflow names, or build numbers.

---

## 3. Legal Basis for Processing

| Category | Legal Basis |
|---|---|
| Essential Data | Contract performance — the plugin needs your settings to function. This data stays on your machine. |
| Crash & Performance Data | Consent (GDPR Article 6(1)(a)) — collected only after you explicitly opt in via the in-plugin consent dialog. |
| Usage Analytics | Consent (GDPR Article 6(1)(a)) — collected only after you explicitly opt in via the in-plugin consent dialog. |

---

## 4. Data Processors

We use the following third-party services to process data you consent to share:

| Processor | Purpose | Data Residency | Privacy Policy |
|---|---|---|---|
| PostHog Inc. | Usage analytics and error tracking | EU (Frankfurt, Germany) | [posthog.com/privacy](https://posthog.com/privacy) |
| Functional Software Inc. (Sentry) | Error tracking, performance monitoring | EU | [sentry.io/privacy](https://sentry.io/privacy/) |

- We do **not** sell your data to any third party.
- We do **not** share your data with any party other than the processors listed above.
- Data is transmitted only when you have granted consent and only while you actively use the plugin.

---

## 5. Data Retention

| Category | Retention Period |
|---|---|
| Crash & performance data | 90 days, then automatically deleted |
| Usage analytics | 12 months, then automatically deleted |

You can request early deletion at any time (see Section 7).

---

## 6. Data Transfers

- **PostHog EU Cloud:** Your data is processed and stored in Frankfurt, Germany. It does not leave the European Union.
- **Sentry EU:** Your data is processed and stored within the European Union.

Where any data transfer outside the EU/EEA is necessary, it is covered by Standard Contractual Clauses (SCCs) or the EU-US Data Privacy Framework.

---

## 7. Your Rights

### Under GDPR (EU/EEA/UK)

You have the right to:

- **Withdraw consent** at any time by toggling the data collection switches off in Settings > Tools > Bitrise CI/CD. This takes effect immediately.
- **Access** your data — contact us to request a copy.
- **Delete** your data — contact us to request erasure.
- **Data portability** — request your data in a machine-readable format.
- **Object** to processing.
- **Lodge a complaint** with your local data protection supervisory authority.

### Under CCPA (California)

You have the right to:

- **Know** what personal information is collected.
- **Delete** your personal information.
- **Opt out** of the sale of personal information. **We do not sell personal information.**
- **Non-discrimination** for exercising your privacy rights.

To exercise any of these rights, contact us at **support@horizonloop.com**.

---

## 8. How to Control Data Collection

- **On first use:** The plugin shows a consent dialog where you choose which data categories to enable. Both options are off by default.
- **At any time:** Go to **Settings > Tools > Bitrise CI/CD** and toggle the data collection switches.
- **Consent is never required** to use the plugin. All features work regardless of your data sharing choices.

---

## 9. Children's Privacy

This plugin is not directed at children under 16. We do not knowingly collect data from children under 16.

---

## 10. Changes to This Policy

We may update this Privacy Policy when we change our data practices. When we do:

- The updated policy will be published at this URL and in the plugin repository.
- Material changes to data collection will trigger a new consent dialog in the plugin.
- The "Last Updated" date at the top will be revised.

---

## 11. Contact

For privacy inquiries, data requests, or questions about this policy:

**Email:** support@horizonloop.com
