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

# Server Metrics 2026-03-16 06:32:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 116283.5 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524476
telemt_connections_bad_total 5624
telemt_handshake_timeouts_total 18677
telemt_upstream_connect_attempt_total 27511
telemt_upstream_connect_success_total 27382
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 27511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25043
telemt_me_reconnect_success_total 21613
telemt_me_reader_eof_total 23128
telemt_me_idle_close_by_peer_total 23128
telemt_me_route_drop_no_conn_total 515843
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 523488
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2542
telemt_desync_full_logged_total 1016
telemt_desync_suppressed_total 1526
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 993
telemt_desync_frames_bucket_total{bucket="gt_10"} 1036
telemt_pool_swap_total 113
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21956
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21579
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 462334
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 9184791892 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 309072515620 (287.85 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 116290.7 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206193
telemt_connections_bad_total 3122
telemt_handshake_timeouts_total 14921
telemt_upstream_connect_attempt_total 31343
telemt_upstream_connect_success_total 31268
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 31343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 31995
telemt_me_reconnect_success_total 25078
telemt_me_reader_eof_total 26888
telemt_me_idle_close_by_peer_total 26887
telemt_me_route_drop_no_conn_total 102963
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180659
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 72
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 25636
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 25062
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 558
telemt_user_connections_total{user="hello"} 180196
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 3971454373 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 93276546576 (86.87 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 116283.1 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226333
telemt_connections_bad_total 4904
telemt_handshake_timeouts_total 4487
telemt_upstream_connect_attempt_total 32591
telemt_upstream_connect_success_total 32583
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 32591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34143
telemt_me_reconnect_success_total 26746
telemt_me_reader_eof_total 28803
telemt_me_idle_close_by_peer_total 28802
telemt_me_route_drop_no_conn_total 79764
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179452
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 27236
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 26738
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 179168
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 17235907293 (16.05 GB)
telemt_user_octets_to_client{user="hello"} 108085727808 (100.66 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 116282.9 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301812
telemt_connections_bad_total 1310
telemt_handshake_timeouts_total 2798
telemt_upstream_connect_attempt_total 27099
telemt_upstream_connect_success_total 27070
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 21425
telemt_me_reconnect_success_total 21293
telemt_me_reader_eof_total 22744
telemt_me_idle_close_by_peer_total 22743
telemt_me_route_drop_no_conn_total 108392
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277328
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 967
telemt_desync_full_logged_total 340
telemt_desync_suppressed_total 627
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 416
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 21561
telemt_me_writer_restored_same_endpoint_total 21282
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 277215
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 4622608904 (4.31 GB)
telemt_user_octets_to_client{user="hello"} 121595155636 (113.24 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 91354.2 (25h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203193
telemt_connections_bad_total 35105
telemt_handshake_timeouts_total 3579
telemt_upstream_connect_attempt_total 26043
telemt_upstream_connect_success_total 25901
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 26043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 115678
telemt_me_reconnect_success_total 21193
telemt_me_reader_eof_total 22505
telemt_me_idle_close_by_peer_total 22505
telemt_me_route_drop_no_conn_total 63946
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159266
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 421
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 21364
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 21089
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 158897
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 2146679701 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 69369599723 (64.61 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 116282.0 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752093
telemt_connections_bad_total 64454
telemt_handshake_timeouts_total 5600
telemt_upstream_connect_attempt_total 24563
telemt_upstream_connect_success_total 24431
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 24563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 19970
telemt_me_reconnect_success_total 18628
telemt_me_reader_eof_total 19898
telemt_me_idle_close_by_peer_total 19898
telemt_me_route_drop_no_conn_total 622513
telemt_me_route_drop_channel_closed_total 101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 759743
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 18887
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18601
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 618394
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 13877810576 (12.92 GB)
telemt_user_octets_to_client{user="hello"} 376474066624 (350.62 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 88
```