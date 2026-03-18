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

# Server Metrics 2026-03-18 10:01:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 4828.0 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185569
telemt_connections_bad_total 1143
telemt_handshake_timeouts_total 3621
telemt_upstream_connect_attempt_total 63946
telemt_upstream_connect_success_total 63025
telemt_upstream_connect_fail_total 921
telemt_upstream_connect_attempts_per_request{bucket="1"} 63946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3004
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 921
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 507428
telemt_me_reconnect_success_total 789
telemt_me_reader_eof_total 735
telemt_me_idle_close_by_peer_total 733
telemt_me_route_drop_no_conn_total 41028
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98394
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 556
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 387
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 776
telemt_me_refill_failed_total 16516
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 160252
telemt_user_connections_current{user="hello"} 1599
telemt_user_octets_from_client{user="hello"} 1871503548 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 35788487037 (33.33 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 518
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 4859.0 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431265
telemt_connections_bad_total 52313
telemt_handshake_timeouts_total 10631
telemt_upstream_connect_attempt_total 847
telemt_upstream_connect_success_total 847
telemt_upstream_connect_attempts_per_request{bucket="1"} 847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 555
telemt_me_reconnect_success_total 544
telemt_me_reader_eof_total 514
telemt_me_idle_close_by_peer_total 514
telemt_me_route_drop_no_conn_total 159732
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342316
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1697
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 1249
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 699
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 523
telemt_me_writer_restored_same_endpoint_total 543
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 341457
telemt_user_connections_current{user="hello"} 3599
telemt_user_octets_from_client{user="hello"} 8086243328 (7.53 GB)
telemt_user_octets_to_client{user="hello"} 126454375680 (117.77 GB)
telemt_user_unique_ips_current{user="hello"} 1118
telemt_user_unique_ips_recent_window{user="hello"} 578
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 4774.2 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344942
telemt_connections_bad_total 19046
telemt_handshake_timeouts_total 8705
telemt_upstream_connect_attempt_total 9218
telemt_upstream_connect_success_total 9218
telemt_upstream_connect_attempts_per_request{bucket="1"} 9218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606390
telemt_me_reconnect_success_total 718
telemt_me_reader_eof_total 684
telemt_me_idle_close_by_peer_total 683
telemt_me_route_drop_no_conn_total 171506
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254089
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 608
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 207
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 711
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 683
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 262111
telemt_user_connections_current{user="hello"} 2652
telemt_user_octets_from_client{user="hello"} 2636928643 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 94780326140 (88.27 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 804
telemt_user_unique_ips_recent_window{user="hello"} 443
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 4804.1 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681196
telemt_connections_bad_total 7746
telemt_handshake_timeouts_total 73323
telemt_upstream_connect_attempt_total 11582
telemt_upstream_connect_success_total 11473
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 11582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2814600
telemt_me_reconnect_success_total 899
telemt_me_reader_eof_total 988
telemt_me_idle_close_by_peer_total 988
telemt_me_route_drop_no_conn_total 1328180
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 534210
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 717
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 505
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 246
telemt_me_writer_removed_unexpected_total 1014
telemt_me_refill_failed_total 99666
telemt_me_writer_restored_same_endpoint_total 804
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 553175
telemt_user_connections_current{user="hello"} 2800
telemt_user_octets_from_client{user="hello"} 3666642110 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 63223551625 (58.88 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 843
telemt_user_unique_ips_recent_window{user="hello"} 509
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 4699.2 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331759
telemt_connections_bad_total 10031
telemt_handshake_timeouts_total 4986
telemt_upstream_connect_attempt_total 10501
telemt_upstream_connect_success_total 10500
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982655
telemt_me_reconnect_success_total 705
telemt_me_reader_eof_total 649
telemt_me_idle_close_by_peer_total 649
telemt_me_route_drop_no_conn_total 142547
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269219
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 846
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 550
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 394
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 657
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 590
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 277631
telemt_user_connections_current{user="hello"} 3403
telemt_user_octets_from_client{user="hello"} 5036631705 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 108247619497 (100.81 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 970
telemt_user_unique_ips_recent_window{user="hello"} 493
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 4584.3 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92817
telemt_connections_bad_total 12282
telemt_handshake_timeouts_total 490
telemt_upstream_connect_attempt_total 770
telemt_upstream_connect_success_total 769
telemt_upstream_connect_attempts_per_request{bucket="1"} 769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 352
telemt_me_reconnect_attempts_total 501
telemt_me_reconnect_success_total 497
telemt_me_reader_eof_total 485
telemt_me_idle_close_by_peer_total 485
telemt_me_route_drop_no_conn_total 35460
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76525
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 169
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 492
telemt_me_writer_restored_same_endpoint_total 489
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 74131
telemt_user_connections_current{user="hello"} 883
telemt_user_octets_from_client{user="hello"} 1372336784 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 16541689608 (15.41 GB)
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 4655.1 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232037
telemt_connections_bad_total 6064
telemt_handshake_timeouts_total 4299
telemt_upstream_connect_attempt_total 822
telemt_upstream_connect_success_total 804
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 519
telemt_me_reconnect_success_total 509
telemt_me_reader_eof_total 481
telemt_me_idle_close_by_peer_total 481
telemt_me_route_drop_no_conn_total 136569
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204887
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 671
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 294
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 498
telemt_me_writer_restored_same_endpoint_total 499
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 204735
telemt_user_connections_current{user="hello"} 2400
telemt_user_octets_from_client{user="hello"} 2984876652 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 96888987872 (90.23 GB)
telemt_user_unique_ips_current{user="hello"} 678
telemt_user_unique_ips_recent_window{user="hello"} 355
```