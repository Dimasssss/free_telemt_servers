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

# Server Metrics 2026-03-13 16:26:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 118408.2 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493206
telemt_connections_bad_total 3959
telemt_handshake_timeouts_total 8902
telemt_upstream_connect_attempt_total 29487
telemt_upstream_connect_success_total 29343
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 29487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2575
telemt_me_reconnect_attempts_total 26960
telemt_me_reconnect_success_total 23421
telemt_me_reader_eof_total 25024
telemt_me_idle_close_by_peer_total 25023
telemt_me_route_drop_no_conn_total 161566
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433282
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1400
telemt_desync_full_logged_total 491
telemt_desync_suppressed_total 909
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 504
telemt_desync_frames_bucket_total{bucket="gt_10"} 590
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 23781
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23405
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 360
telemt_user_connections_total{user="hello"} 432854
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 7659793316 (7.13 GB)
telemt_user_octets_to_client{user="hello"} 201492494500 (187.65 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 118300.7 (32h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239845
telemt_connections_bad_total 1885
telemt_handshake_timeouts_total 1742
telemt_upstream_connect_attempt_total 95903
telemt_upstream_connect_success_total 95097
telemt_upstream_connect_fail_total 806
telemt_upstream_connect_attempts_per_request{bucket="1"} 95903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 806
telemt_me_keepalive_timeout_total 1434
telemt_me_reconnect_attempts_total 119064
telemt_me_reconnect_success_total 26027
telemt_me_reader_eof_total 29689
telemt_me_idle_close_by_peer_total 29689
telemt_me_route_drop_no_conn_total 81837
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163996
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 28
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
telemt_me_writer_removed_unexpected_total 29158
telemt_me_refill_failed_total 2903
telemt_me_writer_restored_same_endpoint_total 26010
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3131
telemt_user_connections_total{user="hello"} 226936
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 2400958227 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 70704287730 (65.85 GB)
telemt_user_msgs_from_client{user="hello"} 992585
telemt_user_msgs_to_client{user="hello"} 5867452
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 118264.4 (32h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287046
telemt_connections_bad_total 2445
telemt_handshake_timeouts_total 14293
telemt_upstream_connect_attempt_total 31633
telemt_upstream_connect_success_total 31629
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16913
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2459
telemt_me_reconnect_attempts_total 26889
telemt_me_reconnect_success_total 25666
telemt_me_reader_eof_total 27502
telemt_me_idle_close_by_peer_total 27502
telemt_me_route_drop_no_conn_total 103215
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260145
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 25953
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25646
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 260058
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 10077756124 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 109232530296 (101.73 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 118239.9 (32h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389017
telemt_connections_bad_total 15068
telemt_handshake_timeouts_total 3822
telemt_upstream_connect_attempt_total 44182
telemt_upstream_connect_success_total 33984
telemt_upstream_connect_fail_total 10198
telemt_upstream_connect_attempts_per_request{bucket="1"} 44182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16331
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 214
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10198
telemt_me_keepalive_timeout_total 4179
telemt_me_reconnect_attempts_total 108445
telemt_me_reconnect_success_total 24243
telemt_me_reader_eof_total 27582
telemt_me_idle_close_by_peer_total 27575
telemt_me_route_drop_no_conn_total 139152
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337386
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27181
telemt_me_refill_failed_total 2626
telemt_me_writer_restored_same_endpoint_total 24233
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2938
telemt_user_connections_total{user="hello"} 341076
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 7674085871 (7.15 GB)
telemt_user_octets_to_client{user="hello"} 125726905698 (117.09 GB)
telemt_user_msgs_from_client{user="hello"} 105476
telemt_user_msgs_to_client{user="hello"} 144632
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 68411.4 (19h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108774
telemt_connections_bad_total 14250
telemt_handshake_timeouts_total 1355
telemt_upstream_connect_attempt_total 27361
telemt_upstream_connect_success_total 27120
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 27361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_timeout_total 1096
telemt_me_reconnect_attempts_total 29986
telemt_me_reconnect_success_total 18812
telemt_me_reader_eof_total 20168
telemt_me_idle_close_by_peer_total 20168
telemt_me_route_drop_no_conn_total 33267
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84773
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 19322
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 18794
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 89672
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 1029318293 (981.63 MB)
telemt_user_octets_to_client{user="hello"} 27879783923 (25.97 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 118197.7 (32h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719364
telemt_connections_bad_total 24639
telemt_handshake_timeouts_total 23996
telemt_upstream_connect_attempt_total 24714
telemt_upstream_connect_success_total 24589
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 24714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 2622
telemt_me_reconnect_attempts_total 23336
telemt_me_reconnect_success_total 18706
telemt_me_reader_eof_total 20077
telemt_me_idle_close_by_peer_total 20074
telemt_me_route_drop_no_conn_total 339710
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 674268
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 667
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19089
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18699
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 647165
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 11270293844 (10.50 GB)
telemt_user_octets_to_client{user="hello"} 330767232888 (308.05 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 62
```