# Google_Cloud_Project
Hardening infrastruktury • Firewall • IAM • SCC • Compute Engine • Cloud Storage

Ten projekt przedstawia praktyczne podejście do zabezpieczania środowiska Google Cloud poprzez analizę ryzyka, identyfikację podatności oraz wdrożenie poprawek zgodnych z zasadami Cloud Security Foundations.

# Zakres prac

Analiza ryzyka i konfiguracji w Security Command Center

Identyfikacja i neutralizacja zagrożeń (public bucket, otwarte porty SSH/RDP, niezgodności w VM)

Utworzenie nowej instancji VM z backupu (snapshot)

Aktualizacja zasad Firewall (blokada SSH/RDP/ICMP, deny-all inbound)

Zabezpieczenie środowiska Storage – usunięcie dostępu publicznego

Wdrożenie zasad least privilege w IAM

Walidacja zmian i redukcja High-Risk Findings

# Użyte usługi GCP

Compute Engine – snapshot, stworzenie nowej VM

VPC Firewall – modyfikacja reguł, segmentacja

Cloud Storage – analiza bucketów i kontrola dostępu

IAM – minimalizacja uprawnień

Security Command Center (SCC) – Risk Overview, zgodność z normami

Logging & Monitoring – walidacja zmian


# Google_Cloud_Project
**Infrastructure Hardening • Firewall • IAM • SCC • Compute Engine • Cloud Storage**

This project demonstrates a practical approach to securing a Google Cloud environment through risk analysis, vulnerability identification, and the implementation of fixes compliant with Cloud Security Foundations principles.

---

## Scope of Work

* **Risk and configuration analysis** using Security Command Center.
* **Identification and neutralization of threats**, including public buckets, open SSH/RDP ports, and VM non-compliance.
* **Creation of a new VM instance** from a backup.
* **Updating Firewall rules**, including blocking SSH/RDP/ICMP and implementing a deny-all inbound policy.
* **Securing the Storage environment** by removing public access.
* **Implementing least privilege principles** within IAM.
* **Validation of changes** and reduction of High-Risk Findings.

---

## GCP Services Used

* **Compute Engine** – Snapshots and the creation of a new VM.
* **VPC Firewall** – Rule modification and network segmentation.
* **Cloud Storage** – Bucket analysis and access control.
* **IAM** – Minimization of permissions.
* **Security Command Center (SCC)** – Risk Overview and compliance verification.
* **Logging & Monitoring** – Validation of implemented changes.

