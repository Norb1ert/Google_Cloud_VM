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
