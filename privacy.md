import 'package:flutter/material.dart';

class PrivacyPolicyScreen extends StatelessWidget {
  const PrivacyPolicyScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: const Text('Privacy Policy')),
      body: SingleChildScrollView(
        padding: const EdgeInsets.all(16),
        child: const Text('''
Privacy Policy (PDF Merger App)

Effective Date: March 16, 2026

1. Introduction

This Privacy Policy explains how our PDF Merger app ("the App") collects, uses, and protects your information. By using the App, you agree to the terms of this Privacy Policy.

2. Information We Collect

Personal Data: We do not collect, store, or share any personal information such as your name, email, or documents.

Device Information: Limited information such as device type, operating system, and crash logs may be collected automatically for improving performance.

Advertising Data: Our App may display ads provided by third-party ad networks (e.g., Google AdMob). These networks may collect anonymous identifiers (such as advertising IDs) to provide personalized ads.

3. How We Use Information

We use the limited information we collect to:

Improve app performance and reliability.

Display ads to keep the App free for users.

4. Data Security

We do not store or transmit your PDF files. All PDF merging and processing happens locally on your device.

5. Third-Party Services

The App may use third-party services (e.g., Google AdMob) that have their own privacy policies regarding data usage.

6. Changes to This Policy

We may update this Privacy Policy from time to time. Continued use of the App after updates means you accept the new terms.

7. Contact Us

If you have any questions about this Privacy Policy, you can contact us at:
support@pdfmerger.com

Last Updated: March 16, 2026
          ''', style: TextStyle(fontSize: 16, height: 1.5)),
      ),
    );
  }
}
