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

# Server Metrics 2026-03-16 17:11:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 12795.1 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133472
telemt_connections_bad_total 618
telemt_handshake_timeouts_total 3783
telemt_upstream_connect_attempt_total 2799
telemt_upstream_connect_success_total 2788
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3244
telemt_me_reconnect_success_total 2074
telemt_me_reader_eof_total 2152
telemt_me_idle_close_by_peer_total 2152
telemt_me_route_drop_no_conn_total 40379
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124642
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 662
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 511
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2123
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2072
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 124571
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 2311714920 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 71782401156 (66.85 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 7574.8 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54622
telemt_connections_bad_total 457
telemt_handshake_timeouts_total 2840
telemt_upstream_connect_attempt_total 1662
telemt_upstream_connect_success_total 1650
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 4717
telemt_me_reconnect_success_total 1212
telemt_me_reader_eof_total 1332
telemt_me_idle_close_by_peer_total 1332
telemt_me_route_drop_no_conn_total 33369
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49551
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 95
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1342
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1207
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 49504
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 651667668 (621.48 MB)
telemt_user_octets_to_client{user="hello"} 15306396408 (14.26 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 12908.2 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52558
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 789
telemt_upstream_connect_attempt_total 3724
telemt_upstream_connect_success_total 3680
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 3724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 39749
telemt_me_reconnect_success_total 1985
telemt_me_reader_eof_total 2275
telemt_me_idle_close_by_peer_total 2275
telemt_me_route_drop_no_conn_total 18335
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47993
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 144
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2279
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 1941
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 48935
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 618673234 (590.01 MB)
telemt_user_octets_to_client{user="hello"} 13539572786 (12.61 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 13044.5 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103323
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 1714
telemt_upstream_connect_attempt_total 2842
telemt_upstream_connect_success_total 2818
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 2842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1444
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 8428
telemt_me_reconnect_success_total 2073
telemt_me_reader_eof_total 2297
telemt_me_idle_close_by_peer_total 2297
telemt_me_route_drop_no_conn_total 39050
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97760
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 560
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2298
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2069
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 97737
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 1349248368 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 25486231796 (23.74 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 10505.9 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60408
telemt_connections_bad_total 19500
telemt_handshake_timeouts_total 479
telemt_upstream_connect_attempt_total 2659
telemt_upstream_connect_success_total 2623
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 2659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 3708
telemt_me_reconnect_success_total 2056
telemt_me_reader_eof_total 2153
telemt_me_idle_close_by_peer_total 2153
telemt_me_route_drop_no_conn_total 47697
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57290
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2142
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 2056
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 38343
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 1967208276 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 28896298528 (26.91 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 12612.3 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148773
telemt_connections_bad_total 1965
telemt_handshake_timeouts_total 3300
telemt_upstream_connect_attempt_total 2707
telemt_upstream_connect_success_total 2707
telemt_upstream_connect_attempts_per_request{bucket="1"} 2707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 7062
telemt_me_reconnect_success_total 2038
telemt_me_reader_eof_total 2223
telemt_me_idle_close_by_peer_total 2223
telemt_me_route_drop_no_conn_total 67357
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137376
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2209
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2033
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 137093
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 2892919748 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 51448970800 (47.92 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 101
```