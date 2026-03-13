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

# Server Metrics 2026-03-13 04:39:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 75961.2 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290073
telemt_connections_bad_total 3032
telemt_handshake_timeouts_total 5774
telemt_upstream_connect_attempt_total 19218
telemt_upstream_connect_success_total 19128
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 19218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1548
telemt_me_reconnect_attempts_total 18796
telemt_me_reconnect_success_total 15300
telemt_me_reader_eof_total 16359
telemt_me_idle_close_by_peer_total 16358
telemt_me_route_drop_no_conn_total 90439
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243402
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 816
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 511
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 296
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 15576
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15284
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 243341
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 4224706736 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 119874045892 (111.64 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 75854.4 (21h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133220
telemt_connections_bad_total 751
telemt_handshake_timeouts_total 1001
telemt_upstream_connect_attempt_total 40731
telemt_upstream_connect_success_total 40222
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 40731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 505
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_timeout_total 554
telemt_me_reconnect_attempts_total 66475
telemt_me_reconnect_success_total 19913
telemt_me_reader_eof_total 21973
telemt_me_idle_close_by_peer_total 21973
telemt_me_route_drop_no_conn_total 48892
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110061
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 21519
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 19898
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1606
telemt_user_connections_total{user="hello"} 126561
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 1308405144 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 38034164375 (35.42 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 75817.9 (21h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160706
telemt_connections_bad_total 1845
telemt_handshake_timeouts_total 2602
telemt_upstream_connect_attempt_total 20970
telemt_upstream_connect_success_total 20968
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 443
telemt_me_reconnect_attempts_total 18283
telemt_me_reconnect_success_total 17119
telemt_me_reader_eof_total 18338
telemt_me_idle_close_by_peer_total 18338
telemt_me_route_drop_no_conn_total 62084
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150304
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 17309
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17099
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 150231
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 2847676084 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 70158840616 (65.34 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 75793.7 (21h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231583
telemt_connections_bad_total 13507
telemt_handshake_timeouts_total 1462
telemt_upstream_connect_attempt_total 33426
telemt_upstream_connect_success_total 23552
telemt_upstream_connect_fail_total 9874
telemt_upstream_connect_attempts_per_request{bucket="1"} 33426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11517
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9874
telemt_me_keepalive_timeout_total 3310
telemt_me_reconnect_attempts_total 64029
telemt_me_reconnect_success_total 16883
telemt_me_reader_eof_total 18879
telemt_me_idle_close_by_peer_total 18872
telemt_me_route_drop_no_conn_total 84537
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193717
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 506
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18580
telemt_me_refill_failed_total 1469
telemt_me_writer_restored_same_endpoint_total 16873
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1697
telemt_user_connections_total{user="hello"} 196465
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 3225049490 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 79236445793 (73.79 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 25965.3 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26385
telemt_connections_bad_total 4854
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 8123
telemt_upstream_connect_success_total 8047
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 8123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 192
telemt_me_reconnect_attempts_total 6775
telemt_me_reconnect_success_total 6750
telemt_me_reader_eof_total 7229
telemt_me_idle_close_by_peer_total 7229
telemt_me_route_drop_no_conn_total 7255
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20682
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6810
telemt_me_writer_restored_same_endpoint_total 6732
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 20682
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 148612764 (141.73 MB)
telemt_user_octets_to_client{user="hello"} 9087031052 (8.46 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 75750.1 (21h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389938
telemt_connections_bad_total 7703
telemt_handshake_timeouts_total 2939
telemt_upstream_connect_attempt_total 16133
telemt_upstream_connect_success_total 16042
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 16133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 1432
telemt_me_reconnect_attempts_total 15883
telemt_me_reconnect_success_total 12255
telemt_me_reader_eof_total 13157
telemt_me_idle_close_by_peer_total 13154
telemt_me_route_drop_no_conn_total 174203
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380174
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 12525
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12248
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 368418
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 6122852444 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 218799110324 (203.77 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 27
```