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

# Server Metrics 2026-03-12 20:41:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 47259.6 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230216
telemt_connections_bad_total 2664
telemt_handshake_timeouts_total 5124
telemt_upstream_connect_attempt_total 11848
telemt_upstream_connect_success_total 11794
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 11848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1450
telemt_me_reconnect_attempts_total 12840
telemt_me_reconnect_success_total 9377
telemt_me_reader_eof_total 9961
telemt_me_idle_close_by_peer_total 9960
telemt_me_route_drop_no_conn_total 70754
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191166
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 9595
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 9361
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 190943
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 3633821288 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 92136793188 (85.81 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 47152.4 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103083
telemt_connections_bad_total 537
telemt_handshake_timeouts_total 789
telemt_upstream_connect_attempt_total 29160
telemt_upstream_connect_success_total 28857
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 29160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 492
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 49386
telemt_me_reconnect_success_total 9954
telemt_me_reader_eof_total 11385
telemt_me_idle_close_by_peer_total 11385
telemt_me_route_drop_no_conn_total 37448
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81474
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 12
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
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 11262
telemt_me_refill_failed_total 1231
telemt_me_writer_restored_same_endpoint_total 9939
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1308
telemt_user_connections_total{user="hello"} 97977
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 1079648176 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 28648570359 (26.68 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 47116.0 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128523
telemt_connections_bad_total 1536
telemt_handshake_timeouts_total 2203
telemt_upstream_connect_attempt_total 13061
telemt_upstream_connect_success_total 13060
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 13061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 297
telemt_me_reconnect_attempts_total 11762
telemt_me_reconnect_success_total 10624
telemt_me_reader_eof_total 11309
telemt_me_idle_close_by_peer_total 11309
telemt_me_route_drop_no_conn_total 48602
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119797
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 10763
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 10604
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 119767
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 2518750596 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 57218973456 (53.29 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 47091.7 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187411
telemt_connections_bad_total 13157
telemt_handshake_timeouts_total 1282
telemt_upstream_connect_attempt_total 24046
telemt_upstream_connect_success_total 14394
telemt_upstream_connect_fail_total 9652
telemt_upstream_connect_attempts_per_request{bucket="1"} 24046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9652
telemt_me_keepalive_timeout_total 2444
telemt_me_reconnect_attempts_total 41367
telemt_me_reconnect_success_total 9126
telemt_me_reader_eof_total 10416
telemt_me_idle_close_by_peer_total 10409
telemt_me_route_drop_no_conn_total 64577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151936
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 491
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 10288
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 9116
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1162
telemt_user_connections_total{user="hello"} 154691
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 2888486022 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 60411931125 (56.26 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 47048.3 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295262
telemt_connections_bad_total 3497
telemt_handshake_timeouts_total 2281
telemt_upstream_connect_attempt_total 9860
telemt_upstream_connect_success_total 9810
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 488
telemt_me_reconnect_attempts_total 11030
telemt_me_reconnect_success_total 7423
telemt_me_reader_eof_total 7923
telemt_me_idle_close_by_peer_total 7922
telemt_me_route_drop_no_conn_total 136081
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292222
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 285
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7629
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 7416
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 280529
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 5161285424 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 137729247856 (128.27 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 42
```