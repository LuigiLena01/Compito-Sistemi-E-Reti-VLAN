# Esercizio di base sulle VLAN in Cisco Packet Tracer

Esercitazione del quinto anno di Sistemi e reti, svolta in **Cisco Packet Tracer**: un router collegato in trunk a uno switch e due PC in due VLAN diverse, con il routing tra VLAN fatto dal router (router-on-a-stick).

Scheda nel portfolio, insieme alla rete più completa con VLAN, Wi-Fi e server: <https://portfoliogigi.com/progetti/rete-vlan-wifi-server/>

## Contenuto

| File | Descrizione |
|---|---|
| `VLAN.pkt` | Progetto Cisco Packet Tracer |

- Due VLAN con le reti `192.168.10.0/24` e `192.168.20.0/24`.
- Collegamento **trunk** 802.1Q tra switch e router.
- Sul router, una sottointerfaccia con `encapsulation dot1Q` per ogni VLAN.

## Come aprirlo

Serve **Cisco Packet Tracer**. Il file è stato salvato con una versione vecchia (6.0.1): le versioni recenti lo aprono, ma potrebbero chiedere di convertirlo.

## Da completare

L'esercizio è rimasto incompleto: le porte dello switch non sono assegnate alle VLAN e uno dei PC ha un gateway diverso dall'indirizzo del router, quindi i due PC non comunicano ancora tra loro.

---

Autore: Luigi Lena · [portfoliogigi.com](https://portfoliogigi.com)
