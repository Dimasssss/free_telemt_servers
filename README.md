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

# Server Metrics 2026-03-12 14:20:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 24413.9 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129251
telemt_connections_bad_total 1373
telemt_handshake_timeouts_total 4490
telemt_upstream_connect_attempt_total 5997
telemt_upstream_connect_success_total 5973
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 254
telemt_me_reconnect_attempts_total 4719
telemt_me_reconnect_success_total 4688
telemt_me_reader_eof_total 4924
telemt_me_idle_close_by_peer_total 4923
telemt_me_route_drop_no_conn_total 36697
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113200
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 541
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 342
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4729
telemt_me_writer_restored_same_endpoint_total 4672
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 113162
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 1893707108 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 42672969584 (39.74 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 24306.7 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53063
telemt_connections_bad_total 445
telemt_handshake_timeouts_total 361
telemt_upstream_connect_attempt_total 7162
telemt_upstream_connect_success_total 6995
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 7162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 161
telemt_me_reconnect_attempts_total 21609
telemt_me_reconnect_success_total 5776
telemt_me_reader_eof_total 6386
telemt_me_idle_close_by_peer_total 6386
telemt_me_route_drop_no_conn_total 23756
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50629
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
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
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 6307
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 5761
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 531
telemt_user_connections_total{user="hello"} 50623
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 587536800 (560.32 MB)
telemt_user_octets_to_client{user="hello"} 14230147916 (13.25 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 24270.3 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73408
telemt_connections_bad_total 1417
telemt_handshake_timeouts_total 1108
telemt_upstream_connect_attempt_total 6488
telemt_upstream_connect_success_total 6488
telemt_upstream_connect_attempts_per_request{bucket="1"} 6488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3324
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 5275
telemt_me_reconnect_success_total 5235
telemt_me_reader_eof_total 5535
telemt_me_idle_close_by_peer_total 5535
telemt_me_route_drop_no_conn_total 25537
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67721
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5271
telemt_me_writer_restored_same_endpoint_total 5215
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 67700
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1895200152 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 38962158688 (36.29 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 24246.1 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93068
telemt_connections_bad_total 1977
telemt_handshake_timeouts_total 707
telemt_upstream_connect_attempt_total 6358
telemt_upstream_connect_success_total 6197
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 6358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 18067
telemt_me_reconnect_success_total 4959
telemt_me_reader_eof_total 5500
telemt_me_idle_close_by_peer_total 5500
telemt_me_route_drop_no_conn_total 34507
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85020
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 268
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 178
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5425
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 4951
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 84904
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 1403882008 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 35586111728 (33.14 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 24215.5 (6h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54372
telemt_connections_bad_total 4629
telemt_handshake_timeouts_total 705
telemt_upstream_connect_attempt_total 20331
telemt_upstream_connect_success_total 20032
telemt_upstream_connect_fail_total 299
telemt_upstream_connect_attempts_per_request{bucket="1"} 20331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 299
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 31455
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4548
telemt_me_idle_close_by_peer_total 4548
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12210
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32630
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 442
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4573
telemt_me_refill_failed_total 869
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 889
telemt_user_connections_total{user="hello"} 47743
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 396630647 (378.26 MB)
telemt_user_octets_to_client{user="hello"} 12023854096 (11.20 GB)
telemt_user_msgs_from_client{user="hello"} 217274
telemt_user_msgs_to_client{user="hello"} 627098
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 24202.9 (6h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146528
telemt_connections_bad_total 781
telemt_handshake_timeouts_total 1105
telemt_upstream_connect_attempt_total 4963
telemt_upstream_connect_success_total 4939
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 4963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3744
telemt_me_reconnect_success_total 3714
telemt_me_reader_eof_total 3911
telemt_me_idle_close_by_peer_total 3911
telemt_me_route_drop_no_conn_total 57682
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140092
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 229
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3758
telemt_me_writer_restored_same_endpoint_total 3707
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 140059
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 2867101872 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 58553750048 (54.53 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 50
```