# Rozšířená realita na webu

## [Prezentace](https://docs.google.com/presentation/d/1wiN_Lsa_bpyaS2wpj8AHzXRh36euV2b-tfG8Oa_SC6I/edit?usp=sharing)


# Web AR knihovny
### [Three.js](https://threejs.org/) + [AR.js](https://ar-js-org.github.io/AR.js-Docs/)
- **Popis:** AR.js je open-source knihovna postavená na Three.js a umožňuje markerless AR pomocí WebXR API

- **Funkce:**
    - podpora markerless AR (detekce rovinných povrchů pomocí WebXR)
    - renderování 3D objektů ve scéně pomocí Three.js
    - dobře zdokumentované a snadné použití
    - podporuje marker-based AR (fiduciální markery, jako jsou vzory typu Hiro nebo custom AR markery)
    - podpora image tracking (rozpoznání a sledování 2D obrazů).

- **Výhody:**
    - rychlost
    - funguje na většině moderních zařízení podporujících WebXR

- **Použití:** hodí se pro jednoduché AR projekty přímo v prohlížeči

### [A-Frame](https://aframe.io/)
- **Popis:** A-Frame je framework založený na HTML a Three.js pro tvorbu VR/AR aplikací, který podporuje WebXR

- **Funkce:**
    - jednoduchý zápis AR scény pomocí HTML značek (```<a-scene>```) 
    - podpora markerless AR pomocí WebXR

- **Výhody:**
    - snadná integrace pro vývojáře s minimálními znalostmi JavaScriptu
    - rozšiřitelné pomocí komponent
    
- **Použití:** skvělé pro rychlé prototypování a vizuálně orientované AR aplikace

### [Babylon.js](https://doc.babylonjs.com/)
- **Popis:** Babylon.js je výkonná 3D grafická knihovna, která podporuje AR přes WebXR

- **Funkce:**
    - robustní podpora WebXR pro markerless AR (detekce rovinných povrchů)
    - pokročilé renderovací možnosti pro složité scény

- **Výhody:**
    - vhodné pro složitější projekty s většími nároky na grafiku
    
- **Použití:** pro pokročilé aplikace AR a VR s pokročilým interaktivním obsahem

### [8thWall](https://www.8thwall.com/)
- **Popis:** komerční platforma pro AR aplikace, která nabízí markerless AR přímo v prohlížeči bez nutnosti použití WebXR

- **Funkce:**
    - podpora různých typů AR na široké škále zařízení (včetně iOS bez WebXR)
    - vestavěné nástroje pro detekci povrchů, odhad hloubky a přizpůsobení světelným podmínkám

- **Výhody:**
    - nejlepší výkon na trhu díky optimalizacím
    - široká podpora zařízení

- **Použití:** pro profesionální a komerční AR aplikace

### [MindAR](https://hiukim.github.io/mind-ar-js-doc/)
- **Popis:** nenáročná knihovna zaměřená na markerless AR

- **Funkce:**
    - podpora detekce 2D obrazů a povrchů
    - kompatibilní s Three.js i A-Frame

- **Výhody:**
    - nenáročnost a rychlost
    - snadno použitelná pro jednoduché AR aplikace

- **Použití:** pro vývoj aplikací s nízkými nároky na výkon

# WebXR API
- WebXR (Web Extended Reality) je API pro webové prohlížeče, které umožňuje vytvářet aplikace využívající rozšířenou (**AR**) a virtuální realitu (**VR**) **přímo na webu**

- **Hlavní vlastnosti:**
    - rozšířená podpora zařízení:
        - podporuje VR headsety (např. Meta Quest, HTC Vive, Valve Index)
        - umožňuje využít AR funkce na mobilních zařízeních, která podporují detekci povrchů (např. iOS a Android)
        - funguje také na chytrých brýlích (např. HoloLens) nebo AR zařízeních

    - umístění 3D objektů ve skutečném prostoru pomocí GPS nebo detekce okolí
    - cross-platform řešení:
        - WebXR funguje na různých zařízeních a operačních systémech, pokud má uživatel moderní webový prohlížeč (Chrome, Edge, Firefox apod.)
    - jednotný přístup:
        - nabízí jednotné API pro interakci s VR i AR technologiemi, což vývojářům zjednodušuje práci

## [Model-viewer](https://modelviewer.dev/)
- ```<model-viewer>``` je webová komponenta vyvinutá Googlem, která umožňuje snadné zobrazování 3D modelů a integraci rozšířené reality (AR) do webových stránek
- je navržena tak, aby byla jednoduchá na použití a zároveň poskytovala pokročilé možnosti renderování a interakce

- tato technologie využívá WebGL pro vykreslování 3D grafiky a WebXR (pokud je dostupné) pro funkce AR, což umožňuje uživatelům snadno zobrazovat a manipulovat s 3D objekty ve webovém prohlížeči

- **Hlavní vlastnosti:**
    - Používá se jako HTML značka (podobně jako ```<img>```), což umožňuje vložit 3D model do webové stránky bez potřeby pokročilého programování

    - ukázka: ```<model-viewer src="model.glb" alt="3D model" auto-rotate camera-controls ar></model-viewer>```
    - podpora formátu GLTF/GLB
    - interaktivní ovládání - rotace, zoom, posun
    - zobrazení modelu v mobilu i v AR

# Úloha 1 - Markerless AR

# Úloha 2 - Marker AR


# Užitečné odkazy
- Glitch: https://glitch.com/
- ChatGPT: https://chatgpt.com/