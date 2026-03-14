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

# Server Metrics 2026-03-14 18:00:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 17027.3 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97574
telemt_connections_bad_total 14538
telemt_handshake_timeouts_total 500
telemt_upstream_connect_attempt_total 4043
telemt_upstream_connect_success_total 4041
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3184
telemt_me_reconnect_success_total 3153
telemt_me_reader_eof_total 3324
telemt_me_idle_close_by_peer_total 3324
telemt_me_route_drop_no_conn_total 34682
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78675
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 316
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3204
telemt_me_writer_restored_same_endpoint_total 3135
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 78603
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 1659249628 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 37579494588 (35.00 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 17026.4 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39397
telemt_connections_bad_total 454
telemt_handshake_timeouts_total 832
telemt_upstream_connect_attempt_total 4643
telemt_upstream_connect_success_total 4608
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2672
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 6294
telemt_me_reconnect_success_total 3720
telemt_me_reader_eof_total 3945
telemt_me_idle_close_by_peer_total 3945
telemt_me_route_drop_no_conn_total 20766
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36700
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3856
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 3715
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 36685
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 533350252 (508.64 MB)
telemt_user_octets_to_client{user="hello"} 15821078528 (14.73 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 17030.9 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41804
telemt_connections_bad_total 358
telemt_handshake_timeouts_total 1739
telemt_upstream_connect_attempt_total 6387
telemt_upstream_connect_success_total 6321
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 6387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 102973
telemt_me_reconnect_success_total 5116
telemt_me_reader_eof_total 5448
telemt_me_idle_close_by_peer_total 5448
telemt_me_route_drop_no_conn_total 16502
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37367
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 5375
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5078
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 37451
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 2854623937 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 20166404766 (18.78 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 17035.8 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52878
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 337
telemt_upstream_connect_attempt_total 4329
telemt_upstream_connect_success_total 4304
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 4329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 3446
telemt_me_reconnect_success_total 3425
telemt_me_reader_eof_total 3571
telemt_me_idle_close_by_peer_total 3571
telemt_me_route_drop_no_conn_total 24092
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50167
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 432
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3460
telemt_me_writer_restored_same_endpoint_total 3423
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 50046
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 639460608 (609.84 MB)
telemt_user_octets_to_client{user="hello"} 16287074124 (15.17 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 17028.6 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39246
telemt_connections_bad_total 3305
telemt_handshake_timeouts_total 2039
telemt_upstream_connect_attempt_total 3913
telemt_upstream_connect_success_total 3869
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 3913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 9505
telemt_me_reconnect_success_total 2983
telemt_me_reader_eof_total 3278
telemt_me_idle_close_by_peer_total 3278
telemt_me_route_drop_no_conn_total 13333
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32083
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 150
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 3210
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 2979
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 32076
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 550406788 (524.91 MB)
telemt_user_octets_to_client{user="hello"} 8430635152 (7.85 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 17028.6 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138545
telemt_connections_bad_total 7098
telemt_handshake_timeouts_total 1658
telemt_upstream_connect_attempt_total 3477
telemt_upstream_connect_success_total 3410
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 3477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 7519
telemt_me_reconnect_success_total 2521
telemt_me_reader_eof_total 2749
telemt_me_idle_close_by_peer_total 2749
telemt_me_route_drop_no_conn_total 72313
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123923
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2701
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2517
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 122583
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 2927321804 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 63067393720 (58.74 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 75
```