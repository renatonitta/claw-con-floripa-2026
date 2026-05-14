# Você não precisa de Mac mini para ter seu OpenClaw

Slides da minha lightning talk no **Claw-con Floripa 2026** — 5 minutos sobre como montei meu OpenClaw sem gastar muito, usando um notebook antigo + Linux/Ubuntu, com Telegram para notificações, RDP via Tailscale para acesso remoto e crons agendados rodando o dia todo.

Por [@renatonitta](https://x.com/renatonitta).

## Arquivos

- `index.html` — apresentação (reveal.js)
- `assets/` — imagens, logos e screenshots usados nos slides

## Como rodar

Feito com [reveal.js](https://revealjs.com/) via CDN. Basta servir o diretório:

```bash
python3 -m http.server 8000
```

E abrir `http://localhost:8000`.
