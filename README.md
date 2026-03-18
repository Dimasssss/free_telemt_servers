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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 14:16:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 20108.4 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 743783
telemt_connections_bad_total 36302
telemt_handshake_timeouts_total 20353
telemt_upstream_connect_attempt_total 66890
telemt_upstream_connect_success_total 65927
telemt_upstream_connect_fail_total 963
telemt_upstream_connect_attempts_per_request{bucket="1"} 66890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 963
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 515716
telemt_me_reconnect_success_total 2910
telemt_me_reader_eof_total 3118
telemt_me_idle_close_by_peer_total 3116
telemt_me_route_drop_no_conn_total 427456
telemt_me_route_drop_channel_closed_total 162
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 578945
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2512
telemt_desync_full_logged_total 883
telemt_desync_suppressed_total 1629
telemt_desync_frames_bucket_total{bucket="1_2"} 702
telemt_desync_frames_bucket_total{bucket="3_10"} 866
telemt_desync_frames_bucket_total{bucket="gt_10"} 944
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3122
telemt_me_refill_failed_total 16708
telemt_me_writer_restored_same_endpoint_total 2805
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 637093
telemt_user_connections_current{user="hello"} 1652
telemt_user_octets_from_client{user="hello"} 8713270448 (8.11 GB)
telemt_user_octets_to_client{user="hello"} 166513530561 (155.08 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 677.1 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77473
telemt_connections_bad_total 2562
telemt_connections_current 3878
telemt_connections_me_current 3878
telemt_handshake_timeouts_total 1419
telemt_upstream_connect_attempt_total 188
telemt_upstream_connect_success_total 187
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 120
telemt_me_reconnect_success_total 119
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 34914
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69033
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 216
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_me_writer_removed_unexpected_total 33
telemt_me_writer_restored_same_endpoint_total 117
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 68823
telemt_user_connections_current{user="hello"} 3878
telemt_user_octets_from_client{user="hello"} 677748748 (646.35 MB)
telemt_user_octets_to_client{user="hello"} 21234645852 (19.78 GB)
telemt_user_unique_ips_current{user="hello"} 1205
telemt_user_unique_ips_recent_window{user="hello"} 593
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 605.0 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51317
telemt_connections_bad_total 2475
telemt_connections_current 3246
telemt_connections_me_current 3246
telemt_handshake_timeouts_total 715
telemt_upstream_connect_attempt_total 101
telemt_upstream_connect_success_total 100
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 32
telemt_me_reconnect_success_total 31
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 15361
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42967
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 101
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_me_writer_removed_unexpected_total 32
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 42965
telemt_user_connections_current{user="hello"} 3246
telemt_user_octets_from_client{user="hello"} 1325239148 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 15181013372 (14.14 GB)
telemt_user_unique_ips_current{user="hello"} 952
telemt_user_unique_ips_recent_window{user="hello"} 456
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 1319.4 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150200
telemt_connections_bad_total 307
telemt_connections_current 2768
telemt_connections_me_current 2768
telemt_handshake_timeouts_total 2440
telemt_upstream_connect_attempt_total 245
telemt_upstream_connect_success_total 243
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 131
telemt_me_reconnect_success_total 130
telemt_me_reader_eof_total 82
telemt_me_idle_close_by_peer_total 81
telemt_me_route_drop_no_conn_total 224514
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134701
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 325
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 238
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 102
telemt_me_writer_restored_same_endpoint_total 119
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 134688
telemt_user_connections_current{user="hello"} 2768
telemt_user_octets_from_client{user="hello"} 713940908 (680.87 MB)
telemt_user_octets_to_client{user="hello"} 15213512228 (14.17 GB)
telemt_user_unique_ips_current{user="hello"} 818
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 19979.4 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1659272
telemt_connections_bad_total 119796
telemt_handshake_timeouts_total 26917
telemt_upstream_connect_attempt_total 15056
telemt_upstream_connect_success_total 15028
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986761
telemt_me_reconnect_success_total 2323
telemt_me_reader_eof_total 2431
telemt_me_idle_close_by_peer_total 2431
telemt_me_route_drop_no_conn_total 1831219
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1391356
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3880
telemt_desync_full_logged_total 1334
telemt_desync_suppressed_total 2546
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 1492
telemt_desync_frames_bucket_total{bucket="gt_10"} 1750
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2392
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2208
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1393225
telemt_user_connections_current{user="hello"} 2991
telemt_user_octets_from_client{user="hello"} 20410861319 (19.01 GB)
telemt_user_octets_to_client{user="hello"} 455148438833 (423.89 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 918
telemt_user_unique_ips_recent_window{user="hello"} 562
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 768.2 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27893
telemt_connections_bad_total 1959
telemt_connections_current 890
telemt_connections_me_current 890
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 156
telemt_upstream_connect_attempt_total 4203
telemt_upstream_connect_success_total 4201
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 329763
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 205
telemt_me_idle_close_by_peer_total 205
telemt_me_route_drop_no_conn_total 23598
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20643
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 23
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 223
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 302
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 24428
telemt_user_connections_current{user="hello"} 890
telemt_user_octets_from_client{user="hello"} 358758309 (342.14 MB)
telemt_user_octets_to_client{user="hello"} 2833495305 (2.64 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 19935.4 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1299590
telemt_connections_bad_total 148968
telemt_handshake_timeouts_total 24874
telemt_upstream_connect_attempt_total 3672
telemt_upstream_connect_success_total 3637
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 3672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 6325
telemt_me_reconnect_success_total 2535
telemt_me_reader_eof_total 2705
telemt_me_idle_close_by_peer_total 2705
telemt_me_route_drop_no_conn_total 789878
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1027228
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3372
telemt_desync_full_logged_total 1117
telemt_desync_suppressed_total 2255
telemt_desync_frames_bucket_total{bucket="1_2"} 626
telemt_desync_frames_bucket_total{bucket="3_10"} 1133
telemt_desync_frames_bucket_total{bucket="gt_10"} 1613
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2675
telemt_me_refill_failed_total 117
telemt_me_writer_restored_same_endpoint_total 2525
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 1026518
telemt_user_connections_current{user="hello"} 3063
telemt_user_octets_from_client{user="hello"} 20245450748 (18.86 GB)
telemt_user_octets_to_client{user="hello"} 464056267616 (432.19 GB)
telemt_user_unique_ips_current{user="hello"} 921
telemt_user_unique_ips_recent_window{user="hello"} 426
```