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

# Server Metrics 2026-03-19 00:46:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 10682.7 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121934
telemt_connections_bad_total 14412
telemt_connections_current 614
telemt_connections_me_current 614
telemt_handshake_timeouts_total 1211
telemt_upstream_connect_attempt_total 2135
telemt_upstream_connect_success_total 2098
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 2135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1562
telemt_me_reconnect_success_total 1557
telemt_me_reader_eof_total 1602
telemt_me_idle_close_by_peer_total 1602
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 38121
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100939
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 571
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 407
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1559
telemt_me_writer_restored_same_endpoint_total 1545
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 98172
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 923984308 (881.18 MB)
telemt_user_octets_to_client{user="hello"} 36481768212 (33.98 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 10686.5 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253754
telemt_connections_bad_total 19207
telemt_connections_current 1382
telemt_connections_me_current 1382
telemt_handshake_timeouts_total 3055
telemt_upstream_connect_attempt_total 1997
telemt_upstream_connect_success_total 1956
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 1997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 1414
telemt_me_reconnect_success_total 1410
telemt_me_reader_eof_total 1475
telemt_me_idle_close_by_peer_total 1475
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 76593
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217012
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 816
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 286
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1433
telemt_me_writer_restored_same_endpoint_total 1397
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 217054
telemt_user_connections_current{user="hello"} 1382
telemt_user_octets_from_client{user="hello"} 10743729696 (10.01 GB)
telemt_user_octets_to_client{user="hello"} 82182832724 (76.54 GB)
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 10683.7 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200848
telemt_connections_bad_total 33045
telemt_connections_current 1071
telemt_connections_me_current 1071
telemt_handshake_timeouts_total 5463
telemt_upstream_connect_attempt_total 2066
telemt_upstream_connect_success_total 2066
telemt_upstream_connect_attempts_per_request{bucket="1"} 2066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1017
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1524
telemt_me_reconnect_success_total 1520
telemt_me_reader_eof_total 1588
telemt_me_idle_close_by_peer_total 1588
telemt_me_route_drop_no_conn_total 65400
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156217
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 694
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 432
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1540
telemt_me_writer_restored_same_endpoint_total 1504
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 156217
telemt_user_connections_current{user="hello"} 1071
telemt_user_octets_from_client{user="hello"} 2005690340 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 91055668284 (84.80 GB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 10737.1 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210321
telemt_connections_bad_total 26466
telemt_connections_current 944
telemt_connections_me_current 944
telemt_handshake_timeouts_total 3725
telemt_upstream_connect_attempt_total 1961
telemt_upstream_connect_success_total 1961
telemt_upstream_connect_attempts_per_request{bucket="1"} 1961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1420
telemt_me_reconnect_success_total 1414
telemt_me_reader_eof_total 1472
telemt_me_idle_close_by_peer_total 1472
telemt_me_route_drop_no_conn_total 73228
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160047
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 449
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 291
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1430
telemt_me_writer_restored_same_endpoint_total 1390
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 159968
telemt_user_connections_current{user="hello"} 944
telemt_user_octets_from_client{user="hello"} 1633803820 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 55901857496 (52.06 GB)
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 10680.5 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221143
telemt_connections_bad_total 13018
telemt_connections_current 1154
telemt_connections_me_current 1154
telemt_handshake_timeouts_total 7252
telemt_upstream_connect_attempt_total 1981
telemt_upstream_connect_success_total 1969
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1427
telemt_me_reconnect_success_total 1417
telemt_me_reader_eof_total 1477
telemt_me_idle_close_by_peer_total 1477
telemt_me_route_drop_no_conn_total 69618
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169213
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 662
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1424
telemt_me_writer_restored_same_endpoint_total 1393
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 169142
telemt_user_connections_current{user="hello"} 1154
telemt_user_octets_from_client{user="hello"} 2175295792 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 102147622524 (95.13 GB)
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 10691.9 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54963
telemt_connections_bad_total 9054
telemt_connections_current 347
telemt_connections_me_current 347
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 3119
telemt_upstream_connect_success_total 3022
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 3119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1563
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_reconnect_attempts_total 4309
telemt_me_reconnect_success_total 2482
telemt_me_reader_eof_total 2583
telemt_me_idle_close_by_peer_total 2583
telemt_me_route_drop_no_conn_total 20385
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44414
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
telemt_me_writer_removed_unexpected_total 2524
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2452
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 44414
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 542873208 (517.72 MB)
telemt_user_octets_to_client{user="hello"} 28509106268 (26.55 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 10682.8 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157756
telemt_connections_bad_total 19035
telemt_connections_current 964
telemt_connections_me_current 964
telemt_handshake_timeouts_total 6345
telemt_upstream_connect_attempt_total 2210
telemt_upstream_connect_success_total 2210
telemt_upstream_connect_attempts_per_request{bucket="1"} 2210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1067
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1668
telemt_me_reconnect_success_total 1662
telemt_me_reader_eof_total 1736
telemt_me_idle_close_by_peer_total 1736
telemt_me_route_drop_no_conn_total 47300
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129415
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 893
telemt_desync_full_logged_total 358
telemt_desync_suppressed_total 535
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 362
telemt_desync_frames_bucket_total{bucket="gt_10"} 376
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1682
telemt_me_writer_restored_same_endpoint_total 1647
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 129439
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 1291511880 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 68866733764 (64.14 GB)
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 79
```