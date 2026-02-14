# SDLC Analysis for Odoo ERP System
## Software Process Models and Requirements Engineering

[![MIT License](https://img.shields.io/badge/License-Academic-blue.svg)](LICENSE)
[![Report Status](https://img.shields.io/badge/Status-Completed-success.svg)](https://github.com/bkshetty/SDLC-ON-ODOO-ERP-SYSTEM)

**Academic Project**  
**Course:** Introduction to Software Engineering (IS1103-1)  
**Institution:** NMAM Institute of Technology, Nitte  
**Student:** Bhuvan Kumar Shetty H  
**USN:** NNM24IS057  
**Semester:** 4th Semester, Section A  
**Academic Year:** 2025-2026  
**Submission Date:** February 15, 2026  

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Abstract](#abstract)
- [Key Findings](#key-findings)
- [Research Methodology](#research-methodology)
- [Document Structure](#document-structure)
- [SDLC Models Analyzed](#sdlc-models-analyzed)
- [Requirements Engineering Framework](#requirements-engineering-framework)
- [Repository Contents](#repository-contents)
- [How to Use This Repository](#how-to-use-this-repository)
- [Citation Guidelines](#citation-guidelines)
- [Technologies Discussed](#technologies-discussed)
- [Future Work](#future-work)
- [Academic Integrity](#academic-integrity)
- [Contact Information](#contact-information)
- [References](#references)

---

## 🎯 Project Overview

This project presents a comprehensive comparative analysis of three fundamental Software Development Lifecycle (SDLC) methodologies—**Waterfall**, **Spiral**, and **Incremental Development**—specifically within the context of implementing **Odoo**, one of the world's most popular open-source Enterprise Resource Planning (ERP) systems.

### Research Objectives

1. **Comparative Analysis**: Evaluate three SDLC models (Waterfall, Spiral, Incremental) against real-world ERP implementation scenarios
2. **Requirements Engineering**: Develop a structured framework for managing functional and non-functional requirements in complex ERP systems
3. **Risk Management**: Identify and propose mitigation strategies for common risks in modular ERP implementations
4. **Practical Recommendations**: Provide actionable guidance for software development teams working on similar large-scale enterprise projects

### Why Odoo?

Odoo was selected as the case study for several compelling reasons:

- **Modular Architecture**: 30+ core applications with thousands of community modules
- **Open-Source Nature**: Transparent codebase enabling deep architectural analysis
- **Real-World Relevance**: Widely deployed across diverse industries and organization sizes
- **Technical Sophistication**: Three-tier MVC architecture with PostgreSQL database and Python business logic
- **Active Development**: Continuous evolution requiring adaptable development methodologies

---

## 📝 Abstract

This report examines three Software Development Lifecycle methodologies—Waterfall, Spiral, and Incremental Development—within the specific context of Odoo, a leading open-source ERP system. Rather than approaching these methodologies from a purely theoretical perspective, this research evaluates them against real-world ERP development challenges: constantly evolving requirements, budget constraints, timeline pressures, and the need for continuous scalability.

### Key Insights

Through systematic examination of Odoo's modular architecture, PostgreSQL-based data layer, and Python-driven business logic, this study reveals significant differences in methodology suitability:

- **Waterfall Model**: Offers predictability and structure but lacks flexibility for changing requirements
- **Spiral Model**: Excels in risk management but introduces complexity overhead
- **Incremental Development**: Aligns naturally with Odoo's modularity, enabling phased system evolution without compromising stability

The research also presents a distinctive requirements engineering framework addressing both functional requirements (multi-currency support, automated workflows, inventory tracking) and non-functional priorities (scalability, performance benchmarks, security controls). A comprehensive validation methodology tackles common challenges including stakeholder alignment, requirement traceability, and continuous refinement throughout the development lifecycle.

**Impact**: This analysis provides critical insights for software engineering teams undertaking ERP projects where flexibility, scalability, and responsiveness are not optional but essential for success.

---

## 🔍 Key Findings

### 1. Incremental Development Emerges as Optimal Approach

**Finding**: For the majority of Odoo implementations, Incremental Development methodology provides the best balance of structure, flexibility, and risk management.

**Rationale**:
- Natural alignment with Odoo's modular architecture
- Enables early value realization through phased module deployment
- Contains risks within individual increments rather than threatening entire project
- Accommodates requirement evolution without destabilizing existing functionality
- Supports progressive budget allocation aligned with demonstrated value delivery

**Supporting Evidence**: 
- Odoo's 30+ core modules map naturally to development increments
- Progressive deployment pattern: Accounting → Inventory → CRM → Manufacturing
- Each module can be developed, tested, and deployed independently
- Integration points are well-defined and manageable incrementally

### 2. Requirements Engineering Demands Continuous Validation

**Finding**: Requirements validation cannot be a one-time phase-end activity; it must occur iteratively throughout the development lifecycle.

**Key Techniques Identified**:
- **Requirements Reviews**: Cross-functional team examination for completeness and consistency
- **Prototyping**: Using Odoo demo environments to validate workflow requirements through hands-on stakeholder interaction
- **Test Scenario Development**: Creating acceptance criteria during requirements definition to ensure testability
- **Traceability Analysis**: Maintaining bidirectional linkages between business objectives and technical specifications

**Critical Success Factors**:
- Early and continuous stakeholder engagement
- Clear acceptance criteria for every requirement
- Formal change control processes to manage requirement evolution
- Requirements prioritization using MoSCoW or similar frameworks

### 3. Risk Management Must Be Proactive, Not Reactive

**Finding**: Successful ERP implementations require explicit risk identification and mitigation strategies embedded within the development process.

**Major Risk Categories Identified**:

1. **Module Dependency Risks**
   - Changes to core modules may cascade to dependent applications
   - Mitigation: Comprehensive dependency mapping and impact analysis

2. **Performance Degradation Risks**
   - System slowdowns can affect user adoption and productivity
   - Mitigation: Load testing with realistic data volumes and user concurrency

3. **Scope Creep Risks**
   - Stakeholder requests for additional features beyond original scope
   - Mitigation: Formal change control with cost/benefit analysis

4. **User Adoption Risks**
   - Resistance to new system or inadequate training
   - Mitigation: Change management program with phased rollout and comprehensive training

### 4. Context Matters: No One-Size-Fits-All Solution

**Finding**: While Incremental Development suits most Odoo projects, specific scenarios may favor alternative approaches.

**Waterfall May Be Appropriate When**:
- Requirements are exceptionally stable and well-understood
- Regulatory environment demands extensive upfront documentation
- Organization has mature ERP processes and minimal customization needs
- Fixed-price contracting requires detailed scope specification

**Spiral May Be Justified When**:
- Project involves novel integration requirements with uncertain feasibility
- Mission-critical deployment cannot tolerate significant failures
- Budget allows for iterative risk analysis overhead
- Compliance requirements (HIPAA, SOX, etc.) demand formal risk assessments

**Example Scenario**: A healthcare organization implementing Odoo with complex HIPAA compliance requirements and integration with legacy clinical systems might benefit from the Spiral Model's explicit risk management emphasis, despite higher methodology overhead.

---

## 🔬 Research Methodology

### Data Collection Approach

This research employed a multi-source data collection strategy:

1. **Literature Review**: Systematic examination of academic papers, industry publications, and official Odoo documentation
2. **Architectural Analysis**: Deep dive into Odoo's technical architecture, module structure, and integration patterns
3. **Comparative Framework Development**: Structured evaluation criteria for assessing SDLC methodology suitability
4. **Requirements Framework Creation**: Development of comprehensive requirements template based on ERP best practices

### Evaluation Criteria

Each SDLC methodology was assessed against four primary dimensions:

#### 1. Requirements Management Capability
- **Functional Requirements**: Ability to capture and track business process requirements
- **Non-Functional Requirements**: Support for quality attributes (performance, security, usability)
- **Change Accommodation**: Flexibility to incorporate evolving requirements
- **Traceability**: Linkage between business objectives and technical specifications

#### 2. Risk and Change Management
- **Risk Identification**: Systematic approach to identifying potential problems
- **Risk Mitigation**: Strategies for reducing likelihood and impact of risks
- **Change Control**: Formal processes for evaluating and approving changes
- **Impact Assessment**: Ability to analyze ripple effects of modifications

#### 3. Time and Cost Constraints
- **Predictability**: Accuracy of schedule and budget estimates
- **Time-to-Value**: Speed of delivering working functionality to stakeholders
- **Cost Efficiency**: Resource utilization and total cost of ownership
- **Budget Flexibility**: Ability to align spending with value realization

#### 4. Scalability and Technical Fit
- **Architectural Alignment**: Compatibility with Odoo's modular structure
- **Team Scalability**: Support for growing development team size
- **Technical Complexity**: Required expertise and tooling sophistication
- **Maintenance Burden**: Long-term sustainability and upgrade compatibility

### Analysis Framework

A structured comparison matrix was developed scoring each methodology across evaluation criteria on a 5-point scale:

| Criteria | Waterfall | Spiral | Incremental |
|----------|-----------|--------|-------------|
| Requirements Flexibility | 2/5 | 4/5 | 5/5 |
| Risk Management | 2/5 | 5/5 | 4/5 |
| Time-to-Value | 1/5 | 3/5 | 5/5 |
| Architectural Fit (Odoo) | 2/5 | 3/5 | 5/5 |
| Budget Predictability | 5/5 | 3/5 | 4/5 |
| Change Accommodation | 1/5 | 4/5 | 5/5 |
| **Overall Suitability** | **2.2/5** | **3.7/5** | **4.7/5** |

---

## 📚 Document Structure

### Report Sections

1. **Introduction**: Context-setting for SDLC methodology selection in ERP implementation
2. **Problem Statement**: Defines the challenge of selecting appropriate development processes
3. **Methodology**: Describes research approach and evaluation framework
4. **Requirements**: Comprehensive requirements framework for Odoo implementation
5. **Requirements Validation**: Strategies for ensuring requirement quality
6. **Results and Analysis**: Comparative evaluation findings
7. **Risk Management and Quality**: Risk mitigation strategies and QA approaches
8. **Limitations and Future Work**: Acknowledges study boundaries and proposes extensions
9. **Conclusion**: Synthesizes findings and provides actionable recommendations
10. **References**: Academic and industry sources cited throughout the research
11. **Declaration**: Academic integrity statement

---

## 🔄 SDLC Models Analyzed

### 1. Waterfall Model

**Origin**: Introduced by Winston W. Royce in 1970  
**Core Principle**: Sequential, phase-gated development progression  

**Phases**:
1. Requirements Analysis & Specification
2. System and Software Design
3. Implementation & Unit Testing
4. Integration & System Testing
5. Deployment & Maintenance

**Strengths in ERP Context**:
- Comprehensive upfront planning reduces ambiguity
- Extensive documentation supports knowledge transfer and compliance
- Clear milestones enable straightforward project tracking
- Well-suited for stable, well-understood requirements
- Fixed-price contracting compatibility

**Weaknesses in ERP Context**:
- Inflexible to changing business requirements
- Late discovery of integration issues or requirement misunderstandings
- No working software until late in development cycle
- High risk of delivering functionally inadequate system despite technical compliance with specifications
- Difficult to incorporate user feedback without significant rework

**Recommended Use Cases**:
- Organizations with mature, stable ERP processes
- Regulatory environments demanding extensive documentation
- Projects with fixed-price contractual arrangements
- Scenarios where requirements are exceptionally well-understood upfront

### 2. Spiral Model

**Origin**: Developed by Barry Boehm in 1986  
**Core Principle**: Risk-driven iterative development with explicit risk analysis phases  

**Quadrants (per iteration)**:
1. **Planning**: Define objectives, alternatives, and constraints
2. **Risk Analysis**: Identify risks, evaluate probability and impact, develop mitigation strategies
3. **Engineering**: Develop and verify deliverables (prototypes or working increments)
4. **Evaluation**: Stakeholder review, determine if objectives met, plan next iteration

**Strengths in ERP Context**:
- Systematic risk identification and mitigation
- Early problem detection when remediation costs remain manageable
- Continuous stakeholder engagement and feedback incorporation
- Flexible accommodation of changing requirements between iterations
- Suitable for projects with significant technical uncertainty

**Weaknesses in ERP Context**:
- Requires specialized risk management expertise
- Higher methodology overhead increases project costs
- Complex project management compared to simpler models
- Difficulty estimating total cost and timeline upfront
- May be overkill for straightforward implementations

**Recommended Use Cases**:
- Novel integration requirements with uncertain technical feasibility
- Mission-critical deployments where failure is unacceptable
- Projects with significant compliance requirements (HIPAA, SOX, GDPR)
- Complex customizations requiring iterative exploration

### 3. Incremental Development Model

**Origin**: Evolutionary approach emerging in 1980s  
**Core Principle**: Progressive feature delivery through self-contained functional increments  

**Process Flow**:
1. **Increment Definition**: Decompose system into logical, self-contained modules
2. **Prioritization**: Order increments by business value and technical dependencies
3. **Development Cycle**: Each increment follows complete mini-SDLC
4. **Integration**: New increments integrate with previously deployed functionality
5. **Deployment**: Working software deployed progressively

**Strengths in ERP Context**:
- Natural alignment with Odoo's modular architecture
- Early value realization through progressive module deployment
- Distributed risk across multiple smaller releases
- Flexibility to incorporate user feedback from deployed increments
- Progressive budget allocation aligned with demonstrated value
- Each increment serves as learning vehicle informing subsequent development

**Weaknesses in ERP Context**:
- Requires sound architectural planning upfront
- Integration challenges between increments
- Potential for scope creep as stakeholders request additional features
- Cumulative deployment overhead across multiple releases
- Managing user expectations during progressive rollout

**Recommended Use Cases** (Most Odoo Implementations):
- Organizations implementing Odoo with phased module adoption
- Projects requiring early value realization and ROI demonstration
- Dynamic business environments with evolving requirements
- Situations where progressive budget approval is necessary
- Teams learning ERP implementation through experience

---

## 📋 Requirements Engineering Framework

### Functional Requirements Categories

#### 1. Financial Management
- Multi-currency transaction support with real-time exchange rates
- Automated accounts payable/receivable workflows
- General ledger with customizable chart of accounts
- Financial statement generation (Balance Sheet, P&L, Cash Flow)
- Multi-company consolidation
- Bank reconciliation automation
- Tax compliance and reporting

#### 2. Inventory & Supply Chain
- Multi-location inventory tracking
- Support for multiple costing methodologies (FIFO, LIFO, Average)
- Automated reorder point management
- Lot and serial number traceability
- Barcode integration for warehouse operations
- Inter-warehouse transfer management
- Inventory valuation reporting

#### 3. Customer Relationship Management (CRM)
- Contact and company relationship management
- Sales pipeline tracking with customizable stages
- Quote and sales order generation
- After-sales support and service ticket management
- Marketing campaign management
- Lead attribution and conversion tracking

#### 4. Human Resources
- Employee information management
- Time and attendance tracking
- Leave management with approval workflows
- Organizational hierarchy visualization
- Document management (contracts, certifications)
- Integration with payroll processing

#### 5. Manufacturing Operations
- Bill of Materials (BOM) management
- Work order generation and scheduling
- Shop floor control and labor tracking
- Quality control checkpoints
- Material requirements planning (MRP)
- Production cost analysis

### Non-Functional Requirements Categories

#### 1. Performance
- Page load times < 2 seconds under normal load (50 concurrent users)
- Report generation < 30 seconds for standard reports
- Database query optimization for large datasets
- Support for minimum 50 concurrent users without degradation
- Scalability to handle projected 5-year growth

#### 2. Security
- Role-based access control (RBAC) with granular permissions
- Integration with Active Directory/LDAP for authentication
- Multi-factor authentication for privileged accounts
- Data encryption in transit (TLS 1.3) and at rest
- Comprehensive audit logging of all data modifications
- Regular security assessments and penetration testing

#### 3. Availability & Reliability
- 99.5% uptime during business hours
- Recovery Time Objective (RTO): 4 hours
- Recovery Point Objective (RPO): 30 minutes maximum data loss
- Automated daily backups with tested restoration procedures
- Disaster recovery plan with documented procedures
- Redundant application server configuration

#### 4. Usability
- Consistent user interface patterns across modules
- Context-sensitive help and documentation
- Multi-language support for international operations
- WCAG 2.1 Level AA accessibility compliance
- Responsive design for desktop and tablet devices
- Intuitive navigation minimizing training requirements

#### 5. Maintainability
- All customizations following Odoo module inheritance best practices
- No direct core code modifications to preserve upgrade compatibility
- Comprehensive technical documentation
- Automated testing for custom functionality
- Version control for all custom code and configurations
- Configuration management across dev/staging/production environments

---



## 🚀 How to Use This Repository

### For Students

If you're a student studying software engineering:

1. **Review the Comparative Analysis**: Understand how different SDLC models apply to real-world scenarios
2. **Examine the Requirements Framework**: Learn structured approaches to requirements engineering
3. **Study the Risk Management Strategies**: See how proactive risk identification prevents project failures
4. **Analyze the Citation Methodology**: Understand proper academic referencing in technical documents

### For Practitioners

If you're implementing an ERP system:

1. **Evaluate SDLC Suitability**: Use the comparison framework to assess which methodology fits your context
2. **Adapt Requirements Templates**: Leverage the requirements structure for your own specifications
3. **Implement Validation Techniques**: Apply the validation strategies to ensure requirement quality
4. **Learn from Identified Risks**: Proactively address common pitfalls in ERP implementations

### For Educators

If you're teaching software engineering:

1. **Case Study Material**: Use this as a real-world example of SDLC analysis
2. **Requirements Engineering**: Demonstrate structured requirements documentation
3. **Comparative Methodology**: Show students how to evaluate multiple approaches systematically
4. **Academic Writing**: Illustrate proper technical report structure and citation practices

---

## 📖 Citation Guidelines

### Citation Style

This report follows **IEEE citation style** as is standard in computer science and software engineering publications.

### In-Text Citation Format

**Narrative Citation** (author as part of sentence):
```
Royce [2] first described the Waterfall Model in 1970...
```

**Parenthetical Citation** (author in parentheses):
```
The Waterfall Model follows a sequential, phase-gated approach [2].
```

**Multiple Sources**:
```
Several researchers have examined SDLC selection criteria [2], [3], [4].
```

### Reference List Format

**Journal Article**:
```
[16] S. Maalem and N. Zarour, "Challenge of Validation in Requirements Engineering," 
Journal of Innovation in Digital Ecosystems, vol. 3, no. 1, pp. 15-21, 2016.
```

**Book**:
```
[3] I. Sommerville, Software Engineering, 10th ed. Boston, MA: Pearson, 2016.
```

**Online Resource**:
```
[5] "Odoo - Open Source ERP and CRM," Odoo S.A., 2025. [Online]. 
Available: https://www.odoo.com
```

### Citation Best Practices

1. **Cite Original Sources**: Reference primary research rather than secondary summaries when possible
2. **Verify Accessibility**: Ensure cited sources are accessible to readers (prefer open-access when available)
3. **Update Access Dates**: For online resources, include access dates
4. **Maintain Consistency**: Use consistent formatting throughout the reference list
5. **Balance Sources**: Include mix of academic papers, textbooks, and industry documentation

---

## 💻 Technologies Discussed

### Core Technologies

**Odoo ERP Platform**
- Version: 18.0 (latest community and enterprise editions)
- License: LGPL v3 (Community Edition)
- Architecture: Three-tier MVC pattern
- Programming Language: Python 3.10+
- Web Framework: Custom Python framework with ORM

**Database Layer**
- PostgreSQL 14+ (primary database)
- Object-Relational Mapping (ORM) for data abstraction
- Support for advanced features: JSONB, full-text search, GIS

**Application Server**
- Python-based business logic
- WSGI-compliant application server
- Multi-protocol support: XML-RPC, JSON-RPC, HTTP/HTTPS

**Frontend Technologies**
- HTML5, CSS3, JavaScript
- Responsive design for cross-device compatibility
- Modern browser support (Chrome, Firefox, Safari, Edge)

### Development Tools & Methodologies

**Version Control**
- Git for source code management
- GitHub for collaborative development and documentation hosting
- Branching strategies for parallel development

**Documentation Tools**
- Markdown for technical documentation
- Mermaid for diagram generation
- LaTeX for academic typesetting (if needed)

**Testing Frameworks**
- Unit testing: Python unittest, pytest
- Integration testing: Selenium for UI automation
- Load testing: Apache JMeter or Locust

---

## 🔮 Future Work

### Short-Term Extensions (3-6 months)

1. **DevOps Pipeline Implementation**
   - Develop complete CI/CD pipeline for Odoo deployments
   - Container orchestration using Docker and Kubernetes
   - Automated testing integration in deployment workflow
   - Infrastructure-as-Code using Terraform or Ansible

2. **Hybrid Methodology Exploration**
   - Investigate combining Incremental Development for core modules with Agile for flexible components
   - Develop decision framework for selecting methodology per module
   - Create hybrid process documentation and best practices

3. **Advanced Requirements Techniques**
   - Implement behavior-driven development (BDD) for requirements specification
   - Explore user story mapping for visual requirements organization
   - Develop requirements prioritization framework (e.g., Kano model, RICE scoring)

### Medium-Term Research (6-12 months)

4. **Empirical Validation**
   - Conduct case studies with organizations implementing Odoo
   - Gather quantitative data on project outcomes across different SDLC approaches
   - Statistical analysis of success factors and failure modes

5. **AI-Assisted Development**
   - Investigate AI tools for automated test case generation from requirements
   - Explore natural language processing for requirements analysis
   - Evaluate code generation tools for accelerating Odoo module development

6. **Performance Optimization**
   - Benchmark performance across different Odoo deployment architectures
   - Develop optimization guidelines for large-scale implementations
   - Create performance monitoring and alerting framework

### Long-Term Vision (1-2 years)

7. **Comprehensive ERP Implementation Framework**
   - Develop end-to-end methodology combining SDLC selection, requirements engineering, and change management
   - Create toolkit with templates, checklists, and decision trees
   - Package as reusable framework for enterprise implementations

8. **Comparative Analysis Extension**
   - Expand comparison to include Agile methodologies (Scrum, Kanban, SAFe)
   - Investigate DevOps practices in ERP context
   - Explore Low-Code/No-Code platforms for ERP customization

9. **Academic Publication**
   - Refine research findings for conference paper submission
   - Target venues: International Conference on Software Engineering (ICSE), Requirements Engineering Conference (RE)
   - Contribute to body of knowledge on ERP development methodologies

---

## 🎓 Academic Integrity

### Declaration

This project represents original academic work completed for the Introduction to Software Engineering course at NMAM Institute of Technology, Nitte. All analysis, comparisons, and recommendations are based on independent research and critical thinking.

### Source Attribution

- All external sources are properly cited using IEEE citation format
- Direct quotations are clearly marked and attributed
- Paraphrased content includes appropriate citations
- No plagiarism or unauthorized collaboration

### Data Integrity

- All data presented is accurately sourced and verifiable
- Comparative analyses reflect genuine evaluation against stated criteria
- Conclusions are supported by evidence presented in the report
- Limitations and assumptions are transparently acknowledged

### Ethical Considerations

- No confidential or proprietary information is disclosed
- All publicly available sources are used in accordance with their licenses
- Academic honesty principles are upheld throughout the research

---

## 📞 Contact Information

**Student**: Bhuvan Kumar Shetty H  
**USN**: NNM24IS057  
**Institution**: NMAM Institute of Technology, Nitte  
**Department**: Information Science & Engineering  
**Semester**: 4th Semester, Section A  
**Academic Year**: 2025-2026  

**GitHub Repository**: [SDLC-ON-ODOO-ERP-SYSTEM](https://github.com/bkshetty/SDLC-ON-ODOO-ERP-SYSTEM)  

**Course Instructor**: Dr. Jason Elroy Martis  
**Course**: Introduction to Software Engineering (IS1103-1)  

For questions, clarifications, or collaboration opportunities, please:
- Open an issue in this GitHub repository
- Contact through the institution's official channels
- Reference this project in academic discussions or follow-up research

---

## 📚 References

### Primary Academic Sources

[1] B. W. Boehm, "A Spiral Model of Software Development and Enhancement," *IEEE Computer*, vol. 21, no. 5, pp. 61-72, May 1988.

[2] W. W. Royce, "Managing the Development of Large Software Systems," *Proceedings of IEEE WESCON*, vol. 26, no. 8, pp. 328-338, August 1970.

[3] I. Sommerville, *Software Engineering*, 10th ed. Boston, MA: Pearson, 2016.

[4] R. S. Pressman and B. R. Maxim, *Software Engineering: A Practitioner's Approach*, 9th ed. New York: McGraw-Hill Education, 2020.

### Odoo Platform Documentation

[5] "Odoo - Open Source ERP and CRM," Odoo S.A., 2025. [Online]. Available: https://www.odoo.com

[6] "Architecture Overview - Odoo 18.0 Documentation," Odoo S.A., 2024. [Online]. Available: https://www.odoo.com/documentation/

[7] "What is Odoo ERP and How Does It Work," Odiware Technologies, April 2025. [Online].

### SDLC Methodology References

[8-14] Various sources on Waterfall, Spiral, and Incremental models from GeeksforGeeks, TechTarget, TeachingAgile, Scaler Topics, and TryQA

### Requirements Engineering

[15] "Requirements Validation Techniques - Software Engineering," GeeksforGeeks, July 2025. [Online].

[16] S. Maalem and N. Zarour, "Challenge of Validation in Requirements Engineering," *Journal of Innovation in Digital Ecosystems*, vol. 3, no. 1, pp. 15-21, 2016.

[17-18] Requirements validation and verification best practices from AdaptiveUS and ArgonDigital

*Complete reference list available in the main report document.*

---

## 📄 License

This project is submitted for academic purposes as part of coursework requirements at NMAM Institute of Technology, Nitte. The documentation and analysis may be used as a learning reference with appropriate attribution.

### Usage Permissions

✅ **Allowed**:
- Reading and learning from the analysis and methodologies
- Citing this work in academic papers with proper attribution
- Using as a reference for similar projects (with citation)
- Sharing with classmates or colleagues for educational purposes

❌ **Not Allowed**:
- Direct copying or plagiarism of content
- Submission as original work for academic credit
- Commercial use without permission
- Modification and redistribution without attribution

---

## 🏆 Acknowledgments

Special thanks to:
- **Dr. Jason Elroy Martis**: Course instructor providing guidance and feedback
- **NMAM Institute of Technology, Nitte**: Academic institution supporting this research
- **Odoo Community**: For developing and maintaining an excellent open-source ERP platform
- **Software Engineering Researchers**: Whose prior work forms the foundation for this analysis

---

**Last Updated**: February 15, 2026  
**Version**: 1.0  
**Status**: Submitted for Academic Review  

---

*For the latest version of this documentation, visit the [GitHub repository](https://github.com/bkshetty/SDLC-ON-ODOO-ERP-SYSTEM).*
