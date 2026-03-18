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

# Server Metrics 2026-03-18 14:41:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 21641.3 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806693
telemt_connections_bad_total 50544
telemt_handshake_timeouts_total 22203
telemt_upstream_connect_attempt_total 67085
telemt_upstream_connect_success_total 66119
telemt_upstream_connect_fail_total 966
telemt_upstream_connect_attempts_per_request{bucket="1"} 67085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 966
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 517189
telemt_me_reconnect_success_total 3045
telemt_me_reader_eof_total 3296
telemt_me_idle_close_by_peer_total 3294
telemt_me_route_drop_no_conn_total 448379
telemt_me_route_drop_channel_closed_total 174
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 621652
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2791
telemt_desync_full_logged_total 958
telemt_desync_suppressed_total 1833
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 952
telemt_desync_frames_bucket_total{bucket="gt_10"} 1049
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3300
telemt_me_refill_failed_total 16749
telemt_me_writer_restored_same_endpoint_total 2939
telemt_me_writer_restored_fallback_total 106
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 679747
telemt_user_connections_current{user="hello"} 1731
telemt_user_octets_from_client{user="hello"} 10142970668 (9.45 GB)
telemt_user_octets_to_client{user="hello"} 178356150017 (166.11 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 2209.7 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240203
telemt_connections_bad_total 12977
telemt_connections_current 3982
telemt_connections_me_current 3982
telemt_handshake_timeouts_total 4641
telemt_upstream_connect_attempt_total 398
telemt_upstream_connect_success_total 395
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 240
telemt_me_reconnect_success_total 236
telemt_me_reader_eof_total 137
telemt_me_idle_close_by_peer_total 136
telemt_me_route_drop_no_conn_total 134072
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211317
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 569
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 393
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 154
telemt_me_writer_restored_same_endpoint_total 234
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 210613
telemt_user_connections_current{user="hello"} 3982
telemt_user_octets_from_client{user="hello"} 2162055596 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 63482002936 (59.12 GB)
telemt_user_unique_ips_current{user="hello"} 1208
telemt_user_unique_ips_recent_window{user="hello"} 574
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 2137.9 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154770
telemt_connections_bad_total 7228
telemt_connections_current 3049
telemt_connections_me_current 3049
telemt_handshake_timeouts_total 3095
telemt_upstream_connect_attempt_total 305
telemt_upstream_connect_success_total 302
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 147
telemt_me_reconnect_success_total 146
telemt_me_reader_eof_total 133
telemt_me_idle_close_by_peer_total 133
telemt_me_route_drop_no_conn_total 51209
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134238
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 455
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 325
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 150
telemt_me_writer_restored_same_endpoint_total 129
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 134212
telemt_user_connections_current{user="hello"} 3049
telemt_user_octets_from_client{user="hello"} 3061138272 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 52575280076 (48.96 GB)
telemt_user_unique_ips_current{user="hello"} 955
telemt_user_unique_ips_recent_window{user="hello"} 456
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 2852.2 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259819
telemt_connections_bad_total 962
telemt_connections_current 2648
telemt_connections_me_current 2648
telemt_handshake_timeouts_total 5308
telemt_upstream_connect_attempt_total 533
telemt_upstream_connect_success_total 531
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 329
telemt_me_reconnect_success_total 326
telemt_me_reader_eof_total 286
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 330959
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229907
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 692
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 489
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 300
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 229849
telemt_user_connections_current{user="hello"} 2648
telemt_user_octets_from_client{user="hello"} 1528097876 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 40741043396 (37.94 GB)
telemt_user_unique_ips_current{user="hello"} 854
telemt_user_unique_ips_recent_window{user="hello"} 424
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 21512.1 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1773475
telemt_connections_bad_total 141539
telemt_handshake_timeouts_total 28296
telemt_upstream_connect_attempt_total 15276
telemt_upstream_connect_success_total 15248
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986936
telemt_me_reconnect_success_total 2497
telemt_me_reader_eof_total 2615
telemt_me_idle_close_by_peer_total 2615
telemt_me_route_drop_no_conn_total 1866948
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1475086
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4146
telemt_desync_full_logged_total 1442
telemt_desync_suppressed_total 2704
telemt_desync_frames_bucket_total{bucket="1_2"} 682
telemt_desync_frames_bucket_total{bucket="3_10"} 1619
telemt_desync_frames_bucket_total{bucket="gt_10"} 1845
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2569
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2382
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1476909
telemt_user_connections_current{user="hello"} 3106
telemt_user_octets_from_client{user="hello"} 22140075963 (20.62 GB)
telemt_user_octets_to_client{user="hello"} 491220293765 (457.48 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 1032
telemt_user_unique_ips_recent_window{user="hello"} 524
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 2302.7 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58937
telemt_connections_bad_total 4238
telemt_connections_current 949
telemt_connections_me_current 949
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 620
telemt_upstream_connect_attempt_total 4489
telemt_upstream_connect_success_total 4484
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 4489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1783
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 329958
telemt_me_reconnect_success_total 504
telemt_me_reader_eof_total 399
telemt_me_idle_close_by_peer_total 399
telemt_me_route_drop_no_conn_total 35657
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47596
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 107
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 416
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 493
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 51368
telemt_user_connections_current{user="hello"} 949
telemt_user_octets_from_client{user="hello"} 792306469 (755.60 MB)
telemt_user_octets_to_client{user="hello"} 7458221913 (6.95 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 1371.6 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115532
telemt_connections_bad_total 3976
telemt_connections_current 2863
telemt_connections_me_current 2863
telemt_handshake_timeouts_total 1120
telemt_upstream_connect_attempt_total 352
telemt_upstream_connect_success_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 131
telemt_me_reconnect_attempts_total 14525
telemt_me_reconnect_success_total 237
telemt_me_reader_eof_total 122
telemt_me_idle_close_by_peer_total 122
telemt_me_route_drop_no_conn_total 131928
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103117
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 205
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 144
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 176
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 103095
telemt_user_connections_current{user="hello"} 2863
telemt_user_octets_from_client{user="hello"} 1019436944 (972.21 MB)
telemt_user_octets_to_client{user="hello"} 21555271068 (20.07 GB)
telemt_user_unique_ips_current{user="hello"} 797
telemt_user_unique_ips_recent_window{user="hello"} 407
```