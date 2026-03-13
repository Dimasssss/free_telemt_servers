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

# Server Metrics 2026-03-13 14:59:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 113197.7 (31h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469013
telemt_connections_bad_total 3228
telemt_handshake_timeouts_total 8646
telemt_upstream_connect_attempt_total 28412
telemt_upstream_connect_success_total 28275
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2449
telemt_me_reconnect_attempts_total 26152
telemt_me_reconnect_success_total 22619
telemt_me_reader_eof_total 24161
telemt_me_idle_close_by_peer_total 24160
telemt_me_route_drop_no_conn_total 152738
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411232
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1348
telemt_desync_full_logged_total 478
telemt_desync_suppressed_total 870
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 565
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 22966
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22603
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 410809
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 7407863024 (6.90 GB)
telemt_user_octets_to_client{user="hello"} 190251862064 (177.19 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 113089.2 (31h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223490
telemt_connections_bad_total 1832
telemt_handshake_timeouts_total 1581
telemt_upstream_connect_attempt_total 81346
telemt_upstream_connect_success_total 80586
telemt_upstream_connect_fail_total 760
telemt_upstream_connect_attempts_per_request{bucket="1"} 81346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 784
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 760
telemt_me_keepalive_timeout_total 1399
telemt_me_reconnect_attempts_total 110802
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29431
telemt_me_idle_close_by_peer_total 29431
telemt_me_route_drop_no_conn_total 80625
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
telemt_user_connections_total{user="hello"} 211211
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 2114262656 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 67091073443 (62.48 GB)
telemt_user_msgs_from_client{user="hello"} 713839
telemt_user_msgs_to_client{user="hello"} 4779118
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 113053.4 (31h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270338
telemt_connections_bad_total 2423
telemt_handshake_timeouts_total 11998
telemt_upstream_connect_attempt_total 30426
telemt_upstream_connect_success_total 30422
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2299
telemt_me_reconnect_attempts_total 25946
telemt_me_reconnect_success_total 24727
telemt_me_reader_eof_total 26495
telemt_me_idle_close_by_peer_total 26495
telemt_me_route_drop_no_conn_total 97693
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246280
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 98
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 24997
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24707
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 246196
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 9533674332 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 105502277784 (98.26 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 113028.5 (31h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369679
telemt_connections_bad_total 15044
telemt_handshake_timeouts_total 3664
telemt_upstream_connect_attempt_total 42455
telemt_upstream_connect_success_total 32308
telemt_upstream_connect_fail_total 10147
telemt_upstream_connect_attempts_per_request{bucket="1"} 42455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15797
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10147
telemt_me_keepalive_timeout_total 4157
telemt_me_reconnect_attempts_total 99680
telemt_me_reconnect_success_total 23610
telemt_me_reader_eof_total 26693
telemt_me_idle_close_by_peer_total 26686
telemt_me_route_drop_no_conn_total 132526
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319877
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1241
telemt_desync_full_logged_total 368
telemt_desync_suppressed_total 873
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 466
telemt_desync_frames_bucket_total{bucket="gt_10"} 470
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26292
telemt_me_refill_failed_total 2372
telemt_me_writer_restored_same_endpoint_total 23600
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2682
telemt_user_connections_total{user="hello"} 322787
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 6876656482 (6.40 GB)
telemt_user_octets_to_client{user="hello"} 121824062957 (113.46 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 63200.1 (17h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97502
telemt_connections_bad_total 12686
telemt_handshake_timeouts_total 1220
telemt_upstream_connect_attempt_total 25883
telemt_upstream_connect_success_total 25660
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 25883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 1035
telemt_me_reconnect_attempts_total 27495
telemt_me_reconnect_success_total 17572
telemt_me_reader_eof_total 18831
telemt_me_idle_close_by_peer_total 18831
telemt_me_route_drop_no_conn_total 29212
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75588
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 334
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 266
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 18035
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 17554
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 80487
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 936829289 (893.43 MB)
telemt_user_octets_to_client{user="hello"} 24393770619 (22.72 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 112985.3 (31h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672774
telemt_connections_bad_total 19356
telemt_handshake_timeouts_total 21260
telemt_upstream_connect_attempt_total 23777
telemt_upstream_connect_success_total 23658
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 23777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 2540
telemt_me_reconnect_attempts_total 22666
telemt_me_reconnect_success_total 18040
telemt_me_reader_eof_total 19365
telemt_me_idle_close_by_peer_total 19362
telemt_me_route_drop_no_conn_total 322223
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636770
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 495
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 310
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18417
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18033
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 609720
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 10478168828 (9.76 GB)
telemt_user_octets_to_client{user="hello"} 319260468788 (297.33 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 75
```