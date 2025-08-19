# Configuración de Secrets para poc_sensible_bvi

## Secrets que configurar en GitHub

### 1. Ir a Settings del repositorio
- Ve a: https://github.com/benjaminvergara19/poc_sensible_bvi
- Click en **Settings** (pestaña del repositorio)
- En el menú izquierdo: **Secrets and variables** → **Actions**

### 2. Configurar los siguientes Repository Secrets:

#### REPO_READ_TOKEN
- **Name:** `REPO_READ_TOKEN`
- **Secret:** `[PAT TOKEN PROVIDED SEPARATELY]`
- **Descripción:** PAT token para leer el repositorio poc_publico_bvi

#### DATABRICKS_HOST
- **Name:** `DATABRICKS_HOST`
- **Secret:** `[DATABRICKS HOST URL PROVIDED SEPARATELY]`
- **Descripción:** URL del workspace de Databricks

#### DATABRICKS_TOKEN
- **Name:** `DATABRICKS_TOKEN`
- **Secret:** `[DATABRICKS TOKEN PROVIDED SEPARATELY]`
- **Descripción:** Token de autenticación de Databricks

## Pasos para configurar:

1. **New repository secret** para cada uno
2. Pegar el **Name** exactamente como se muestra arriba
3. Pegar el **Secret** correspondiente
4. Click **Add secret**

## Verificación

Una vez configurados, deberías ver 3 secrets en:
- `https://github.com/benjaminvergara19/poc_sensible_bvi/settings/secrets/actions`

✅ REPO_READ_TOKEN  
✅ DATABRICKS_HOST  
✅ DATABRICKS_TOKEN