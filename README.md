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

# Server Metrics 2026-03-12 12:12:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16752.6 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89474
telemt_connections_bad_total 529
telemt_handshake_timeouts_total 3237
telemt_upstream_connect_attempt_total 4117
telemt_upstream_connect_success_total 4097
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 4116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 3243
telemt_me_reconnect_success_total 3222
telemt_me_reader_eof_total 3357
telemt_me_idle_close_by_peer_total 3356
telemt_me_route_drop_no_conn_total 24957
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80583
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 372
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 150
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3244
telemt_me_writer_restored_same_endpoint_total 3206
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 80550
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 1117891852 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 26334768272 (24.53 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16645.5 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35565
telemt_connections_bad_total 271
telemt_handshake_timeouts_total 296
telemt_upstream_connect_attempt_total 5236
telemt_upstream_connect_success_total 5118
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 5236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 130
telemt_me_reconnect_attempts_total 17362
telemt_me_reconnect_success_total 4259
telemt_me_reader_eof_total 4711
telemt_me_idle_close_by_peer_total 4711
telemt_me_route_drop_no_conn_total 15705
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33830
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 4684
telemt_me_refill_failed_total 409
telemt_me_writer_restored_same_endpoint_total 4244
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 33831
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 397184640 (378.78 MB)
telemt_user_octets_to_client{user="hello"} 8909028924 (8.30 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 16609.2 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49019
telemt_connections_bad_total 126
telemt_handshake_timeouts_total 430
telemt_upstream_connect_attempt_total 4568
telemt_upstream_connect_success_total 4568
telemt_upstream_connect_attempts_per_request{bucket="1"} 4568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 3712
telemt_me_reconnect_success_total 3686
telemt_me_reader_eof_total 3870
telemt_me_idle_close_by_peer_total 3870
telemt_me_route_drop_no_conn_total 16707
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46145
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3705
telemt_me_writer_restored_same_endpoint_total 3666
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 46131
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 1524057188 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 31214536880 (29.07 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 16584.9 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61192
telemt_connections_bad_total 1082
telemt_handshake_timeouts_total 304
telemt_upstream_connect_attempt_total 4592
telemt_upstream_connect_success_total 4480
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 4592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 10146
telemt_me_reconnect_success_total 3606
telemt_me_reader_eof_total 3925
telemt_me_idle_close_by_peer_total 3925
telemt_me_route_drop_no_conn_total 20363
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55918
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3856
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3598
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 55916
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 1037830880 (989.75 MB)
telemt_user_octets_to_client{user="hello"} 29155630412 (27.15 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16554.2 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33712
telemt_connections_bad_total 3141
telemt_handshake_timeouts_total 433
telemt_upstream_connect_attempt_total 4599
telemt_upstream_connect_success_total 4393
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 4599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 20329
telemt_me_reconnect_success_total 3524
telemt_me_reader_eof_total 4046
telemt_me_idle_close_by_peer_total 4046
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 10308
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29254
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 375
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 266
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4070
telemt_me_refill_failed_total 526
telemt_me_writer_restored_same_endpoint_total 3507
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 546
telemt_user_connections_total{user="hello"} 29251
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 196639972 (187.53 MB)
telemt_user_octets_to_client{user="hello"} 7512159196 (7.00 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 16541.1 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91839
telemt_connections_bad_total 758
telemt_handshake_timeouts_total 884
telemt_upstream_connect_attempt_total 3331
telemt_upstream_connect_success_total 3315
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 2474
telemt_me_reconnect_success_total 2453
telemt_me_reader_eof_total 2583
telemt_me_idle_close_by_peer_total 2583
telemt_me_route_drop_no_conn_total 38143
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87139
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2484
telemt_me_writer_restored_same_endpoint_total 2446
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 87106
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 2337219264 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 44011303324 (40.99 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 60
```