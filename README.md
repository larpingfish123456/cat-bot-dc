# cat-bot-dc
entities/                     # Base44 data collections
  DocPage
  Feature
  SiteSettings
  TeamMember

src/
  api/
    base44Client.js           # Base44 SDK client init

  components/
    admin/
      AdminPasswordModal.jsx  # Admin auth modal
      DocsPanel.jsx           # Manage Docs content
      FeaturesPanel.jsx       # Manage Features content
      SettingsPanel.jsx       # Site settings management
      TeamPanel.jsx           # Manage Team members
    landing/
      HeroSection.jsx
      FeaturesSection.jsx
      TeamSection.jsx
    ui/                       # shadcn/ui primitives (button, dialog,
                               # card, table, form, sidebar, etc.)
    AnimatedBackground.jsx
    AuthLayout.jsx
    GoogleIcon.jsx
    Layout.jsx
    LoadingScreen.jsx
    Navbar.jsx
    ProtectedRoute.jsx
    ScrollToTop.jsx
    UserNotRegisteredError.jsx

  hooks/
    use-mobile.jsx

  lib/
    AuthContext.jsx           # Auth state/provider
    app-params.js
    query-client.js
    utils.js

  pages/
    Home.jsx
    Features.jsx
    Commands.jsx
    Docs.jsx
    Team.jsx
    Login.jsx
    Register.jsx
    ForgotPassword.jsx
    ResetPassword.jsx
    AdminPanel.jsx
    PageNotFound.jsx

  utils/
    index.ts

  App.jsx
  index.css
  main.jsx

.gitignore
components.json
eslint.config.js
index.html
jsconfig.json
package.json
postcss.config.js
tailwind.config.js
vite.config.js
