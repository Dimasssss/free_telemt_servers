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

# Server Metrics 2026-03-12 11:41:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14911.2 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79261
telemt_connections_bad_total 526
telemt_handshake_timeouts_total 2779
telemt_upstream_connect_attempt_total 3676
telemt_upstream_connect_success_total 3660
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 145
telemt_me_reconnect_attempts_total 2894
telemt_me_reconnect_success_total 2876
telemt_me_reader_eof_total 2998
telemt_me_idle_close_by_peer_total 2997
telemt_me_route_drop_no_conn_total 21805
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71850
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 311
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2892
telemt_me_writer_restored_same_endpoint_total 2860
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 71821
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 1022606772 (975.23 MB)
telemt_user_octets_to_client{user="hello"} 24608472092 (22.92 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 14804.0 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31549
telemt_connections_bad_total 265
telemt_handshake_timeouts_total 266
telemt_upstream_connect_attempt_total 4919
telemt_upstream_connect_success_total 4811
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 4919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 14421
telemt_me_reconnect_success_total 4039
telemt_me_reader_eof_total 4406
telemt_me_idle_close_by_peer_total 4406
telemt_me_route_drop_no_conn_total 13321
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29951
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
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
telemt_me_writer_removed_unexpected_total 4377
telemt_me_refill_failed_total 324
telemt_me_writer_restored_same_endpoint_total 4024
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 29952
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 311936620 (297.49 MB)
telemt_user_octets_to_client{user="hello"} 7280323064 (6.78 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 14767.5 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43738
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 392
telemt_upstream_connect_attempt_total 4060
telemt_upstream_connect_success_total 4060
telemt_upstream_connect_attempts_per_request{bucket="1"} 4060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3293
telemt_me_reconnect_success_total 3269
telemt_me_reader_eof_total 3427
telemt_me_idle_close_by_peer_total 3427
telemt_me_route_drop_no_conn_total 14805
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41056
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
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3282
telemt_me_writer_restored_same_endpoint_total 3249
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 41043
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 1015189416 (968.16 MB)
telemt_user_octets_to_client{user="hello"} 30687447704 (28.58 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 14743.1 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53797
telemt_connections_bad_total 1039
telemt_handshake_timeouts_total 261
telemt_upstream_connect_attempt_total 4309
telemt_upstream_connect_success_total 4206
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 4309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 7239
telemt_me_reconnect_success_total 3420
telemt_me_reader_eof_total 3653
telemt_me_idle_close_by_peer_total 3653
telemt_me_route_drop_no_conn_total 17532
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49046
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 171
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3584
telemt_me_refill_failed_total 118
telemt_me_writer_restored_same_endpoint_total 3412
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 49045
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 981462800 (936.00 MB)
telemt_user_octets_to_client{user="hello"} 27288973436 (25.41 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14712.6 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29048
telemt_connections_bad_total 2799
telemt_handshake_timeouts_total 420
telemt_upstream_connect_attempt_total 4360
telemt_upstream_connect_success_total 4176
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 4360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 17448
telemt_me_reconnect_success_total 3395
telemt_me_reader_eof_total 3831
telemt_me_idle_close_by_peer_total 3831
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 8636
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25035
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 235
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 284
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3855
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 3378
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 25032
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 161448948 (153.97 MB)
telemt_user_octets_to_client{user="hello"} 6629695336 (6.17 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 14699.5 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79230
telemt_connections_bad_total 747
telemt_handshake_timeouts_total 764
telemt_upstream_connect_attempt_total 2924
telemt_upstream_connect_success_total 2908
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 2153
telemt_me_reconnect_success_total 2137
telemt_me_reader_eof_total 2242
telemt_me_idle_close_by_peer_total 2242
telemt_me_route_drop_no_conn_total 33179
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75059
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 172
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2161
telemt_me_writer_restored_same_endpoint_total 2130
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 75026
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 2154405228 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 37488347060 (34.91 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 54
```