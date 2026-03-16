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

# Server Metrics 2026-03-16 22:10:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 12325.2 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78286
telemt_connections_bad_total 717
telemt_handshake_timeouts_total 3460
telemt_upstream_connect_attempt_total 2312
telemt_upstream_connect_success_total 2295
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1667
telemt_me_reconnect_success_total 1659
telemt_me_reader_eof_total 1733
telemt_me_idle_close_by_peer_total 1733
telemt_me_route_drop_no_conn_total 26729
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70569
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 347
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1665
telemt_me_writer_restored_same_endpoint_total 1638
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 70523
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 1343186908 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 45574492108 (42.44 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 12576.7 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58926
telemt_connections_bad_total 505
telemt_handshake_timeouts_total 2725
telemt_upstream_connect_attempt_total 2734
telemt_upstream_connect_success_total 2702
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 2734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 2076
telemt_me_reconnect_success_total 2071
telemt_me_reader_eof_total 2167
telemt_me_idle_close_by_peer_total 2167
telemt_me_route_drop_no_conn_total 23086
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53383
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2098
telemt_me_writer_restored_same_endpoint_total 2055
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 53365
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 812620124 (774.97 MB)
telemt_user_octets_to_client{user="hello"} 24082300220 (22.43 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 12352.9 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30709
telemt_connections_bad_total 384
telemt_handshake_timeouts_total 228
telemt_upstream_connect_attempt_total 3080
telemt_upstream_connect_success_total 3061
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 2439
telemt_me_reconnect_success_total 2418
telemt_me_reader_eof_total 2552
telemt_me_idle_close_by_peer_total 2552
telemt_me_route_drop_no_conn_total 10376
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29323
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2444
telemt_me_writer_restored_same_endpoint_total 2407
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 29319
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 602459380 (574.55 MB)
telemt_user_octets_to_client{user="hello"} 11300552988 (10.52 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 12412.2 (3h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59365
telemt_connections_bad_total 2983
telemt_handshake_timeouts_total 409
telemt_upstream_connect_attempt_total 2607
telemt_upstream_connect_success_total 2575
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 2607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 1952
telemt_me_reconnect_success_total 1932
telemt_me_reader_eof_total 2015
telemt_me_idle_close_by_peer_total 2015
telemt_me_route_drop_no_conn_total 19033
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54378
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1958
telemt_me_writer_restored_same_endpoint_total 1925
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 54364
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 742404340 (708.01 MB)
telemt_user_octets_to_client{user="hello"} 23805494180 (22.17 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 12384.2 (3h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41527
telemt_connections_bad_total 12769
telemt_handshake_timeouts_total 195
telemt_upstream_connect_attempt_total 3350
telemt_upstream_connect_success_total 3291
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 3349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 3767
telemt_me_reconnect_success_total 2657
telemt_me_reader_eof_total 2736
telemt_me_idle_close_by_peer_total 2736
telemt_me_route_drop_no_conn_total 11008
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27323
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2759
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2649
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 27319
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 231401936 (220.68 MB)
telemt_user_octets_to_client{user="hello"} 8207649876 (7.64 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 12545.1 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87195
telemt_connections_bad_total 1058
telemt_handshake_timeouts_total 753
telemt_upstream_connect_attempt_total 2395
telemt_upstream_connect_success_total 2380
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1240
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 1754
telemt_me_reconnect_success_total 1751
telemt_me_reader_eof_total 1850
telemt_me_idle_close_by_peer_total 1850
telemt_me_route_drop_no_conn_total 50034
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88073
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1777
telemt_me_writer_restored_same_endpoint_total 1741
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 82538
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 1655420932 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 46846722184 (43.63 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 551.7 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22
telemt_upstream_connect_attempt_total 84
telemt_upstream_connect_success_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 84
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_reconnect_attempts_total 16
telemt_me_reconnect_success_total 16
telemt_me_route_drop_no_conn_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 16
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 22
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 157444688 (150.15 MB)
telemt_user_octets_to_client{user="hello"} 22632028 (21.58 MB)
telemt_user_unique_ips_current{user="hello"} 1
telemt_user_unique_ips_recent_window{user="hello"} 1
```