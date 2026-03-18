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

# Server Metrics 2026-03-18 14:52:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 22259.6 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 829027
telemt_connections_bad_total 55981
telemt_handshake_timeouts_total 22965
telemt_upstream_connect_attempt_total 67163
telemt_upstream_connect_success_total 66194
telemt_upstream_connect_fail_total 969
telemt_upstream_connect_attempts_per_request{bucket="1"} 67163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 969
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 518608
telemt_me_reconnect_success_total 3087
telemt_me_reader_eof_total 3381
telemt_me_idle_close_by_peer_total 3379
telemt_me_route_drop_no_conn_total 454953
telemt_me_route_drop_channel_closed_total 177
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636944
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2856
telemt_desync_full_logged_total 984
telemt_desync_suppressed_total 1872
telemt_desync_frames_bucket_total{bucket="1_2"} 802
telemt_desync_frames_bucket_total{bucket="3_10"} 974
telemt_desync_frames_bucket_total{bucket="gt_10"} 1080
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3385
telemt_me_refill_failed_total 16792
telemt_me_writer_restored_same_endpoint_total 2981
telemt_me_writer_restored_fallback_total 106
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 695026
telemt_user_connections_current{user="hello"} 1592
telemt_user_octets_from_client{user="hello"} 10323824120 (9.61 GB)
telemt_user_octets_to_client{user="hello"} 182603230269 (170.06 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 528
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 2827.5 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293434
telemt_connections_bad_total 16709
telemt_connections_current 4073
telemt_connections_me_current 4073
telemt_handshake_timeouts_total 6508
telemt_upstream_connect_attempt_total 475
telemt_upstream_connect_success_total 472
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 274
telemt_me_reconnect_success_total 270
telemt_me_reader_eof_total 172
telemt_me_idle_close_by_peer_total 171
telemt_me_route_drop_no_conn_total 157068
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256184
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 790
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 567
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 188
telemt_me_writer_restored_same_endpoint_total 268
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 255446
telemt_user_connections_current{user="hello"} 4073
telemt_user_octets_from_client{user="hello"} 2805961184 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 81706152228 (76.09 GB)
telemt_user_unique_ips_current{user="hello"} 1232
telemt_user_unique_ips_recent_window{user="hello"} 571
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 2756.0 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195841
telemt_connections_bad_total 9759
telemt_connections_current 3201
telemt_connections_me_current 3201
telemt_handshake_timeouts_total 4198
telemt_upstream_connect_attempt_total 366
telemt_upstream_connect_success_total 363
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 185
telemt_me_reconnect_success_total 183
telemt_me_reader_eof_total 172
telemt_me_idle_close_by_peer_total 172
telemt_me_route_drop_no_conn_total 66561
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170270
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 533
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 377
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 189
telemt_me_writer_restored_same_endpoint_total 166
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 170244
telemt_user_connections_current{user="hello"} 3201
telemt_user_octets_from_client{user="hello"} 3593886820 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 67372119688 (62.75 GB)
telemt_user_unique_ips_current{user="hello"} 985
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 3470.3 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305255
telemt_connections_bad_total 1176
telemt_connections_current 2839
telemt_connections_me_current 2839
telemt_handshake_timeouts_total 5903
telemt_upstream_connect_attempt_total 579
telemt_upstream_connect_success_total 577
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 375
telemt_me_reconnect_success_total 371
telemt_me_reader_eof_total 334
telemt_me_idle_close_by_peer_total 333
telemt_me_route_drop_no_conn_total 374111
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 271532
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 789
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 561
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 347
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 271476
telemt_user_connections_current{user="hello"} 2839
telemt_user_octets_from_client{user="hello"} 2091535112 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 50496343340 (47.03 GB)
telemt_user_unique_ips_current{user="hello"} 851
telemt_user_unique_ips_recent_window{user="hello"} 426
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 22130.0 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1814355
telemt_connections_bad_total 145033
telemt_handshake_timeouts_total 28858
telemt_upstream_connect_attempt_total 15418
telemt_upstream_connect_success_total 15390
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 805
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2987034
telemt_me_reconnect_success_total 2594
telemt_me_reader_eof_total 2712
telemt_me_idle_close_by_peer_total 2712
telemt_me_route_drop_no_conn_total 1882493
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1508553
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4296
telemt_desync_full_logged_total 1505
telemt_desync_suppressed_total 2791
telemt_desync_frames_bucket_total{bucket="1_2"} 700
telemt_desync_frames_bucket_total{bucket="3_10"} 1672
telemt_desync_frames_bucket_total{bucket="gt_10"} 1924
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2666
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2479
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1510376
telemt_user_connections_current{user="hello"} 3020
telemt_user_octets_from_client{user="hello"} 23088502727 (21.50 GB)
telemt_user_octets_to_client{user="hello"} 504632878785 (469.98 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 963
telemt_user_unique_ips_recent_window{user="hello"} 434
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 2919.7 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68982
telemt_connections_bad_total 4475
telemt_connections_current 874
telemt_connections_me_current 874
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 719
telemt_upstream_connect_attempt_total 4627
telemt_upstream_connect_success_total 4621
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 4627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1865
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 330051
telemt_me_reconnect_success_total 597
telemt_me_reader_eof_total 506
telemt_me_idle_close_by_peer_total 506
telemt_me_route_drop_no_conn_total 40948
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56957
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 125
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 512
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 586
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 60730
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 1103365337 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 9580317981 (8.92 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 1989.4 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150407
telemt_connections_bad_total 5334
telemt_connections_current 2574
telemt_connections_me_current 2574
telemt_handshake_timeouts_total 1276
telemt_upstream_connect_attempt_total 452
telemt_upstream_connect_success_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14582
telemt_me_reconnect_success_total 294
telemt_me_reader_eof_total 183
telemt_me_idle_close_by_peer_total 183
telemt_me_route_drop_no_conn_total 148630
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132930
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 333
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 201
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 233
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 133790
telemt_user_connections_current{user="hello"} 2574
telemt_user_octets_from_client{user="hello"} 1358637632 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 35694448656 (33.24 GB)
telemt_user_unique_ips_current{user="hello"} 783
telemt_user_unique_ips_recent_window{user="hello"} 341
```