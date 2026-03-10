# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-10 06:48:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 113333.8 (31h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218047
telemt_connections_bad_total 2419
telemt_handshake_timeouts_total 1948
telemt_upstream_connect_attempt_total 205101
telemt_upstream_connect_success_total 205037
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 205101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 189061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 205025
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 5431363755 (5.06 GB)
telemt_user_octets_to_client{user="hello"} 123136923113 (114.68 GB)
telemt_user_msgs_from_client{user="hello"} 5122948
telemt_user_msgs_to_client{user="hello"} 7694401
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 113332.8 (31h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65289
telemt_connections_bad_total 3196
telemt_handshake_timeouts_total 918
telemt_upstream_connect_attempt_total 57747
telemt_upstream_connect_success_total 57706
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 57747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 370
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57694
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 2199918006 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 26158794788 (24.36 GB)
telemt_user_msgs_from_client{user="hello"} 1682449
telemt_user_msgs_to_client{user="hello"} 7577492
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 113333.7 (31h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94765
telemt_connections_bad_total 1085
telemt_handshake_timeouts_total 4373
telemt_upstream_connect_attempt_total 64511
telemt_upstream_connect_success_total 64509
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 64511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64497
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 6191398256 (5.77 GB)
telemt_user_octets_to_client{user="hello"} 58648571071 (54.62 GB)
telemt_user_msgs_from_client{user="hello"} 3805160
telemt_user_msgs_to_client{user="hello"} 9217677
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 113328.1 (31h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92324
telemt_connections_bad_total 873
telemt_handshake_timeouts_total 1150
telemt_upstream_connect_attempt_total 85510
telemt_upstream_connect_success_total 85321
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 85510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10067
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85309
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 2486125290 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 63981727556 (59.59 GB)
telemt_user_msgs_from_client{user="hello"} 2251589
telemt_user_msgs_to_client{user="hello"} 14654363
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 113333.5 (31h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147426
telemt_connections_bad_total 24735
telemt_handshake_timeouts_total 3999
telemt_upstream_connect_attempt_total 112437
telemt_upstream_connect_success_total 111645
telemt_upstream_connect_fail_total 792
telemt_upstream_connect_attempts_per_request{bucket="1"} 112437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 792
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111633
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 1763593367 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 98863938943 (92.07 GB)
telemt_user_msgs_from_client{user="hello"} 2467234
telemt_user_msgs_to_client{user="hello"} 13274570
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 10
```