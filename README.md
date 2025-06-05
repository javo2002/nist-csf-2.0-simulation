# NIST CSF 2.0 Project Documentation

This repository documents an implementation of the NIST Cybersecurity Framework (CSF) 2.0 for CyberTech Inc., a ficticious small company with 50 employees. My role as a new Cybersecurity Analyst was to help the company with it's security posture. The project demonstrates my understanding of NIST CSF 2.0 by creating Current and Target Profiles, conducting a gap analysis, and planning Tier progression.

My Role: Bob (Cyber Security Analyst)

## Job Ad

For a detailed understanding of my role of a Cyber Security Analyst at Cyber Tech Inc. Here is a job description for greater context:

[📄 View Job Ad PDF](assets/job_ad.pdf)

## Project Structure
- **docs/**: Detailed documentation of the project, including Current/Target Profiles, gap analysis, and stakeholder input.
- **assets/**: Visual aids (e.g., diagrams, charts) to explain NIST CSF concepts.
- **templates/**: Reusable templates for risk registers, policies, and incident playbooks.

## Directory Structure

```
nist-csf-2.0-project/
├── docs/                      # All project documentation
│   ├── overview/              # High-level project overview
│   │   ├── project_scope.md   # Scope of the fictitious company (CyberTech Inc.)
│   │   ├── nist_csf_overview.md # Brief explanation of NIST CSF 2.0
│   │   └── objectives.md      # Project goals (e.g., create Current/Target Profiles)
│   │
│   ├── current_profile/       # Current state of CyberTech Inc.
│   │   ├── govern.md          # Governance gaps (e.g., no formal policy)
│   │   ├── identify.md        # Asset/risk management gaps
│   │   ├── protect.md         # Weaknesses in safeguards (e.g., no MFA)
│   │   ├── detect.md          # Lack of monitoring tools
│   │   ├── respond.md         # No incident response plan
│   │   └── recover.md         # Untested recovery procedures
│   │
│   ├── target_profile/        # Desired state of CyberTech Inc.
│   │   ├── govern.md          # Governance goals (e.g., formal policy)
│   │   ├── identify.md        # Asset/risk management goals
│   │   ├── protect.md         # Safeguard improvements (e.g., MFA, backups)
│   │   ├── detect.md          # Monitoring goals (e.g., SIEM deployment)
│   │   ├── respond.md         # Incident response plan
│   │   └── recover.md         # Recovery testing goals
│   │
│   ├── gap_analysis/          # Analysis of gaps between Current and Target
│   │   ├── govern_gaps.md     # Governance gaps and action plan
│   │   ├── identify_gaps.md   # Asset/risk gaps and action plan
│   │   ├── protect_gaps.md    # Safeguard gaps and action plan
│   │   ├── detect_gaps.md     # Monitoring gaps and action plan
│   │   ├── respond_gaps.md    # Incident response gaps and action plan
│   │   └── recover_gaps.md    # Recovery gaps and action plan
│   │
│   ├── stakeholder_input/     # Notes from discussions with friends (stakeholders)
│   │   ├── executive_input.md # CEO/CFO priorities (e.g., compliance, budget)
│   │   ├── it_input.md        # IT Manager input (e.g., technical challenges)
│   │   ├── hr_input.md        # HR Director input (e.g., training needs)
│   │   └── legal_input.md     # Legal/Compliance input (e.g., regulatory needs)
│   │
│   ├── tier_progression/      # Explanation of Tiers 1-4
│   │   ├── tier_1.md          # Partial (current state)
│   │   ├── tier_2.md          # Risk Informed (target state)
│   │   ├── tier_3.md          # Repeatable (future state)
│   │   └── tier_4.md          # Adaptive (aspirational state)
│   │
│   └── templates/             # Reusable templates
│       ├── risk_register.md   # Risk register template
│       ├── policy_template.md # Cybersecurity policy template
│       └── incident_playbook.md # Incident response playbook template
│
├── assets/                    # Visual aids (e.g., diagrams, charts)
│   ├── nist_csf_functions.png # Diagram of NIST CSF Functions
│   ├── current_profile.png    # Visual summary of Current Profile
│   ├── target_profile.png     # Visual summary of Target Profile
│   └── tier_progression.png   # Visual progression from Tier 1 to Tier 4
│
├── README.md                  # Project overview and setup instructions
├── LICENSE                    # Project license (e.g., MIT, Apache 2.0)
└── CONTRIBUTING.md            # Guidelines for contributors (e.g., friends)
```

---

## How to Use This Repository

1. **Navigate the Documentation**:
   - Explore the `docs/` folder to view detailed documentation for each section (e.g., Current Profile, Target Profile, Gap Analysis).
   - Use the `templates/` folder for reusable templates (e.g., risk register, incident playbook).

2. **View Visual Aids**:
   - Check the `assets/` folder for diagrams and charts that explain key concepts (e.g., NIST CSF Functions, Tier progression).

3. **Contribute**:
   - If you'd like to contribute, follow the guidelines in `CONTRIBUTING.md`.

---

## Key Features

- **Current Profile**: Documents CyberTech Inc.'s existing cybersecurity posture.
- **Target Profile**: Outlines desired cybersecurity outcomes and timelines.
- **Gap Analysis**: Identifies gaps between Current and Target Profiles.
- **Tier Progression**: Provides a roadmap for improving cybersecurity practices.
- **Stakeholder Input**: Includes meeting notes from discussions with key stakeholders.
- **Templates**: Offers reusable templates for risk management and incident response.

---

## Contact

For questions or feedback, please open an issue in this repository or contact Javier Williams at jnajwilliams@gmail.com.

---

## Acknowledgments

Special thanks to my friends for acting as stakeholders and to provide valuable data for NIST CSF 2.0 implementation.
