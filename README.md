# Blast Lanes

Bomberman-style party game for 2–4 phones. Swipe to step one tile, tap to drop a bomb, first to 3 rounds wins.

**Play:** https://heckiemoney1.github.io/blast-lanes/

One player taps **Host game** and shares the 4-letter code; everyone else taps **Join**. Phones meet on a free public MQTT relay ([EMQX](https://www.emqx.com/en/mqtt/public-mqtt5-broker), with [HiveMQ](https://www.hivemq.com/mqtt/public-mqtt-broker/) as a fallback) over a normal secure connection, so it works across any Wi-Fi or cellular network with no account or server to set up. **Practice** plays against bots offline.

Tip: in Safari, Share → Add to Home Screen for full-screen play.
