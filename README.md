# Vertipots Growing System

Official sales & technical website for the patented **Vertipots** vertical farming system designed by **Louis Wilken** (40+ years horticulture, Pretoria).

## Live previews

| Host | URL |
|------|-----|
| **Production domain** | https://vertipots.co.za/ |
| **GitHub Pages** (this repo) | https://gilbertbouic.github.io/vertipots/ |

### Enable GitHub Pages (one-time)
1. Open [Repository Settings → Pages](https://github.com/gilbertbouic/vertipots/settings/pages)
2. Source: **Deploy from a branch**
3. Branch: `main` → folder `/ (root)`
4. Save

## Local preview
```bash
cd ~/Projects/vertipots
python3 -m http.server 8080
```
Open http://localhost:8080

## Site map
| Page | File | Purpose |
|------|------|---------|
| Home | `index.html` | Hero, benefits, applications teaser, CTAs |
| The System | `system.html` | How it works + comparison table |
| Advantages | `advantages.html` | Full benefit set for growers |
| Applications | `applications.html` | Tunnels, urban, mobile, lodges |
| Economics | `economics.html` | Density / media / planning model |
| Gallery | `gallery.html` | Photos & diagrams |
| About Louis | `about.html` | Inventor story, vision, mission |
| Contact | `contact.html` | Details + enquiry form (mailto) |

## Contact
- **Email:** louis@vertipots.co.za  
- **Phone / WhatsApp:** +27 76 234 5870  
- **Address:** 275 Soutpansberg Road, Rietondale, Pretoria 0084  

## Stack
Static HTML/CSS (no build step). Suitable for GitHub Pages or any static host / DNS for vertipots.co.za.
