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

# Server Metrics 2026-03-18 14:11:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 19801.8 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 733638
telemt_connections_bad_total 36278
telemt_handshake_timeouts_total 20140
telemt_upstream_connect_attempt_total 66788
telemt_upstream_connect_success_total 65828
telemt_upstream_connect_fail_total 960
telemt_upstream_connect_attempts_per_request{bucket="1"} 66788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 960
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 514509
telemt_me_reconnect_success_total 2855
telemt_me_reader_eof_total 3027
telemt_me_idle_close_by_peer_total 3025
telemt_me_route_drop_no_conn_total 419292
telemt_me_route_drop_channel_closed_total 160
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 569909
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2489
telemt_desync_full_logged_total 871
telemt_desync_suppressed_total 1618
telemt_desync_frames_bucket_total{bucket="1_2"} 699
telemt_desync_frames_bucket_total{bucket="3_10"} 860
telemt_desync_frames_bucket_total{bucket="gt_10"} 930
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3031
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2750
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 628067
telemt_user_connections_current{user="hello"} 1757
telemt_user_octets_from_client{user="hello"} 8624864380 (8.03 GB)
telemt_user_octets_to_client{user="hello"} 164047942217 (152.78 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 577
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 371.3 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50319
telemt_connections_bad_total 851
telemt_connections_current 3975
telemt_connections_me_current 3975
telemt_handshake_timeouts_total 886
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
telemt_me_route_drop_no_conn_total 22567
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45382
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 98
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_me_writer_removed_unexpected_total 33
telemt_me_writer_restored_same_endpoint_total 117
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 45180
telemt_user_connections_current{user="hello"} 3975
telemt_user_octets_from_client{user="hello"} 330564388 (315.25 MB)
telemt_user_octets_to_client{user="hello"} 11072525548 (10.31 GB)
telemt_user_unique_ips_current{user="hello"} 1227
telemt_user_unique_ips_recent_window{user="hello"} 602
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 299.7 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27720
telemt_connections_bad_total 984
telemt_connections_current 3024
telemt_connections_me_current 3024
telemt_handshake_timeouts_total 377
telemt_upstream_connect_attempt_total 98
telemt_upstream_connect_success_total 97
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 98
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 29
telemt_me_reconnect_success_total 28
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 7708
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23336
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 21
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_removed_unexpected_total 28
telemt_me_writer_restored_same_endpoint_total 11
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_user_connections_total{user="hello"} 23339
telemt_user_connections_current{user="hello"} 3024
telemt_user_octets_from_client{user="hello"} 987861340 (942.10 MB)
telemt_user_octets_to_client{user="hello"} 6943075812 (6.47 GB)
telemt_user_unique_ips_current{user="hello"} 945
telemt_user_unique_ips_recent_window{user="hello"} 449
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 1013.9 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124223
telemt_connections_bad_total 260
telemt_connections_current 2839
telemt_connections_me_current 2839
telemt_handshake_timeouts_total 1985
telemt_upstream_connect_attempt_total 200
telemt_upstream_connect_success_total 198
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 86
telemt_me_reconnect_success_total 85
telemt_me_reader_eof_total 32
telemt_me_idle_close_by_peer_total 32
telemt_me_route_drop_no_conn_total 199026
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111901
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 248
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 181
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 54
telemt_me_writer_restored_same_endpoint_total 74
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 111886
telemt_user_connections_current{user="hello"} 2839
telemt_user_octets_from_client{user="hello"} 524453492 (500.16 MB)
telemt_user_octets_to_client{user="hello"} 10343203676 (9.63 GB)
telemt_user_unique_ips_current{user="hello"} 817
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 19673.7 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1615452
telemt_connections_bad_total 113279
telemt_handshake_timeouts_total 26359
telemt_upstream_connect_attempt_total 14965
telemt_upstream_connect_success_total 14937
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 14965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986715
telemt_me_reconnect_success_total 2278
telemt_me_reader_eof_total 2387
telemt_me_idle_close_by_peer_total 2387
telemt_me_route_drop_no_conn_total 1772367
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1355992
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3836
telemt_desync_full_logged_total 1317
telemt_desync_suppressed_total 2519
telemt_desync_frames_bucket_total{bucket="1_2"} 618
telemt_desync_frames_bucket_total{bucket="3_10"} 1478
telemt_desync_frames_bucket_total{bucket="gt_10"} 1740
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2346
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2163
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 1357861
telemt_user_connections_current{user="hello"} 3264
telemt_user_octets_from_client{user="hello"} 20180524335 (18.79 GB)
telemt_user_octets_to_client{user="hello"} 450451654129 (419.52 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 1094
telemt_user_unique_ips_recent_window{user="hello"} 717
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 462.6 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20770
telemt_connections_bad_total 1246
telemt_connections_current 947
telemt_connections_me_current 947
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 124
telemt_upstream_connect_attempt_total 4183
telemt_upstream_connect_success_total 4181
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1638
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 329743
telemt_me_reconnect_success_total 293
telemt_me_reader_eof_total 178
telemt_me_idle_close_by_peer_total 178
telemt_me_route_drop_no_conn_total 20844
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14695
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 196
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 282
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 18480
telemt_user_connections_current{user="hello"} 947
telemt_user_octets_from_client{user="hello"} 254421737 (242.64 MB)
telemt_user_octets_to_client{user="hello"} 1611863645 (1.50 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 19629.9 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1279171
telemt_connections_bad_total 148762
telemt_handshake_timeouts_total 24750
telemt_upstream_connect_attempt_total 3596
telemt_upstream_connect_success_total 3563
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 3596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 6294
telemt_me_reconnect_success_total 2504
telemt_me_reader_eof_total 2674
telemt_me_idle_close_by_peer_total 2674
telemt_me_route_drop_no_conn_total 777406
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1008788
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3348
telemt_desync_full_logged_total 1109
telemt_desync_suppressed_total 2239
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 1129
telemt_desync_frames_bucket_total{bucket="gt_10"} 1598
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2644
telemt_me_refill_failed_total 117
telemt_me_writer_restored_same_endpoint_total 2494
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 1008111
telemt_user_connections_current{user="hello"} 3142
telemt_user_octets_from_client{user="hello"} 19826215192 (18.46 GB)
telemt_user_octets_to_client{user="hello"} 453528984220 (422.38 GB)
telemt_user_unique_ips_current{user="hello"} 898
telemt_user_unique_ips_recent_window{user="hello"} 491
```