# uptime-checks

Checagem externa de disponibilidade a cada 5 min. As URLs ficam no secret `TARGETS` (uma por linha) e nunca
aparecem nos logs; o estado guarda só um hash. Alerta no Telegram (`TELEGRAM_BOT_TOKEN`, `TELEGRAM_CHAT_ID`) ou,
sem ele, a execução falha e o GitHub manda e-mail.
