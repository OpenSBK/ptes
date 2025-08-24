# Penetration Testing Levels Overview

## Introduction

This document provides an overview of the four levels of penetration testing as defined by the modernized Penetration Testing Execution Standard (PTES). The 2025 edition introduces a refined approach to testing levels, acknowledging that different organizations have varying needs, maturity levels, regulatory requirements, and threat landscapes.

## The Four Levels

### [Level 1: Baseline Assessment](level1-baseline-assessment.md)
**Compliance-Driven Security Validation**
- Largely automated scanning with basic human validation
- Duration: 1-3 days
- Automation: 80-90%
- Best for: Regulatory compliance, regular monitoring, budget-conscious organizations

### [Level 2: Standard Penetration Test](level2-standard-penetration-test.md)
**Balanced Security Assessment**
- Combines automated tools with manual testing and exploitation
- Duration: 1-3 weeks
- Automation: 50-70%
- Best for: Annual assessments, due diligence, industry standard validation

### [Level 3: Advanced Adversary Simulation](level3-advanced-adversary-simulation.md)
**Sophisticated Threat Actor Simulation**
- In-depth manual testing simulating advanced persistent threats
- Duration: 3-8 weeks
- Automation: 20-30%
- Best for: High-value targets, critical infrastructure, mature security programs

### [Level 4: Red Team Engagement](level4-red-team-engagement.md)
**Realistic Adversary Simulation**
- Extended timeline, stealth-focused assessment with business objectives
- Duration: 3-12 months
- Automation: 10-20%
- Best for: Critical infrastructure, nation-state threat preparation, executive awareness

## Level Comparison Matrix

| Aspect | Level 1 | Level 2 | Level 3 | Level 4 |
|--------|---------|---------|---------|---------|
| **Primary Focus** | Compliance | Best Practice | Advanced Threats | Realistic Simulation |
| **Automation** | 80-90% | 50-70% | 20-30% | 10-20% |
| **Duration** | 1-3 days | 1-3 weeks | 3-8 weeks | 3-12 months |
| **Cost** | $ | $$ | $$$ | $$$$ |
| **Expertise Required** | Junior-Mid | Mid-Senior | Senior-Expert | Expert-Specialist |
| **Detection Evasion** | None | Basic | Advanced | Maximum |
| **Business Impact** | Minimal | Low | Moderate | Significant |

## Choosing the Right Level

### Risk-Based Selection
- **Low Risk Environment**: Level 1-2
- **Medium Risk Environment**: Level 2-3
- **High Risk Environment**: Level 3-4

### Regulatory Requirements
- **Basic Compliance** (PCI DSS, HIPAA): Level 1-2
- **Advanced Compliance** (Financial, Defense): Level 2-3
- **Critical Infrastructure**: Level 3-4

### Security Program Maturity
- **Developing Programs**: Level 1-2
- **Mature Programs**: Level 2-3
- **Advanced Programs**: Level 3-4

## Implementation Strategies

### Progressive Approach
Organizations typically progress through levels as their security maturity evolves:
1. Start with **Level 1** for baseline establishment
2. Progress to **Level 2** for comprehensive validation
3. Advance to **Level 3** for sophisticated threat testing
4. Implement **Level 4** for complete adversary simulation

### Hybrid Approaches
Many organizations combine multiple levels:
- **Annual Level 2** with **Quarterly Level 1**
- **Level 3** for critical systems, **Level 2** for standard systems
- **Periodic Level 4** exercises with regular **Level 2** assessments

## Framework Integration

### NIST Cybersecurity Framework Alignment
Each level supports all five NIST CSF functions (Identify, Protect, Detect, Respond, Recover) with increasing sophistication and depth.

### PTES Methodology
All levels follow the seven-phase PTES methodology:
1. Pre-engagement Interactions
2. Intelligence Gathering
3. Threat Modeling
4. Vulnerability Analysis
5. Exploitation
6. Post Exploitation
7. Reporting

The depth and sophistication of each phase increases with the level.

### MITRE ATT&CK Integration
- **Levels 1-2**: Basic technique validation
- **Level 3**: Comprehensive tactic and technique simulation
- **Level 4**: Advanced persistent threat campaign simulation

## Key Benefits by Level

### Level 1 Benefits
- Cost-effective compliance validation
- Quick turnaround for regular monitoring
- Baseline security posture establishment

### Level 2 Benefits
- Comprehensive security validation
- Real vulnerability exploitation
- Industry standard compliance

### Level 3 Benefits
- Advanced threat simulation
- Sophisticated attack technique validation
- Deep security program assessment

### Level 4 Benefits
- Maximum realism in threat simulation
- Complete defensive capability assessment
- Executive-level risk demonstration

## Conclusion

The four-level penetration testing framework provides organizations with a scalable approach to security validation. The key to success lies in selecting the appropriate level that aligns with organizational risk profile, regulatory requirements, security maturity, and available resources.

Most organizations benefit from a multi-level approach, using different levels for different systems and purposes while progressing their overall security testing maturity over time.

---

## Document Structure

This overview is supported by detailed documentation for each level:

- **[level1-baseline-assessment.md](level1-baseline-assessment.md)** - Detailed Level 1 documentation
- **[level2-standard-penetration-test.md](level2-standard-penetration-test.md)** - Detailed Level 2 documentation
- **[level3-advanced-adversary-simulation.md](level3-advanced-adversary-simulation.md)** - Detailed Level 3 documentation
- **[level4-red-team-engagement.md](level4-red-team-engagement.md)** - Detailed Level 4 documentation

Each detailed document provides comprehensive information about methodology, activities, use cases, pros/cons, and reporting requirements for that specific level.