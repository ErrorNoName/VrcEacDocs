# Outils pour MelonLoader et BepInEx avec VRChat

Ce document présente une liste d'outils utiles pour utiliser MelonLoader ou BepInEx avec VRChat après avoir contourné l'EAC via les méthodes Linux ou de certification.

## Mods Essentiels pour VRChat

### UI et Navigation

1. **VRChatUtilityKit** - [GitHub](https://github.com/loukylor/VRC-Mods)
   - Bibliothèque requise par de nombreux mods
   - Améliore les performances de chargement des mods

2. **UIExpansionKit** - [GitHub](https://github.com/knah/VRCMods)
   - Ajoute des menus personnalisés et des options dans l'interface VRChat
   - Permet d'accéder rapidement aux fonctionnalités des mods

3. **ActionMenu++** - [GitHub](https://github.com/gompo/ActionMenuApi)
   - Étend le menu d'action radial avec de nouvelles fonctionnalités
   - Permet d'ajouter des raccourcis personnalisés

4. **ImmersiveTouch** - [GitHub](https://github.com/DragonPlayerX/ImmersiveTouch)
   - Améliore les interactions tactiles
   - Ajoute des retours haptiques réalistes

### Performance et Optimisation

5. **MemoryManager** - [GitHub](https://github.com/knah/VRCMods)
   - Réduit les fuites de mémoire
   - Améliore la stabilité lors de longues sessions

6. **ParticleAndDynamicBoneLimiter** - [GitHub](https://github.com/knah/VRCMods)
   - Limite les effets de particules gourmands en ressources
   - Réduit la surcharge due aux os dynamiques (Dynamic Bones)

7. **ClearCache** - [GitHub](https://github.com/d-magit/VRChat-Mods)
   - Nettoie automatiquement le cache pour éviter les problèmes de stockage
   - Optimise le chargement des avatars et mondes

8. **FPSCounter** - [GitHub](https://github.com/knah/VRCMods)
   - Affiche un compteur FPS personnalisable
   - Montre les statistiques de performance en temps réel

### Socialisation et Communication

9. **XSOverlay Integration** - [GitHub](https://github.com/DubyaDude/RubyBingle)
   - Intègre les notifications de bureau dans VRChat
   - Permet de voir et répondre aux messages Discord/Telegram sans quitter VR

10. **DesktopCamera** - [GitHub](https://github.com/DragonPlayerX/DesktopCamera)
    - Permet de contrôler la caméra facilement sur Desktop
    - Ajoute des options de caméra avancées

11. **BetterPlayerList** - [GitHub](https://github.com/nitrog0d/BetterPlayerList)
    - Améliore la liste des joueurs avec des informations supplémentaires
    - Offre des options de tri et filtrage avancées

12. **VRCMediaControls** - [GitHub](https://github.com/DragonPlayerX/VRCMediaControls)
    - Améliore les contrôles des vidéos et musiques
    - Ajoute des raccourcis pour le volume et la synchronisation

### Sécurité et Confidentialité

13. **AdvancedSafety** - [GitHub](https://github.com/knah/VRCMods)
    - Protège contre les crashers et les avatars malveillants
    - Offre des options de filtrage personnalisées

14. **ImmobilizePlayerMod** - [GitHub](https://github.com/DragonPlayerX/ImmobilizePlayer)
    - Permet de se figer en place pour éviter les problèmes de mouvement indésirable
    - Utile dans les mondes bondés ou pour prendre des photos

15. **AvatarHider** - [GitHub](https://github.com/knah/VRCMods)
    - Cache sélectivement les avatars pour améliorer les performances
    - Options pour masquer automatiquement les avatars très complexes

### Création de Contenu

16. **CameraPlus** - [GitHub](https://github.com/DragonPlayerX/PlayerRotater)
    - Outils avancés pour la photographie dans VRChat
    - Contrôles de caméra professionnels (profondeur de champ, exposition, etc.)

17. **VRCTools** - [GitHub](https://github.com/Cyril-Xd/VRCTools)
    - Suite d'outils pour les créateurs de contenu
    - Extraction d'informations sur les avatars et les mondes

18. **PostProcessing** - [GitHub](https://github.com/knah/VRCMods)
    - Ajoute des effets post-traitement personnalisables
    - Améliore la qualité visuelle des captures d'écran

## Gestionnaires de Mods

### Pour MelonLoader

1. **MelonManager** - [GitHub](https://github.com/SamuelHDMods/MelonManager)
   - Interface graphique pour gérer les mods MelonLoader
   - Installation, mise à jour et désactivation faciles des mods

2. **MelonLoader Mod Manager** - [GitHub](https://github.com/LavaGang/MelonLoader.ModManager)
   - Outil officiel pour gérer les mods MelonLoader
   - Vérification des dépendances et résolution des conflits

### Pour BepInEx

3. **BepInEx ConfigurationManager** - [GitHub](https://github.com/BepInEx/BepInEx.ConfigurationManager)
   - Interface graphique pour configurer les plugins BepInEx
   - Modification des paramètres en temps réel

4. **BepInEx Plugin Manager** - [GitHub](https://github.com/sinai-dev/BepInEx.Plugin.Manager)
   - Gestion des plugins avec interface utilisateur
   - Organisation et activation/désactivation faciles

## Outils de Développement

1. **Unity Explorer** - [GitHub](https://github.com/sinai-dev/UnityExplorer)
   - Inspecteur de scène Unity en temps réel
   - Utile pour les développeurs de mods et la création d'avatars

2. **RuntimeGraphicsSettings** - [GitHub](https://github.com/knah/VRCMods)
   - Modification des paramètres graphiques en temps réel
   - Déblocage d'options graphiques avancées

3. **Il2CppAssemblyUnhollower** - [GitHub](https://github.com/knah/Il2CppAssemblyUnhollower)
   - Générateur de wrappers pour le développement de mods
   - Essentiel pour les développeurs de mods avancés

4. **MelonLoader.Support** - [GitHub](https://github.com/LavaGang/MelonLoader.Support)
   - Documentation et outils pour le développement de mods
   - Exemples de code et templates

## Conseils d'Utilisation

### Optimiser l'Expérience

1. **Priorité aux mods essentiels**
   - Commencez par les mods de performance et de sécurité
   - Ajoutez progressivement d'autres mods pour identifier les problèmes

2. **Gestion de la mémoire**
   - Ne chargez pas trop de mods simultanément
   - Utilisez MemoryManager pour surveiller l'utilisation de la RAM

3. **Compatibilité**
   - Vérifiez les versions compatibles des mods
   - Certains mods peuvent entrer en conflit - testez-les un par un

### Sécurité

1. **Téléchargez toujours depuis des sources fiables**
   - GitHub des développeurs originaux
   - Forums officiels des communautés de modding

2. **Sauvegardez régulièrement vos configurations**
   - Exportez vos paramètres après une configuration stable
   - Conservez des copies des versions fonctionnelles des mods

3. **Discrétion dans les mondes publics**
   - Évitez de mentionner l'utilisation de mods dans les mondes publics
   - N'utilisez pas de fonctionnalités visiblement modifiées en public

## Dépannage Courant

### Problème: Les mods ne se chargent pas

**Solutions:**
- Vérifiez les logs de MelonLoader/BepInEx pour identifier l'erreur
- Assurez-vous que votre version de MelonLoader/BepInEx est compatible
- Vérifiez les dépendances manquantes

### Problème: Crash au démarrage

**Solutions:**
- Désactivez temporairement tous les mods pour identifier le problème
- Ajoutez les mods un par un pour identifier celui qui cause le crash
- Vérifiez la compatibilité des versions

### Problème: Performances réduites

**Solutions:**
- Utilisez MemoryManager et FPSCounter pour surveiller les performances
- Désactivez les mods gourmands en ressources
- Limitez les particules et os dynamiques avec ParticleAndDynamicBoneLimiter

## Ressources Utiles

- **Discord VRChat Modding Group**: Communauté principale pour le modding VRChat
- **GitHub MelonLoader**: Documentation et mises à jour officielles
- **GitHub BepInEx**: Wiki et guides pour BepInEx
- **VRCMods.com**: Catalogue de mods avec descriptions et liens

*Dernière mise à jour: Juillet 2025*
