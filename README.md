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

# Server Metrics 2026-03-13 13:48:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 108919.2 (30h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448959
telemt_connections_bad_total 3215
telemt_handshake_timeouts_total 8493
telemt_upstream_connect_attempt_total 27472
telemt_upstream_connect_success_total 27343
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 27472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2410
telemt_me_reconnect_attempts_total 25435
telemt_me_reconnect_success_total 21907
telemt_me_reader_eof_total 23394
telemt_me_idle_close_by_peer_total 23393
telemt_me_route_drop_no_conn_total 144161
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392101
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1313
telemt_desync_full_logged_total 466
telemt_desync_suppressed_total 847
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 479
telemt_desync_frames_bucket_total{bucket="gt_10"} 553
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 22246
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21891
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 391682
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 7116310912 (6.63 GB)
telemt_user_octets_to_client{user="hello"} 178252205400 (166.01 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 108813.4 (30h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210038
telemt_connections_bad_total 1701
telemt_handshake_timeouts_total 1519
telemt_upstream_connect_attempt_total 69929
telemt_upstream_connect_success_total 69198
telemt_upstream_connect_fail_total 731
telemt_upstream_connect_attempts_per_request{bucket="1"} 69929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 653
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 731
telemt_me_keepalive_timeout_total 1389
telemt_me_reconnect_attempts_total 103908
telemt_me_reconnect_success_total 26008
telemt_me_reader_eof_total 29202
telemt_me_idle_close_by_peer_total 29202
telemt_me_route_drop_no_conn_total 79858
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160862
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28666
telemt_me_refill_failed_total 2430
telemt_me_writer_restored_same_endpoint_total 25991
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2658
telemt_user_connections_total{user="hello"} 198410
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 2014817644 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 64271146273 (59.86 GB)
telemt_user_msgs_from_client{user="hello"} 559369
telemt_user_msgs_to_client{user="hello"} 3918414
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 108776.7 (30h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255608
telemt_connections_bad_total 2080
telemt_handshake_timeouts_total 10261
telemt_upstream_connect_attempt_total 29256
telemt_upstream_connect_success_total 29252
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 29256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15658
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2267
telemt_me_reconnect_attempts_total 24993
telemt_me_reconnect_success_total 23778
telemt_me_reader_eof_total 25473
telemt_me_idle_close_by_peer_total 25473
telemt_me_route_drop_no_conn_total 93101
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234035
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 24036
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23758
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 233953
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 9462602108 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 100647223336 (93.74 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 108752.4 (30h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353281
telemt_connections_bad_total 15036
telemt_handshake_timeouts_total 3422
telemt_upstream_connect_attempt_total 41219
telemt_upstream_connect_success_total 31102
telemt_upstream_connect_fail_total 10117
telemt_upstream_connect_attempts_per_request{bucket="1"} 41219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10117
telemt_me_keepalive_timeout_total 4128
telemt_me_reconnect_attempts_total 96450
telemt_me_reconnect_success_total 22623
telemt_me_reader_eof_total 25606
telemt_me_idle_close_by_peer_total 25599
telemt_me_route_drop_no_conn_total 126690
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304476
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1149
telemt_desync_full_logged_total 338
telemt_desync_suppressed_total 811
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 434
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 25216
telemt_me_refill_failed_total 2302
telemt_me_writer_restored_same_endpoint_total 22613
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2593
telemt_user_connections_total{user="hello"} 307386
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 6667174238 (6.21 GB)
telemt_user_octets_to_client{user="hello"} 114836782185 (106.95 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 58923.8 (16h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88303
telemt_connections_bad_total 11832
telemt_handshake_timeouts_total 1205
telemt_upstream_connect_attempt_total 24637
telemt_upstream_connect_success_total 24440
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 24637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 1003
telemt_me_reconnect_attempts_total 26492
telemt_me_reconnect_success_total 16572
telemt_me_reader_eof_total 17790
telemt_me_idle_close_by_peer_total 17790
telemt_me_route_drop_no_conn_total 26374
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67544
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 180
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 17026
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16554
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 72444
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 884469953 (843.50 MB)
telemt_user_octets_to_client{user="hello"} 21409925423 (19.94 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 108708.7 (30h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 633655
telemt_connections_bad_total 17946
telemt_handshake_timeouts_total 18262
telemt_upstream_connect_attempt_total 22933
telemt_upstream_connect_success_total 22815
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 22933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2507
telemt_me_reconnect_attempts_total 22040
telemt_me_reconnect_success_total 17416
telemt_me_reader_eof_total 18697
telemt_me_idle_close_by_peer_total 18694
telemt_me_route_drop_no_conn_total 307825
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 603134
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 472
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 17786
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17409
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 576081
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 10083856196 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 306274541584 (285.24 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 58
```