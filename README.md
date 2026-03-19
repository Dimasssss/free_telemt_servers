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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 12:47:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 355.2 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15613
telemt_connections_bad_total 564
telemt_connections_current 1676
telemt_connections_me_current 1676
telemt_handshake_timeouts_total 508
telemt_upstream_connect_attempt_total 102
telemt_upstream_connect_success_total 84
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 29
telemt_me_reconnect_success_total 13
telemt_me_route_drop_no_conn_total 8081
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14137
telemt_me_writer_pick_total{mode="p2c",result="full"} 54
telemt_me_writer_pick_total{mode="p2c",result="closed"} 152
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 2
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 220
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 13790
telemt_user_connections_current{user="hello"} 1676
telemt_user_octets_from_client{user="hello"} 266735228 (254.38 MB)
telemt_user_octets_to_client{user="hello"} 3718052408 (3.46 GB)
telemt_user_unique_ips_current{user="hello"} 580
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 265.1 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35964
telemt_connections_bad_total 777
telemt_connections_current 3518
telemt_connections_me_current 3518
telemt_handshake_timeouts_total 213
telemt_upstream_connect_attempt_total 1388
telemt_upstream_connect_success_total 1384
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 87
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 103
telemt_me_reconnect_success_total 101
telemt_me_reader_eof_total 40
telemt_me_idle_close_by_peer_total 40
telemt_me_route_drop_no_conn_total 16078
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32018
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 69
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 63
telemt_me_writer_restored_same_endpoint_total 46
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_user_connections_total{user="hello"} 33097
telemt_user_connections_current{user="hello"} 3518
telemt_user_octets_from_client{user="hello"} 217731150 (207.64 MB)
telemt_user_octets_to_client{user="hello"} 5833380502 (5.43 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1249
telemt_user_unique_ips_recent_window{user="hello"} 572
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 243.3 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39023
telemt_connections_bad_total 2098
telemt_connections_current 2891
telemt_connections_me_current 2891
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 175
telemt_upstream_connect_success_total 174
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 109
telemt_me_reconnect_success_total 109
telemt_me_reader_eof_total 22
telemt_me_idle_close_by_peer_total 22
telemt_me_route_drop_no_conn_total 15542
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27399
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 80
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 44
telemt_me_writer_restored_same_endpoint_total 108
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5542
telemt_user_connections_total{user="hello"} 27254
telemt_user_connections_current{user="hello"} 2891
telemt_user_octets_from_client{user="hello"} 130547412 (124.50 MB)
telemt_user_octets_to_client{user="hello"} 5213732200 (4.86 GB)
telemt_user_unique_ips_current{user="hello"} 1021
telemt_user_unique_ips_recent_window{user="hello"} 522
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 230.8 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27517
telemt_connections_bad_total 3300
telemt_connections_current 2777
telemt_connections_me_current 2777
telemt_handshake_timeouts_total 369
telemt_upstream_connect_attempt_total 131
telemt_upstream_connect_success_total 127
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 64
telemt_me_reconnect_success_total 64
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 9424
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21913
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 39
telemt_me_writer_restored_same_endpoint_total 61
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_user_connections_total{user="hello"} 21792
telemt_user_connections_current{user="hello"} 2777
telemt_user_octets_from_client{user="hello"} 138746924 (132.32 MB)
telemt_user_octets_to_client{user="hello"} 3637682224 (3.39 GB)
telemt_user_unique_ips_current{user="hello"} 951
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 53954.1 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3578899
telemt_connections_bad_total 721651
telemt_connections_current 3496
telemt_connections_me_current 3496
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 70176
telemt_upstream_connect_attempt_total 61402
telemt_upstream_connect_success_total 58923
telemt_upstream_connect_fail_total 2479
telemt_upstream_connect_attempts_per_request{bucket="1"} 61402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2479
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70111
telemt_me_reconnect_success_total 7061
telemt_me_reader_eof_total 7377
telemt_me_idle_close_by_peer_total 7374
telemt_me_route_drop_no_conn_total 1596725
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2389822
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10216
telemt_desync_full_logged_total 3183
telemt_desync_suppressed_total 7033
telemt_desync_frames_bucket_total{bucket="1_2"} 1867
telemt_desync_frames_bucket_total{bucket="3_10"} 4347
telemt_desync_frames_bucket_total{bucket="gt_10"} 4002
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7179
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7037
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 2438705
telemt_user_connections_current{user="hello"} 3496
telemt_user_octets_from_client{user="hello"} 38419671423 (35.78 GB)
telemt_user_octets_to_client{user="hello"} 891497633644 (830.27 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1113
telemt_user_unique_ips_recent_window{user="hello"} 559
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 195.2 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7335
telemt_connections_bad_total 111
telemt_connections_current 980
telemt_connections_me_current 980
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 81
telemt_upstream_connect_success_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 81
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_me_reconnect_attempts_total 15
telemt_me_reconnect_success_total 15
telemt_me_route_drop_no_conn_total 7239
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6862
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 367
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 6862
telemt_user_connections_current{user="hello"} 980
telemt_user_octets_from_client{user="hello"} 33138136 (31.60 MB)
telemt_user_octets_to_client{user="hello"} 647854276 (617.84 MB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 195.4 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17630
telemt_connections_bad_total 1047
telemt_connections_current 3048
telemt_connections_me_current 3048
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 90
telemt_upstream_connect_success_total 88
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 90
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 26
telemt_me_reconnect_success_total 26
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 3219
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15160
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 26
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_user_connections_total{user="hello"} 15157
telemt_user_connections_current{user="hello"} 3048
telemt_user_octets_from_client{user="hello"} 129941064 (123.92 MB)
telemt_user_octets_to_client{user="hello"} 4325892492 (4.03 GB)
telemt_user_unique_ips_current{user="hello"} 1023
telemt_user_unique_ips_recent_window{user="hello"} 461
```