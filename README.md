# AWS SAA-C03 Practice 🚀

<div align="center">

![Study Resource](https://img.shields.io/badge/Study-Resource-FF9900?style=for-the-badge)
![Exam Code](https://img.shields.io/badge/Exam-SAA--C03-232F3E?style=for-the-badge)
![Questions](https://img.shields.io/badge/Questions-650-FF6B6B?style=for-the-badge)
![Practice Exams](https://img.shields.io/badge/Practice%20Exams-10-4ECDC4?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**650 Questions • 10 Full Practice Exams • Interactive Quiz**

**Last reviewed: 2026-04-09**

**[👉 Start Quiz](https://shinigami368.github.io/aws-saa-tips/)**

</div>

---

## 🎯 Who Is This For?

| User | Use Case |
|------------|----------|
| **Exam Candidates** | Quick, intensive review |
| **Engineers** | Pre-exam final check |
| **Instructors** | Resource for students |

> ⚠️ **Disclaimer**: This is an independent community study resource. It is not affiliated with, endorsed by, or sponsored by AWS. Always verify against [official AWS documentation](https://docs.aws.amazon.com/).

---

## 📚 Quick Access

| File | Description |
|-------|----------|
| [📋 Study Guide](https://shinigami368.github.io/aws-saa-tips/website/study-guide.html) | 19 sections, all topics |
| [⚡ Cheat Sheet](https://shinigami368.github.io/aws-saa-tips/website/cheat-sheet.html) | Last 24-hour review |
| [🎯 Interactive Quiz](https://shinigami368.github.io/aws-saa-tips/) | 650 questions, 10 exams |
| [📖 README](https://shinigami368.github.io/aws-saa-tips/website/README.html) | Project overview |

---

## ✨ Features

- 650 practice questions across 10 full exam sets
- Topic filtering with a single primary category per question
- Direct links to official AWS documentation for every question
- Study guide and cheat sheet for pre-quiz review
- Final results summary with score, time spent, exam breakdown, and topic breakdown
- Last-question `Finish Quiz` flow for custom exam combinations

---

## 🧭 How to Use the Quiz

1. Select the exam sets you want to include.
2. Optionally filter by one topic to drill a specific area.
3. Click `Start Quiz`.
4. Answer questions one by one and use the AWS docs links when you want source material.
5. On the last question, click `Finish Quiz`.
6. Review score, accuracy, time spent, and performance by exam and topic.

### Recommended Flows

- Full practice exam: select one exam only
- Focused drill: select multiple exams + one topic
- Broad revision: select 5-10 exams with `All Topics`

---

## 🗺️ Study Path

```
┌─────────────────────────────────────────────────────────────────┐
│  STEP 1: Learn the Basics                                        │
│  📖 Read the study guide                                         │
├─────────────────────────────────────────────────────────────────┤
│  STEP 2: Compare Services                                        │
│  ⚖️ Memorize comparison tables                                   │
├─────────────────────────────────────────────────────────────────┤
│  STEP 3: Learn the Tricks                                        │
│  🕵️ Trick patterns and gotcha facts                              │
├─────────────────────────────────────────────────────────────────┤
│  STEP 4: Practice                                                │
│  📝 Solve practice exams                                          │
├─────────────────────────────────────────────────────────────────┤
│  STEP 5: Final Review                                            │
│  ⚡ Cheat sheet + 24-hour checklist                              │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🎓 Exam Topics (Weights)

| Domain | Weight | Focus Areas |
|--------|---------|---------------|
| **Design Secure Architectures** | ~30% | IAM, S3, VPC, Encryption |
| **Design Resilient Architectures** | ~26% | Multi-AZ, ASG, RDS, S3 |
| **Design High-Performing Architectures** | ~24% | caching, ELB, Aurora, DynamoDB |
| **Design Cost-Optimized Architectures** | ~20% | Spot, RI, Savings Plans |

---

## ⚡ Quick Review - Key Rules

### Storage
```
✦ Query S3 with SQL          → Athena
✦ Private S3 access (free)   → Gateway VPC Endpoint
✦ Immutable data              → S3 Object Lock (Compliance)
✦ Unpredictable access        → S3 Intelligent-Tiering
```

### Compute
```
✦ Least operational overhead   → Fargate, Lambda, Aurora Serverless
✦ Java Lambda cold start     → SnapStart
✦ Remote EC2 access          → Session Manager (no SSH keys)
```

### Database
```
✦ Read scaling               → Read Replicas
✦ HA failover               → Multi-AZ
✦ Lambda + DB connections    → RDS Proxy
✦ Sub-ms DynamoDB reads     → DAX
```

### Decoupling
```
✦ 1 message → many consumers → SNS → SQS (fan-out)
✦ Message ordering           → SQS FIFO
✦ Real-time streaming       → Kinesis
```

---

## 🏆 Exam Strategy

### Time Management
| Question | Minutes |
|------|--------|
| 65 questions | 130 minutes |
| 1 question | ~2 minutes |

### Keyword-Based Solution
```
"least operational overhead"  → Choose Serverless/Managed services
"highly available"            → Choose Multi-AZ solutions
"private access"             → Use VPC Endpoint
"credential rotation"        → Secrets Manager
```

### Elimination Tactics
Always eliminate 2 of 4 options immediately:
- ❌ Single-AZ solution → eliminate when "highly available" is asked
- ❌ Glacier → eliminate when "immediate access" is asked
- ❌ EC2 + custom scripts → eliminate when "least overhead" is asked
- ❌ IAM user sharing → eliminate in cross-account questions

---

## 📖 Resources

- [AWS SAA-C03 Official Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Exam-Guide.pdf)
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)
- [AWS Documentation](https://docs.aws.amazon.com/)
- [AWS Skill Builder](https://explore.skillbuilder.aws/)

---

## ✅ Quick Smoke Checklist

- Main page loads and `Start Quiz` opens the quiz
- Exam selection updates total question count and estimated time
- Topic buttons show live counts and disable empty topics
- Questions render with 4 options and official AWS docs links
- Last question shows `Finish Quiz`
- Results screen shows correct, incorrect, answered, accuracy, time spent, result
- Results screen shows breakdown by exam and topic
- Study guide, cheat sheet, README, and LICENSE links open correctly

---

## 🗺️ Topic Quick Access

| Topic | File |
|------|-------|
| All Topics | [📋 Study Guide](https://shinigami368.github.io/aws-saa-tips/website/study-guide.html) |
| Last Minute Review | [⚡ Cheat Sheet](https://shinigami368.github.io/aws-saa-tips/website/cheat-sheet.html) |
| Practice Questions | [🎯 Start Quiz](https://shinigami368.github.io/aws-saa-tips/) |

---

## 📝 License

This project is licensed under MIT License. See [LICENSE](LICENSE) for details.

---

<div align="center">

**Live Demo: [https://shinigami368.github.io/aws-saa-tips/](https://shinigami368.github.io/aws-saa-tips/)**

</div>
