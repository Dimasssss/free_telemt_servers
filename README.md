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

# Server Metrics 2026-03-19 00:51:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 10989.4 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125191
telemt_connections_bad_total 14845
telemt_connections_current 618
telemt_connections_me_current 618
telemt_handshake_timeouts_total 1243
telemt_upstream_connect_attempt_total 2243
telemt_upstream_connect_success_total 2204
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 2243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1625
telemt_me_reconnect_success_total 1620
telemt_me_reader_eof_total 1678
telemt_me_idle_close_by_peer_total 1678
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 38869
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103623
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 581
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1622
telemt_me_writer_restored_same_endpoint_total 1608
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 100856
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 952722604 (908.59 MB)
telemt_user_octets_to_client{user="hello"} 36911722012 (34.38 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 10993.2 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259035
telemt_connections_bad_total 19229
telemt_connections_current 1514
telemt_connections_me_current 1514
telemt_handshake_timeouts_total 3262
telemt_upstream_connect_attempt_total 2096
telemt_upstream_connect_success_total 2051
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 2096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 1466
telemt_me_reconnect_success_total 1462
telemt_me_reader_eof_total 1535
telemt_me_idle_close_by_peer_total 1535
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 78000
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221573
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1486
telemt_me_writer_restored_same_endpoint_total 1449
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 221614
telemt_user_connections_current{user="hello"} 1514
telemt_user_octets_from_client{user="hello"} 10769734516 (10.03 GB)
telemt_user_octets_to_client{user="hello"} 84347559984 (78.55 GB)
telemt_user_unique_ips_current{user="hello"} 599
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 10990.6 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204845
telemt_connections_bad_total 34029
telemt_connections_current 1021
telemt_connections_me_current 1021
telemt_handshake_timeouts_total 5473
telemt_upstream_connect_attempt_total 2165
telemt_upstream_connect_success_total 2165
telemt_upstream_connect_attempts_per_request{bucket="1"} 2165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1064
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1580
telemt_me_reconnect_success_total 1576
telemt_me_reader_eof_total 1652
telemt_me_idle_close_by_peer_total 1652
telemt_me_route_drop_no_conn_total 66440
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159104
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 707
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1596
telemt_me_writer_restored_same_endpoint_total 1560
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 159104
telemt_user_connections_current{user="hello"} 1021
telemt_user_octets_from_client{user="hello"} 2027483064 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 93323244304 (86.91 GB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 11043.7 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217447
telemt_connections_bad_total 27208
telemt_connections_current 971
telemt_connections_me_current 971
telemt_handshake_timeouts_total 4022
telemt_upstream_connect_attempt_total 2056
telemt_upstream_connect_success_total 2056
telemt_upstream_connect_attempts_per_request{bucket="1"} 2056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1472
telemt_me_reconnect_success_total 1466
telemt_me_reader_eof_total 1531
telemt_me_idle_close_by_peer_total 1531
telemt_me_route_drop_no_conn_total 74011
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163086
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 461
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1482
telemt_me_writer_restored_same_endpoint_total 1442
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 163007
telemt_user_connections_current{user="hello"} 971
telemt_user_octets_from_client{user="hello"} 1652020060 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 56813331692 (52.91 GB)
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 10987.2 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225806
telemt_connections_bad_total 13228
telemt_connections_current 1167
telemt_connections_me_current 1167
telemt_handshake_timeouts_total 7362
telemt_upstream_connect_attempt_total 2077
telemt_upstream_connect_success_total 2065
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1480
telemt_me_reconnect_success_total 1471
telemt_me_reader_eof_total 1538
telemt_me_idle_close_by_peer_total 1538
telemt_me_route_drop_no_conn_total 71205
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172811
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 676
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 412
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 266
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1477
telemt_me_writer_restored_same_endpoint_total 1447
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 172739
telemt_user_connections_current{user="hello"} 1167
telemt_user_octets_from_client{user="hello"} 2211761616 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 103283028712 (96.19 GB)
telemt_user_unique_ips_current{user="hello"} 519
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 10998.8 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56171
telemt_connections_bad_total 9056
telemt_connections_current 331
telemt_connections_me_current 331
telemt_handshake_timeouts_total 166
telemt_upstream_connect_attempt_total 3236
telemt_upstream_connect_success_total 3129
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 3236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 4373
telemt_me_reconnect_success_total 2546
telemt_me_reader_eof_total 2649
telemt_me_idle_close_by_peer_total 2649
telemt_me_route_drop_no_conn_total 20840
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45578
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2590
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2516
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 45578
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 612271132 (583.91 MB)
telemt_user_octets_to_client{user="hello"} 29143837172 (27.14 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 10989.5 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160838
telemt_connections_bad_total 19273
telemt_connections_current 981
telemt_connections_me_current 981
telemt_handshake_timeouts_total 6579
telemt_upstream_connect_attempt_total 2311
telemt_upstream_connect_success_total 2311
telemt_upstream_connect_attempts_per_request{bucket="1"} 2311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1726
telemt_me_reconnect_success_total 1720
telemt_me_reader_eof_total 1802
telemt_me_idle_close_by_peer_total 1802
telemt_me_route_drop_no_conn_total 48284
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131971
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 907
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 366
telemt_desync_frames_bucket_total{bucket="gt_10"} 380
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1740
telemt_me_writer_restored_same_endpoint_total 1705
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 131994
telemt_user_connections_current{user="hello"} 981
telemt_user_octets_from_client{user="hello"} 1314927424 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 70150018204 (65.33 GB)
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 83
```