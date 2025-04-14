FROM ghcr.io/tomquist/hame-relay-addon:latest

# Optional: Arbeitsverzeichnis
WORKDIR /app

# Falls dein Code noch TS ist, musst du auch `tsconfig.json`, `package*.json` und `src/` kopieren
# und den Build nochmal anstoßen

# Falls dein Code bereits JS (z. B. `dist/`) ist:
COPY dist/ ./dist/

# Falls du aus TypeScript baust:
# COPY src/ ./src/
# COPY tsconfig.json package*.json ./
# RUN npm ci && npm run build
