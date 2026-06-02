# Model Forge Studio - Elite Pre-Grader

A web-based internal tool designed to evaluate Pokémon card centering, log condition defects, and estimate grading scores (PSA, ACE, BGS, TAG) prior to submission. 

## 🚀 Current Status: Closed Beta
This application is currently in an invite-only testing phase for the Discord community. Public registration is temporarily disabled while the core features and UI are refined. 

## ⚙️ Core Features
*   **Smart TCG Search:** Integrates with the Pokémon TCG API to pull exact card variants and sets using smart text/number splitting.
*   **Live Pricing Engine:** Automatically estimates raw card values with fallback routing to PriceCharting for specific variant checks.
*   **Centering HUD:** Calculates and visualizes front and back face split percentages for centering accuracy.
*   **Secure Binder Storage:** Utilizes Firebase Firestore and Storage with strict authentication rules to securely isolate user collections and images.

## 🛠️ Tech Stack
*   **Frontend:** HTML5, CSS3, Vanilla JavaScript
*   **Backend / Auth:** Firebase (Firestore, Storage, Authentication)
*   **Data Sources:** Pokémon TCG API

## 📝 Ongoing Development
*   Enhancing the visual crosshair UI for image alignment.
*   Expanding database payloads to save specific centering metrics to user binders.
