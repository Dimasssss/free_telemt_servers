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

# Server Metrics 2026-03-18 14:36:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 21334.2 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793253
telemt_connections_bad_total 46327
telemt_handshake_timeouts_total 21818
telemt_upstream_connect_attempt_total 67053
telemt_upstream_connect_success_total 66087
telemt_upstream_connect_fail_total 966
telemt_upstream_connect_attempts_per_request{bucket="1"} 67053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 966
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 517168
telemt_me_reconnect_success_total 3024
telemt_me_reader_eof_total 3275
telemt_me_idle_close_by_peer_total 3273
telemt_me_route_drop_no_conn_total 444340
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 613527
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2718
telemt_desync_full_logged_total 944
telemt_desync_suppressed_total 1774
telemt_desync_frames_bucket_total{bucket="1_2"} 758
telemt_desync_frames_bucket_total{bucket="3_10"} 935
telemt_desync_frames_bucket_total{bucket="gt_10"} 1025
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3279
telemt_me_refill_failed_total 16749
telemt_me_writer_restored_same_endpoint_total 2918
telemt_me_writer_restored_fallback_total 106
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 671628
telemt_user_connections_current{user="hello"} 1696
telemt_user_octets_from_client{user="hello"} 9986182084 (9.30 GB)
telemt_user_octets_to_client{user="hello"} 175626046177 (163.56 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 1902.8 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211640
telemt_connections_bad_total 10531
telemt_connections_current 3931
telemt_connections_me_current 3931
telemt_handshake_timeouts_total 4086
telemt_upstream_connect_attempt_total 342
telemt_upstream_connect_success_total 339
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 196
telemt_me_reconnect_success_total 193
telemt_me_reader_eof_total 87
telemt_me_idle_close_by_peer_total 86
telemt_me_route_drop_no_conn_total 117843
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186631
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 488
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 109
telemt_me_writer_restored_same_endpoint_total 191
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 186363
telemt_user_connections_current{user="hello"} 3931
telemt_user_octets_from_client{user="hello"} 1953824932 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 54576521364 (50.83 GB)
telemt_user_unique_ips_current{user="hello"} 1230
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 2545.5 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239322
telemt_connections_bad_total 888
telemt_connections_current 2558
telemt_connections_me_current 2558
telemt_handshake_timeouts_total 4907
telemt_upstream_connect_attempt_total 451
telemt_upstream_connect_success_total 449
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 290
telemt_me_reconnect_success_total 287
telemt_me_reader_eof_total 240
telemt_me_idle_close_by_peer_total 239
telemt_me_route_drop_no_conn_total 310025
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211781
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 662
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 473
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 294
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 261
telemt_me_writer_restored_same_endpoint_total 276
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 211729
telemt_user_connections_current{user="hello"} 2558
telemt_user_octets_from_client{user="hello"} 1384670668 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 35521533368 (33.08 GB)
telemt_user_unique_ips_current{user="hello"} 861
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 21205.8 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1753317
telemt_connections_bad_total 140426
telemt_handshake_timeouts_total 28024
telemt_upstream_connect_attempt_total 15260
telemt_upstream_connect_success_total 15232
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 802
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986920
telemt_me_reconnect_success_total 2481
telemt_me_reader_eof_total 2597
telemt_me_idle_close_by_peer_total 2597
telemt_me_route_drop_no_conn_total 1858637
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1457985
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4085
telemt_desync_full_logged_total 1420
telemt_desync_suppressed_total 2665
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 1589
telemt_desync_frames_bucket_total{bucket="gt_10"} 1821
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2551
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2366
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1459817
telemt_user_connections_current{user="hello"} 3206
telemt_user_octets_from_client{user="hello"} 21816002767 (20.32 GB)
telemt_user_octets_to_client{user="hello"} 483463148093 (450.26 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 991
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 1995.1 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53020
telemt_connections_bad_total 3886
telemt_connections_current 888
telemt_connections_me_current 888
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 588
telemt_upstream_connect_attempt_total 4434
telemt_upstream_connect_success_total 4429
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 4434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1754
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 329903
telemt_me_reconnect_success_total 451
telemt_me_reader_eof_total 346
telemt_me_idle_close_by_peer_total 346
telemt_me_route_drop_no_conn_total 33396
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42299
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 98
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 363
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 440
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 46073
telemt_user_connections_current{user="hello"} 888
telemt_user_octets_from_client{user="hello"} 661498769 (630.85 MB)
telemt_user_octets_to_client{user="hello"} 6397070457 (5.96 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 1064.7 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95981
telemt_connections_bad_total 3290
telemt_connections_current 2693
telemt_connections_me_current 2693
telemt_handshake_timeouts_total 1000
telemt_upstream_connect_attempt_total 318
telemt_upstream_connect_success_total 318
telemt_upstream_connect_attempts_per_request{bucket="1"} 318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 114
telemt_me_reconnect_attempts_total 14491
telemt_me_reconnect_success_total 203
telemt_me_reader_eof_total 86
telemt_me_idle_close_by_peer_total 86
telemt_me_route_drop_no_conn_total 127222
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86987
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 165
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 108
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 142
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 86971
telemt_user_connections_current{user="hello"} 2693
telemt_user_octets_from_client{user="hello"} 832442292 (793.88 MB)
telemt_user_octets_to_client{user="hello"} 15518859864 (14.45 GB)
telemt_user_unique_ips_current{user="hello"} 787
telemt_user_unique_ips_recent_window{user="hello"} 387
```