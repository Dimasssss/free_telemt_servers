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

# Server Metrics 2026-03-10 19:56:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 19851.3 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74931
telemt_connections_bad_total 2612
telemt_handshake_timeouts_total 2064
telemt_upstream_connect_attempt_total 66775
telemt_upstream_connect_success_total 66762
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 66775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66760
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 2159648725 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 50779282206 (47.29 GB)
telemt_user_msgs_from_client{user="hello"} 1988729
telemt_user_msgs_to_client{user="hello"} 3664007
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 19850.4 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29303
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 468
telemt_upstream_connect_attempt_total 26860
telemt_upstream_connect_success_total 26852
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 26860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26850
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 932280233 (889.09 MB)
telemt_user_octets_to_client{user="hello"} 21691090070 (20.20 GB)
telemt_user_msgs_from_client{user="hello"} 919648
telemt_user_msgs_to_client{user="hello"} 6590935
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 19850.2 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46461
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 3651
telemt_upstream_connect_attempt_total 39943
telemt_upstream_connect_success_total 39942
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 39943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39940
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 621379052 (592.59 MB)
telemt_user_octets_to_client{user="hello"} 37801361327 (35.21 GB)
telemt_user_msgs_from_client{user="hello"} 857151
telemt_user_msgs_to_client{user="hello"} 5660171
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 19849.0 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41550
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 39889
telemt_upstream_connect_success_total 39771
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 39889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39769
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 649752309 (619.65 MB)
telemt_user_octets_to_client{user="hello"} 31251025376 (29.10 GB)
telemt_user_msgs_from_client{user="hello"} 855139
telemt_user_msgs_to_client{user="hello"} 5858827
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 19850.3 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60401
telemt_connections_bad_total 5339
telemt_handshake_timeouts_total 1286
telemt_upstream_connect_attempt_total 51256
telemt_upstream_connect_success_total 51012
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 51256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51010
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 1531672895 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 38831031368 (36.16 GB)
telemt_user_msgs_from_client{user="hello"} 1413862
telemt_user_msgs_to_client{user="hello"} 5480417
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 13
```