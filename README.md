<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Privacy Policy · Xenith</title>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg:       #0A0A0F;
      --surface:  #141420;
      --border:   #1E1E2E;
      --accent:   #C8F135;
      --text:     #F0F0F8;
      --muted:    #7070A0;
      --red:      #FF4D4D;
    }

    html { background: var(--bg); color: var(--text); font-family: -apple-system, BlinkMacSystemFont, "SF Pro Text", "Segoe UI", sans-serif; -webkit-font-smoothing: antialiased; }

    body { max-width: 680px; margin: 0 auto; padding: 60px 24px 100px; }

    header { margin-bottom: 56px; }

    .wordmark {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      margin-bottom: 40px;
      text-decoration: none;
    }
    .wordmark-icon {
      width: 36px; height: 36px;
      background: var(--accent);
      border-radius: 9px;
      display: flex; align-items: center; justify-content: center;
    }
    .wordmark-icon svg { width: 20px; height: 20px; }
    .wordmark-name {
      font-size: 18px;
      font-weight: 700;
      letter-spacing: -0.3px;
      color: var(--text);
    }

    h1 {
      font-size: clamp(28px, 5vw, 38px);
      font-weight: 700;
      letter-spacing: -0.8px;
      line-height: 1.15;
      color: var(--text);
      margin-bottom: 12px;
    }

    .meta {
      font-size: 13px;
      color: var(--muted);
    }

    .intro {
      margin-top: 28px;
      padding: 20px 22px;
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 14px;
      font-size: 14px;
      line-height: 1.7;
      color: #A0A0C0;
    }

    section { margin-top: 48px; }

    h2 {
      font-size: 11px;
      font-weight: 700;
      letter-spacing: 1.2px;
      text-transform: uppercase;
      color: var(--accent);
      margin-bottom: 16px;
    }

    p {
      font-size: 15px;
      line-height: 1.75;
      color: #C0C0D8;
      margin-bottom: 14px;
    }
    p:last-child { margin-bottom: 0; }

    ul {
      margin: 10px 0 14px 0;
      padding-left: 20px;
    }
    li {
      font-size: 15px;
      line-height: 1.75;
      color: #C0C0D8;
      margin-bottom: 6px;
    }

    .tag {
      display: inline-block;
      background: var(--accent);
      color: #0A0A0F;
      font-size: 10px;
      font-weight: 700;
      letter-spacing: 0.8px;
      text-transform: uppercase;
      padding: 3px 8px;
      border-radius: 5px;
      margin-right: 8px;
      vertical-align: middle;
    }

    .tag.red { background: var(--red); color: #fff; }
    .tag.blue { background: #3B82F6; color: #fff; }

    .divider {
      height: 1px;
      background: var(--border);
      margin: 48px 0 0;
    }

    .contact-card {
      margin-top: 48px;
      padding: 24px;
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 16px;
    }
    .contact-card h2 { margin-bottom: 10px; }
    .contact-card p { margin-bottom: 10px; }
    .contact-card a {
      color: var(--accent);
      text-decoration: none;
      font-size: 15px;
      font-weight: 600;
    }
    .contact-card a:hover { text-decoration: underline; }

    footer {
      margin-top: 64px;
      font-size: 12px;
      color: var(--muted);
    }
  </style>
</head>
<body>

  <header>
    <div class="wordmark">
      <div class="wordmark-icon">
        <svg viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M10 2L13.5 8H17L14 12H16L10 18L4 12H6L3 8H6.5L10 2Z" fill="#0A0A0F"/>
        </svg>
      </div>
      <span class="wordmark-name">Xenith</span>
    </div>

    <h1>Privacy Policy</h1>
    <p class="meta">Effective date: June 25, 2026 &nbsp;·&nbsp; Last updated: June 25, 2026</p>

    <div class="intro">
      Xenith is a fitness app built for personal use. Your data is stored in your private iCloud account and is never accessible to us. We do not operate databases containing your personal information and we never sell your data to anyone.
    </div>
  </header>

  <section>
    <h2>1 · What We Collect</h2>
    <p>Xenith collects only what is necessary to provide your fitness tracking and AI features:</p>
    <ul>
      <li><strong>Profile data</strong> — name, age, height, weight, fitness goal, and activity level that you enter during onboarding or in Settings.</li>
      <li><strong>Food logs</strong> — meals you log manually, via food description, or by scanning a photo.</li>
      <li><strong>Workout logs</strong> — workouts you log in-app, including exercise names, sets, reps, and weights.</li>
      <li><strong>Apple Health data</strong> — active calories burned, workouts, and sleep analysis, read from HealthKit with your explicit permission.</li>
      <li><strong>Sleep entries</strong> — sleep duration, bed time, and wake time, either from Apple Watch via HealthKit or entered manually.</li>
      <li><strong>Daily AI reports</strong> — the generated coaching reports saved to your account.</li>
    </ul>
  </section>

  <section>
    <h2>2 · iCloud &amp; CloudKit Storage</h2>
    <p><span class="tag blue">iCloud</span> All of your Xenith data — profile, food logs, workouts, sleep entries, and daily reports — is stored in your private iCloud account using Apple's CloudKit framework.</p>
    <p>This means:</p>
    <ul>
      <li>Your data syncs automatically across all your Apple devices signed into the same iCloud account.</li>
      <li>Your data is stored in <strong>your</strong> iCloud container, not on Xenith's servers. Xenith has no access to read, modify, or delete your CloudKit data.</li>
      <li>iCloud storage is governed by <a href="https://www.apple.com/legal/privacy/" target="_blank" rel="noopener">Apple's Privacy Policy</a>.</li>
      <li>If you delete the Xenith app, your data remains in iCloud until you delete it manually via <strong>Settings → [Your Name] → iCloud → Manage Account Storage</strong>, or until you contact us to request deletion.</li>
    </ul>
    <p>Because Xenith cannot access your CloudKit container, we are unable to retrieve or restore your data on your behalf. Your iCloud account credentials protect your data.</p>
  </section>

  <section>
    <h2>3 · HealthKit</h2>
    <p><span class="tag">Apple</span> Xenith requests read access to Apple Health for active energy burned, workouts, and sleep analysis. This data is used solely to calculate your personalized calorie targets and populate your dashboard.</p>
    <p>Xenith does not write data to Apple Health. HealthKit data is never shared with third parties, never used for advertising, and is not stored in CloudKit — it is read live from HealthKit on your device only. You can revoke HealthKit access at any time in <strong>Settings → Privacy &amp; Security → Health → Xenith</strong>.</p>
  </section>

  <section>
    <h2>4 · AI Features &amp; OpenAI</h2>
    <p><span class="tag">Third Party</span> Xenith's AI features — Scan Meal, Describe Meal, and Daily Report — are powered by OpenAI's API. When you use these features, the following data is sent to OpenAI's servers to generate your result:</p>
    <ul>
      <li><strong>Scan Meal</strong> — the photo you take or upload, plus an optional restaurant or food source you provide.</li>
      <li><strong>Describe Meal</strong> — the text description of your meal that you type.</li>
      <li><strong>Daily Report</strong> — an anonymized summary of yesterday's calorie intake, macros, workout activity, and sleep duration. No personally identifying information (name, age, exact weight) is included in this summary.</li>
    </ul>
    <p>Data sent to OpenAI is governed by <a href="https://openai.com/policies/privacy-policy" target="_blank" rel="noopener">OpenAI's Privacy Policy</a>. OpenAI does not use API data to train their models by default. AI features require a Xenith Pro subscription and are entirely optional — the app is fully functional without them.</p>
  </section>

  <section>
    <h2>5 · Subscriptions &amp; Payments</h2>
    <p><span class="tag">Apple</span> Xenith Pro subscriptions are processed entirely by Apple through In-App Purchase. Xenith never sees, stores, or processes your payment information. All billing, receipts, and subscription management are handled by Apple. You can manage or cancel your subscription in <strong>Settings → [Your Name] → Subscriptions</strong>.</p>
  </section>

  <section>
    <h2>6 · Data We Do Not Collect</h2>
    <p>Xenith does not collect:</p>
    <ul>
      <li>Your email address or any account credentials — there is no Xenith account system.</li>
      <li>Location data.</li>
      <li>Device identifiers for advertising purposes.</li>
      <li>Crash analytics or usage telemetry.</li>
    </ul>
    <p><span class="tag red">Never</span> We do not sell, rent, or share your personal data with advertisers, data brokers, or any third party for commercial purposes.</p>
  </section>

  <section>
    <h2>7 · Data Deletion</h2>
    <p>Because your data lives in your private iCloud container, you control deletion:</p>
    <ul>
      <li><strong>Delete all data:</strong> Go to <strong>Settings → [Your Name] → iCloud → Manage Account Storage → Xenith</strong> and delete the app's storage.</li>
      <li><strong>Delete the app:</strong> Removes Xenith from your device but your iCloud data persists until deleted as above.</li>
    </ul>
    <p>To request confirmation that no data about you is held by Xenith outside of iCloud, contact us at the email below and we will respond within 30 days.</p>
  </section>

  <section>
    <h2>8 · Children's Privacy</h2>
    <p>Xenith is not directed at children under 13. We do not knowingly collect information from children under 13. If you believe a child has provided information through the app, please contact us and we will take steps to address it.</p>
  </section>

  <section>
    <h2>9 · Changes to This Policy</h2>
    <p>We may update this Privacy Policy as Xenith evolves. When we do, we will update the "Last updated" date at the top of this page. Continued use of Xenith after changes are posted constitutes your acceptance of the updated policy.</p>
  </section>

  <div class="divider"></div>

  <div class="contact-card">
    <h2>Contact</h2>
    <p>Questions about this policy or requests regarding your data:</p>
    <a href="mailto:xenithapp1@gmail.com">xenithapp1@gmail.com</a>
  </div>

  <footer>
    <p>© 2026 Xenith. All rights reserved.</p>
  </footer>

</body>
</html>
