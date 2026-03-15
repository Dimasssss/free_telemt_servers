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

# Server Metrics 2026-03-15 16:35:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 66054.8 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303583
telemt_connections_bad_total 2789
telemt_handshake_timeouts_total 9066
telemt_upstream_connect_attempt_total 16304
telemt_upstream_connect_success_total 16219
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 16304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9015
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16296
telemt_me_reconnect_success_total 12907
telemt_me_reader_eof_total 13753
telemt_me_idle_close_by_peer_total 13753
telemt_me_route_drop_no_conn_total 453229
telemt_me_route_drop_channel_closed_total 75
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340749
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1771
telemt_desync_full_logged_total 709
telemt_desync_suppressed_total 1062
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 699
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13148
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12873
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 279852
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 5898190388 (5.49 GB)
telemt_user_octets_to_client{user="hello"} 230555990048 (214.72 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 66062.5 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118677
telemt_connections_bad_total 2820
telemt_handshake_timeouts_total 11123
telemt_upstream_connect_attempt_total 18245
telemt_upstream_connect_success_total 18245
telemt_upstream_connect_attempts_per_request{bucket="1"} 18245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 17249
telemt_me_reconnect_success_total 14887
telemt_me_reader_eof_total 15903
telemt_me_idle_close_by_peer_total 15902
telemt_me_route_drop_no_conn_total 48721
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101225
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 15140
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 14871
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 101209
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 2029212352 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 50472644308 (47.01 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 66054.6 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124461
telemt_connections_bad_total 1665
telemt_handshake_timeouts_total 3083
telemt_upstream_connect_attempt_total 19702
telemt_upstream_connect_success_total 19694
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 19702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 23677
telemt_me_reconnect_success_total 16323
telemt_me_reader_eof_total 17507
telemt_me_idle_close_by_peer_total 17507
telemt_me_route_drop_no_conn_total 48400
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108570
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16706
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16315
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 108466
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 10446999712 (9.73 GB)
telemt_user_octets_to_client{user="hello"} 61905920712 (57.65 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 66054.5 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167203
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 1041
telemt_upstream_connect_attempt_total 15874
telemt_upstream_connect_success_total 15863
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 15874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12630
telemt_me_reconnect_success_total 12550
telemt_me_reader_eof_total 13353
telemt_me_idle_close_by_peer_total 13353
telemt_me_route_drop_no_conn_total 65282
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153772
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 539
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 350
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 12702
telemt_me_writer_restored_same_endpoint_total 12539
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 153685
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 2871676364 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 70831953804 (65.97 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 41125.8 (11h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101225
telemt_connections_bad_total 22802
telemt_handshake_timeouts_total 2247
telemt_upstream_connect_attempt_total 12743
telemt_upstream_connect_success_total 12671
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 12743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 104869
telemt_me_reconnect_success_total 10429
telemt_me_reader_eof_total 10928
telemt_me_idle_close_by_peer_total 10928
telemt_me_route_drop_no_conn_total 34693
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73656
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 183
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 10481
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10325
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 73791
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 1261603081 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 29784163107 (27.74 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 66054.2 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429948
telemt_connections_bad_total 56770
telemt_handshake_timeouts_total 3527
telemt_upstream_connect_attempt_total 14331
telemt_upstream_connect_success_total 14248
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 12205
telemt_me_reconnect_success_total 10904
telemt_me_reader_eof_total 11590
telemt_me_idle_close_by_peer_total 11590
telemt_me_route_drop_no_conn_total 251084
telemt_me_route_drop_channel_closed_total 61
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380504
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11060
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10877
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 354052
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 9411778892 (8.77 GB)
telemt_user_octets_to_client{user="hello"} 188173274616 (175.25 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 82
```