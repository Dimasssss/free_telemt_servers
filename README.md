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

# Server Metrics 2026-03-17 06:34:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 42562.5 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254739
telemt_connections_bad_total 3365
telemt_handshake_timeouts_total 8289
telemt_upstream_connect_attempt_total 8878
telemt_upstream_connect_success_total 8831
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 8878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6727
telemt_me_reconnect_success_total 6702
telemt_me_reader_eof_total 7137
telemt_me_idle_close_by_peer_total 7137
telemt_me_route_drop_no_conn_total 78582
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228738
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1691
telemt_desync_full_logged_total 526
telemt_desync_suppressed_total 1165
telemt_desync_frames_bucket_total{bucket="1_2"} 385
telemt_desync_frames_bucket_total{bucket="3_10"} 853
telemt_desync_frames_bucket_total{bucket="gt_10"} 453
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 6771
telemt_me_writer_restored_same_endpoint_total 6681
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 228527
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 3065329000 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 99349541184 (92.53 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 42813.9 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143976
telemt_connections_bad_total 2207
telemt_handshake_timeouts_total 11016
telemt_upstream_connect_attempt_total 11736
telemt_upstream_connect_success_total 11589
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 11736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_reconnect_attempts_total 10644
telemt_me_reconnect_success_total 9468
telemt_me_reader_eof_total 10011
telemt_me_idle_close_by_peer_total 10011
telemt_me_route_drop_no_conn_total 53490
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125245
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 335
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 213
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9589
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9452
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 125254
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 1535461136 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 53209267580 (49.55 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 42589.8 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85644
telemt_connections_bad_total 1110
telemt_handshake_timeouts_total 2758
telemt_upstream_connect_attempt_total 11442
telemt_upstream_connect_success_total 11382
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 11442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9281
telemt_me_reconnect_success_total 9230
telemt_me_reader_eof_total 9882
telemt_me_idle_close_by_peer_total 9882
telemt_me_route_drop_no_conn_total 29266
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73960
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9340
telemt_me_writer_restored_same_endpoint_total 9219
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 73942
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 6138398848 (5.72 GB)
telemt_user_octets_to_client{user="hello"} 23832433988 (22.20 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 42649.3 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152671
telemt_connections_bad_total 4011
telemt_handshake_timeouts_total 6371
telemt_upstream_connect_attempt_total 9653
telemt_upstream_connect_success_total 9572
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 9653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_reconnect_attempts_total 7441
telemt_me_reconnect_success_total 7383
telemt_me_reader_eof_total 7856
telemt_me_idle_close_by_peer_total 7856
telemt_me_route_drop_no_conn_total 50797
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137763
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 258
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 182
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7491
telemt_me_writer_restored_same_endpoint_total 7376
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 137778
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 1488595202 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 66737728913 (62.15 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 42621.1 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115604
telemt_connections_bad_total 34127
telemt_handshake_timeouts_total 2374
telemt_upstream_connect_attempt_total 12969
telemt_upstream_connect_success_total 12798
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 12969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_reconnect_attempts_total 13808
telemt_me_reconnect_success_total 10550
telemt_me_reader_eof_total 11144
telemt_me_idle_close_by_peer_total 11144
telemt_me_route_drop_no_conn_total 29217
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75932
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10789
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 10542
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 76029
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 796626371 (759.72 MB)
telemt_user_octets_to_client{user="hello"} 34965040798 (32.56 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 42782.1 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276215
telemt_connections_bad_total 38367
telemt_handshake_timeouts_total 2206
telemt_upstream_connect_attempt_total 8713
telemt_upstream_connect_success_total 8667
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6568
telemt_me_reconnect_success_total 6539
telemt_me_reader_eof_total 7012
telemt_me_idle_close_by_peer_total 7012
telemt_me_route_drop_no_conn_total 223504
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303382
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 261
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 6638
telemt_me_writer_restored_same_endpoint_total 6529
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 225318
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 3334061944 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 154665135068 (144.04 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 30788.6 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1096
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 15361
telemt_upstream_connect_success_total 15361
telemt_upstream_connect_attempts_per_request{bucket="1"} 15361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 13818
telemt_me_reconnect_success_total 13742
telemt_me_reader_eof_total 15072
telemt_me_idle_close_by_peer_total 15072
telemt_me_route_drop_no_conn_total 118
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 888
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 13868
telemt_me_writer_restored_same_endpoint_total 13742
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 888
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 199373620 (190.14 MB)
telemt_user_octets_to_client{user="hello"} 12052188328 (11.22 GB)
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```