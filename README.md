Etape 1:
Vérification de l'intégrité du fichier Mobexler.ova en calculant son empreinte numérique SHA256 via PowerShell.
<img width="1437" height="508" alt="image" src="https://github.com/user-attachments/assets/cf0e983f-0354-455f-acd3-93bb6ca4e98f" />

Etape 2:
Importation de l'appareil virtuel (OVA) dans l'interface de gestion de VirtualBox.
<img width="649" height="587" alt="image" src="https://github.com/user-attachments/assets/292c3ed9-4bb8-4a23-b353-d553e6726cb7" />


Configuration de la première interface réseau en mode NAT pour permettre l'accès à internet depuis la machine virtuelle.
<img width="970" height="652" alt="image" src="https://github.com/user-attachments/assets/1250aa1b-394f-4db0-b221-b8aec9515b90" />


Paramétrage de la deuxième interface en mode « Réseau privé hôte » pour la communication directe entre l'hôte et la VM.
<img width="967" height="644" alt="image" src="https://github.com/user-attachments/assets/4f9f0524-9dac-4675-9ed9-5b358b725274" />

etape 3:

Interface de connexion (Login) du système d'exploitation Mobexler une fois la machine démarrée.
<img width="1546" height="894" alt="image" src="https://github.com/user-attachments/assets/aeb7fa85-db75-4bed-bf8b-6193d75df94b" />

etape 4:

Utilisation de la commande ip a pour lister et vérifier l'état des interfaces réseau actives sur le système.
<img width="1595" height="870" alt="image" src="https://github.com/user-attachments/assets/03972e38-e545-422d-8da6-537c64ad907d" />

Consultation de la table de routage IP pour confirmer la passerelle par défaut et la connectivité réseau.
<img width="1517" height="191" alt="image" src="https://github.com/user-attachments/assets/4ea605e6-cbd9-4777-8ff6-125a64bf54e6" />

Test de connectivité externe réussi vers les serveurs DNS de Google (8.8.8.8) via une commande ping.
<img width="1368" height="337" alt="image" src="https://github.com/user-attachments/assets/b32fb52f-7e40-46e8-9a89-d49741fb7cd1" />
<img width="1554" height="398" alt="image" src="https://github.com/user-attachments/assets/d892503f-704f-4f4a-beff-acc404bcfccc" />


etape 5:

Création d'un instantané (snapshot) nommé « CLEAN_BASELINE_TP1 » dans VirtualBox pour sauvegarder l'état initial propre de la machine virtuelle.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/51b53be2-95f3-4bdf-a427-4e2c6b7e0808" />


etape 6:

Première tentative de détection d'un appareil Android où le statut apparaît comme « non autorisé ».
<img width="1606" height="1055" alt="image" src="https://github.com/user-attachments/assets/3d4e9347-ba7d-4af6-bfca-1e8ed1ece2ec" />

Confirmation de la connexion ADB avec l'appareil Android désormais correctement reconnu et autorisé.
<img width="975" height="121" alt="image" src="https://github.com/user-attachments/assets/3fab7e55-4526-4537-9d86-a558631005a6" />
