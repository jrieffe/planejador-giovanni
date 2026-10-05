# Planejador · Giovanni M. J. Afonso

Agenda semanal de estudos e rotina, sincronizada entre Giovanni e o Pai via Firebase Realtime Database. Instalável no iPhone (Safari → Compartilhar → Adicionar à Tela de Início).

- **Até 31/12/2026:** Inglês + Francês
- **A partir de jan/2027:** Biologia, Química e Física no idioma escolhido (editável)
- Rotina fixa: musculação seg/qua/sex 15h · luta ter/qui 15h · Lidiane qua 17h · futebol qua 18:30

## Arquivos
- `index.html` — o app
- `tutorial_giovanni.html` — como usar
- `sw.js`, `manifest.json`, ícones — PWA

## Regras do Firebase
Realtime Database → Regras:
```json
{
  "rules": {
    "giovanni2027": { ".read": true, ".write": true },
    "gio_test": { ".read": true, ".write": true }
  }
}
```
