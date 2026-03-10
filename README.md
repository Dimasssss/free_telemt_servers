# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-10 21:56:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 27016.9 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92214
telemt_connections_bad_total 3289
telemt_handshake_timeouts_total 2179
telemt_upstream_connect_attempt_total 82638
telemt_upstream_connect_success_total 82606
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 82638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82602
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 2515527831 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 65515263680 (61.02 GB)
telemt_user_msgs_from_client{user="hello"} 2398202
telemt_user_msgs_to_client{user="hello"} 4314220
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 27016.1 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35074
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 31966
telemt_upstream_connect_success_total 31957
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 31966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31953
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 1655679442 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 31463226035 (29.30 GB)
telemt_user_msgs_from_client{user="hello"} 1312495
telemt_user_msgs_to_client{user="hello"} 8246502
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 27015.9 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56947
telemt_connections_bad_total 419
telemt_handshake_timeouts_total 3965
telemt_upstream_connect_attempt_total 49358
telemt_upstream_connect_success_total 49356
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 49358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49352
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 760647903 (725.41 MB)
telemt_user_octets_to_client{user="hello"} 45492595681 (42.37 GB)
telemt_user_msgs_from_client{user="hello"} 1050176
telemt_user_msgs_to_client{user="hello"} 6838706
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 27014.7 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52100
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 322
telemt_upstream_connect_attempt_total 50031
telemt_upstream_connect_success_total 49890
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 50031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49886
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 810520064 (772.97 MB)
telemt_user_octets_to_client{user="hello"} 36854256240 (34.32 GB)
telemt_user_msgs_from_client{user="hello"} 1092517
telemt_user_msgs_to_client{user="hello"} 6998667
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 27016.1 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75254
telemt_connections_bad_total 6767
telemt_handshake_timeouts_total 1407
telemt_upstream_connect_attempt_total 64072
telemt_upstream_connect_success_total 63828
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 64072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8437
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63824
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 2005375750 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 48370831103 (45.05 GB)
telemt_user_msgs_from_client{user="hello"} 1808865
telemt_user_msgs_to_client{user="hello"} 6914301
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 5985.4 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```