<template>
  <div class="privacy-policy">
    <div class="container">
      <header class="policy-header">
        <h1>Privacy Policy</h1>
        <p class="last-updated">Last updated: {{ lastUpdated }}</p>
      </header>

      <div class="policy-content">
        <div class="section">
          <h2>1. Introduction</h2>
          <p>
            This Privacy Policy describes how our English Learning App ("we",
            "our", or "us") handles your information when you use our mobile
            application (the "Service").
          </p>
          <p>
            <strong>Important:</strong> Our app is designed with privacy in
            mind. We do not collect, store, or transmit any personal data from
            your device.
          </p>
        </div>

        <div class="section">
          <h2>2. Information We Do NOT Collect</h2>
          <p>Our English Learning App does not collect any of the following:</p>
          <ul>
            <li>
              Personal identification information (name, email, phone number,
              etc.)
            </li>
            <li>Device information or identifiers</li>
            <li>Location data</li>
            <li>Usage analytics or statistics</li>
            <li>Learning progress or study data</li>
            <li>Audio recordings or voice data</li>
            <li>Any other personal or sensitive information</li>
          </ul>
        </div>

        <div class="section">
          <h2>3. Local Data Storage</h2>
          <p>
            All your learning progress, vocabulary lists, and study data are
            stored locally on your device only. This information:
          </p>
          <ul>
            <li>Never leaves your device</li>
            <li>Is not transmitted to our servers or any third parties</li>
            <li>Is only accessible by you through the app</li>
            <li>Will be deleted if you uninstall the app</li>
          </ul>
        </div>

        <div id="data-deletion" class="section">
          <h2>4. Data Deletion / 数据删除</h2>
          <p><strong>English</strong></p>
          <p>
            EnTeacher lets you delete all locally stored learning data
            directly within the app — no need to contact the developer.
          </p>
          <p><strong>Steps:</strong></p>
          <ol class="steps-list">
            <li>Open the EnTeacher app</li>
            <li>On the home screen, tap "Clear Learning Data"</li>
            <li>Confirm the deletion in the dialog that appears</li>
          </ol>
          <p>
            This permanently deletes all learning progress, word mastery
            status, statistics, and session history stored on your device.
            This action cannot be undone.
          </p>
          <p>
            EnTeacher does not upload any user data to a server or third
            party — all data is stored locally on your device only.
          </p>
          <p><strong>中文</strong></p>
          <p>
            EnTeacher 支持在应用内一键清除所有本地学习数据，无需联系开发者。
          </p>
          <p><strong>操作步骤：</strong></p>
          <ol class="steps-list">
            <li>打开 EnTeacher App</li>
            <li>在首页找到"清除学习数据"（Clear Learning Data）按钮</li>
            <li>点击后在弹窗中确认清除</li>
          </ol>
          <p>
            点击确认后，应用会立即删除设备上保存的全部学习进度、单词掌握状态、统计数据和学习历史记录，此操作不可撤销。
          </p>
          <p>
            EnTeacher 不会将任何用户数据上传至服务器或第三方，所有数据仅保存在用户设备本地。
          </p>
        </div>

        <div class="section">
          <h2>5. Third-Party Services</h2>
          <p>
            Our app does not integrate with any third-party services, analytics
            platforms, advertising networks, or external APIs. We do not share
            any information with third parties because we do not collect any
            information.
          </p>
        </div>

        <div class="section">
          <h2>6. Internet Connection</h2>
          <p>
            Our app functions completely offline and does not require an
            internet connection. No data is transmitted over the internet during
            normal app usage.
          </p>
        </div>

        <div class="section">
          <h2>7. Children's Privacy</h2>
          <p>
            Our app is safe for users of all ages, including children under 13.
            Since we do not collect any personal information, there are no
            special privacy concerns for younger users.
          </p>
        </div>

        <div class="section">
          <h2>8. Data Security</h2>
          <p>
            Since all data remains on your device and we do not collect or
            transmit any information, the security of your data is entirely
            under your control through your device's built-in security features.
          </p>
        </div>

        <div class="section">
          <h2>9. Changes to This Privacy Policy</h2>
          <p>
            We may update our Privacy Policy from time to time. We will notify
            you of any changes by posting the new Privacy Policy on this page
            and updating the "Last updated" date.
          </p>
        </div>

        <div class="section">
          <h2>10. Contact Us</h2>
          <p>
            If you have any questions about this Privacy Policy, please contact
            us at:
          </p>
          <div class="contact-info">
            <p><strong>Email:</strong>cs@bg.exchange</p>
            <!-- <p><strong>Address:</strong> [Your Company Address]</p> -->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from "vue";

const lastUpdated = ref("September 2025");
</script>

<style scoped>
.privacy-policy {
  min-height: 100vh;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  padding: 0;
}

.container {
  width: 100%;
  max-width: none;
  margin: 0;
  background-color: white;
  min-height: 100vh;
}

.policy-header {
  text-align: center;
  padding: 4rem 2rem 3rem;
  background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
  color: white;
  margin-bottom: 0;
}

.policy-header h1 {
  font-size: 4rem;
  margin-bottom: 1rem;
  font-weight: 700;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
}

.last-updated {
  font-size: 1.2rem;
  opacity: 0.9;
  margin: 0;
}

.policy-content {
  max-width: 1400px;
  margin: 0 auto;
  padding: 4rem 3rem;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(600px, 1fr));
  gap: 2rem;
}

.section {
  background: #ffffff;
  padding: 2.5rem;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
  border: 1px solid #e9ecef;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.section:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 30px rgba(0, 0, 0, 0.12);
}

.section h2 {
  color: #2c3e50;
  font-size: 1.8rem;
  margin-bottom: 1.5rem;
  font-weight: 600;
  border-bottom: 3px solid #667eea;
  padding-bottom: 0.5rem;
}

.section p {
  line-height: 1.7;
  color: #495057;
  margin-bottom: 1.2rem;
  font-size: 1.1rem;
}

.section ul {
  margin: 1.5rem 0;
  padding-left: 0;
}

.section li {
  line-height: 1.7;
  color: #495057;
  margin-bottom: 0.8rem;
  font-size: 1.1rem;
  list-style: none;
  position: relative;
  padding-left: 2rem;
}

.section li::before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #28a745;
  font-weight: bold;
  font-size: 1.2rem;
}

.section {
  scroll-margin-top: 2rem;
}

.steps-list {
  margin: 1.5rem 0;
  padding-left: 1.5rem;
  counter-reset: none;
}

.steps-list li {
  line-height: 1.7;
  color: #495057;
  margin-bottom: 0.8rem;
  font-size: 1.1rem;
  list-style: decimal;
  padding-left: 0.5rem;
}

.steps-list li::before {
  content: none;
}

.contact-info {
  background: linear-gradient(135deg, #e3f2fd, #f3e5f5);
  padding: 2rem;
  border-radius: 8px;
  margin: 1.5rem 0;
  border: 1px solid #e1e5e9;
}

.contact-info p {
  margin: 0.8rem 0;
  font-size: 1.1rem;
}

.note {
  font-size: 1rem;
  color: #856404;
  font-style: italic;
  background: linear-gradient(135deg, #fff3cd, #ffeaa7);
  padding: 1.5rem;
  border-radius: 8px;
  border-left: 4px solid #ffc107;
  margin-top: 1.5rem;
}

strong {
  color: #2c3e50;
  font-weight: 600;
}

/* 响应式设计 */
@media (max-width: 1200px) {
  .policy-content {
    grid-template-columns: 1fr;
    max-width: 900px;
    padding: 3rem 2rem;
  }
}

@media (max-width: 768px) {
  .policy-header {
    padding: 2rem 1rem;
  }

  .policy-header h1 {
    font-size: 2.5rem;
  }

  .policy-content {
    padding: 2rem 1rem;
    gap: 1.5rem;
  }

  .section {
    padding: 1.5rem;
  }

  .section h2 {
    font-size: 1.5rem;
  }
}

@media (max-width: 480px) {
  .policy-header h1 {
    font-size: 2rem;
  }

  .section h2 {
    font-size: 1.3rem;
  }

  .section p,
  .section li {
    font-size: 1rem;
  }
}
</style>
