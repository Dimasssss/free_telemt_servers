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

# Server Metrics 2026-03-18 14:00:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 19191.7 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 709563
telemt_connections_bad_total 34556
telemt_handshake_timeouts_total 19434
telemt_upstream_connect_attempt_total 66689
telemt_upstream_connect_success_total 65729
telemt_upstream_connect_fail_total 960
telemt_upstream_connect_attempts_per_request{bucket="1"} 66689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 960
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 514410
telemt_me_reconnect_success_total 2757
telemt_me_reader_eof_total 2930
telemt_me_idle_close_by_peer_total 2928
telemt_me_route_drop_no_conn_total 399035
telemt_me_route_drop_channel_closed_total 158
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549763
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2402
telemt_desync_full_logged_total 841
telemt_desync_suppressed_total 1561
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 835
telemt_desync_frames_bucket_total{bucket="gt_10"} 908
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2933
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2652
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 607925
telemt_user_connections_current{user="hello"} 1771
telemt_user_octets_from_client{user="hello"} 8407923236 (7.83 GB)
telemt_user_octets_to_client{user="hello"} 158762527017 (147.86 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 573
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 19223.4 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1886161
telemt_connections_bad_total 141987
telemt_handshake_timeouts_total 42764
telemt_upstream_connect_attempt_total 3453
telemt_upstream_connect_success_total 3441
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3534
telemt_me_reconnect_success_total 2388
telemt_me_reader_eof_total 2472
telemt_me_idle_close_by_peer_total 2471
telemt_me_route_drop_no_conn_total 1461702
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1609468
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4994
telemt_desync_full_logged_total 1570
telemt_desync_suppressed_total 3424
telemt_desync_frames_bucket_total{bucket="1_2"} 1016
telemt_desync_frames_bucket_total{bucket="3_10"} 2011
telemt_desync_frames_bucket_total{bucket="gt_10"} 1967
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2439
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2387
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1608444
telemt_user_connections_current{user="hello"} 4655
telemt_user_octets_from_client{user="hello"} 37943662952 (35.34 GB)
telemt_user_octets_to_client{user="hello"} 505252388812 (470.55 GB)
telemt_user_unique_ips_current{user="hello"} 1395
telemt_user_unique_ips_recent_window{user="hello"} 777
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 19138.2 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1385902
telemt_connections_bad_total 106053
telemt_handshake_timeouts_total 30679
telemt_upstream_connect_attempt_total 11946
telemt_upstream_connect_success_total 11946
telemt_upstream_connect_attempts_per_request{bucket="1"} 11946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 449
telemt_me_reconnect_attempts_total 612312
telemt_me_reconnect_success_total 2707
telemt_me_reader_eof_total 2866
telemt_me_idle_close_by_peer_total 2865
telemt_me_route_drop_no_conn_total 678463
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1085595
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3389
telemt_desync_full_logged_total 1118
telemt_desync_suppressed_total 2271
telemt_desync_frames_bucket_total{bucket="1_2"} 950
telemt_desync_frames_bucket_total{bucket="3_10"} 1219
telemt_desync_frames_bucket_total{bucket="gt_10"} 1220
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2846
telemt_me_refill_failed_total 19794
telemt_me_writer_restored_same_endpoint_total 2672
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 1093058
telemt_user_connections_current{user="hello"} 3428
telemt_user_octets_from_client{user="hello"} 14293836839 (13.31 GB)
telemt_user_octets_to_client{user="hello"} 443496708448 (413.04 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1047
telemt_user_unique_ips_recent_window{user="hello"} 590
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 403.2 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33319
telemt_connections_bad_total 120
telemt_connections_current 2835
telemt_connections_me_current 2835
telemt_handshake_timeouts_total 616
telemt_upstream_connect_attempt_total 143
telemt_upstream_connect_success_total 142
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 73
telemt_me_reconnect_success_total 73
telemt_me_reader_eof_total 19
telemt_me_idle_close_by_peer_total 19
telemt_me_route_drop_no_conn_total 14320
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27277
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_me_writer_removed_unexpected_total 41
telemt_me_writer_restored_same_endpoint_total 62
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 27265
telemt_user_connections_current{user="hello"} 2835
telemt_user_octets_from_client{user="hello"} 258671308 (246.69 MB)
telemt_user_octets_to_client{user="hello"} 4437219344 (4.13 GB)
telemt_user_unique_ips_current{user="hello"} 825
telemt_user_unique_ips_recent_window{user="hello"} 532
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 19063.1 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1492540
telemt_connections_bad_total 107101
telemt_handshake_timeouts_total 24915
telemt_upstream_connect_attempt_total 14916
telemt_upstream_connect_success_total 14888
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 14916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986666
telemt_me_reconnect_success_total 2229
telemt_me_reader_eof_total 2332
telemt_me_idle_close_by_peer_total 2332
telemt_me_route_drop_no_conn_total 1339893
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1243787
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3752
telemt_desync_full_logged_total 1286
telemt_desync_suppressed_total 2466
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 1448
telemt_desync_frames_bucket_total{bucket="gt_10"} 1726
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2295
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2114
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 1245668
telemt_user_connections_current{user="hello"} 3245
telemt_user_octets_from_client{user="hello"} 19847331839 (18.48 GB)
telemt_user_octets_to_client{user="hello"} 444206964725 (413.70 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 1061
telemt_user_unique_ips_recent_window{user="hello"} 702
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 147.9 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11241
telemt_connections_current 894
telemt_connections_me_current 894
telemt_relay_adaptive_promotions_total 13
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 4380
telemt_upstream_connect_success_total 4366
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 51154
telemt_me_reconnect_success_total 177
telemt_me_reader_eof_total 66
telemt_me_idle_close_by_peer_total 66
telemt_me_route_drop_no_conn_total 988
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6075
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 85
telemt_me_refill_failed_total 1593
telemt_me_writer_restored_same_endpoint_total 136
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 3411
telemt_user_connections_total{user="hello"} 10162
telemt_user_connections_current{user="hello"} 894
telemt_user_octets_from_client{user="hello"} 26374503 (25.15 MB)
telemt_user_octets_to_client{user="hello"} 433289685 (413.22 MB)
telemt_user_msgs_from_client{user="hello"} 24021
telemt_user_msgs_to_client{user="hello"} 37823
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 328
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 19019.3 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1221835
telemt_connections_bad_total 140450
telemt_handshake_timeouts_total 24257
telemt_upstream_connect_attempt_total 3509
telemt_upstream_connect_success_total 3476
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 3509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 4918
telemt_me_reconnect_success_total 2440
telemt_me_reader_eof_total 2573
telemt_me_idle_close_by_peer_total 2573
telemt_me_route_drop_no_conn_total 704992
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 962750
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3227
telemt_desync_full_logged_total 1078
telemt_desync_suppressed_total 2149
telemt_desync_frames_bucket_total{bucket="1_2"} 597
telemt_desync_frames_bucket_total{bucket="3_10"} 1096
telemt_desync_frames_bucket_total{bucket="gt_10"} 1534
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2539
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 2430
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 962084
telemt_user_connections_current{user="hello"} 3222
telemt_user_octets_from_client{user="hello"} 19316161648 (17.99 GB)
telemt_user_octets_to_client{user="hello"} 436803042748 (406.80 GB)
telemt_user_unique_ips_current{user="hello"} 967
telemt_user_unique_ips_recent_window{user="hello"} 515
```