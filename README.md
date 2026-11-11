# Atelier WAN – Travaux pratiques (RSI 3)

**Amin MRIRI** – RSI 3 – Institut Supérieur des Études Technologiques de Nabeul  
Enseignant : M. Zied Romdane – Année universitaire 2026-2027

Ce dépôt rassemble mes comptes rendus de travaux pratiques de l'atelier WAN, le projet GNS3 de chaque maquette et la capsule vidéo réalisée avec ActivePresenter. Les maquettes ont été réalisées sous **GNS3 2.2.61** avec des routeurs **Cisco 3725** (Dynamips, IOS 12.4) et des hôtes **VPCS**.

## Sommaire

| N° | TP | Compte rendu | Projet GNS3 / vidéo |
|---|---|---|---|
| 01 | [Configuration d'un routeur avec le protocole BGP](01_TP_BGP) | [PDF](01_TP_BGP/CR_TP_BGP_Amin_MRIRI.pdf) · [Word](01_TP_BGP/CR_TP_BGP_Amin_MRIRI.docx) | [TP_BGP](01_TP_BGP/TP_BGP_Amin_MRIRI.gns3p) |
| 02 | [Redistribution de routes OSPF / RIPv2 / EIGRP (lab)](02_Redistribution_OSPF_RIP_EIGRP) | [PDF](02_Redistribution_OSPF_RIP_EIGRP/CR_TP_Redistribution_OSPF_RIP_EIGRP_Amin_MRIRI.pdf) · [Word](02_Redistribution_OSPF_RIP_EIGRP/CR_TP_Redistribution_OSPF_RIP_EIGRP_Amin_MRIRI.docx) | [TP_Redistribution_OSPF_EIGRP_RIP](02_Redistribution_OSPF_RIP_EIGRP/TP_Redistribution_OSPF_EIGRP_RIP_Amin_MRIRI.gns3p) |
| 03 | [La redistribution de routes : exemple OSPF / RIP du cours](03_Redistribution_cours_OSPF_RIP) | [PDF](03_Redistribution_cours_OSPF_RIP/CR_Redistribution_cours_OSPF_RIP_Amin_MRIRI.pdf) · [Word](03_Redistribution_cours_OSPF_RIP/CR_Redistribution_cours_OSPF_RIP_Amin_MRIRI.docx) | [TP_Redistribution_cours_OSPF_RIP](03_Redistribution_cours_OSPF_RIP/TP_Redistribution_cours_OSPF_RIP_Amin_MRIRI.gns3p) |
| 04 | [TP 1 : Configuration d'un backbone MPLS (Partie I et Partie II)](04_TP1_MPLS) | Partie I : [PDF](04_TP1_MPLS/CR_TP1_MPLS_Partie1_Amin_MRIRI.pdf) · [Word](04_TP1_MPLS/CR_TP1_MPLS_Partie1_Amin_MRIRI.docx)<br>Partie II : [PDF](04_TP1_MPLS/CR_TP1_MPLS_Partie2_Amin_MRIRI.pdf) · [Word](04_TP1_MPLS/CR_TP1_MPLS_Partie2_Amin_MRIRI.docx) | [TP1_MPLS](04_TP1_MPLS/TP1_MPLS_Amin_MRIRI.gns3p) |
| 05 | [TP 2 : Configuration d'un VPN MPLS](05_TP2_VPN_MPLS) | [PDF](05_TP2_VPN_MPLS/CR_TP2_VPN_MPLS_Amin_MRIRI.pdf) · [Word](05_TP2_VPN_MPLS/CR_TP2_VPN_MPLS_Amin_MRIRI.docx) | [TP2_MPLS_VPN](05_TP2_VPN_MPLS/TP2_MPLS_VPN_Amin_MRIRI.gns3p) |
| 06 | [TP 3 : Configuration du DHCP et NAT](06_TP3_DHCP_NAT) | [PDF](06_TP3_DHCP_NAT/CR_TP3_DHCP_NAT_Amin_MRIRI.pdf) · [Word](06_TP3_DHCP_NAT/CR_TP3_DHCP_NAT_Amin_MRIRI.docx) | [TP3_DHCP_NAT](06_TP3_DHCP_NAT/TP3_DHCP_NAT_Amin_MRIRI.gns3p) |
| 07 | [TP 4 : VPN IPsec et tunnel GRE over IPsec](07_TP4_VPN_IPsec_GRE) | VPN IPsec : [PDF](07_TP4_VPN_IPsec_GRE/CR_TP4_VPN_IPsec_Amin_MRIRI.pdf) · [Word](07_TP4_VPN_IPsec_GRE/CR_TP4_VPN_IPsec_Amin_MRIRI.docx)<br>GRE over IPsec : [PDF](07_TP4_VPN_IPsec_GRE/CR_TP4_GRE_over_IPsec_Amin_MRIRI.pdf) · [Word](07_TP4_VPN_IPsec_GRE/CR_TP4_GRE_over_IPsec_Amin_MRIRI.docx) | [TP4_IPsec](07_TP4_VPN_IPsec_GRE/TP4_IPsec_Amin_MRIRI.gns3p) · [TP4_GRE_IPsec](07_TP4_VPN_IPsec_GRE/TP4_GRE_IPsec_Amin_MRIRI.gns3p) |
| 08 | [Capsule vidéo d'un TP avec ActivePresenter (lab BGP)](08_TP_ActivePresenter) | [PDF](08_TP_ActivePresenter/CR_TP_ActivePresenter_Amin_MRIRI.pdf) · [Word](08_TP_ActivePresenter/CR_TP_ActivePresenter_Amin_MRIRI.docx) | [Vidéo MP4](08_TP_ActivePresenter/TP_BGP_Amin_MRIRI.mp4) |

## Contenu des dossiers

- `CR_*.pdf` : compte rendu à lire directement ; `CR_*.docx` : la même version au format Word.
- `*.gns3p` : projet portable GNS3 (topologie, liens et configurations des équipements).
- `08_TP_ActivePresenter/TP_BGP_Amin_MRIRI.mp4` : capsule vidéo de démonstration du lab BGP.

## Ouvrir un projet GNS3

1. Dans GNS3 : **File → Import portable project**, puis choisir le fichier `.gns3p`.
2. Les images Cisco IOS ne sont pas incluses (licence) : associer une image **c3725** (IOS 12.4) dans *Edit → Preferences → Dynamips → IOS routers*.
3. Démarrer les équipements : les configurations sont enregistrées dans le projet.

## Outils utilisés

GNS3 2.2.61 · Dynamips (Cisco 3725) · VPCS · PuTTY · Wireshark · ActivePresenter 10
