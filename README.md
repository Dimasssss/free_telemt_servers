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

# Server Metrics 2026-03-14 20:33:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 26221.7 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134295
telemt_connections_bad_total 16105
telemt_handshake_timeouts_total 1379
telemt_upstream_connect_attempt_total 5909
telemt_upstream_connect_success_total 5907
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 4575
telemt_me_reconnect_success_total 4539
telemt_me_reader_eof_total 4810
telemt_me_idle_close_by_peer_total 4810
telemt_me_route_drop_no_conn_total 48311
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110832
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 488
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 312
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4617
telemt_me_writer_restored_same_endpoint_total 4521
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 110753
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 2377555584 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 65515985900 (61.02 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 26221.0 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54880
telemt_connections_bad_total 684
telemt_handshake_timeouts_total 962
telemt_upstream_connect_attempt_total 6776
telemt_upstream_connect_success_total 6732
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 6776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 7945
telemt_me_reconnect_success_total 5367
telemt_me_reader_eof_total 5711
telemt_me_idle_close_by_peer_total 5711
telemt_me_route_drop_no_conn_total 28548
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51102
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5523
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 5362
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 51090
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 1318905996 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 22022500792 (20.51 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 26224.9 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61424
telemt_connections_bad_total 389
telemt_handshake_timeouts_total 1888
telemt_upstream_connect_attempt_total 8709
telemt_upstream_connect_success_total 8619
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 8709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4565
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 245
telemt_me_reconnect_attempts_total 104796
telemt_me_reconnect_success_total 6933
telemt_me_reader_eof_total 7400
telemt_me_idle_close_by_peer_total 7400
telemt_me_route_drop_no_conn_total 23398
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55935
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 7209
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6887
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 56000
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 3821101381 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 40627249214 (37.84 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 26229.8 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78706
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 590
telemt_upstream_connect_attempt_total 6466
telemt_upstream_connect_success_total 6426
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 6466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 4919
telemt_me_reconnect_success_total 4894
telemt_me_reader_eof_total 5146
telemt_me_idle_close_by_peer_total 5146
telemt_me_route_drop_no_conn_total 34055
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74502
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 606
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 453
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4949
telemt_me_writer_restored_same_endpoint_total 4892
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 74549
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 1197199500 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 25493962654 (23.74 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 26223.2 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57316
telemt_connections_bad_total 5050
telemt_handshake_timeouts_total 3306
telemt_upstream_connect_attempt_total 6258
telemt_upstream_connect_success_total 6187
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 6258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 11349
telemt_me_reconnect_success_total 4814
telemt_me_reader_eof_total 5232
telemt_me_idle_close_by_peer_total 5232
telemt_me_route_drop_no_conn_total 19006
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46249
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5063
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4810
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 46236
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 1370645996 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 27891032584 (25.98 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 26222.8 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198562
telemt_connections_bad_total 7293
telemt_handshake_timeouts_total 2649
telemt_upstream_connect_attempt_total 5126
telemt_upstream_connect_success_total 5031
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 5126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2571
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 251
telemt_me_reconnect_attempts_total 8670
telemt_me_reconnect_success_total 3664
telemt_me_reader_eof_total 3977
telemt_me_idle_close_by_peer_total 3977
telemt_me_route_drop_no_conn_total 111359
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182797
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3865
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3660
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 179285
telemt_user_connections_current{user="hello"} 480
telemt_user_octets_from_client{user="hello"} 3892779784 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 91445513360 (85.17 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 47
```