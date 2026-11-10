# Multiredz
Instaladores do Multiredz (Windows e Mac) e atualizações automáticas.

## Instalar

**Windows:** baixe e rode o `Multiredz-Setup-<versão>.exe` da [última versão](https://github.com/dxrz7/multilogin-releases/releases/latest). Se o Windows avisar "aplicativo não reconhecido", clique em *Mais informações → Executar assim mesmo*.

**Mac:** baixe o `.dmg` na [última versão](https://github.com/dxrz7/multilogin-releases/releases/latest): `arm64` para chip Apple (M1 a M5), `x64` para Intel. Abra o `.dmg` e arraste o Multiredz para **Aplicativos**.

Se o Mac disser que o app está **"danificado"** (acontece porque o app não é assinado pela Apple), abra o **Terminal** e rode:
```bash
xattr -cr /Applications/Multiredz.app
```
Depois abra o app normalmente. Se aparecer "não pode ser verificado", vá em **Ajustes do Sistema → Privacidade e Segurança → Abrir Mesmo Assim**.
