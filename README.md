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

# Server Metrics 2026-03-13 14:54:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 112890.8 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467633
telemt_connections_bad_total 3228
telemt_handshake_timeouts_total 8646
telemt_upstream_connect_attempt_total 28362
telemt_upstream_connect_success_total 28225
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2436
telemt_me_reconnect_attempts_total 26102
telemt_me_reconnect_success_total 22569
telemt_me_reader_eof_total 24111
telemt_me_idle_close_by_peer_total 24110
telemt_me_route_drop_no_conn_total 152312
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409900
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1347
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 870
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 565
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 22916
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22553
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 409477
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 7359272096 (6.85 GB)
telemt_user_octets_to_client{user="hello"} 189503713648 (176.49 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 112783.7 (31h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222820
telemt_connections_bad_total 1830
telemt_handshake_timeouts_total 1581
telemt_upstream_connect_attempt_total 80706
telemt_upstream_connect_success_total 79947
telemt_upstream_connect_fail_total 759
telemt_upstream_connect_attempts_per_request{bucket="1"} 80706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 775
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 759
telemt_me_keepalive_timeout_total 1399
telemt_me_reconnect_attempts_total 110802
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29431
telemt_me_idle_close_by_peer_total 29431
telemt_me_route_drop_no_conn_total 80314
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162508
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 26
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
telemt_me_writer_removed_unexpected_total 28895
telemt_me_refill_failed_total 2645
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2873
telemt_user_connections_total{user="hello"} 210572
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 2109844873 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 66909545729 (62.31 GB)
telemt_user_msgs_from_client{user="hello"} 703896
telemt_user_msgs_to_client{user="hello"} 4727384
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 112747.5 (31h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269063
telemt_connections_bad_total 2378
telemt_handshake_timeouts_total 11843
telemt_upstream_connect_attempt_total 30377
telemt_upstream_connect_success_total 30373
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2292
telemt_me_reconnect_attempts_total 25897
telemt_me_reconnect_success_total 24678
telemt_me_reader_eof_total 26446
telemt_me_idle_close_by_peer_total 26446
telemt_me_route_drop_no_conn_total 97365
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245240
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
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 24948
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24658
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 245155
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 9528273704 (8.87 GB)
telemt_user_octets_to_client{user="hello"} 105357167704 (98.12 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 112722.9 (31h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368599
telemt_connections_bad_total 15044
telemt_handshake_timeouts_total 3658
telemt_upstream_connect_attempt_total 42406
telemt_upstream_connect_success_total 32259
telemt_upstream_connect_fail_total 10147
telemt_upstream_connect_attempts_per_request{bucket="1"} 42406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10147
telemt_me_keepalive_timeout_total 4147
telemt_me_reconnect_attempts_total 99631
telemt_me_reconnect_success_total 23560
telemt_me_reader_eof_total 26642
telemt_me_idle_close_by_peer_total 26635
telemt_me_route_drop_no_conn_total 132127
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318834
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1236
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 871
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 465
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26241
telemt_me_refill_failed_total 2372
telemt_me_writer_restored_same_endpoint_total 23550
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2681
telemt_user_connections_total{user="hello"} 321744
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 6868393486 (6.40 GB)
telemt_user_octets_to_client{user="hello"} 121398249593 (113.06 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 62894.4 (17h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96865
telemt_connections_bad_total 12630
telemt_handshake_timeouts_total 1218
telemt_upstream_connect_attempt_total 25756
telemt_upstream_connect_success_total 25541
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 25756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 1034
telemt_me_reconnect_attempts_total 27419
telemt_me_reconnect_success_total 17496
telemt_me_reader_eof_total 18753
telemt_me_idle_close_by_peer_total 18753
telemt_me_route_drop_no_conn_total 28977
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75031
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 332
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 17957
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 17478
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 79930
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 934042417 (890.77 MB)
telemt_user_octets_to_client{user="hello"} 24207723091 (22.55 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 112679.8 (31h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 670003
telemt_connections_bad_total 19324
telemt_handshake_timeouts_total 21249
telemt_upstream_connect_attempt_total 23743
telemt_upstream_connect_success_total 23624
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 23743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 2532
telemt_me_reconnect_attempts_total 22632
telemt_me_reconnect_success_total 18006
telemt_me_reader_eof_total 19327
telemt_me_idle_close_by_peer_total 19324
telemt_me_route_drop_no_conn_total 321208
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 634104
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 481
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18381
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17999
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 607056
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 10420561232 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 317856129188 (296.03 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 89
```