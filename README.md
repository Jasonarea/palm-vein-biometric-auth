# Palm-Vein Biometric Authentication System
**Korean Federation of Community Credit Cooperatives (KFCC) · 2019–2024**

## Overview

This project involved the deployment and operation of a palm-vein biometric authentication system for financial identity verification, integrated across banking branch networks and extended to airport security infrastructure.

The system allowed customers to register their palm-vein biometric data at bank branches and use that identity credential across institutional boundaries, including airport security checkpoints.

---

## Problem

Biometric authentication systems in financial environments must satisfy two competing demands: they must be technically secure, and they must be operationally adoptable by real users in real workflows.

Our palm-vein system was technically successful. Registration data was securely stored, credentials were cryptographically sound, and the interoperability layer between banking and airport systems functioned as designed.

However, after deployment, an unexpected pattern emerged: many customers who had already registered their palm-vein data at bank branches chose to re-register at airports rather than use their existing credentials. The system worked — but users did not trust or understand that it should work across contexts.

---

## Root Cause: A Usability Failure, Not a Technical One

The issue was not security or reliability. It was usability.

The re-registration process at airports introduced additional friction. Users were unfamiliar with the concept of cross-institutional credential sharing. Faced with uncertainty and an extra step, people defaulted to the path they understood, even if it was redundant.

This experience revealed a fundamental insight: **a technically correct security system can still fail if it is not designed around how people actually think and behave.**

---

## Key Insights

- Security system adoption depends not only on technical correctness, but on alignment with user mental models and workflows
- Friction at enrollment or re-use points can undermine even a cryptographically sound system
- Cross-institutional identity systems require deliberate UX design to communicate trust and familiarity to end users
- This experience was the origin of my research interest in **Usable Security** and **Human-Centered Authentication**

---

## Technical Scope

- Integrated palm-vein biometric hardware with internal banking teller terminal systems
- Designed identity verification workflows for biometric enrollment and authentication
- Extended credential interoperability to external airport security networks
- Implemented authentication history management and audit logging
- Operated within a closed financial network with strict data integrity requirements

---

## Technologies

`Java` `C` `Oracle SQL` `Biometric Authentication` `FEP Systems` `Core Banking Infrastructure`

---

## Reflection

This project shaped my understanding of security as a human problem, not just a technical one. It led me to ask: what does it mean for a security system to truly succeed? Not just to be correct, but to be trusted, understood, and naturally adopted by the people it is designed to protect.

These questions are what drive my current research interests in usable security and human-centered authentication design.

---

## References

- [MG새마을금고, 바이오인증 공항연계 서비스 출시 (미디어인뉴스, 2022.09.30)](https://www.mediainnews.com/news/articleView.html?idxno=25310)
- [관련 기사 (IT조선, 2020.07.17)](https://it.chosun.com/news/articleView.html?idxno=2020071703086)
