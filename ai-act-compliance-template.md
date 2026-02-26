# AI Act — Compliance by Design Dossier / Dossier de Conformité by Design

**Template version / Version du modèle :** 1.0  
**Reference / Référence :** `[ORG-YYYY-NNN]`  
**Date :** `[YYYY-MM-DD]`  
**Classification / Classification :** `[PUBLIC / INTERNAL / CONFIDENTIAL]`  
**Open Chain Reference / Référence Open Chain :** `[REPO-URL | SBOM-ID]`

---

> **EN** — This template is designed for AI systems developed or distributed under open source licences (Open Chain / OpenChain ISO/IEC 5230). It operationalises the requirements of Regulation (EU) 2024/1689 (AI Act) within a "compliance by design" approach, integrating governance, traceability, and sovereignty requirements from the earliest design stages.
>
> **FR** — Ce modèle est conçu pour les systèmes d'IA développés ou distribués sous licences open source (Open Chain / OpenChain ISO/IEC 5230). Il opérationnalise les exigences du Règlement (UE) 2024/1689 (AI Act) dans une approche « conformité by design », en intégrant dès la conception les exigences de gouvernance, de traçabilité et de souveraineté.

---

## Table of Contents / Table des matières

1. [Document Identification / Identification du document](#1)
2. [System Description / Description du système](#2)
3. [Risk Classification / Classification du risque](#3)
4. [Open Source Governance / Gouvernance Open Source](#4)
5. [Data Governance / Gouvernance des données](#5)
6. [Technical Architecture & Security / Architecture technique et sécurité](#6)
7. [Human Oversight / Supervision humaine](#7)
8. [Transparency & Explainability / Transparence et explicabilité](#8)
9. [Robustness, Accuracy & Cybersecurity / Robustesse, précision et cybersécurité](#9)
10. [Fundamental Rights Impact Assessment / Évaluation d'impact sur les droits fondamentaux](#10)
11. [Conformity Assessment / Évaluation de la conformité](#11)
12. [Post-Market Monitoring / Surveillance post-déploiement](#12)
13. [Incident Management / Gestion des incidents](#13)
14. [Sign-off & Traceability / Validation et traçabilité](#14)
15. [Annexes](#15)

---

## 1 · Document Identification / Identification du document {#1}

| Field / Champ | Value / Valeur |
|---|---|
| **EN** System Name / **FR** Nom du système | `[System Name]` |
| **EN** System Version / **FR** Version du système | `[x.y.z]` |
| **EN** Provider / **FR** Fournisseur | `[Organisation Name]` |
| **EN** Legal Entity / **FR** Entité légale | `[Legal Name, Reg. Number]` |
| **EN** Contact (Art. 46) / **FR** Contact (Art. 46) | `[name@domain.tld]` |
| **EN** Document Owner / **FR** Propriétaire du document | `[Name, Role]` |
| **EN** Applicable Standard / **FR** Norme applicable | EU AI Act (EU) 2024/1689 |
| **EN** Open Source Licence / **FR** Licence open source | `[SPDX identifier, e.g. Apache-2.0]` |
| **EN** OpenChain Conformance / **FR** Conformité OpenChain | `[ISO/IEC 5230 — Yes / In progress / N/A]` |
| **EN** SBOM Available / **FR** SBOM disponible | `[Yes / No — URL or path]` |
| **EN** EU Representative / **FR** Représentant UE | `[Name / N/A]` |

### 1.1 Document History / Historique du document

| Version | Date | Author / Auteur | Changes / Modifications |
|---|---|---|---|
| 1.0 | `YYYY-MM-DD` | `[Name]` | Initial release / Création initiale |
| | | | |

---

## 2 · System Description / Description du système {#2}

### 2.1 EN — Intended Purpose / FR — Finalité prévue

> **EN** Describe the intended purpose of the AI system, including the specific tasks it performs, the domain of use, and the intended user population.
>
> **FR** Décrire la finalité prévue du système d'IA, y compris les tâches spécifiques réalisées, le domaine d'utilisation et la population d'utilisateurs ciblée.

`[Description — max. 500 words / 500 mots]`

### 2.2 EN — Reasonably Foreseeable Misuse / FR — Mésusage raisonnablement prévisible

`[Description of foreseeable misuse scenarios / Scénarios de mésusage prévisibles]`

### 2.3 EN — System Architecture Overview / FR — Vue d'ensemble de l'architecture

| Component / Composant | Technology / Technologie | Licence (SPDX) | Role / Rôle |
|---|---|---|---|
| Core model / Modèle principal | `[e.g. LLM, CNN]` | `[Apache-2.0]` | `[description]` |
| Inference engine / Moteur d'inférence | `[e.g. ONNX Runtime]` | `[MIT]` | `[description]` |
| Data pipeline / Pipeline de données | `[e.g. Apache Spark]` | `[Apache-2.0]` | `[description]` |
| API layer / Couche API | `[e.g. FastAPI]` | `[MIT]` | `[description]` |
| Frontend / Interface | `[e.g. React]` | `[MIT]` | `[description]` |

### 2.4 EN — Deployment Context / FR — Contexte de déploiement

- **EN** Deployment type / **FR** Type de déploiement : `[ On-premise / Cloud / Hybrid / Edge ]`
- **EN** Target geography / **FR** Géographie cible : `[ EU / National / Global ]`
- **EN** Operational environment / **FR** Environnement opérationnel : `[description]`
- **EN** Interfaces with critical infrastructure / **FR** Interfaces avec infrastructure critique : `[ Yes / No — detail ]`

---

## 3 · Risk Classification / Classification du risque {#3}

### 3.1 EN — AI Act Risk Level Determination / FR — Détermination du niveau de risque AI Act

| Criterion / Critère | Assessment / Évaluation |
|---|---|
| **EN** Prohibited practice (Art. 5) / **FR** Pratique interdite (Art. 5) | `[ Yes — STOP / No — continue ]` |
| **EN** High-risk category (Annex III) / **FR** Catégorie à haut risque (Annexe III) | `[ Yes / No / Borderline ]` |
| **EN** High-risk (product safety, Annex I) / **FR** Haut risque (sécurité produit, Annexe I) | `[ Yes / No ]` |
| **EN** General-purpose AI (Art. 3(63)) / **FR** IA à usage général (Art. 3(63)) | `[ Yes / No ]` |
| **EN** GPAI with systemic risk (Art. 51) / **FR** GPAI à risque systémique (Art. 51) | `[ Yes / No / N/A ]` |
| **EN** Limited risk (transparency, Art. 50) / **FR** Risque limité (transparence, Art. 50) | `[ Yes / No ]` |
| **EN** Minimal risk / **FR** Risque minimal | `[ Yes / No ]` |

### 3.2 EN — Final Classification / FR — Classification finale

**Risk Level / Niveau de risque :** `[ PROHIBITED / HIGH / GPAI-SYSTEMIC / LIMITED / MINIMAL ]`

**EN** Justification / **FR** Justification :
`[Detailed justification with reference to specific articles / Justification détaillée avec référence aux articles applicables]`

### 3.3 EN — Open Source Exemption Analysis (Art. 2(12)) / FR — Analyse d'exemption open source (Art. 2(12))

> **EN** The AI Act provides limited exemptions for open source components. Assess applicability carefully, especially where the system is deployed in a professional or high-risk context.
>
> **FR** L'AI Act prévoit des exemptions limitées pour les composants open source. Évaluer attentivement l'applicabilité, notamment lorsque le système est déployé dans un contexte professionnel ou à haut risque.

- **EN** Exemption claimed / **FR** Exemption revendiquée : `[ Yes / No / Partial ]`
- **EN** Basis / **FR** Fondement : `[Art. 2(12) — description]`
- **EN** Limitations / **FR** Limitations : `[description]`

---

## 4 · Open Source Governance / Gouvernance Open Source {#4}

### 4.1 EN — OpenChain Compliance / FR — Conformité OpenChain

| Requirement / Exigence | Status / Statut | Evidence / Preuve |
|---|---|---|
| FOSS policy documented / Politique FOSS documentée | `[ ✓ / ✗ / In progress ]` | `[link/path]` |
| FOSS competence program / Programme de compétences FOSS | `[ ✓ / ✗ / In progress ]` | `[link/path]` |
| FOSS review process / Processus de revue FOSS | `[ ✓ / ✗ / In progress ]` | `[link/path]` |
| SBOM generation / Génération du SBOM | `[ ✓ / ✗ / In progress ]` | `[link/path]` |
| Contribution compliance / Conformité des contributions | `[ ✓ / ✗ / In progress ]` | `[link/path]` |
| Community oversight / Supervision communautaire | `[ ✓ / ✗ / In progress ]` | `[link/path]` |

### 4.2 EN — SBOM (Software Bill of Materials) / FR — Nomenclature logicielle

- **EN** SBOM format / **FR** Format SBOM : `[ SPDX-2.3 / CycloneDX-1.4 / SWID ]`
- **EN** SBOM location / **FR** Localisation SBOM : `[URL or repository path]`
- **EN** Update frequency / **FR** Fréquence de mise à jour : `[e.g. at each release / à chaque release]`
- **EN** Includes AI model provenance / **FR** Inclut la provenance du modèle IA : `[ Yes / No ]`
- **EN** Includes training dataset references / **FR** Inclut les références aux jeux de données : `[ Yes / No ]`

### 4.3 EN — Supply Chain & Dependency Audit / FR — Audit de la chaîne d'approvisionnement

`[Description of processes for vetting upstream dependencies, vulnerability scanning, licence compatibility checks / Description des processus de vérification des dépendances amont, d'analyse de vulnérabilités, de vérification de compatibilité des licences]`

---

## 5 · Data Governance / Gouvernance des données {#5}

### 5.1 EN — Training Data / FR — Données d'entraînement

| Dataset / Jeu de données | Source | Licence (SPDX) | Volume | Preprocessing / Prétraitement |
|---|---|---|---|---|
| `[Name]` | `[origin]` | `[licence]` | `[size]` | `[steps]` |

### 5.2 EN — Data Quality Measures / FR — Mesures de qualité des données

| Measure / Mesure | Method / Méthode | Threshold / Seuil | Status / Statut |
|---|---|---|---|
| Bias assessment / Évaluation des biais | `[method]` | `[threshold]` | `[ Pass / Fail / Pending ]` |
| Completeness / Complétude | `[method]` | `[threshold]` | `[ Pass / Fail / Pending ]` |
| Representativeness / Représentativité | `[method]` | `[threshold]` | `[ Pass / Fail / Pending ]` |
| Data poisoning check / Vérification empoisonnement | `[method]` | `[threshold]` | `[ Pass / Fail / Pending ]` |

### 5.3 EN — GDPR Alignment / FR — Alignement RGPD

- **EN** Personal data processed / **FR** Données personnelles traitées : `[ Yes / No ]`
- **EN** Lawful basis / **FR** Base légale : `[Art. 6 GDPR — specify]`
- **EN** DPIA conducted / **FR** AIPD réalisée : `[ Yes / No — reference ]`
- **EN** Data retention / **FR** Conservation des données : `[duration and policy]`
- **EN** Data localisation (EU) / **FR** Localisation des données (UE) : `[ Yes / No / Hybrid ]`

### 5.4 EN — Data Sovereignty / FR — Souveraineté des données

`[Description of measures ensuring data sovereignty, including storage location, access controls, encryption, and applicable legal frameworks / Description des mesures garantissant la souveraineté des données, incluant localisation, contrôles d'accès, chiffrement et cadres légaux applicables]`

---

## 6 · Technical Architecture & Security / Architecture technique et sécurité {#6}

### 6.1 EN — System Design Principles / FR — Principes de conception système

| Principle / Principe | Implementation / Implémentation | Evidence / Preuve |
|---|---|---|
| Privacy by design / Vie privée by design | `[description]` | `[link]` |
| Security by design / Sécurité by design | `[description]` | `[link]` |
| Fail-safe defaults / Défauts sûrs | `[description]` | `[link]` |
| Minimal footprint / Empreinte minimale | `[description]` | `[link]` |
| Auditability / Auditabilité | `[description]` | `[link]` |
| Sovereign architecture / Architecture souveraine | `[description]` | `[link]` |

### 6.2 EN — Model Card / FR — Fiche modèle

- **EN** Model type / **FR** Type de modèle : `[e.g. transformer, CNN, ensemble]`
- **EN** Training framework / **FR** Framework d'entraînement : `[e.g. PyTorch, TensorFlow]`
- **EN** Model size / **FR** Taille du modèle : `[parameters / disk size]`
- **EN** Quantisation applied / **FR** Quantisation appliquée : `[ Yes — format / No ]`
- **EN** Inference hardware / **FR** Matériel d'inférence : `[CPU / GPU / NPU — spec]`
- **EN** Performance metrics / **FR** Métriques de performance : `[Accuracy, F1, etc. — values]`
- **EN** Known limitations / **FR** Limitations connues : `[description]`

### 6.3 EN — Security Assessment / FR — Évaluation de la sécurité

| Threat / Menace | Likelihood / Probabilité | Impact | Mitigation / Atténuation |
|---|---|---|---|
| Adversarial attacks / Attaques adversariales | `[H/M/L]` | `[H/M/L]` | `[measure]` |
| Data poisoning / Empoisonnement des données | `[H/M/L]` | `[H/M/L]` | `[measure]` |
| Model extraction / Extraction du modèle | `[H/M/L]` | `[H/M/L]` | `[measure]` |
| Prompt injection (if LLM) | `[H/M/L]` | `[H/M/L]` | `[measure]` |
| Supply chain compromise / Compromission chaîne | `[H/M/L]` | `[H/M/L]` | `[measure]` |
| Inference attacks / Attaques d'inférence | `[H/M/L]` | `[H/M/L]` | `[measure]` |

### 6.4 EN — Cryptographic Controls / FR — Contrôles cryptographiques

| Control / Contrôle | Algorithm / Algorithme | Standard | Status / Statut |
|---|---|---|---|
| Data at rest / Données au repos | `[e.g. AES-256-GCM]` | `[FIPS 140-3]` | `[ ✓ / ✗ ]` |
| Data in transit / Données en transit | `[e.g. TLS 1.3]` | `[RFC 8446]` | `[ ✓ / ✗ ]` |
| Model signing / Signature du modèle | `[e.g. Ed25519]` | `[RFC 8032]` | `[ ✓ / ✗ ]` |
| Audit log integrity / Intégrité journaux | `[e.g. SHA-3-256]` | `[FIPS 202]` | `[ ✓ / ✗ ]` |

---

## 7 · Human Oversight / Supervision humaine {#7}

### 7.1 EN — Oversight Mechanisms / FR — Mécanismes de supervision (Art. 14)

| Mechanism / Mécanisme | Description | Responsible / Responsable |
|---|---|---|
| Human-in-the-loop | `[description]` | `[role]` |
| Human-on-the-loop | `[description]` | `[role]` |
| Human-in-command | `[description]` | `[role]` |
| Override capability / Capacité de dérogation | `[description]` | `[role]` |
| Shutdown procedure / Procédure d'arrêt | `[description]` | `[role]` |

### 7.2 EN — Human Reviewer Qualifications / FR — Qualifications des superviseurs humains

`[Description of required qualifications, training, and responsibilities for human reviewers / Description des qualifications requises, de la formation et des responsabilités des superviseurs humains]`

### 7.3 EN — Automation Bias Mitigation / FR — Atténuation du biais d'automatisation

`[Measures taken to prevent over-reliance on AI outputs and ensure effective human oversight / Mesures prises pour prévenir la surconfiance dans les sorties IA et garantir une supervision humaine effective]`

---

## 8 · Transparency & Explainability / Transparence et explicabilité {#8}

### 8.1 EN — User Transparency Obligations / FR — Obligations de transparence envers les utilisateurs (Art. 13, 50)

| Obligation / Obligation | Method / Méthode | Status / Statut |
|---|---|---|
| AI system disclosure / Divulgation système IA | `[description]` | `[ ✓ / ✗ / N/A ]` |
| Capability & limitations notice | `[description]` | `[ ✓ / ✗ / N/A ]` |
| Human contact point / Point de contact humain | `[description]` | `[ ✓ / ✗ / N/A ]` |
| Decision explanation / Explication décision | `[description]` | `[ ✓ / ✗ / N/A ]` |
| Right to contest / Droit à contestation | `[description]` | `[ ✓ / ✗ / N/A ]` |

### 8.2 EN — Explainability Techniques / FR — Techniques d'explicabilité

| Technique | Scope / Portée | Output / Sortie | Stakeholder / Partie prenante |
|---|---|---|---|
| `[e.g. SHAP / LIME / Attention maps]` | `[global / local]` | `[format]` | `[user / auditor / regulator]` |

### 8.3 EN — Technical Documentation (Art. 11) / FR — Documentation technique (Art. 11)

`[Confirm that technical documentation covers: general description, design specifications, training methodologies, validation results, known limitations, monitoring procedures — or indicate gaps / Confirmer que la documentation technique couvre : description générale, spécifications de conception, méthodologies d'entraînement, résultats de validation, limitations connues, procédures de monitoring — ou indiquer les lacunes]`

---

## 9 · Robustness, Accuracy & Cybersecurity / Robustesse, précision et cybersécurité {#9}

### 9.1 EN — Performance Benchmarks / FR — Benchmarks de performance (Art. 15)

| Metric / Métrique | Baseline / Référence | Target / Cible | Achieved / Atteint | Test Set / Jeu de test |
|---|---|---|---|---|
| Accuracy / Précision | `[value]` | `[value]` | `[value]` | `[description]` |
| F1 Score | `[value]` | `[value]` | `[value]` | `[description]` |
| Fairness metric / Métrique d'équité | `[value]` | `[value]` | `[value]` | `[description]` |
| Latency / Latence | `[value]` | `[value]` | `[value]` | `[description]` |
| Availability / Disponibilité | `[value]` | `[value]` | `[value]` | `[description]` |

### 9.2 EN — Robustness Testing / FR — Tests de robustesse

| Test Type / Type de test | Tool / Outil | Result / Résultat | Date |
|---|---|---|---|
| Adversarial robustness | `[e.g. Foolbox, ART]` | `[Pass / Fail]` | `YYYY-MM-DD` |
| Distribution shift | `[method]` | `[Pass / Fail]` | `YYYY-MM-DD` |
| Edge case coverage / Cas limites | `[method]` | `[Pass / Fail]` | `YYYY-MM-DD` |
| Red teaming | `[method]` | `[Pass / Fail]` | `YYYY-MM-DD` |

### 9.3 EN — Cybersecurity Framework Alignment / FR — Alignement cadre cybersécurité

- **EN** Framework applied / **FR** Cadre appliqué : `[ ANSSI / NIST CSF / ISO 27001 / NIS2 / Other ]`
- **EN** Penetration testing / **FR** Tests de pénétration : `[ Date, scope, result ]`
- **EN** Vulnerability disclosure policy / **FR** Politique de divulgation : `[ URL ]`
- **EN** CVE monitoring / **FR** Surveillance CVE : `[ Tool / Process ]`
- **EN** NIS2 applicability / **FR** Applicabilité NIS2 : `[ Yes / No / Under assessment ]`

---

## 10 · Fundamental Rights Impact Assessment / Évaluation d'impact sur les droits fondamentaux {#10}

### 10.1 EN — FRIA Screening / FR — Criblage AIFDR (Art. 27)

> **EN** Required for deployers of high-risk AI systems in specific sectors. Complete for all systems as best practice.
>
> **FR** Obligatoire pour les déployeurs de systèmes IA à haut risque dans des secteurs spécifiques. À compléter pour tous les systèmes en bonne pratique.

| Right / Droit | Risk identified / Risque identifié | Severity / Gravité | Mitigation / Atténuation |
|---|---|---|---|
| Non-discrimination / Non-discrimination | `[Yes/No — description]` | `[H/M/L]` | `[measure]` |
| Privacy / Vie privée | `[Yes/No — description]` | `[H/M/L]` | `[measure]` |
| Freedom of expression / Liberté d'expression | `[Yes/No — description]` | `[H/M/L]` | `[measure]` |
| Right to explanation / Droit à l'explication | `[Yes/No — description]` | `[H/M/L]` | `[measure]` |
| Access to justice / Accès à la justice | `[Yes/No — description]` | `[H/M/L]` | `[measure]` |
| Human dignity / Dignité humaine | `[Yes/No — description]` | `[H/M/L]` | `[measure]` |
| Labour rights / Droits du travail | `[Yes/No — description]` | `[H/M/L]` | `[measure]` |

### 10.2 EN — Equality & Non-Discrimination Audit / FR — Audit égalité et non-discrimination

`[Results of bias testing across protected characteristics: gender, age, ethnicity, disability, etc. / Résultats des tests de biais sur les caractéristiques protégées : genre, âge, ethnicité, handicap, etc.]`

---

## 11 · Conformity Assessment / Évaluation de la conformité {#11}

### 11.1 EN — Assessment Route / FR — Voie d'évaluation (Art. 43-44)

| Route / Voie | Applicable / Applicable | Details / Détails |
|---|---|---|
| Internal assessment / Auto-évaluation (Art. 43(2)) | `[ Yes / No ]` | `[description]` |
| Notified body / Organisme notifié (Art. 43(1)) | `[ Yes / No ]` | `[body name / nom organisme]` |
| Standards harmonisées (Annex II) | `[ Yes / No ]` | `[standards list]` |
| Common specifications / Spécifications communes | `[ Yes / No ]` | `[reference]` |

### 11.2 EN — EU Declaration of Conformity / FR — Déclaration UE de conformité (Art. 47)

- **EN** DoC issued / **FR** DoC émise : `[ Yes / No / In preparation ]`
- **EN** DoC reference / **FR** Référence DoC : `[document ID]`
- **EN** DoC date / **FR** Date DoC : `[YYYY-MM-DD]`
- **EN** Signatory / **FR** Signataire : `[Name, Title]`

### 11.3 EN — EU AI Office Registration / FR — Enregistrement Bureaux IA UE (Art. 49)

- **EN** Registration required / **FR** Enregistrement requis : `[ Yes / No ]`
- **EN** EU AI Database ID / **FR** ID Base de données IA UE : `[ID or N/A]`
- **EN** Registration date / **FR** Date d'enregistrement : `[YYYY-MM-DD or N/A]`

---

## 12 · Post-Market Monitoring / Surveillance post-déploiement {#12}

### 12.1 EN — Monitoring Plan / FR — Plan de surveillance (Art. 72)

| Activity / Activité | Frequency / Fréquence | Responsible / Responsable | Tool / Outil |
|---|---|---|---|
| Performance monitoring / Surveillance performance | `[e.g. Continuous]` | `[role]` | `[tool]` |
| Bias drift monitoring / Dérive des biais | `[e.g. Weekly]` | `[role]` | `[tool]` |
| Data distribution shift | `[e.g. Monthly]` | `[role]` | `[tool]` |
| User feedback analysis | `[e.g. Monthly]` | `[role]` | `[tool]` |
| Dependency vulnerability scan | `[e.g. Daily]` | `[role]` | `[tool]` |
| Regulatory update review | `[e.g. Quarterly]` | `[role]` | `[tool]` |

### 12.2 EN — Serious Incident Reporting / FR — Notification d'incidents graves (Art. 73)

- **EN** Reporting authority / **FR** Autorité de notification : `[National market surveillance authority]`
- **EN** Reporting timeline / **FR** Délai de notification : `[15 working days for serious incidents]`
- **EN** Escalation procedure / **FR** Procédure d'escalade : `[link/reference]`

### 12.3 EN — Version & Update Management / FR — Gestion des versions et mises à jour

`[Policy for managing model updates, retraining triggers, version deprecation, and communication to users / Politique de gestion des mises à jour du modèle, déclencheurs de réentraînement, dépréciation de version et communication aux utilisateurs]`

---

## 13 · Incident Management / Gestion des incidents {#13}

### 13.1 EN — Incident Classification / FR — Classification des incidents

| Severity / Gravité | Definition / Définition | Response Time / Délai réponse | Notification / Notification |
|---|---|---|---|
| Critical / Critique | Fundamental rights violation, safety failure | < 4h | Authority + Users |
| High / Élevé | Significant accuracy/fairness degradation | < 24h | Authority |
| Medium / Moyen | Performance degradation, minor bias | < 72h | Internal |
| Low / Faible | Cosmetic issues, minor anomalies | < 7 days | Log only |

### 13.2 EN — Incident Register Template / FR — Registre des incidents (modèle)

| Field / Champ | Value / Valeur |
|---|---|
| Incident ID | `INC-YYYY-NNN` |
| Date detected / Date de détection | `YYYY-MM-DD HH:MM` |
| Severity / Gravité | `[ Critical / High / Medium / Low ]` |
| Description | `[description]` |
| Root cause / Cause racine | `[analysis]` |
| Affected users / Utilisateurs affectés | `[number / category]` |
| Mitigation applied / Atténuation appliquée | `[actions]` |
| Resolution date / Date résolution | `YYYY-MM-DD` |
| Authority notified / Autorité notifiée | `[ Yes / No — date ]` |
| Lessons learned / Leçons apprises | `[description]` |

---

## 14 · Sign-off & Traceability / Validation et traçabilité {#14}

### 14.1 EN — Review & Approval / FR — Revue et approbation

| Role / Rôle | Name / Nom | Signature | Date |
|---|---|---|---|
| AI System Owner / Responsable système IA | `[name]` | `____________` | `YYYY-MM-DD` |
| Data Protection Officer / DPO | `[name]` | `____________` | `YYYY-MM-DD` |
| Chief Information Security Officer | `[name]` | `____________` | `YYYY-MM-DD` |
| Open Source Compliance Officer | `[name]` | `____________` | `YYYY-MM-DD` |
| Legal Counsel / Conseil juridique | `[name]` | `____________` | `YYYY-MM-DD` |
| Executive Sponsor / Sponsor exécutif | `[name]` | `____________` | `YYYY-MM-DD` |

### 14.2 EN — Cryptographic Document Integrity / FR — Intégrité cryptographique du document

```
Document hash (SHA-256) / Empreinte SHA-256 : [hash value]
Signing key fingerprint / Empreinte clé de signature : [fingerprint]
Signed by / Signé par : [name, role]
Timestamp / Horodatage : [ISO 8601]
GPG/PGP signature : [detached .sig file reference]
```

### 14.3 EN — Retention & Archival / FR — Conservation et archivage

- **EN** Retention period / **FR** Durée de conservation : `[ 10 years minimum per Art. 18 ]`
- **EN** Archive location / **FR** Lieu d'archivage : `[path / system]`
- **EN** Access control / **FR** Contrôle d'accès : `[policy reference]`
- **EN** Backup frequency / **FR** Fréquence de sauvegarde : `[policy]`

---

## 15 · Annexes {#15}

### Annex A — Glossary / Annexe A — Glossaire

| Term / Terme | Definition EN | Définition FR |
|---|---|---|
| AI System | A machine-based system that, for a given set of objectives, infers from inputs how to generate outputs (EU AI Act, Art. 3(1)) | Système fondé sur des machines qui, pour un ensemble d'objectifs donnés, déduit à partir de données d'entrée la façon de générer des sorties (AI Act UE, Art. 3(1)) |
| High-risk AI | AI system listed in Annex III or posing significant safety risks per Annex I | Système d'IA figurant à l'Annexe III ou présentant des risques importants pour la sécurité selon l'Annexe I |
| GPAI | General-Purpose AI model trained on broad data, capable of diverse tasks | Modèle d'IA à usage général entraîné sur un large corpus, capable de tâches diverses |
| OpenChain | ISO/IEC 5230 standard for open source licence compliance | Norme ISO/IEC 5230 pour la conformité aux licences open source |
| SBOM | Software Bill of Materials — inventory of all software components | Nomenclature logicielle — inventaire de tous les composants logiciels |
| FRIA | Fundamental Rights Impact Assessment (Art. 27 AI Act) | Évaluation d'impact sur les droits fondamentaux (Art. 27 AI Act) |
| DoC | EU Declaration of Conformity (Art. 47 AI Act) | Déclaration UE de conformité (Art. 47 AI Act) |
| By Design | Approach integrating compliance requirements at the earliest design stage | Approche intégrant les exigences de conformité dès les premières étapes de conception |

### Annex B — Applicable Regulations & Standards / Annexe B — Réglementations et normes applicables

| Reference | Title | Relevance / Pertinence |
|---|---|---|
| (EU) 2024/1689 | EU Artificial Intelligence Act | Primary regulation / Règlement principal |
| (EU) 2016/679 | GDPR | Data protection / Protection des données |
| (EU) 2022/2555 | NIS2 Directive | Cybersecurity / Cybersécurité |
| ISO/IEC 5230:2020 | OpenChain (FOSS Compliance) | Open source governance / Gouvernance OS |
| ISO/IEC 42001:2023 | AI Management System | AI governance / Gouvernance IA |
| ISO/IEC 27001:2022 | Information Security | Security management / Management sécurité |
| ISO/IEC 25010:2023 | System quality (SQuaRE) | Quality model / Modèle qualité |
| NIST AI RMF 1.0 | AI Risk Management Framework | Risk management / Gestion des risques |
| CRA (EU) 2024/2847 | Cyber Resilience Act | Product security / Sécurité produit |
| ETSI EN 303 645 | IoT/Edge security baseline | If edge deployment / Si déploiement edge |

### Annex C — Checklist Summary / Annexe C — Résumé de la liste de contrôle

#### High-Risk AI Systems / Systèmes IA à haut risque

- [ ] Risk management system established (Art. 9) / Système de gestion des risques établi (Art. 9)
- [ ] Data governance procedures (Art. 10) / Procédures de gouvernance des données (Art. 10)
- [ ] Technical documentation complete (Art. 11) / Documentation technique complète (Art. 11)
- [ ] Record-keeping enabled (Art. 12) / Journalisation activée (Art. 12)
- [ ] Transparency to users (Art. 13) / Transparence envers les utilisateurs (Art. 13)
- [ ] Human oversight measures (Art. 14) / Mesures de supervision humaine (Art. 14)
- [ ] Accuracy, robustness, cybersecurity (Art. 15) / Précision, robustesse, cybersécurité (Art. 15)
- [ ] Conformity assessment completed (Art. 43) / Évaluation de la conformité réalisée (Art. 43)
- [ ] EU DoC issued (Art. 47) / DoC UE émise (Art. 47)
- [ ] CE marking affixed (Art. 48) / Marquage CE apposé (Art. 48)
- [ ] EU AI Database registration (Art. 49) / Enregistrement base de données UE (Art. 49)
- [ ] Post-market monitoring plan (Art. 72) / Plan de surveillance post-marché (Art. 72)
- [ ] Serious incident reporting ready (Art. 73) / Notification d'incidents graves prête (Art. 73)

#### Open Source Specifics / Spécificités Open Source

- [ ] OpenChain compliance assessed / Conformité OpenChain évaluée
- [ ] SBOM generated and published / SBOM généré et publié
- [ ] Licence compatibility verified / Compatibilité des licences vérifiée
- [ ] Open source exemption scope defined / Périmètre d'exemption open source défini
- [ ] Community security disclosure policy / Politique de divulgation sécurité communautaire
- [ ] Upstream vulnerability monitoring / Surveillance des vulnérabilités amont
- [ ] Contribution governance documented / Gouvernance des contributions documentée

### Annex D — References & Tools / Annexe D — Références et outils

| Resource / Ressource | URL |
|---|---|
| EU AI Act official text / Texte officiel AI Act UE | https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689 |
| EU AI Office / Bureau IA UE | https://digital-strategy.ec.europa.eu/en/policies/european-approach-artificial-intelligence |
| OpenChain Project | https://www.openchainproject.org |
| SPDX SBOM standard | https://spdx.dev |
| CycloneDX SBOM standard | https://cyclonedx.org |
| NIST AI RMF | https://airc.nist.gov/RMF_Overview |
| ISO 42001 | https://www.iso.org/standard/81230.html |
| ANSSI AI Security | https://www.ssi.gouv.fr |
| AI Verify Foundation | https://aiverifyfoundation.sg |

---

*Template prepared by / Modèle préparé par : Technical Author / Rédacteur technique*  
*Inspired by / Inspiré de : EU AI Act (EU) 2024/1689, OpenChain ISO/IEC 5230, ISO/IEC 42001:2023*  
*Licence / Licence : CC BY-SA 4.0 — Attribution required / Attribution requise*  
*Last updated / Dernière mise à jour : 2026-02-26*
