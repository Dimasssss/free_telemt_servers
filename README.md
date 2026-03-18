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

# Server Metrics 2026-03-18 14:21:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 20414.5 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 755671
telemt_connections_bad_total 38062
telemt_handshake_timeouts_total 20629
telemt_upstream_connect_attempt_total 66926
telemt_upstream_connect_success_total 65963
telemt_upstream_connect_fail_total 963
telemt_upstream_connect_attempts_per_request{bucket="1"} 66926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 963
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 515752
telemt_me_reconnect_success_total 2946
telemt_me_reader_eof_total 3154
telemt_me_idle_close_by_peer_total 3152
telemt_me_route_drop_no_conn_total 431179
telemt_me_route_drop_channel_closed_total 168
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 587923
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2567
telemt_desync_full_logged_total 904
telemt_desync_suppressed_total 1663
telemt_desync_frames_bucket_total{bucket="1_2"} 713
telemt_desync_frames_bucket_total{bucket="3_10"} 883
telemt_desync_frames_bucket_total{bucket="gt_10"} 971
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3158
telemt_me_refill_failed_total 16708
telemt_me_writer_restored_same_endpoint_total 2841
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 646052
telemt_user_connections_current{user="hello"} 1723
telemt_user_octets_from_client{user="hello"} 9452855340 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 168836133225 (157.24 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 982.6 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104129
telemt_connections_bad_total 4064
telemt_connections_current 3918
telemt_connections_me_current 3918
telemt_handshake_timeouts_total 1921
telemt_upstream_connect_attempt_total 207
telemt_upstream_connect_success_total 206
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 120
telemt_me_reconnect_success_total 119
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 46633
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92288
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 288
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_me_writer_removed_unexpected_total 33
telemt_me_writer_restored_same_endpoint_total 117
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 92064
telemt_user_connections_current{user="hello"} 3918
telemt_user_octets_from_client{user="hello"} 969850120 (924.92 MB)
telemt_user_octets_to_client{user="hello"} 30396550544 (28.31 GB)
telemt_user_unique_ips_current{user="hello"} 1217
telemt_user_unique_ips_recent_window{user="hello"} 589
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 910.7 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73007
telemt_connections_bad_total 3399
telemt_connections_current 3118
telemt_connections_me_current 3118
telemt_handshake_timeouts_total 1040
telemt_upstream_connect_attempt_total 104
telemt_upstream_connect_success_total 103
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 35
telemt_me_reconnect_success_total 34
telemt_me_reader_eof_total 13
telemt_me_idle_close_by_peer_total 13
telemt_me_route_drop_no_conn_total 22631
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62174
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 161
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_me_writer_removed_unexpected_total 35
telemt_me_writer_restored_same_endpoint_total 17
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 62161
telemt_user_connections_current{user="hello"} 3118
telemt_user_octets_from_client{user="hello"} 1537086336 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 23634457576 (22.01 GB)
telemt_user_unique_ips_current{user="hello"} 950
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 1625.3 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173786
telemt_connections_bad_total 336
telemt_connections_current 2696
telemt_connections_me_current 2696
telemt_handshake_timeouts_total 3187
telemt_upstream_connect_attempt_total 258
telemt_upstream_connect_success_total 256
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 144
telemt_me_reconnect_success_total 143
telemt_me_reader_eof_total 95
telemt_me_idle_close_by_peer_total 94
telemt_me_route_drop_no_conn_total 246749
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155339
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 408
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 294
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 115
telemt_me_writer_restored_same_endpoint_total 132
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 155316
telemt_user_connections_current{user="hello"} 2696
telemt_user_octets_from_client{user="hello"} 838319912 (799.48 MB)
telemt_user_octets_to_client{user="hello"} 20218643844 (18.83 GB)
telemt_user_unique_ips_current{user="hello"} 791
telemt_user_unique_ips_recent_window{user="hello"} 431
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 20285.4 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1683656
telemt_connections_bad_total 126431
telemt_handshake_timeouts_total 27201
telemt_upstream_connect_attempt_total 15109
telemt_upstream_connect_success_total 15081
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 800
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986813
telemt_me_reconnect_success_total 2374
telemt_me_reader_eof_total 2482
telemt_me_idle_close_by_peer_total 2482
telemt_me_route_drop_no_conn_total 1838549
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1407541
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3926
telemt_desync_full_logged_total 1350
telemt_desync_suppressed_total 2576
telemt_desync_frames_bucket_total{bucket="1_2"} 649
telemt_desync_frames_bucket_total{bucket="3_10"} 1516
telemt_desync_frames_bucket_total{bucket="gt_10"} 1761
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2444
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2259
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1409398
telemt_user_connections_current{user="hello"} 2825
telemt_user_octets_from_client{user="hello"} 20723739251 (19.30 GB)
telemt_user_octets_to_client{user="hello"} 461194161997 (429.52 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 924
telemt_user_unique_ips_recent_window{user="hello"} 413
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 1073.7 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34363
telemt_connections_bad_total 2368
telemt_connections_current 833
telemt_connections_me_current 833
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 267
telemt_upstream_connect_attempt_total 4272
telemt_upstream_connect_success_total 4269
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 329788
telemt_me_reconnect_success_total 336
telemt_me_reader_eof_total 231
telemt_me_idle_close_by_peer_total 231
telemt_me_route_drop_no_conn_total 26812
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26227
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 248
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 325
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 30011
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 490457249 (467.74 MB)
telemt_user_octets_to_client{user="hello"} 3724751605 (3.47 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 144.5 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15767
telemt_connections_bad_total 74
telemt_connections_current 2546
telemt_connections_me_current 2546
telemt_handshake_timeouts_total 174
telemt_upstream_connect_attempt_total 211
telemt_upstream_connect_success_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_me_reconnect_attempts_total 14427
telemt_me_reconnect_success_total 139
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 9245
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13873
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 39
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 78
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 13873
telemt_user_connections_current{user="hello"} 2546
telemt_user_octets_from_client{user="hello"} 216191824 (206.18 MB)
telemt_user_octets_to_client{user="hello"} 2115018164 (1.97 GB)
telemt_user_unique_ips_current{user="hello"} 828
telemt_user_unique_ips_recent_window{user="hello"} 476
```