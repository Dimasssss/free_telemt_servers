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

# Server Metrics 2026-03-19 01:58:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 14976.2 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176474
telemt_connections_bad_total 21179
telemt_connections_current 648
telemt_connections_me_current 648
telemt_handshake_timeouts_total 6690
telemt_upstream_connect_attempt_total 3016
telemt_upstream_connect_success_total 2967
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 3016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2216
telemt_me_reconnect_success_total 2207
telemt_me_reader_eof_total 2302
telemt_me_idle_close_by_peer_total 2302
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 50157
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140956
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 916
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 676
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 391
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2214
telemt_me_writer_restored_same_endpoint_total 2193
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 138186
telemt_user_connections_current{user="hello"} 648
telemt_user_octets_from_client{user="hello"} 1502335584 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 45282051796 (42.17 GB)
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 14979.5 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330393
telemt_connections_bad_total 21895
telemt_connections_current 1467
telemt_connections_me_current 1467
telemt_handshake_timeouts_total 6190
telemt_upstream_connect_attempt_total 2932
telemt_upstream_connect_success_total 2877
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 2932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 2118
telemt_me_reconnect_success_total 2109
telemt_me_reader_eof_total 2218
telemt_me_idle_close_by_peer_total 2218
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 102683
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283159
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1028
telemt_desync_full_logged_total 346
telemt_desync_suppressed_total 682
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 391
telemt_desync_frames_bucket_total{bucket="gt_10"} 405
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2145
telemt_me_writer_restored_same_endpoint_total 2095
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 283203
telemt_user_connections_current{user="hello"} 1467
telemt_user_octets_from_client{user="hello"} 11448087668 (10.66 GB)
telemt_user_octets_to_client{user="hello"} 108348554836 (100.91 GB)
telemt_user_unique_ips_current{user="hello"} 586
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 14976.6 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267189
telemt_connections_bad_total 50405
telemt_connections_current 1115
telemt_connections_me_current 1115
telemt_handshake_timeouts_total 6397
telemt_upstream_connect_attempt_total 2898
telemt_upstream_connect_success_total 2898
telemt_upstream_connect_attempts_per_request{bucket="1"} 2898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1432
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2138
telemt_me_reconnect_success_total 2131
telemt_me_reader_eof_total 2247
telemt_me_idle_close_by_peer_total 2247
telemt_me_route_drop_no_conn_total 81377
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202718
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 983
telemt_desync_full_logged_total 354
telemt_desync_suppressed_total 629
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 390
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2162
telemt_me_writer_restored_same_endpoint_total 2115
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 202709
telemt_user_connections_current{user="hello"} 1115
telemt_user_octets_from_client{user="hello"} 2461088248 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 119913005248 (111.68 GB)
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 15029.9 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301753
telemt_connections_bad_total 28396
telemt_connections_current 941
telemt_connections_me_current 941
telemt_handshake_timeouts_total 5054
telemt_upstream_connect_attempt_total 2763
telemt_upstream_connect_success_total 2763
telemt_upstream_connect_attempts_per_request{bucket="1"} 2763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2006
telemt_me_reconnect_success_total 1998
telemt_me_reader_eof_total 2099
telemt_me_idle_close_by_peer_total 2099
telemt_me_route_drop_no_conn_total 94962
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204396
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 566
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2023
telemt_me_writer_restored_same_endpoint_total 1974
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 204312
telemt_user_connections_current{user="hello"} 941
telemt_user_octets_from_client{user="hello"} 1882674964 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 67969917068 (63.30 GB)
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 14973.4 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289177
telemt_connections_bad_total 17155
telemt_connections_current 1225
telemt_connections_me_current 1225
telemt_handshake_timeouts_total 9512
telemt_upstream_connect_attempt_total 2839
telemt_upstream_connect_success_total 2823
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2066
telemt_me_reconnect_success_total 2054
telemt_me_reader_eof_total 2158
telemt_me_idle_close_by_peer_total 2158
telemt_me_route_drop_no_conn_total 89310
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221929
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 890
telemt_desync_full_logged_total 337
telemt_desync_suppressed_total 553
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 332
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2065
telemt_me_writer_restored_same_endpoint_total 2030
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 221852
telemt_user_connections_current{user="hello"} 1225
telemt_user_octets_from_client{user="hello"} 6742055144 (6.28 GB)
telemt_user_octets_to_client{user="hello"} 122705586516 (114.28 GB)
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 14984.7 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72147
telemt_connections_bad_total 9275
telemt_connections_current 272
telemt_connections_me_current 272
telemt_handshake_timeouts_total 258
telemt_upstream_connect_attempt_total 4277
telemt_upstream_connect_success_total 4148
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 4277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_reconnect_attempts_total 5219
telemt_me_reconnect_success_total 3388
telemt_me_reader_eof_total 3540
telemt_me_idle_close_by_peer_total 3540
telemt_me_route_drop_no_conn_total 28417
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60545
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3438
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3358
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 60545
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 860011512 (820.17 MB)
telemt_user_octets_to_client{user="hello"} 42104690404 (39.21 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 14975.7 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204490
telemt_connections_bad_total 22712
telemt_connections_current 1009
telemt_connections_me_current 1009
telemt_handshake_timeouts_total 9628
telemt_upstream_connect_attempt_total 3224
telemt_upstream_connect_success_total 3224
telemt_upstream_connect_attempts_per_request{bucket="1"} 3224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2466
telemt_me_reconnect_success_total 2458
telemt_me_reader_eof_total 2583
telemt_me_idle_close_by_peer_total 2583
telemt_me_route_drop_no_conn_total 60559
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167206
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1024
telemt_desync_full_logged_total 400
telemt_desync_suppressed_total 624
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 424
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2486
telemt_me_writer_restored_same_endpoint_total 2443
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 167230
telemt_user_connections_current{user="hello"} 1009
telemt_user_octets_from_client{user="hello"} 1691418392 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 86154154508 (80.24 GB)
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 97
```