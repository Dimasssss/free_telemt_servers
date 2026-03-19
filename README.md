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

# Server Metrics 2026-03-19 00:56:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 11295.8 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128266
telemt_connections_bad_total 15404
telemt_connections_current 586
telemt_connections_me_current 586
telemt_handshake_timeouts_total 1285
telemt_upstream_connect_attempt_total 2292
telemt_upstream_connect_success_total 2253
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 2292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1674
telemt_me_reconnect_success_total 1669
telemt_me_reader_eof_total 1727
telemt_me_idle_close_by_peer_total 1727
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 39805
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106016
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 593
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1671
telemt_me_writer_restored_same_endpoint_total 1656
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 103249
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 964246684 (919.58 MB)
telemt_user_octets_to_client{user="hello"} 37313158940 (34.75 GB)
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 11299.8 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264233
telemt_connections_bad_total 19246
telemt_connections_current 1422
telemt_connections_me_current 1422
telemt_handshake_timeouts_total 3441
telemt_upstream_connect_attempt_total 2150
telemt_upstream_connect_success_total 2105
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 2150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 1520
telemt_me_reconnect_success_total 1516
telemt_me_reader_eof_total 1590
telemt_me_idle_close_by_peer_total 1590
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 79533
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226274
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 836
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 552
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1540
telemt_me_writer_restored_same_endpoint_total 1503
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 226314
telemt_user_connections_current{user="hello"} 1422
telemt_user_octets_from_client{user="hello"} 10794478320 (10.05 GB)
telemt_user_octets_to_client{user="hello"} 86177694124 (80.26 GB)
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 11297.2 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209461
telemt_connections_bad_total 35153
telemt_connections_current 1094
telemt_connections_me_current 1094
telemt_handshake_timeouts_total 5520
telemt_upstream_connect_attempt_total 2216
telemt_upstream_connect_success_total 2216
telemt_upstream_connect_attempts_per_request{bucket="1"} 2216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1094
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1631
telemt_me_reconnect_success_total 1627
telemt_me_reader_eof_total 1705
telemt_me_idle_close_by_peer_total 1705
telemt_me_route_drop_no_conn_total 67629
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162318
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 718
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 446
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 286
telemt_desync_frames_bucket_total{bucket="gt_10"} 289
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1649
telemt_me_writer_restored_same_endpoint_total 1611
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 162318
telemt_user_connections_current{user="hello"} 1094
telemt_user_octets_from_client{user="hello"} 2053137992 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 95663999052 (89.09 GB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 11350.3 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224318
telemt_connections_bad_total 27277
telemt_connections_current 865
telemt_connections_me_current 865
telemt_handshake_timeouts_total 4205
telemt_upstream_connect_attempt_total 2095
telemt_upstream_connect_success_total 2095
telemt_upstream_connect_attempts_per_request{bucket="1"} 2095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1511
telemt_me_reconnect_success_total 1505
telemt_me_reader_eof_total 1572
telemt_me_idle_close_by_peer_total 1572
telemt_me_route_drop_no_conn_total 74875
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166120
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 463
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1523
telemt_me_writer_restored_same_endpoint_total 1481
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 166039
telemt_user_connections_current{user="hello"} 865
telemt_user_octets_from_client{user="hello"} 1669829552 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 57664983952 (53.70 GB)
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 11293.8 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230794
telemt_connections_bad_total 13408
telemt_connections_current 1172
telemt_connections_me_current 1172
telemt_handshake_timeouts_total 7609
telemt_upstream_connect_attempt_total 2133
telemt_upstream_connect_success_total 2121
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1536
telemt_me_reconnect_success_total 1526
telemt_me_reader_eof_total 1593
telemt_me_idle_close_by_peer_total 1593
telemt_me_route_drop_no_conn_total 72319
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176544
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 273
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1532
telemt_me_writer_restored_same_endpoint_total 1502
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 176472
telemt_user_connections_current{user="hello"} 1172
telemt_user_octets_from_client{user="hello"} 2256945000 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 104819181532 (97.62 GB)
telemt_user_unique_ips_current{user="hello"} 503
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 11305.2 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57416
telemt_connections_bad_total 9056
telemt_connections_current 334
telemt_connections_me_current 334
telemt_handshake_timeouts_total 174
telemt_upstream_connect_attempt_total 3329
telemt_upstream_connect_success_total 3222
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 3329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1682
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 4466
telemt_me_reconnect_success_total 2639
telemt_me_reader_eof_total 2745
telemt_me_idle_close_by_peer_total 2745
telemt_me_route_drop_no_conn_total 21380
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46761
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
telemt_me_writer_removed_unexpected_total 2686
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2609
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 46761
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 650557232 (620.42 MB)
telemt_user_octets_to_client{user="hello"} 30122592892 (28.05 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 11295.9 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163933
telemt_connections_bad_total 19605
telemt_connections_current 988
telemt_connections_me_current 988
telemt_handshake_timeouts_total 6832
telemt_upstream_connect_attempt_total 2383
telemt_upstream_connect_success_total 2383
telemt_upstream_connect_attempts_per_request{bucket="1"} 2383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1798
telemt_me_reconnect_success_total 1792
telemt_me_reader_eof_total 1876
telemt_me_idle_close_by_peer_total 1876
telemt_me_route_drop_no_conn_total 49115
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134326
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 912
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 547
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1814
telemt_me_writer_restored_same_endpoint_total 1777
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 134349
telemt_user_connections_current{user="hello"} 988
telemt_user_octets_from_client{user="hello"} 1338721852 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 70978716484 (66.10 GB)
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 71
```