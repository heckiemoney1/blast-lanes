# Blast Lanes

Bomberman-style party game for 2–4 phones. Swipe to step one tile, tap to drop a bomb, first to 3 rounds wins.

**Play:** https://heckiemoney1.github.io/blast-lanes/

One player taps **Host game** and shares the 4-letter code; everyone else taps **Join**. Phones meet on a free public MQTT relay ([EMQX](https://www.emqx.com/en/mqtt/public-mqtt5-broker), with [HiveMQ](https://www.hivemq.com/mqtt/public-mqtt-broker/) as a fallback) over a normal secure connection, so it works across any Wi-Fi or cellular network with no account or server to set up. **Practice** plays against bots offline.

In the lobby the host picks the setting (thirteen of them in two sets, City and Wilds, or a different one each round), the map (classic, random shapes, or a big multi-room arena raining power-ups, where the camera follows you) and toggles extra power-ups (kick, pierce, line bomb, shield), arena hazards (conveyor belts, ice, teleporters, laser lanes), ghost revenge, 2v2 teams and Wikipedia respawns. **TV** shows the match on a laptop or TV without taking a seat, and a phone that drops out can rejoin its seat from the home screen.

Tip: in Safari, Share → Add to Home Screen for full-screen play.
